##Description

| Variables used in script  | Explanation |
| :------------- | :-------------: |
| `x_train` <br>`y_train` <br>`x_test`<br> `y_test`<br> `subject_train`<br> `subject_test`  | Contains the data from the downloaded files  |
| `x_data`<br>`y_data` <br> `subject_data` | Merge the previous datasets to further analysis  |
| `features` | Contains the correct names for the `x_data`
|`mean_and_sd_features` <br> `activities` | A numeric vector used to extract the desired data |
|`all_data`| Binds all the data in a single data set|
|`averages_data`|Independent tidy data set with the average of each variable for each activity and each subject|
 
##Transformations to clean up data

The script called `run_analysis.R` was created and does the following:

- [x] Merges the training and the test sets to create one data set
- [x] Extracts only the measurements on the mean and standard deviation for each measurement
- [x] Uses descriptive activity names to name the activities in the data set
- [x] Appropriately labels the data set with descriptive variable names
- [x] From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

