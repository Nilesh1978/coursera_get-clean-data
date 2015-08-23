## Code Book

### Subject and Activity

These variables identify the unique subject/activity pair the variables relate to:

* Subject: the integer subject ID.
* Activity: the string activity name
  * Walking
  * Walking Upstairs
  * Walking Downstairs
  * Sitting
  *	Standing
  * Laying
	
### Variables
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* features contains the correct names for the x_data dataset, which are applied to the column names stored in
`mean_and_std_features`, a numeric vector used to extract the desired data.
* A similar approach is taken with activity names through the activities variable.
* all_data merges `x_data`, `y_data` and `subject_data` in a big dataset.

### Attributes
After setting the source directory for the files, read into tables the data located in

* features.txt
* activity_labels.txt
* subject_train.txt
* x_train.txt
* y_train.txt
* subject_test.txt
* x_test.txt
* y_test.txt
