# Predicting Glassdoor Review Ratings using Data Mining Techniques

## Abstract
Glassdoor is a popular platform for employees to leave anonymous reviews and ratings of their employer and can be helpful for job seekers and others who are considering working for a particular company. Glassdoor ratings may have a significant impact on a company's reputation and success. This study explores whether a Glassdoor reviewer's profession can predict whether a rating is high or low using a large (>100k) dataset collected from Kaggle and converted to binary with One-Hot Encoding. 

We use an unsupervised learning and a supervised learning approach. The unsupervised approach combines k-Modes Clustering with Frequent Pattern Mining, while the supervised learning approach picks and tunes a Logistic Regression Classifier as the best supervised model. We find reviewers with job titles belonging to the category “Service Professional” can accurately predict an overall low satisfaction with most rating parameters, while ‘Technology Professional’ can accurately predict an overall low satisfaction. Finally, we find that ‘Business Professional’ from the Consulting industry can predict high satisfaction with career opportunities and low satisfaction with work-life balance. The results raise some questions towards an unfortunate tendency for service professionals to be unsatisfied with their workplace and how organisations may consider if part of their workforce are systemically dissatisfied.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Unsupervised Learning](#unsupervised-learning)
  - [Supervised Learning](#supervised-learning)
- [Results](#results)
  - [Service Professional](#service-professional)
  - [Technology Professional](#technology-professional)
  - [Business Professional](#business-professional)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

## Introduction
Glassdoor reviews provide valuable insights for job seekers and companies. This project aims to determine if a reviewer's profession can predict the rating they give using data mining techniques.

## Dataset
The dataset used in this project was sourced from Kaggle and contains over 100,000 Glassdoor reviews. The data was converted to binary using One-Hot Encoding to facilitate the analysis.

A link to the reviews can be found here: https://www.kaggle.com/datasets/davidgauthier/glassdoor-job-reviews

## Methodology

### Data Preprocessing
- Data was cleaned and preprocessed.
- One-Hot Encoding was used to convert categorical data into a binary format.

### Unsupervised Learning
- k-Modes Clustering was used to group similar job titles.
- Frequent Pattern Mining identified common patterns in the reviews.

### Supervised Learning
- A Logistic Regression Classifier was trained and tuned to predict review ratings.
- Model performance was evaluated using standard metrics.

## Results

### Service Professional
Service professionals tend to predict an overall low satisfaction with most rating parameters.

### Technology Professional
Technology professionals also tend to predict an overall low satisfaction.

### Business Professional
Business professionals from the consulting industry predict high satisfaction with career opportunities but low satisfaction with work-life balance.

## Conclusion
The findings suggest that profession can be a significant predictor of Glassdoor review ratings, with notable trends observed among different professional categories.

## Future Work
Future research could explore more advanced models and include additional features to improve predictive accuracy. Investigating the reasons behind the dissatisfaction among service professionals could also provide valuable insights.

## Acknowledgements
We thank Kaggle for providing the dataset and all contributors to this project.

