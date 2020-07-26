Source of the original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The attached R script (run_analysis.R) performs the following to clean up the data:


Merges the training and the test sets to create one data set.

Extracts only the measurements on the mean and standard deviation for each measurement.

Uses descriptive activity names to name the activities in the data set

Appropriately labels the data set with descriptive variable names.

From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


The script also appropriately labels the data set with descriptive names:
  tbodyacc-mean-x   
  
  tbodyacc-mean-y   
  
  tbodyacc-mean-z   
  
  tbodyacc-std-x  
  
  tbodyacc-std-y  
  
  tbodyacc-std-z  
  
  tgravityacc-mean-x  
  
  tgravityacc-mean-y  
