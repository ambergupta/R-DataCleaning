
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. 
The goal is to prepare tidy data that can be used for later analysis.

About Data

This data is collected for wearable computing for Samsung Galaxy S smartphone for analysis. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Data source

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Script

This script take the test and training data and produces tidy data set. 1- Merges the training and the test sets to create one data set. 2- Extracts only the measurements on the mean and standard deviation for each measurement. 3- Sets descriptive activity names to name the activities in the data set 4- Appropriately labels the data set with descriptive variable names. 5- Generates an independent tidy data set with the average of each variable for each activity and each subject.

How to Run

Run the script from the same folder where you have extracted the zipped data.

$Rscript run_analysis

Output

Script generate two data sets 
 - data_tidy.txt 
- data_tidy_mean.txt
