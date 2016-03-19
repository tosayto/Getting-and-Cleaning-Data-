## Getting-and-Cleaning-Data


####Author:tosayto
####Date:2016-03-18

#####Source of input:https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
#####Software version: RStudio Version 0.99.491 (R x64 3.2.2)
#####Required packeges:data.table version 1.9.6

###Loading data
```
train <- read.table("UCI HAR Dataset/train/X_train.txt")

test <- read.table("UCI HAR Dataset/test/X_test.txt")

train.activity.id <- read.table("UCI HAR Dataset/train/y_train.txt")

train_subject_id <- read.table("UCI HAR Dataset/train/subject_train.txt")

test.activity.id <- read.table("UCI HAR Dataset/test/y_test.txt")

test.subject.id <- read.table("UCI HAR Dataset/test/subject_test.txt")
```


###1 Merges the training and the test sets to create one data set.

###Loading column names
```
train_column_names_df = read.table("UCI HAR Dataset/features.txt")
```
####train data
#####Adding column names to training data
```
colnames(train)<- train_column_names_df[,"V2"]
```

#####Adding activity column to training dataset
```
train.and.activity.id <- cbind(train, train.activity.id) 
```

#####renaming column name to 'activity.id
```
names(train.and.activity.id)[names(train.and.activity.id) == 'V1'] <- 'activity.id'
```
#####Adding subject column to training dataset
```
train.and.activity.id.and.subject.id <-cbind(train.and.activity.id, train_subject_id)
```
#####renaming column name to 'subject.id
```
names(train.and.activity.id.and.subject.id)[names(train.and.activity.id.and.subject.id) == 'V1'] <- 'subject.id'
```
####test data
#####Adding column names to training data
```
colnames(test)<- train_column_names_df[,"V2"]
```

#####Adding activity column to test dataset
```
test.and.activity.id <- cbind(test, test.activity.id) 
```

#####renaming column name to 'activity.id
```
names(test.and.activity.id)[names(test.and.activity.id) == 'V1'] <- 'activity.id'
```

#####Adding subject column to test dataset
```
test.and.activity.id_and_subject_id <-cbind(test.and.activity.id, test.subject.id)
```
#####renaming column name to 'subject.id
```
names(test.and.activity.id_and_subject_id)[names(test.and.activity.id_and_subject_id) == 'V1'] <- 'subject.id'
```
####Merge train and test datasets with rbind
```
train_and_test <- rbind(train.and.activity.id.and.subject.id, test.and.activity.id_and_subject_id)
```

###2 Extracts only the measurements on the mean and standard deviation for each measurement.

##### create a vector that contain strings to remove columns from dataset
```
to_remove_column_names <- c("mad()", "max()", "min()", "sma()", "energy()", "iqr()", "entropy()", "arCoeff()", 
                            "correlation()", "maxInds()", "meanFreq()", "skewness()", "kurtosis()", "bandsEnergy()",
                            "angle()")
```
#####remove columns from dataset
```
train_and_test_rows_removed<-train_and_test[,-grep(paste(to_remove_column_names,collapse = "|"), names(train_and_test))]
```

###3 Uses descriptive activity names to name the activities in the data set

```
train_and_test_rows_removed[,"activity_id"] <- data.frame(apply(train_and_test_rows_removed["activity_id"], 2, as.factor))
levels(train_and_test_rows_removed$activity_id) <- c("WALKING", "WALKING_UPSTAIRS", "WALKING_DOWNSTAIRS", "SITTING", "STANDING", "LAYING")
```

###4 Appropriately labels the data set with descriptive variable names.

#####Each column name is replaced with discriptive names
#####Although some words not discriptive you should read the codebook.
```
for(i in names(train_and_test_rows_removed)){

  temp <- i
  
  //if column name begins with t replace it with t. (time)
  
  if(grepl("^t", i)){
    temp <- sub("^t","t.", temp)
  }
  
  //if it begins with f replace it with fft. (fast fourier transform)
  
  if(grepl("^f", i)){
    temp <- sub("^f","fft.", i)
  }
  
  //if it contains Body replace it with body_
  
  if(grepl("Body", i)){
    temp <- gsub("Body","body.", temp)
  }
  
  //if it contains Acc replace it with acc. (accelerometer)
  
  if(grepl("Acc", i)){
    temp <- sub("Acc","acc.", temp)
  }
  
  //if it contains Gyro replace it with gyro. (gyroscope)
  
  if(grepl("Gyro", i)){
    temp <- sub("Gyro","gyro.", temp)
  }
  
  //if it contains Jerk replace it with jerk.
  
  if(grepl("Jerk", i)){
    temp <- sub("Jerk","jerk.", temp)
  }
  
  //if it contains Mag replace it with mag. (magnitude)
  
  if(grepl("Mag", i)){
    temp <- sub("Mag","mag.", temp)
  }
  
 //if it contains Gravity replace it with gravity.
 
  if(grepl("Gravity", i)){
    temp <- sub("Gravity","gravity.", temp)
  }
  
  //if it contains -mean replace it with mean
  
  if(grepl("mean", i)){
    temp <- sub("-mean","mean", temp)
  }
  
  //if it contains -std replace it with std (Standar Deviation)
  
  if(grepl("std", i)){
    temp <- sub("-std","std", temp)
  }
  
  //if it contains () replace it with nothing
  
  if(grepl("\\(\\)", i)){
    temp <- sub("\\(\\)","", temp)
  }
  
  //if it contains -X replace it with .X
  
  if(grepl("-X", i)){
    temp <- sub("-X",".X", temp)
  }
  
  //if it contains -Y replace it with .Y
  
  if(grepl("-Y", i)){
    temp <- sub("-Y",".Y", temp)
  }
  
  //if it contains -Z replace it with .Z
  
  if(grepl("-Z", i)){
    temp <- sub("-Z",".Z", temp)
  }
  
  names(train_and_test_rows_removed)[names(train_and_test_rows_removed) == i] <- temp
}
```
###5 From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
```
tidy_data <- train_and_test_rows_removed
```

#####install.packages("data.table")
```
library(data.table)
```
#####Converting a data.frame to data.table
```
dt<-as.data.table(tidy_data)
```

#####putting colomn names in a variable
```
t<-colnames(dt)
```
####Calculating mean of each variable per activity and adding to dataset
```
expr<-NULL
for(i in 1:66){

   expr<- parse(text=paste(t[i],".activity.id.avg", ":=mean(",t[i],")", sep = ""))
   
  dt[, eval(expr),by=activity.id]
  
  
}
```
####Calculating mean of each variable per subject and adding to dataset
```
expr<-NULL

for(i in 1:66){

  expr<- parse(text=paste(t[i],".subject.id.avg", ":=mean(",t[i],")", sep = ""))
  
  dt[, eval(expr),by=subject.id]
  
  
}
```

### 6 Output the tidy dataset

#####writing tidy dataset to file "tidy_data.txt".
```
write.table(dt, file="tidy_data.txt", row.names = FALSE)
```
