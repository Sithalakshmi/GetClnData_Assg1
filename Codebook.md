The <b>run_analysis.R</b> script does the foloowing:
* Merges the training and test sets to create one data set from X, subject and Y files within the source data.
* Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement.
* Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set.
* Labels the data set with descriptive names. Cleansing of data is done to remove brackets and underscores.
* Creates another independent tidy data set with the average of each measurement for each activity and each subject.
