# Diabetes case study

## Dataset and purpose

The dataset I used was already wrangled (the data was clean and tidy). The purpose of this exercise was to showcase my ability to train, tune, test and extract information from supervised machine learning models.
<br>


## Summary of Findings
In this case study we wanted to analyze the likelyhood of diabetes given certain factors such as age, glucose, BMI ...

Given that there was a reasonable amount of class imbalance (with less than 35% of patients having diabetes), I chose to consider the f1 score to evaluate the accuracy of our models.

I used 3 different supervised machine learning techniques to predict whether or not the patient would have diabetes. The three techniques used were AdaBoostClassifier(), SVC(), and RandomForestClassifier(). The AdaBoostClassifier was the fastest and had the highest f1_score.

Furthermore all three models highlighted that the feature that was the most predictive of diabetes was glucose followed by age and BMI (the two latter were not given in order of importance, as they differ in the RandomForestClassifier() and AdaBoostClassifier()).


## Downloading the Dataset

The dataset has been included in the repository since it is very small (<25KB).
