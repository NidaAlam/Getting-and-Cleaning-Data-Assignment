#Getting and Cleaning Data Course Project

What you find in this repository
CodeBook.md: information about raw and tidy data set and elaboration made to transform them
LICENSE: license terms for text and code
README.md: this file
run_analysis.R: R script to transform raw data set in a tidy one
How to create the tidy data set
clone this repository: git clone git@github.com:maurotrb/getting-cleaning-data-2014-project.git
download compressed raw data
unzip raw data and copy the directory UCI HAR Dataset to the cloned repository root directory
open a R console and set the working directory to the repository root (use setwd())
source run_analisys.R script (it requires the plyr package): source('run_analysis.R')
In the repository root directory you find the file sensor_avg_by_act_sub.txt with the tidy data set.
