# GettingAndCleaningData: Course Project

As prerequisite download the dataset into the working directory and extract it so the relative path is ./UCI HAR Dataset

The attached R script, run_analysis.R, performs the following steps:

- Loads the activity and feature info
- Loads the train and test datasets and extract only the measurements on the mean and standard deviation for each measurement.
- Loads the activity and subject data for each dataset, and merges those columns with the dataset
- Merges the test and train datasets
- Converts the activity and subject columns into factors
- Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
- Produces the file run_analysis_tidy.txt with the tidy data.
