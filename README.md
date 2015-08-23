##Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course. The R script, `run_analysis.R`, does the following:

1. Assumes that files that is already downloaded. Unzipped files are in the folder `/data/UCI HAR Dataset`
2. Read data from the files into the variables
3. Merges the training and the test sets to create one data set
4. Extracts only the measurements on the mean and standard deviation for each measurement.
5. Use descriptive activity names to name the activities in the data set
6. Appropriately label the data set with descriptive variable names. Change `t` to `Time`, `f` to `Frequency`, `mean()` to `Mean`
and `std()` to `StdDev`
7. Create a second, independent tidy data set with the average of each variable for each activity and each subject

#Files

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analyses described in the 5 steps. 
They can be launched in RStudio by just importing the file.

The `tidydata.txt` that consists of independent tidy data set with the average of each variable for each activity 
and each subject. This file is also uploaded
