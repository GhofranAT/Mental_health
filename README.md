# Mental Health
Analyzing the mental health in tech companies survey from 2014

## 1. Installation:

All libraries that are used in this project are installed with the Anaconda distribution.
Python version: Python 3.8.8

## 2. Project Motivation:

Mental health is one of the important aspects of human healthcare. However, I observed that many people do not nither believe in mental illness nor give it the same importance as physical illnesses when they encounter it. This motivated me to analyze a dataset related to mental health and get some insights into people's behaviors relating to it.

## 3.File Descriptions:

#### Mental_health_survey.ipynb:
A Jupyter notebook with all the python codes that were used to clean the data and analyze it.
### survey.csv: 
The source of the dataset

## 4. Project Details:
The main objective of this project was to analyze how people encounter mental health problems. The first thing that conflicted with the analysis process is that existed some illogical values of ages that were above 90 or much lower than 12. For this, all the illogical values were replaced with the mean of the logical age in the dataset. The second that conflicts with the analysis are the null values in the work-interfere column. The proportion of them was about 20.9%, so deleting the null values is not preferred since it may lead to specific insights. For that, A function was used to create dummy variables for that column. The project answered 3 questions from the dataset, which are:
- Does the family history of mental health affect the decision of seeking treatment?
- Is there any relation between the ability of the people to seek help for mental health problems and their ages?
- What is the proportion of people that feel that mental health problems interfere with work?

The results are shared in this link: [click_here](https://medium.com/@gftawfiq/mental-health-270dca4b0a1d)

## 5. Author:
This project was created by Ghofran Al Tawfiq
## 6. Data Source:
Kaggle.com[Data Source](https://www.kaggle.com/osmi/mental-health-in-tech-survey)

