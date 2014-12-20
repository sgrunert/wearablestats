	DATA DICTIONARY - Wearablestats File

-------------------------------------------------------
Variable Naming Convention Key
-------------------------------------------------------

Code		Description
---------------------------
t		A time signal.
f		A frequency signal.
Body 		A body value.
Gravity 	A gravity value.
Acc		An acceleration value.
Gyro		A gyroscopic value.
Jerk		A combined linear acceleration and angular velocity value.
Mag		Magnitude measure.
std()		For standard deviation metrics.
mean()		For mean metrics.
X		One of 3 axial signals.
Y		One of 3 axial signals.
Z		One of 3 axial signals.


-------------------------------------------------------
Variable Definition
-------------------------------------------------------

subject
     Data Type: Integer
     Values: 1 to 30.
     Description: A subject is a volunteer who participated in the study, identified by a number.

activity
     Data Type: Character
     Values: 
		LAYING
		SITTING
		STANDING

		WALKING
		WALKING_DOWNSTAIRS

		WALKING_UPSTAIRS


     Description: An activity is the behavior of the subject at the time a measurement was taken.

tBodyAcc-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAcc-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAcc-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tGravityAcc-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tGravityAcc-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.
     Description: Time measure,

tGravityAcc-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAccJerk-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAccJerk-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAccJerk-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyro-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyro-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyro-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyroJerk-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyroJerk-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyroJerk-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAccMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tGravityAccMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAccJerkMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyroMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyGyroJerkMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAcc-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAcc-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAcc-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAccJerk-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAccJerk-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAccJerk-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyGyro-std()-X
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyGyro-std()-Y
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyGyro-std()-Z
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyAccMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyBodyAccJerkMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyBodyGyroMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

fBodyBodyGyroJerkMag-std()
     Data Type: Numeric
     Values: Standard deviation for subject-activity group.

tBodyAcc-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAcc-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAcc-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

tGravityAcc-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

tGravityAcc-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

tGravityAcc-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAccJerk-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAccJerk-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAccJerk-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyro-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyro-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyro-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyroJerk-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyroJerk-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyroJerk-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAccMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

tGravityAccMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyAccJerkMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyroMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

tBodyGyroJerkMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAcc-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAcc-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAcc-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAccJerk-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAccJerk-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAccJerk-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyGyro-mean()-X
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyGyro-mean()-Y
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyGyro-mean()-Z
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyAccMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyBodyAccJerkMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyBodyGyroMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

fBodyBodyGyroJerkMag-mean()
     Data Type: Numeric
     Values: Mean for subject-activity group.

