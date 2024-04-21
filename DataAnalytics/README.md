# Prediction and Recommendation System of Spotify Tracks

**Bug Killer** (Yixuan Chen, Yushi Dai, Zhizhen Xie, Muchen Liang) - Columbia Engineering

**Data Set:** https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

## Introduction:

The music industry is highly competitive, with thousands of new songs being released every day. To be successful, musicians and record labels need to understand what makes a song popular and how to promote it effectively. In recent years, machine learning algorithms have been used to predict the popularity of songs based on various features.
The dataset we used in this project is one found on Kaggle with  Spotify tracks over a range of 125 different genres, and each track has some audio features associated with it. There are in total of 20 columns in this dataset: except for the common ones like artist, track name, and album name, there are also more professional and music-related columns like energy, acousticness, danceability, tempo, and likeness. Through this project, we first performed data preprocessing procedures as well as Exploratory Data Analysis, and then built several predictive models including classification models XGBoost, Decision Tree, Random Forest, and regression models Linear Regression and Logistic Regression, which can help us understand what factors contribute to a song's popularity; finally, we made a recommendation system that could return a playlist of 10 songs with the greatest cosine similarity with the specific track input.

## Results:

<img src="https://github.com/ycsilvia/Coursework/blob/main/DataAnalytics/Example%20of%20result%20of%20the%20recommended%20system.jpg" width="128"/>
