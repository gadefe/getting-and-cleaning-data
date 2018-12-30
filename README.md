# Getting and Cleaning data

The R script, run_analysis.R, does the following:

1. Download the dataset in the working directory if not existing
2. Load the activity and feature information
3. Loads both the training and test datasets and keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8. The end result is save in the file tidy.txt.
