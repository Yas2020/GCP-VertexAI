# GCP-VertexAI
This repo contains projects I did on GCP using AI Platform- Vertex AI
Project1: Demand forcast for a retailer in a month at item-shop level. Dataset was provided by Kaggle for the course "How to win Kaggle competitions by top Kagglers".
Data contains 2.9M historical sale recodrs and after preparation as time series, it grows to about 9.9M rows. I trained a XGBoost model to predict sales for a 
month in future by creating a custom job using Python client API and submit the job (with/without hyperparametertuning) to VertexAI. The advantage of having access to 
high memory machine (Large Model) for this project on GCP allows more flexibilty for exploration.
