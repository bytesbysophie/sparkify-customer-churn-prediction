# Sparkify Customer Churn Prediction

## Table of Contents
1. [Installation](#Installation)
2. [Project Motivation and Description](#Project-Motivation)
3. [File Descriptions](#File-Descriptions)
4. [Authors and Acknowledgements](#Authors-Acknowledgements)

## Installation <a name="Installation"></a>
Following libraries must be installed for running the notebook:

    - pyspark
    - pandas
    - matplotlib
    - seaborn
    - user_agents (pip install pyyaml ua-parser user-agents)

## Project Motivation and Description <a name="Project-Motivation"></a>

This project aims to predict customer churn for the fictional music streaming service Sparkify using PySpark.

In more detail, the goal is to identify users with a high churn risk by finding patterns in the behaviour of already churned users.

For this project a small subset of the user log data has been provided to locally build a pyspark model that can be scaled on a much bigger dataset on a distributed spark cluster.

The key parts of the project are:
* Exploratory data analysis to get familiar with the data and identify potential features
* Feature engineering (based on the previous analysis) that provides proper input for the machine learning model, leveraging sparks pipeline concept
* Selection, training, evaluation and optimization of a classification model
* A [blog post on medium](https://medium.com/@bytesbysophie/predicting-customer-churn-with-pyspark-for-a-music-streaming-service-9ea4908579?sk=3d1a7ed43423d9e8d983b93d96b1e6fa) that documents the project with a technical audience in mind

## File Descriptions <a name="File-Descriptions"></a>

* Sparkify.ipynb: The jupyter notebook containing the  exploratory data analysis, feature engineering and model development
* mini_sparkify_event_data.json: The provided subset of the user log data from Sparkify


## Authors and Acknowledgements <a name="Authors-Acknowledgements"></a>
This project has been implemented as part of the Udacity Data Scientist Nanodegree program. The data has been provided by Udacity accordingly.
