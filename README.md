# Customer_Churn_Prediction_Analysis

### Notebook runtime: Tensorflow 1.15 Python3.7 CPU Optimised

### Description
A well-known bank has been observing a lot of customers closing their accounts or switching to competitor banks over the past couple of quarters. This has caused a huge dent in their quarterly revenues and might drastically affect annual revenues for the ongoing financial year, causing stocks to plunge and market cap to reduce significantly. The idea is to be able to predict which customers are going to churn so that necessary actions/interventions can be taken by the bank to retain such customers.

In this machine learning churn prediction project, we are provided with customer data pertaining to his past transactions with the bank and some demographic information. We use this to establish relations/associations between data features and customer's propensity to churn and build a classification model to predict whether the customer will leave the bank or not. We also go about explaining model predictions through multiple visualizations and give insight into which factor(s) are responsible for the churn of the customers.

During long time to develope a ML solution, a handy solution to track all the
information is provided via ML Monitoring and Experiment Tracking
● MLFoundry is TrueFoundry’s ML Monitoring & Experiment Tracking solution built
on top of the amazing open-source solutions such as MLFlow, EvidentlyAI,
Whylabs, Streamlit. It allows you to track your experiments, and monitor your model
performance & data drift.
● It is a client-side library that allows users to log their experiments, models,
metrics, data & features. This data is fed to TrueFoundry’s monitoring systems to
generate informative dashboards and insights.
● You get a complete dashboard to monitor your data, features, models and
compare experiments.
Get API Access

Installation
TrueFoundry’s monitoring solution depends on two libraries (mlfoundry & mlfoundry-ui)
which can be installed via pip. As mlfoundry depends on many different libraries, we
recommend working within virtual environments, as and when the dependencies issues
were to happen, they are easy to contain.

You need API access to run the MLFoundry library. You will be asked to enter the API key after
executing the code mlf.login()
To get the API Key please signup on to - https://app.truefoundry.com and create an API token
from settings (https://app.truefoundry.com/settings)

A blog of TrueFoundry:
https://medium.com/analytics-vidhya/tracking-and-monitoring-transformers-with-mlfoundry-460a3b860600

### Techologies:

1. model: jupyter notebook, TrueFoundy/MlFoundry, API

2. deployment: Terraform, Flask, Docker, EKS, ECR, ECS, AWS Farget, s3, Gunicorn/Unicorn, ELB, Code commit, Code Build, Code Deploy, Code Pipeline

### Assets:



### Model Developement Steps:

1. Jupyter notebook select run time tensorflwo 1.15 python 3.7 (python 3.8)

2. Connect to truefondry API

3. feature engineering 

4. Log experiements via TrueFoundry api


### Model Deployment Steps:

1. Code commit Repository
 - create repository named: CustomerChurnAppDeployment

 - push model to repository from cloud9: git remote add origin https://git-codecommit.us-east-1.amazonaws.com/v1/repos/CustomerChurnAppDeployment

 - git push origin master


2. AWS ECR

3. AWS Code Build

4. Importing resources to Terraform/ Terrraform commands and console

5. AWS Load Balancer

6. AWS ECS cluster

7. AWS ECS service and code pipeline

8. Code pipeline demo

9. AWS s3 bucket



