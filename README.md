GettingAndCleaningData

run_analysis.R should do the following:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Please upload the tidy data set created in step 5 of the instructions. 
Please upload your data set as a txt file created with write.table() using row.name=FALSE 
(do not cut and paste a dataset directly into the text box, as this may cause errors 
saving your submission).
Repository structure
-directory /project_data, contains all files needed for evaluation by run_analysis.R

-README.md, this file.

-codebook.md, contains the description of variables produced by run_analysis.R

-run_analysis.R, is the R script that produces the tidyData.txt file

-tidyData.txt, is the file generated by run_analysis.R, which contains the reshaped data set processed from /project_data

Running the run_analysis.R script
create a directory on your local machine where you would like to clone the repository
change directory into what you created in #1
clone this repository : git clone https://github.com/dholtz/GettingAndCleaningData
change directory into the GettingAndCleaningData directory
start R from the command line
source("run_analysis.R")
How the, run_analysis.R script works
Review the run_analysis.R script in the root of the cloned repository.

This script is heavily commented and explains step-wise what is happening. DRY Principle (http://en.wikipedia.org/wiki/Don't_repeat_yourself)
