# Using AI to Predict Diabetes Diagnosis With Risk Factor Database

## Python 3 Libraries and Modules Used:
- numpy
- pandas
- matplotlib
- scikit-learn

## Purpose and Usage:

- Purpose - demonstrate the usage of Artificial Intelligence Classification Models via supervised learning in combination with medical data to further build and/or extrapolate medical diagnositc abilities

- Usage - this code uses the attached database 'diabetes_clean.csv' which is a compilation of diabetes diagnosis, medical, socioeconomic, and medical risk factors based of the CDC's BRFSS teleophone survey.
  
## Data Source:
- UCI Machine Learning Repository located here:

https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

This database was downloaded via Kaggle. This code was linked to the UCI Machine Learning Repository on 9/25/2023.

We will be mainly using the diabetes_clean.csv file which is originally named:
diabetes _ 012 _ health _ indicators _ BRFSS2015.csv - a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is class imbalance in this dataset. This dataset has 21 feature variables

Renaming was done for succinct-ness of the project and code.

The questions that this project endeavors to ask include the following:

1) Can survey questions from the BRFSS provide accurate predictions of an individual's diabetes diagnosis?
2) What risk factors are most predictive of diabetes?
3) Can we use a subset of the risk factors to accurately predict whether and individual has diabetes?
4) Can we create a short form of questions from the BRFSS using feature selection to accurately predict if someone might have or is at risk of diabetes?

Answers to these questions (literally and methodologically) can be found in the attached Jupyter Notebook
