# Build-a-Churn-Prediction-Model-using-Ensemble-Learning
Ensemble methods aim to combine the predictions of several base estimators built with a given learning algorithm to improve obustness over a single estimator. 

# Project Description

nsemble methods aim to combine the predictions of several base estimators built with a given learning algorithm to improve obustness over a single estimator. Ensemble methods are ideal for regression and classification, where they reduce bias and variance to boost the accuracy of models. The most famous ensemble methods are boosting and bagging. 

Bagging is a homogeneous weak learners’ model that learns from each other independently in parallel and combines them for determining the model average. The Random Forest model uses Bagging.

Boosting is also a homogeneous weak learners’ model but works differently from Bagging. In this model, learners learn sequentially and adaptively to improve model predictions of a learning algorithm. The AdaBoost and Gradient Boosting use Boosting techniques.

In our case study, we will be working on a churn dataset. Churned Customers are those who have decided to end their relationship with their existing company. XYZ is a service-providing company that provides customers with a one-year subscription plan for their product. The company wants to know if the customers will renew the subscription for the coming year or not.

## Data Description 

This data provides information about a video streaming service company, where they want to predict if the customer will churn or not. The CSV consists of around 2000 rows and 16 columns