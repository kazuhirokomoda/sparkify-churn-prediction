# Sparkify Churn Prediction

## Project Overview

This project aims to predict likely-to-churn-users on a fictional music streaming service named Sparkify.

Any user on this service falls into one of the three categories below, and he/she can switch freely while using the service:

1. non-registered (including withdrawn) user
2. free user
3. paid user

We can define any switch towards lower number in the above list as "Churn", and given user activity data on the Sparkify service, we try to identify who are likely to churn: **churn prediction problem**.

## Project Motivation

Being able to tell whether a customer is about to trigger a churn event can be a great advantage for any customer facing service providers, and Sparkify is no exception. If a certain customer is considered to be likely to stop using the service soon, the service provider can take some countermeasures, such as giving discount offers or 1-to-1 followups in a timely manner, so the customer may voluntarily stay and keep generating revenue.

## Installation

Tested on a Jupyter environment

- Python 3.6
- Pandas
- Matplotlib
- Seaborn
- PySpark ML v2.4.3

## File Descriptions

- `README.md`: Overall information of the project
- `Sparkify.ipynb`: Code for data analysis and model building

## Results

Please find the summary of the analysis results in my blog post: [Churn Prediction Project: Learn from user activities and don't let them just go away!](https://kazuhirokomoda.medium.com/churn-prediction-project-learn-from-user-activities-and-dont-let-them-just-go-away-ea670e52cecc)

## Licensing, Authors, Acknowledgements

- [Udacity Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
