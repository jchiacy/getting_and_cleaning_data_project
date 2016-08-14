## Requirements
#### 1) Merges the training and the test sets to create one data set.
##### The training and test datasets were read and stored in working directory. 
##### The following files were read and merged into one dataset
##### features.txt, activityType, subjectTrain, xTrain, yTrain | subjectTest, xTest, yTest

#### 2) Extracts only the measurements on the mean and standard deviation for each measurement.
##### Create logical vector so that we can subset out the required columns

#### 3) Uses descriptive activity names to name the activities in the data set

#### 4) Appropriately labels the data set with descriptive variable names.
##### using gsub to appropriately label the dataset

#### 5) From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
##### create tidyData set which includes the average of each vairable for each activity and subject. 
