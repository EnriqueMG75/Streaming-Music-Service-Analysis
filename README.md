
# Streaming Music Service Analysis

This Github repo is complementary to this Medium post:
https://medium.com/@enriquemg_52937/science-can-predict-if-you-will-give-up-spotify-71d89320b9c0

# Machine Learning with Apache Spark

The purpose of this project is to analyze data from a music streaming service to create a 
Machine Learning model that let us forecast if users will give up the subscription (Churn).

The project is organized in these steps: 

1 Set up of the Spark session on IBM Watson Studio and load data

2 Data exploration and Data Wrangling

3 Churn definition

4 Data Analysis

5 Feature Engineering

6 Machine Learning Modeling

7 Feature Importance Analysis

8 Conclusion

# Motivation

To creates the best possible model to forecast if the users will give up the 
streaming music service.

This motivation have been achived because I have created a model with an accuracy 
of 91%

# Technologies and Libraries used

Apache Spark, IBM Cloud, IBM Watson Studio, Jupyter Notebook, PySpark, Pandas,
MatplotLib, Seaborn, Python 3.6

# Files

- Streaming_Music_Service_Analysis.ipynb
- README.md 

# Summary of the results

We have build and train a Gradient-Boosted model with a very good accuracy of
91% and an F1 score of 0.90868.
The most important feature, the one that most contributes to the model’s success is subscription_time, followed by the rolls adverts watched by users. Third, the number of thumbs up. Fourth, the songs played per session. Fifth, the number of thumbs down. 

# Data Source

Data belong to Udacity Data Scientist Nanodegree and comes from a simulated streaming music service