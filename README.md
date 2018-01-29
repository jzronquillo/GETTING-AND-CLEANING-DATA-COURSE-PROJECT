### README FILE FOR GETTING AND CLEANING DATA COURSE PROJECT

##### This repository contains the R code and documentation files for the Data Science's track course "Getting and Cleaning data".

#### FILES

##### * CodeBook.md, the code book, which describes the variables, the data, and any transformations or work that was performed to clean up the data

##### * run_analysis.R, the R script that was used to create the data set 
#####  run_analysis.R does the following:
##### 1. Merges the training and the test sets to create one data set.
##### 2. Extracts only the measurements on the mean and standard deviation for each measurement.
##### 3. Uses descriptive activity names to name the activities in the data set
##### 4. Appropriately labels the data set with descriptive variable names.
#####       * prefix t is replaced by time
#####       * Acc is replaced by Accelerometer
#####        * Gyro is replaced by Gyroscope
#####       * prefix f is replaced by frequency
#####        * Mag is replaced by Magnitude
#####        * BodyBody is replaced by Body
##### 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject


##### * tidy_data.txt, contains the tidy data set.

