# getting_and_cleaning_data_final_project

This repository is a submission by Joseph Michalski for the final project for the Getting and Cleaning data class through Coursera.

The data set used for this is found at this website: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones.

There are three files on this repository.

The first file, CodeBook.md, describes the variables, data and transformations on the data to create the ending, tidy data set.

The second file, run_analysis.R, prepares the data, then runs the transformations described in the code book.  These steps can be summarized:
  Merges the training and test data sets to create one dataset.
  Extracts the measurements for the mean and standard deviation for each observation.
  Renames the activities with descriptive activity names to name the activities in the dataset.
  Appropriately labels the dataset with more descriptive variable names.
  Creates an independent, tidy dataset from the dataset created in the above steps with the average of each variable for each activity and
  subject.
  
The final file, FinalData.txt, is the exported dataset created by the transformations described above.
