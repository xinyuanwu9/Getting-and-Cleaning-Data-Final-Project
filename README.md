# Getting-and-Cleaning-Data-Final-Project
This file summarizes the the data manipulation process for the Getting and Cleaning data course project. The output produced by script run_analysis.R is tidy.txt.
  1. Downloaded the data set from the web, and extracted to the working directory.
  2. Read the label of activities and variable names (features) from the folder.
  3. Subset the variable names including "mean" and "std". Clean the variable names by removing redundant characters.
  4. Read the training and testing data set. Combine the data with subject and activity variable for each data set.
  5. Merge the training and testing data set to form a full data set.
  6. Convert the subject and activity variable into factors.
  7. Create a new data set which calculates the mean of each variable for each activity and each subject. Export the final data set to tidy.txt.
