Source Data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Details of source data: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 



Merges the training and the test sets to create one data set
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 


Data files:
README.txt
features_info.txt
features.txt
activity_labels.txt
train/X_train.txt
train/y_train.txt
test/X_test.txt
test/y_test.txt


Require the following libraries: reshapre2 & data.table 
Load the features and activity labels.
Extract the mean and standard deviation .
Process datas
Merge data set. 

Result is a saved tiny_data data set
