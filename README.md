# run_analysis.R

This is the R script submitted for the Week 4 programming assignment of the 'Getting and
Cleaning Data' class in the DataScience specialization. This script assumes that the original 
dataset from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
is downloaded and unzipped to the current working directory.

This script performs the following actions
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
