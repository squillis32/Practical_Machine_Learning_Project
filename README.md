# Practical_Machine_Learning_Project
===================================================================================
This repository is for the Coursera "Practical Machine Learning" course project.

The goal is to predict the manner in which 6 participants completed a set of exercises.
The data comes from accelerometers on the belt, forearm, arm, and dumbell of the particpants while exercising.

The training data for this project are available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

Both the training data frame with 19,622 observations and the testing data frame with 20 observations consists of 160 variables.
We will list the first 11:

1 - X (integer)
2 - user_name (character)
3 - raw_timestamp_part_1 (int)
4 - raw_timestamp_part_2 (int)
5 - cvtd_timestamp (character)
6 - new_window (character)
7 - num_window (integer)
8 - roll_belt (numeric)
9 - pitch_belt (numeric)
10 - yaw_belt (numeric)
11 - total_accel_belt (integer)

=========================================================================================

Peer Review Portion
Your submission for the Peer Review portion should consist of a link to a Github repo with your R markdown and compiled HTML file describing your analysis. Please constrain the text of the writeup to < 2000 words and the number of figures to be less than 5. It will make it easier for the graders if you submit a repo with a gh-pages branch so the HTML page can be viewed online (and you always want to make it easy on graders :-).

=============================================================================================

Files
Practical_Machine_Learning.Rmd, Practical_Machine_Learning_template.md, Practical_Machine_Learning.html contains the R scripts that performs the analysis on the raw data.
