Getting and Cleaning Data Course Project
==========================================

This repository contains the R code and files for the Data Science's specialisation course "Getting and Cleaning data"

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analysis described in the 5 steps. It merges the training and test dataset. The UCI HAR Dataset must be extracted and the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. The output of the 5th step is called `tidy.txt`
