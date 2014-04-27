CodeBook for "tidydataout.txt"
===

by: James Ferre

class: Getting and Cleaning Data (getdata-002)
___

The following highlights the variables of "tidydataout.txt" created by the "run_analysis.R" script. Note that in addition to this markdown document, a complete explication of the "run_analysis.R" script is available in README.md file. Furthermore, "run_analysis.R" script includes step by step comments.

About "tidydataout.txt", note that while the file has the .txt extension, it is actually formatted as a .csv.

    1. activity: factor with 6 levels, in order: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING, indicated the activity being perfomed at the moment of data gathering,

    2. subject: integer (numeric) value from 1 to 30 indicating the subject.

    * For variables 3 to 68 the varaible is numeric and the name indicates:

        * Acc and Gyro: data origin, accelerometer and gyroscope, respectively.
        * -XYZ: the three dimensional axis, X,Y, or Z, respectiveli (3-axial)
        * Body and Gravity: Acceleratuion signal source, Body or Gravity, determined using low pass Butterworth filter with a corner frequency of 0.3 Hz. 
        * -mean() and -std(): Mean value or Standard deviation, respectively.
        * t of f: t denotes time domain signals, these were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. On the other hand, f denotes the use of a Fast Fourier Transform (FFT) was applied.
    
    3. tBodyAcc-mean()-X
    4. tBodyAcc-mean()-Y
    5. tBodyAcc-mean()-Z
    6. tBodyAcc-std()-X
    7. tBodyAcc-std()-Y
    8. tBodyAcc-std()-Z
    9. tGravityAcc-mean()-X
    10. tGravityAcc-mean()-Y
    11. tGravityAcc-mean()-Z
    12. tGravityAcc-std()-X
    13. tGravityAcc-std()-Y
    14. tGravityAcc-std()-Z
    15. tBodyAccJerk-mean()-X
    16. tBodyAccJerk-mean()-Y
    17. tBodyAccJerk-mean()-Z
    18. tBodyAccJerk-std()-X
    19. tBodyAccJerk-std()-Y
    20. tBodyAccJerk-std()-Z
    21. tBodyGyro-mean()-X
    22. tBodyGyro-mean()-Y
    23. tBodyGyro-mean()-Z
    24. tBodyGyro-std()-X
    25. tBodyGyro-std()-Y
    26. tBodyGyro-std()-Z
    27. tBodyGyroJerk-mean()-X
    28. tBodyGyroJerk-mean()-Y
    29. tBodyGyroJerk-mean()-Z
    30. tBodyGyroJerk-std()-X
    31. tBodyGyroJerk-std()-Y
    32. tBodyGyroJerk-std()-Z
    33. tBodyAccMag-mean()
    34. tBodyAccMag-std()
    35. tGravityAccMag-mean()
    36. tGravityAccMag-std()
    37. tBodyAccJerkMag-mean()
    38. tBodyAccJerkMag-std()
    39. tBodyGyroMag-mean()
    40. tBodyGyroMag-std()
    41. tBodyGyroJerkMag-mean()
    42. tBodyGyroJerkMag-std()
    43. fBodyAcc-mean()-X
    44. fBodyAcc-mean()-Y
    45. fBodyAcc-mean()-Z
    46. fBodyAcc-std()-X
    47. fBodyAcc-std()-Y
    48. fBodyAcc-std()-Z
    49. fBodyAccJerk-mean()-X
    50. fBodyAccJerk-mean()-Y
    51. fBodyAccJerk-mean()-Z
    52. fBodyAccJerk-std()-X
    53. fBodyAccJerk-std()-Y
    54. fBodyAccJerk-std()-Z
    55. fBodyGyro-mean()-X
    56. fBodyGyro-mean()-Y
    57. fBodyGyro-mean()-Z
    58. fBodyGyro-std()-X
    59. fBodyGyro-std()-Y
    60. fBodyGyro-std()-Z
    61. fBodyAccMag-mean()
    62. fBodyAccMag-std()
    63. fBodyBodyAccJerkMag-mean()
    64. fBodyBodyAccJerkMag-std()
    65. fBodyBodyGyroMag-mean()
    66. fBodyBodyGyroMag-std()
    67. fBodyBodyGyroJerkMag-mean()
    68. fBodyBodyGyroJerkMag-std()