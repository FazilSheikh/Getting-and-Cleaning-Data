Getting-and-Cleaning-Data
=========================

My Repository for the course 'Getting and Cleaning Data' on Coursera
It contains the following files :
README.md
CodeBook.md
run_analysis.R

The README file gives overall description about the project. 
The code book describes the variables, the data and the transformations/work performed to clean up the data.
The R script called 'run_analysis.R' that does the following:

1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names. 
5.Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

How Script Works :

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. 
This tidy dataset will be written to a tab-delimited file called tidy.txt.

STEPS :

Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory 
Run source("run_analysis.R"), then it will generate a new file tidy.txt in your working directory.
