# getting_cleaning_data_week4Project

"Getting and Cleaning Data" Week 4 project- Johns Hopkins Coursera Course.
Contains R code, codebook, and tidy data set for the assignment.

Files:
CodeBook.md describes the how to use all this, variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file. Here are the five steps:

Merges the training and the test sets to create one data set. (Use command rbind) 
Extracts only the measurements on the mean and standard deviation for each measurement. (Use grep command to get column indexes to get mean() and std() ) 
Uses descriptive activity names to name the activities in the data set. Convert activity labels to characters and add a new column as factor.
Appropriately labels the data set with descriptive variable names. Give the selected descriptive names to variable columns.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. ( group_by and summarize_each in dplyr package) 
tidyData.txt is the output of the final step
