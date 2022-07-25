# Cleaning_Data
 
Final project in the Getting and Cleaning Data course

The run_analysis.r program does the following:
1. Downloads the dataset archive file
2. Unzips the dataset archive
3. Imports the following files
4. Perform a column combine to merge subjects, activities, and data into one table: allSubjects & allActivities & allData -> mergedData
5. Replace numeric activity identifiers with descriptive activity identifiers in mergedData table
6. Extract only mean and standard deviation features from the mergeData table into the reducedData table
7. Perform text substitutions to create more descriptive variable names for the features in the reducedData table
8. Use mean to summarize the features grouped by both the subject and activity variables into the tidyData data-frame
9. Write out the tidyData data-frame into a tab delimited text file.
