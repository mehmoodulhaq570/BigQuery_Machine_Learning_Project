# BigQuery_Machine_Learning_Project

## Collaborators

- Kashif Muneer (SUNet ID: 2021-CE-34)
- Mehmood Ul Haq (SUNet ID: 2021-CE-35)

# London Fire Brigade Incident Group Prediction

This project aims to develop a machine learning model to predict incident groups based on data from the London Fire Brigade service calls. By leveraging a Gradient Boosting Classifier, the model categorizes incidents into different groups, facilitating more efficient resource allocation and incident response management within the London Fire Brigade.

## Table of Contents

- [Overview](#overview)
- [Project Description](#project-description)
- [Programming Language](#programming-language)
- [Environment](#environment)
- [Dataset](#dataset)
- [Analysis of Dataset](#analysis-of-dataset)
- [Data Exploration](#data-exploration)
- [Data Prediction](#data-prediction)
- [Conclusion](#conclusion)
- [Collaborators](#collaborators)

## Overview

The goal of this project is to develop a machine learning model using a Gradient Boosting Classifier to predict the incident group based on data from the London Fire Brigade service calls. By classifying incidents into different groups, the model aims to contribute to better resource allocation and incident response management within the London Fire Brigade.

## Project Description

The project utilizes Python programming language and runs in the Google Colab environment. The dataset used for this project is the London Fire Brigade Service Calls Dataset, sourced from the BigQuery Public Dataset. The model development involves querying and preprocessing the dataset, training a Gradient Boosting Classifier, making predictions, and evaluating the model's performance.

## Programming Language

Python

## Environment

The project is developed in Google Colab.

## Dataset

- **Dataset Name:** London Fire Brigade Service Calls Dataset
- **Dataset Link:** [BigQuery Public Dataset: London Fire Brigade Service Calls](https://console.cloud.google.com/bigquery?project=gcp-2021-ce-35&supportedpurview=project&ws=!1m10!1m4!4m3!1sbigquery-public-data!2slondon_fire_brigade!3sfire_brigade_service_calls!1m4!4m3!1sbigquery-public-data!2schicago_crime!3scrime)

## Analysis of Dataset

The analysis of the dataset involves querying a subset of data from BigQuery for initial analysis, loading it into a DataFrame, and displaying a snapshot. This helps in understanding the structure and features of the dataset.

## Data Exploration

Data exploration includes querying the complete dataset from BigQuery, preprocessing it, and visualizing the count of incidents by group. This step provides insights into the distribution of incidents across different groups, aiding in understanding the data distribution.

## Data Prediction

Data prediction involves extracting features and the target variable for prediction, splitting the data, training a Gradient Boosting model, making predictions, and evaluating the model. This step assesses the model's performance in predicting incident groups.

## Conclusion

**General Observations:**  
The initial data analysis provided a snapshot of the dataset, including key features.

**Prediction Results:**  
The Gradient Boosting model achieved an accuracy of {accuracy_gb:.2f} on the test set. The classification report provides detailed metrics for each incident group, indicating strengths and areas for improvement.

**Implications for Fire Brigade Operations:**  
Predictive models can assist in anticipating incident types and response times, enhancing operational efficiency.

**Concluding Remarks:**  
The analysis and prediction serve as valuable tools for enhancing decision-making within the Fire Brigade.


- For issues or feedback, please contact me at mehmodulhaq1040@gmail.com...
