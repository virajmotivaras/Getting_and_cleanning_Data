Getting_and_cleaning_Data
==========================

Created this repository for the course project

The code takes for granted all the data is present in the same folder, un-compressed and without names altered.
The folder structure is as follows:
Root directory
  |
  |----run_analysis.R
  |----activity_labels.txt
  |----averages_data.txt
  |----features.txt
  |----test (folder)
      |----X_test.txt
      |----y_test.txt
      |----subject_test.txt
  |----train (folder)
      |----X_train.txt
      |----y_train.txt
      |----subject_train.txt

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

The output of the 5th step is called averages_data.txt, and uploaded in the course project's form
