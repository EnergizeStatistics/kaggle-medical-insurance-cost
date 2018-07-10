# Medical Insurance Cost Prediction #
This repository hosts my code to predict medical insurance cost.

## Introduction ##
I work in a healthcare insurance company. Both literature and original analysis we internally perform have shown that a small proportion of patients consume the majority of healthcare resources. We would like to be proactive in directing targeted interventions towards those patients who are at risk of becoming high-cost users. A project that I work on is to use predictive models to identify patients at risk of incurring high medical cost, before making recommendations to providers to take actions to prevent such cost.   

## Description ##
I do not have permission to publish actual medical data from work. The analysis in this repository uses public data provided by [Kaggle](https://www.kaggle.com/mirichoi0218/insurance/) as a demonstration. 

I did the analysis following my own template of data science interview challenges, with one business-oriented step that I consider important to health insurance companies, where I defined a custom cost function to bias the predictions towards overestimation. I performed the usual exploratory data analysis with visualization, before implementing a random forest model and a neural network model.

Customer cost function was inspired by [this StackExchange answer](https://datascience.stackexchange.com/questions/10471/linear-regression-with-non-symmetric-cost-function).

## Requirements ## 
`Python`, `Keras`, and the common `Python` analytical packages. 