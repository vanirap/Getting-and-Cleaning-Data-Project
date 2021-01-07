# Codebook
This code book describes the variables, the data, and any transformations or work performed in run_analysis.R to clean up the data.

The R script run_analysis.R does the following. 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The steps followed to implement this in the script are:
* Load dplyr library
* Download the dataset and extract it
* Assisn each data to a variable
* Merge the training and the test sets to create one data set
* Extract only the measurements on the mean and standard deviation for each measurement
* Uses descriptive activity names to name the activities in the data set
* Appropriately label the data set with descriptive activity names
* Create a second, independent tidy data set with the average of each variable for each activity and each subject
* Export FinalData into FinalData.txt file
