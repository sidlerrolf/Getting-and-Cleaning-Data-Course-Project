# Getting-and-Cleaning-Data-Course-Project
Coursera - Peer-graded Assignment - Week 4
Link to data source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

### STEP 1: Merges the training and the test sets to create one data set
## read data into data frames
## add column name for subject files
## add column names for measurement files
## add column name for label files
## combine files into one dataset

### STEP 2: Extracts only the measurements on the mean and standard deviation for each measurement.
## determine which columns contain "mean()" or "std()"
## ensure that we also keep the subjectID and activity columns
## remove unnecessary columns

### STEP 3: Uses descriptive activity names to name the activities in the data set.

### STEP 4: Appropriately labels the data set with descriptive activity names. 
## convert the activity column from integer to factor

### STEP 5a: load reshape2 package
## load the reshape2 package (will be used in STEP 5)

### STEP 5b: Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
## create the tidy data set
## write the tidy data set to a file
