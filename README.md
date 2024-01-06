# Spotify Track Popularity Prediction Project

![image](https://github.com/EloynVazquez/Predicting_Track_Popularity/assets/150309159/a93fcd92-0c67-44cd-aa47-c0160be77a84)

By Eloyn Vazquez

## 🎧 Introduction
Welcome to my Capstone Project, where we explore the Spotify dataset to understand and predict track popularity. This project dives into the vast musical repository of Spotify, analyzing various factors that influence a track's success on the platform. Our goal is to unveil the complexities of musical preferences and trends, using advanced data science techniques.
## 🎯 Project Overview
The project's main objective is to use machine learning to predict the popularity of tracks on Spotify. We aim to answer questions like:

What elements contribute to the popularity of a track on Spotify?
Can we accurately predict a track's popularity using these elements?
How do various musical features and artist influences affect track popularity?
What insights can we draw from the data to understand music trends?

## 📊 Dataset
Our dataset is sourced from Spotify and includes a wide array of attributes related to tracks. Key features include:

Track attributes like tempo, energy, and valence.
Artist popularity and influence.
User engagement metrics and play counts.
Temporal trends and release dates.

## 🚀Roadmap

## 🧹 Data Cleaning
The data cleaning process involved several steps to ensure the dataset was ready for analysis:

Loaded the dataset and performed an initial overview to understand its shape, columns, and data types.
Checked for missing ('NaN') values, duplicates, and unique values in each column.
Extracted the first artist from the 'artists' list and counted the occurrences for each song.
Created a copy of the dataset named 'spotify' for further processing.

## 🕵️‍♂️ Exploratory Data Analysis (EDA)
Performed EDA to identify patterns, anomalies, and insights within the data.
Analyzed relationships between variables, visualized dependencies, and modified data based on correlations.
Checked the correlation coefficient of numeric variables and visualized these relationships.
Explored the distribution of various features like popularity, danceability, energy, loudness, etc., through histograms and scatter plots.
Conducted hypothesis testing for each numeric feature against the target variable 'popularity'.

## 🧠 Feature Engineering and Baseline Modeling
Handled categorical variables like 'key' and 'mode' and transformed them into numerical values.
Classified the top 25% of songs as popular and the bottom 75% as not popular for binary classification.
Selected features including acousticness, danceability, duration_ms, energy, instrumentalness, key, liveness, mode, speechiness, tempo, valence.
Split the data into training and testing sets, with 80% for training and 20% for testing.

## 📈 Model Optimization and Predictions
Tested multiple models including Logistic Regression, Random Forest Classifier, K-Nearest Neighbors Classifier, and Decision Tree Classifier.
Evaluated models based on accuracy and AUC scores.
Random Forest Classifier emerged as the most effective model with an accuracy of 88.04%.
Decision Tree Classifier showed a superior AUC score of 61.27%, despite a lower accuracy.
K-Nearest Neighbors Classifier and Logistic Regression models demonstrated reasonable accuracy scores.

## 📝 Conclusion and Learnings
The project successfully predicted Spotify track popularity using various machine learning models.
The analysis revealed significant insights about the relationship between different musical features and popularity.
The Random Forest Classifier was the most effective model, highlighting the robustness of machine learning in analyzing music trends.
The project underscores the importance of data cleaning, feature engineering, model selection, and evaluation in predictive modeling.



