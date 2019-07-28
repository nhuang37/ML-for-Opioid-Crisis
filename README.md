# ML-for-Opioid-Crisis
Project for 'DS-GA 1001 Introduction to Data Science'

## Overview
The opioid crisis is an unprecedented epidemic. National surveys have been conducted to better understand the drug abuse phenomenon. Critical insights can be uncovered by performing feature selection related to drug abuse behavior, so as to obtain a good understanding of a user‘s behavioral patterns, and build a model to predict the likelihood of opioid abuse such that healthcare providers, and families of at-risk users can take preventive measures.

## Data
2015 National Survey on Drug Use and Health (NSDUH-2015). 
Download the data from [here](https://www.datafiles.samhsa.gov/study-dataset/national-survey-drug-use-and-health-2015-nsduh-2015-ds0001-nid16894).

## Feature Selection using Iterative Mutual Information Selection algorithm
we propose a novel iterative conditional mutual information feature selection algorithm (CMI-FS). The algorithm iteratively selects features that maximize their mutual information with the target variable conditionally to any other feature already selected. 

## Random Forest model results and interpretation using LIME package
A random forest of max_depth=10 and n_estimators=20 is selected as the best model from hyper-parameter tuning. We also utilize LIME to interpret the model on the user instance basis.
