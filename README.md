Getting and Cleaning Data: Course Project
=========================================

About the raw data
------------------
The features (561 of them) are unlabeled and can be found in the x_test.txt. 
The activity labels are in the y_test.txt file.
The test subjects are in the subject_test.txt file.

The same holds for the training set.

I created a script called run_analysis.R which will merge the test and training sets together.
After merging, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, I created a tidy data set containing the means of all the columns per test subject and per activity.
This tab-delimited dataset can be found in the tidy.txt file.

The CodeBook.md file explains the transformations performed and the resulting data and variables.

