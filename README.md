The script creates a directory to extract the compressed data to.
It then downloads and extracts the data for the assignment.
Each file is read in to R and merged such that subject and activity data are in one data form.
The mean and SD are extracted.
The activity results are recoded from numeric to character data (ie. from 4 or 5 to sitting or standing respectively) as coded in the activity_labels.txt file
Data headings are cleaned and renamed.
Clean data is output as asignment_tidy_data.txt
