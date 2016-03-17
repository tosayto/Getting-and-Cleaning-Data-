###CODEBOOK
==================================================================
Human Activity Recognition Using Smartphones Dataset
==================================================================
The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. 
These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. 
Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. 
Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). 
Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fffBodyAcc-XYZ, fffBodyAccJerk-XYZ, fffBodyGyro-XYZ, fffBodyAccJerkMag, fffBodyGyroMag, fffBodyGyroJerkMag. 
(Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

#####Notes: 
======
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.

For more information about this dataset contact: activityrecognition@smartlab.ws


[1] "t.body.acc.mean.X"  
	NUMMERIC 
	Time Body Accelerometer Mean X 
	
[2] "t.body.acc.mean.Y"
	NUMMERIC
	Time Body Accelerometer Mean Y
	
[3] "t.body.acc.mean.Z" 
	NUMMERIC
	Time Body Accelerometer Mean Z
	
[4] "t.body.acc.std.X"
	NUMMERIC
	Time Body Accelerometer Standard Deviation X
	
[5] "t.body.acc.std.Y"
	NUMMERIC
	Time Body Accelerometer Standard Deviation Y
	
[6] "t.body.acc.std.Z"
	NUMMERIC
	Time Body Accelerometer Standard Deviation Z
	
[7] "t.gravity.acc.mean.X"
	NUMMERIC
	Time Gravity Accelerometer Mean X
	
[8] "t.gravity.acc.mean.Y"
	NUMMERIC
	Time Gravity Accelerometer Mean Y
	
[9] "t.gravity.acc.mean.Z"
	NUMMERIC
	Time Gravity Accelerometer Mean Z
	
[10] "t.gravity.acc.std.X"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation X
	
[11] "t.gravity.acc.std.Y"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation Y
	
[12] "t.gravity.acc.std.Z"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation Z
	
[13] "t.body.acc.jerk.mean.X"
	NUMMERIC
	Time Body Accelerometer Jerk Mean X
	
[14] "t.body.acc.jerk.mean.Y"
	NUMMERIC
	Time Body Accelerometer Jerk Mean Y
	
[15] "t.body.acc.jerk.mean.Z"
	NUMMERIC
	Time Body Accelerometer Jerk Mean Z
	
[16] "t.body.acc.jerk.std.X"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation X
	
[17] "t.body.acc.jerk.std.Y"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation Y
	
[18] "t.body.acc.jerk.std.Z"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation Z
	
[19] "t.body.gyro.mean.X"
	NUMMERIC
	Time Body Gyroscope Mean X
	
[20] "t.body.gyro.mean.Y"
	NUMMERIC
	Time Body Gyroscope Mean Y
	
[21] "t.body.gyro.mean.Z" 
	NUMMERIC
	Time Body Gyroscope Mean Z
	
[22] "t.body.gyro.std.X"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Z
	
[23] "t.body.gyro.std.Y"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Y
	
[24] "t.body.gyro.std.Z"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Z
	
[25] "t.body.gyro.jerk.mean.X"
	NUMMERIC
	Time Body Gyroscope Jerk Mean X
	
[26] "t.body.gyro.jerk.mean.Y"
	NUMMERIC
	Time Body Gyroscope Jerk Mean Y
	
[27] "t.body.gyro.jerk.mean.Z"
	NUMMERIC
	Time Body Gyroscope Jerk Mean Z
	
[28] "t.body.gyro.jerk.std.X"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation X
	
[29] "t.body.gyro.jerk.std.Y"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation Y
	
[30] "t.body.gyro.jerk.std.Z"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation Z
	
[31] "t.body.acc.mag.mean"
	NUMMERIC 
	Body Accelerometer Magnitude Mean
	
[32] "t.body.acc.mag.std"
	NUMMERIC 
	Body Accelerometer Magnitude Standard Deviation
	
[33] "t.gravity.acc.mag.mean"
	NUMMERIC 
	Accelerometer Gravity Accelerometer Magnitude Mean
	
[34] "t.gravity.acc.mag.std" 
	NUMMERIC 
	Time Gravity Accelerometer Magnitude Standard Deviation
	
[35] "t.body.acc.jerk.mag.mean"
	NUMMERIC
	Time Body Accelerometer Jerk Magnitude Mean
	
[36] "t.body.acc.jerk.mag.std" 
	NUMMERIC
	Time Body Accelerometer Jerk Magnitude Standard Deviation
	
[37] "t.body.gyro.mag.mean"
	NUMMERIC
	Time Body Gyroscope Magnitude Mean
	
[38] "t.body.gyro.mag.std"
	NUMMERIC
	Time Body Gyroscope Magnitude Standard Deviation
	
[39] "t.body.gyro.jerk.mag.mean"
	NUMMERIC
	Time Body Gyroscope Jerk Magnitude Mean
	
[40] "t.body.gyro.jerk.mag.std"
	NUMMERIC
	Time Body Gyroscope Jerk Magnitude Standard Deviation
	
[41] "fft.body.acc.mean.X"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean X
	
[42] "fft.body.acc.mean.Y"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean Y  
	
[43] "fft.body.acc.mean.Z"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean Z
	
[44] "fft.body.acc.std.X"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation X
	
[45] "fft.body.acc.std.Y"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation Y 
	
[46] "fft.body.acc.std.Z"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation Z
	
[47] "fft.body.acc.jerk.mean.X"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean X
	
[48] "fft.body.acc.jerk.mean.Y"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean Y 
	
[49] "fft.body.acc.jerk.mean.Z"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean Z
	
[50] "fft.body.acc.jerk.std.X"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation X
	
[51] "fft.body.acc.jerk.std.Y"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation Y
	
[52] "fft.body.acc.jerk.std.Z"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation Z
	
[53] "fft.body.gyro.mean.X"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean X
	
[54] "fft.body.gyro.mean.Y"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean Y
	
[55] "fft.body.gyro.mean.Z"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean Z
	
[56] "fft.body.gyro.std.X"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation X
	
[57] "fft.body.gyro.std.Y"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation Y
	
[58] "fft.body.gyro.std.Z" 
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation Z
	
[59] "fft.body.acc.mag.mean"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Magnitude Mean
	
[60] "fft.body.acc.mag.std"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Magnitude Standard Deviation
	
[61] "fft.body.body.acc.jerk.mag.mean"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Magnitude Mean
	
[62] "fft.body.body.acc.jerk.mag.std"
	NUMMERIC
	Fast Fourier Transform Body Body Accelerometer Jerk Magnitude Standard Deviation
	
[63] "fft.body.body.gyro.mag.mean"
	NUMMERIC
	Fast Fourier Transform Body Body Gyroscope Magnitude Mean
	
[64] "fft.body.body.gyro.mag.std"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Magnitude Standard Deviation
	
[65] "fft.body.body.gyro.jerk.mag.mean"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Jerk Magnitude Mean
	
[66] "fft.body.body.gyro.jerk.mag.std" 
	NUMMERIC
	Fast Fourier Transform Body Body Gyroscope Jerk Magnitude Standard Deviation
	
[67] "activity.id"
    INTEGER
	Performed six activities: 
	1 WALKING, 
	2 WALKING_UPSTAIRS, 
	3 WALKING_DOWNSTAIRS, 
	4 SITTING, 
	5 STANDING, 
	6 LAYING	
	
[68] "subject.id"
	INTEGER
	From 1 to 30
	the identifier of the subject who carried out the experiment.
	The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years.

#####REMOVED FEATURES:

Features wherein the next calculations made, is removed from our dataset.

*mad(): Median absolute deviation 
*max(): Largest value in array
*min(): Smallest value in array
*sma(): Signal magnitude area
*energy(): Energy measure. Sum of the squares divided by the number of values. 
*iqr(): Interquartile range 
*entropy(): Signal entropy
*arCoeff(): Autorregresion coefficients with Burg order equal to 4
*correlation(): correlation coefficient between two signals
*maxInds(): index of the frequency component with largest magnitude
*meanFreq(): Weighted average of the frequency components to obtain a mean frequency
*skewness(): skewness of the frequency domain signal 
*kurtosis(): kurtosis of the frequency domain signal 
*bandsEnergy(): Energy of a frequency interval within the 64 bins of the FFT of each window.
*angle(): Angle between to vectors.

#####ADDED FEATURES:

Features from 69 to 200 are added.
Each feature from 1 to 66 is grouped by each activity and each subject and we have calculated its average and added as new feature to dataset.
We have done this to make comparison easy. The feature names that ends with .activity.id.avg are the features grouped by activity. The features 
ends with .subject.id.avg are the freatures grouped by subjects.

[69] "t.body.acc.mean.X.activity.id.avg"  
	NUMMERIC 
	Time Body Accelerometer Mean X Activity Id Average
	
[70] "t.body.acc.mean.Y.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Mean Y Activity Id Average
	
[71] "t.body.acc.mean.Z.activity.id.avg" 
	NUMMERIC
	Time Body Accelerometer Mean Z Activity Id Average
	
[72] "t.body.acc.std.X.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Standard Deviation X Activity Id Average
	
[73] "t.body.acc.std.Y.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Standard Deviation Y Activity Id Average
	
[74] "t.body.acc.std.Z.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Standard Deviation Z Activity Id Average
	
[75] "t.gravity.acc.mean.X.activity.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Mean X Activity Id Average
	
[76] "t.gravity.acc.mean.Y.activity.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Mean Y Activity Id Average
	
[77] "t.gravity.acc.mean.Z.activity.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Mean Z Activity Average
	
[78] "t.gravity.acc.std.X.activity.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation X Activity Id Average
	
[79] "t.gravity.acc.std.Y.activity.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation Y Activity Id Average
	
[80] "t.gravity.acc.std.Z.activity.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation Z Activity Id Average
	
[81] "t.body.acc.jerk.mean.X.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Mean X Activity Id Average
	
[82] "t.body.acc.jerk.mean.Y.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Mean Y Activity Id Average
	
[83] "t.body.acc.jerk.mean.Z.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Mean Z Activity Id Average
	
[84] "t.body.acc.jerk.std.X.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation X Activity Id Average
	
[85] "t.body.acc.jerk.std.Y.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation Y Activity Id Average
	
[86] "t.body.acc.jerk.std.Z.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation Z Activity Id Average
	
[87] "t.body.gyro.mean.X.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Mean X Activity Id Average
	
[88] "t.body.gyro.mean.Y.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Mean Y Activity Id Average
	
[89] "t.body.gyro.mean.Z.activity.id.avg" 
	NUMMERIC
	Time Body Gyroscope Mean Z Activity Id Average
	
[90] "t.body.gyro.std.X.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Standard Deviation X Activity Id Average
	
[91] "t.body.gyro.std.Y.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Y Activity Id Average
	
[92] "t.body.gyro.std.Z.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Z Activity Id Average
	
[93] "t.body.gyro.jerk.mean.X.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Mean X Activity Id Average
	
[94] "t.body.gyro.jerk.mean.Y.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Mean Y Activity Id Average
	
[95] "t.body.gyro.jerk.mean.Z.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Mean Z Activity Id Average
	
[96] "t.body.gyro.jerk.std.X.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation X Activity Id Average
	
[97] "t.body.gyro.jerk.std.Y.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation Y Activity Id Average
	
[98] "t.body.gyro.jerk.std.Z.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation Z Activity Id Average
	
[99] "t.body.acc.mag.mean.activity.id.avg"
	NUMMERIC 
	Time Body Accelerometer Magnitude Mean Activity Id Average
	
[100] "t.body.acc.mag.std.activity.id.avg"
	NUMMERIC 
	Time Body Accelerometer Magnitude Standard Deviation Activity Id Average
	
[101] "t.gravity.acc.mag.mean.activity.id.avg"
	NUMMERIC 
	Time Accelerometer Gravity Accelerometer Magnitude Mean Activity Id Average
	
[102] "t.gravity.acc.mag.std.activity.id.avg" 
	NUMMERIC 
	Time Gravity Accelerometer Magnitude Standard Deviation Activity Id Average
	
[103] "t.body.acc.jerk.mag.mean.activity.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Magnitude Mean Activity Id Average
	
[104] "t.body.acc.jerk.mag.std.activity.id.avg" 
	NUMMERIC
	Time Body Accelerometer Jerk Magnitude Standard Deviation Activity Id Average
	
[105] "t.body.gyro.mag.mean.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Magnitude Mean Activity Id Average
	
[106] "t.body.gyro.mag.std.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Magnitude Standard Deviation Activity Id Average
	
[107] "t.body.gyro.jerk.mag.mean.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Magnitude Mean Activity Id Average
	
[108] "t.body.gyro.jerk.mag.std.activity.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Magnitude Standard Deviation Activity Id Average
	
[109] "fft.body.acc.mean.X.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean X Activity Id Average
	
[110] "fft.body.acc.mean.Y.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean Y Activity Id Average 
	
[111] "fft.body.acc.mean.Z.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean Z Activity Id Average 
	
[112] "fft.body.acc.std.X.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation X Activity Id Average
	
[113] "fft.body.acc.std.Y.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation Y Activity Id Average
	
[114] "fft.body.acc.std.Z.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation Z Activity Id Average
	
[115] "fft.body.acc.jerk.mean.X.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean X Activity Id Average
	
[116] "fft.body.acc.jerk.mean.Y.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean Y Activity Id Average 
	
[117] "fft.body.acc.jerk.mean.Z.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean Z Activity Id Average
	
[118] "fft.body.acc.jerk.std.X.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation X Activity Id Average
	
[119] "fft.body.acc.jerk.std.Y.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation Y Activity Id Average
	
[120] "fft.body.acc.jerk.std.Z.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation Z Activity Id Average
	
[121] "fft.body.gyro.mean.X.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean X Activity Id Average
	
[122] "fft.body.gyro.mean.Y.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean Y Activity Id Average
	
[123] "fft.body.gyro.mean.Z.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean Z Activity Id Average
	
[124] "fft.body.gyro.std.X.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation X Activity Id Average
	
[125] "fft.body.gyro.std.Y.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation Y Activity Id Average
	
[126] "fft.body.gyro.std.Z.activity.id.avg" 
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation Z Activity Id Average
	
[127] "fft.body.acc.mag.mean.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Magnitude Mean Activity Id Average
	
[128] "fft.body.acc.mag.std.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Magnitude Standard Deviation Activity Id Average
	
[129] "fft.body.body.acc.jerk.mag.mean.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Magnitude Mean Activity Id Average
	
[130] "fft.body.body.acc.jerk.mag.std.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Body Accelerometer Jerk Magnitude Standard Deviation Activity Id Average
	
[131] "fft.body.body.gyro.mag.mean.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Body Gyroscope Magnitude Mean Activity Id Average
	
[132] "fft.body.body.gyro.mag.std.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Magnitude Standard Deviation Activity Id Average
	
[133] "fft.body.body.gyro.jerk.mag.mean.activity.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Jerk Magnitude Mean Activity Id Average
	
[134] "fft.body.body.gyro.jerk.mag.std.activity.id.avg" 
	NUMMERIC
	Fast Fourier Transform Body Body Gyroscope Jerk Magnitude Standard Deviation
	
[135] "t.body.acc.mean.X.subject.id.avg"  
	NUMMERIC 
	Time Body Accelerometer Mean X Subject Id Average
	
[136] "t.body.acc.mean.Y.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Mean Y Subject Id Average
	
[137] "t.body.acc.mean.Z.subject.id.avg" 
	NUMMERIC
	Time Body Accelerometer Mean Z Subject Id Average
	
[138] "t.body.acc.std.X.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Standard Deviation X Subject Id Average
	
[139] "t.body.acc.std.Y.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Standard Deviation Y Subject Id Average
	
[140] "t.body.acc.std.Z.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Standard Deviation Z Subject Id Average
	
[141] "t.gravity.acc.mean.X.subject.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Mean X Subject Id Average
	
[142] "t.gravity.acc.mean.Y.subject.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Mean Y Subject Id Average
	
[143] "t.gravity.acc.mean.Z.subject.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Mean Z Subject Id Average
	
[144] "t.gravity.acc.std.X.subject.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation X Subject Id Average
	
[145] "t.gravity.acc.std.Y.subject.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation Y Subject Id Average
	
[146] "t.gravity.acc.std.Z.subject.id.avg"
	NUMMERIC
	Time Gravity Accelerometer Standard Deviation Z Subject Id Average
	
[147] "t.body.acc.jerk.mean.X.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Mean X Subject Id Average
	
[148] "t.body.acc.jerk.mean.Y.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Mean Y Subject Id Average
	
[149] "t.body.acc.jerk.mean.Z.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Mean Z Subject Id Average
	
[150] "t.body.acc.jerk.std.X.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation X Subject Id Average
	
[151] "t.body.acc.jerk.std.Y.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation Y Subject Id Average
	
[152] "t.body.acc.jerk.std.Z.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Standard Deviation Z Subject Id Average
	
[153] "t.body.gyro.mean.X.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Mean X Subject Id Average
	
[154] "t.body.gyro.mean.Y.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Mean Y Subject Id Average
	
[155] "t.body.gyro.mean.Z.subject.id.avg" 
	NUMMERIC
	Time Body Gyroscope Mean Z Subject Id Average
	
[156] "t.body.gyro.std.X.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Z Subject Id Average
	
[157] "t.body.gyro.std.Y.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Y Subject Id Average
	
[158] "t.body.gyro.std.Z.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Standard Deviation Z Subject Id Average
	
[159] "t.body.gyro.jerk.mean.X.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Mean X Subject Id Average
	
[160] "t.body.gyro.jerk.mean.Y.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Mean Y Subject Id Average
	
[161] "t.body.gyro.jerk.mean.Z.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Mean Z Subject Id Average
	
[162] "t.body.gyro.jerk.std.X.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation X Subject Id Average
	
[163] "t.body.gyro.jerk.std.Y.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation Y Subject Id Average
	
[164] "t.body.gyro.jerk.std.Z.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Standard Deviation Z Subject Id Average
	
[165] "t.body.acc.mag.mean.subject.id.avg"
	NUMMERIC 
	Body Accelerometer Magnitude Mean Subject Id Average
	
[166] "t.body.acc.mag.std.subject.id.avg"
	NUMMERIC 
	Body Accelerometer Magnitude Standard Deviation Subject Id Average  
	
[167] "t.gravity.acc.mag.mean.subject.id.avg"
	NUMMERIC 
	Accelerometer Gravity Accelerometer Magnitude Mean Subject Id Average
	
[168] "t.gravity.acc.mag.std.subject.id.avg" 
	NUMMERIC 
	Time Gravity Accelerometer Magnitude Standard Deviation Subject Id Average
	
[169] "t.body.acc.jerk.mag.mean.subject.id.avg"
	NUMMERIC
	Time Body Accelerometer Jerk Magnitude Mean Subject Id Average
	
[170] "t.body.acc.jerk.mag.std.subject.id.avg" 
	NUMMERIC
	Time Body Accelerometer Jerk Magnitude Standard Deviation Subject Id Average
	
[171] "t.body.gyro.mag.mean.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Magnitude Mean Subject Id Average
	
[172] "t.body.gyro.mag.std.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Magnitude Standard Deviation Subject Id Average
	
[173] "t.body.gyro.jerk.mag.mean.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Magnitude Mean Subject Id Average
	
[174] "t.body.gyro.jerk.mag.std.subject.id.avg"
	NUMMERIC
	Time Body Gyroscope Jerk Magnitude Standard Deviation Subject Id Average
	
[175] "fft.body.acc.mean.X.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean X Subject Id Average
	
[176] "fft.body.acc.mean.Y.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean Y Subject Id Average 
	
[177] "fft.body.acc.mean.Z.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Mean Z Subject Id Average
	
[178] "fft.body.acc.std.X.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation X Subject Id Average
	
[179] "fft.body.acc.std.Y.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation Y Subject Id Average
	
[180] "fft.body.acc.std.Z.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Standard Deviation Z Subject Id Average 
	
[181] "fft.body.acc.jerk.mean.X.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean X Subject Id Average
	
[182] "fft.body.acc.jerk.mean.Y.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean Y Subject Id Average 
    
[183] "fft.body.acc.jerk.mean.Z.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Mean Z Subject Id Average
	
[184] "fft.body.acc.jerk.std.X.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation X Subject Id Average
	
[185] "fft.body.acc.jerk.std.Y.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation Y Subject Id Average 
	
[186] "fft.body.acc.jerk.std.Z.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Standard Deviation Z Subject Id Average
	
[187] "fft.body.gyro.mean.X.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean X Subject Id Average
	
[188] "fft.body.gyro.mean.Y.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean Y Subject Id Average
	
[189] "fft.body.gyro.mean.Z.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Mean Z Subject Id Average
	
[190] "fft.body.gyro.std.X.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation X Subject Id Average
	
[191] "fft.body.gyro.std.Y.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation Y Subject Id Average
	
[192] "fft.body.gyro.std.Z.subject.id.avg" 
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Standard Deviation Z Subject Id Average
	
[193] "fft.body.acc.mag.mean.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Magnitude Mean Subject Id Average
	
[194] "fft.body.acc.mag.std.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Magnitude Standard Deviation Subject Id Average
	
[195] "fft.body.body.acc.jerk.mag.mean.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Accelerometer Jerk Magnitude Mean Subject Id Average
	
[196] "fft.body.body.acc.jerk.mag.std.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Body Accelerometer Jerk Magnitude Standard Deviation Subject Id Average
	
[197] "fft.body.body.gyro.mag.mean.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Body Gyroscope Magnitude Mean Subject Id Average
	
[198] "fft.body.body.gyro.mag.std.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Magnitude Standard Deviation Subject Id Average
	
[199] "fft.body.body.gyro.jerk.mag.mean.subject.id.avg"
	NUMMERIC
	Fast Fourier Transform Body Gyroscope Jerk Magnitude Mean Subject Id Average
	
[200] "fft.body.body.gyro.jerk.mag.std.subject.id.avg" 
	NUMMERIC
	Fast Fourier Transform Body Body Gyroscope Jerk Magnitude Standard Deviation Subject Id Average
	
	

#####License:
========
Use of this dataset in publications must be acknowledged by referencing the following publication [1] 

[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.

Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita. November 2012.