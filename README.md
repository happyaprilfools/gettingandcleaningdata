# Getting and Cleaning Data

## README
This file describes the contents of this repository. 
It will also provide steps on running the R script in transforming the raw data set as proviced in the link of Project into a tidy dataset.

# References:

Project on Getting and Cleaning Data - Coursera - DOST - Module 3

# Contents
This section describes the contents of this repository.

Filename       | Description
-------------  | -------------
README.md      | Describes the content of the repository and steps in running tidy_data.
CODEBOOK.md    | Describes the variables within the tidied dataset
run_analysis.R | Analysis function of the raw data

# Setup
Before running the script, the following has to be setup:

The R Environment is installed.
Data has been downloaded.
Data has already been extracted to the default working directory of your R environment.
It is assumed that the directory structure and file names of the extracted files follows that of the origin ZIP file. The only exception is that the parent directory name has been renamed to "UCI_HAR_Dataset".

# Steps
To get the tidied data, please follow the following steps:

a. Source the analysis function into R and run the function. -source('<your default R working directory>/run_analysis.R'))
run_analysis()
  
b. Once the function has completed running, you will see one output file "tidy_data.txt" - in your working directory. 

c. To read the files into R, please use the following functions:

# Open and read text file
read.table("tidy_data.txt", header=TRUE)

AAAR_happyaprilfools
