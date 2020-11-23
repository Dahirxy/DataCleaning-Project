# DataCleaning-Project
The included R script, run_analysis.R, conducts the following:

1.Downloads the dataset from web into the working directory called "data_cleaning_project".

2. Read both the train and test datasets and merge them into features(measurements), activity and subject , respectively.

3. Load the features data, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names to descriptive. 

4. Extract data by selected columns(from step 3), and merge feasures, activity and subject data.
 Also, replace activity column to it's name by refering activity label (loaded step 3).

5.Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity.
 The result is shown in the file Tidy.txt.
