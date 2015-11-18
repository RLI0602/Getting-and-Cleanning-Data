This file explains how all of the scripts work and how they are connected.
Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
Create one R script called run_analysis.R that does the following: 
    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement. 
    Uses descriptive activity names to name the activities in the data set.
    Appropriately labels the data set with descriptive variable names. 
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
two output files are generated in the current working directory:
    merged_data.txt: it contains a data frame called cleanedData with 10299*68 dimension.
    data_with_means.txt: it contains a data frame called result with 180*68 dimension.


