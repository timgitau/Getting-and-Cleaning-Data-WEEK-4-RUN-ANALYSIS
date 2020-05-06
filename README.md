# Getting-and-Cleaning-Data-WEEK-4-RUN-ANALYSIS
#Week 4 projects with Readme and  Run Analysis files
#You should create one R script called run_analysis.R that does the following.

#Merges the training and the test sets to create one data set.
#Extracts only the measurements on the mean and standard deviation for each measurement.
#Uses descriptive activity names to name the activities in the data set
#Appropriately labels the data set with descriptive variable names.
#From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#How the script works and the code book describing the variables.
# 1. Merge the training and the test sets to create one data set.

# WORKING DIRECTORY IS SET TO - UCI HAR Dataset
# Import training data from files & Name the columns
# Merge Data into complete training set
# Import test data from files & Name columns
# Merge Data into complete test set
# Combine Training Data Set and Test Data Set into one Merged Data Set
# Create columns vector to prepare data for subsetting

## 2. Extract only the measurements on the mean and standard deviation for each measurement

# Create a vector that indentifies the ID, mean & stddev columns as TRUE
# Update MergedDataSet based on previously identified columns


### 3. Use descriptive activity names to name the activities in the data set

# Add in descriptive activity names to MergedDataSet & update columns vector


#### 4. Appropriately label the data set with descriptive activity names.

# Tidy column names
# Update MergedDataSet with new descriptive column names
# Remove activityType column

##### 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Averaging each activity and each subject as Tidy Data
# Export tidyData set 
