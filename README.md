# DF-Capstone-Mercari-Price-Suggestion
## Mercari Price Suggestion Capstone Project

<img align="right" width="300" src="https://user-images.githubusercontent.com/54026477/124735597-15033500-df0e-11eb-9dbb-0076694ecfc9.png">
My final capstone project for Digital Futures Academy, for suggesting the price of various products on the Mercari Marketplace.

### Description:
It can be extremely difficult to price products. Products have so many variables that can alter the price such as trends, brand names and while most products depreciate over time, others can actually increase in price.

Mercari, Japan's biggest app-based community marketplace have set out a Kaggle competition to tackle this, and build an algorithm that automatically suggests prices for their products.

The data provided would contain user-inputted text descriptions of their products, including details such as product category name, brand name and item condition.

### Conclusions:
The evaluation of the results would be measured by the Root Mean Squared Logarithmic Error (RMSLE). When comparing the model results, the Ridge Regressor had the lowest RMSLE, of 0.4468. The winning model on Kaggle recieved a RMSLE of 0.3776 with the median result being around 0.5459. Many of the highest scoring models combined Ridge Regression with more advanced Neural Network techniques to improve their score.

Overall, achieving an RMSLE of 0.4468 would place this algorithm in the top 30% of the Kaggle competition. With these results we can conclude that predicting the price of Mercari products with the given data could be done accurately.

###
##
This repository contains the capstone project notebook, and presentation.

The dataset used is too large to be stored in this repository, however it as this was a public Kaggle competition, it can be downloaded from: https://www.kaggle.com/c/mercari-price-suggestion-challenge/data

The two files necessary to download are the train.tsv and test_stg2.tsv files, which will both have to be unzipped prior to the use of this notebook.
