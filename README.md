Wearable Stats File Processing
=================================================================
Author: S.Grunert  
Create: 14December2014  
Subject: Coursera Course: Getdata-016: Project 1  


Introduction
-----------------------------------------------------------------
The data set in the wearablestats file is a combination and summarization of study data from the Human Activity Recognition Using Smartphones Dataset, Version 1.0.[1][2] A study data package is provided as a zip file and was used as the raw data input for the wearablestats file.[3] Downstream processing to produce the wearablestats file is described below.


Original Study Design
-----------------------------------------------------------------
Excerpt from Study README file:[3]

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. 


Github Repository Contents
-----------------------------------------------------------------
README File:      This document.
run_analysis.R File: 	 An R script, with comments, for processing study data.
Wearablestats Code Book: A data dictionary for the wearablestats file produced by run_analysis.R.


Downstream Data Processing
-----------------------------------------------------------------
Data processing combines the training and test raw datasets from the study, summarizes the mean and standard deviation columns by subject-actvity, and applies descriptive variable names. 

The sequence of data processing is as follows:

1) Initialize data directory.

2) Download zip file from the study website and unzip study raw data into the data directory.

3) Read in applicable study files and prepare subject-activity row identifiers.

4) Read in data files, label variable columns, reduce the number of columns, and merge into a single file.

5) Melt the combined data by subject-activity, aggregate variables as means, and otherwise reshape into a tidy dataset.

6) Write the tidy dataset to a flat file.

7) Clean-up post processing.


Source Data Acknowledgements
-----------------------------------------------------------------
Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.
activityrecognition@smartlab.ws
www.smartlab.ws



References
-----------------------------------------------------------------
[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

[2] For More on Study: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

[3] For Study Raw Data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip





