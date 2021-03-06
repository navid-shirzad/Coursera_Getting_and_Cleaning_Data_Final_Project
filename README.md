#Getting and Cleaning Data - Course Project
This is the readme file of the course project for the Getting and Cleaning Data Coursera course, done by **`Navid Shirzad`**. 

##run_analysis.R
The R script, **`run_analysis.R`**, does the following:

* Download the dataset if it does not already exist in the working directory
* Load the activity and feature info
* Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
* Loads the activity and subject data for each dataset, and merges those columns with the dataset
* Merges the two datasets
* Converts the activity and subject columns into factors
* Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

##tidy.txt
The end result is shown in the file **`tidy.txt`**.

##CodeBook.md
**`CodeBook.md`** is a code book that describes the variables, the data, and any transformations or work that was performed to clean up the data called.
