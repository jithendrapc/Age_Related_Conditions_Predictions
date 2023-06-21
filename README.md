# Age_Related_Conditions_Predictions
Goal 
The goal  is to predict if a person has any of three medical conditions. We have to predict if the person has one or more of any of the three medical conditions (Class 1), or none of the three medical conditions (Class 0). We will create a model trained on measurements of health characteristics.

To determine if someone has these medical conditions requires a long and intrusive process to collect information from patients. With predictive models, we can shorten this process and keep patient details private by collecting key characteristics relative to the conditions, then encoding these characteristics.

Dataset Description:
The  data comprises over fifty anonymized health characteristics linked to three age-related conditions. Our goal is to predict whether a subject has or has not been diagnosed with one of these conditions -- a binary classification problem.

Files and Field Descriptions:
train.csv - The training set.
Id Unique identifier for each observation.
AB-GL Fifty-six anonymized health characteristics. All are numeric except for EJ, which is categorical.
Class A binary target: 1 indicates the subject has been diagnosed with one of the three conditions, 0 indicates they have not.
test.csv - The test set. Your goal is to predict the probability that a subject in this set belongs to each of the two classes.
sample_submission.csv - A sample submission file in the correct format
