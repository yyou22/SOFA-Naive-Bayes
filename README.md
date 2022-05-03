# SOFA - Naive Bayes Classifier
Author: Yuzhe You

This is an implementation of Naive Bayes Algorithmn using MIMIC-III data on septic patients.
The goal of this project is to evaluate the SIRS scoring system through data extraction/visualization and machine learning.

# Naive Bayes Algorithm

Bayes classifiers use training data to calculate an observed probability of each class based on all the features. The probability links feature values to classes like a map. When labeling the test data, we utilize the feature values in the test data and the “map” to classify our test data with the most likely class.

This link provides more details about the Naive Bayes Algorithm:
http://www.socr.umich.edu/people/dinov/courses/DSPA_notes/07_NaiveBayesianClass.html

# Sequential Organ Failure Assessment Score

## SOFA Score

The sequential organ failure assessment score (SOFA score), previously known as the sepsis-related organ failure assessment score, is used to track a person’s status during the stay in an intensive care unit (ICU) to determine the extent of a person’s organ function or rate of failure. The score is based on six different scores, one each for the respiratory, cardiovascular, hepatic, coagulation, renal and neurological systems.

## Quick SOFA Score

The Quick SOFA Score (quickSOFA or qSOFA) was introduced by the Sepsis-3 group in February 2016 as a simplified version of the SOFA Score as an initial way to identify patients at high risk for poor outcome with an infection. The SIRS Criteria definitions of sepsis are being replaced as they were found to possess too many limitations; the “current use of 2 or more SIRS criteria to identify sepsis was unanimously considered by the task force to be unhelpful.” The qSOFA simplifies the SOFA score drastically by only including its 3 clinical criteria and by including “any altered mentation” instead of requiring a GCS <15. qSOFA can easily and quickly be repeated serially on patients.

See here for the full documentation presented in HTML format:
https://yyou22.github.io/SOFA-Naive-Bayes/