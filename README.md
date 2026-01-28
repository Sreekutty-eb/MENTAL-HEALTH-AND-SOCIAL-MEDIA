# Mental Health Analysis Using Social Media Data
## Project Overview

This project analyzes how social media activity relates to mental health conditions. Using data science and machine learning techniques, the project explores patterns in user behavior and predicts a person's mental state based on social media-related features.

Mental health issues are increasing worldwide, and social media plays a major role in emotional well-being. This project aims to use data to understand and model that relationship.

## Objectives

Analyze mental health trends from social media dataset

Perform Exploratory Data Analysis (EDA) to find patterns

Preprocess and encode categorical data

Build machine learning models to predict mental state

Compare model performances

## Dataset Description

The dataset contains information such as:

Feature	Description
person_name	Name of the individual
date	Date of activity
gender	Gender of the user
platform	Social media platform used
mental_state	Target variable (mental health condition)

The dataset is used to understand how user characteristics and platform usage relate to mental health.

 ## Technologies Used

Python
 
Pandas – Data handling

Matplotlib – Data visualization

Scikit-learn – Machine Learning models

Jupyter Notebook

## Project Workflow
1️ Data Loading

Dataset loaded using Pandas

Checked structure using .head(), .tail()

Missing values checked using .isna().sum()

2️ Data Preprocessing

Categorical columns converted using Label Encoding

Features and target variable separated

Data split into:

Training set (80%)

Testing set (20%)

## Exploratory Data Analysis (EDA)

Visualizations created using Matplotlib

Analyzed:

Distribution of mental states

Gender vs mental health

Platform usage trends

## Machine Learning Models Used
Logistic Regression	Baseline classification model
Decision Tree Classifier	Rule-based prediction
Random Forest Classifier	Ensemble learning model

## Future Improvements

Use deep learning models

Add more psychological features

Use real-time social media data

Deploy as a web application

## Conclusion

This project demonstrates how data science and machine learning can be used to analyze and predict mental health conditions using social media data. It highlights the role of AI in supporting mental health awareness and early detection.
