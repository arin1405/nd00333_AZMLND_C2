
# Operationalizing Machine Learning

In this project we aim to deploy and consume a Machine Learning model on Microsoft Azure via Azure Machine Learning Studio. We first created an AutoML run to identify the best model for the given Bank-Marketing dataset. AutoML found out the Voting Ensemble as the best model which we deployed and consumed through the endpoint. We also documented our model's REST API using the swagger UI. To automate everything, we created a pipeline in the notebook and included all the steps that created an AutoML model. The best model is saved in pickel file. 

We tested our best running model using a test dataset and created a confusion matrix. We created a rest endpoint to this best model and scheduled an experiment on it.

## Architecture
The architecture of the process is shown below:

![architecture](screenshots/Architecture.png)

## Overview

We used Bank marketing dataset taken from UCI Machine Learning repository. The data is related to direct marketing campaigns of a Portuguese banking institution.

The dataset was already present in Azure ML Studio.

![dataset](screenshots/1. Dataset.JPG)

