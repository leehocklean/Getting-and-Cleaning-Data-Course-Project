# Getting-and-Cleaning-Data-Course-Project

Executive summary for the course project for Coursera's Getting and Cleaning Data course.


The R script, 'run_analysis.R', runs the following procedures:


1. Download dataset if it does not already exist in the working directory

2. Load the activity and feature information

3. Load the training and test datasets, and retain only those columns which
 reflect a mean or standard deviation

4. Load the activity and subject data for each dataset and merge the columns with the dataset

5. Merge the two datasets

6. Convert the columns for 'activity' and 'subject' into factors

7. Create a tidy dataset that consists of the average (mean) value of each
 variable for each subject and activity pair.



The resultant output is a file called 'tidy.txt'.