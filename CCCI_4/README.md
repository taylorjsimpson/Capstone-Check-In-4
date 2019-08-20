# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Predicting Movie Revenue

## Project Author
 [Taylor Simpson](https://github.com/taylorjsimpson) |

## Contents of Repo

<!--ts-->
* [Code](http://localhost:8889/tree/CCCI_4/code)
  * [Data Collection & Data Aggregation]
  http://localhost:8889/notebooks/CCCI_4/code/Data_Collection_%26_Cleaning.ipynb
  * [Exploratory Data Analysis]
  (http://localhost:8889/notebooks/CCCI_4/code/EDA.ipynb)
  * [Supervised Learning Regression Model](http://localhost:8889/notebooks/CCCI_4/code/Supervised_Learning_Regression_Models.ipynb)
  * [Supervised Learning Classification Model](http://localhost:8889/notebooks/CCCI_4/code/Supervised_Learning_Classification_Model.ipynb)
  * [Master Copy]
  (http://localhost:8889/notebooks/CCCI_4/code/Master_Copy.ipynb)
<!--te-->

## Table Of Contents
[1. Problem Statement](#1.-Problem-Statement)<br>
[2. Executive Summary](#2.-Tools-&-Methodology)<br>
[3. Data Dictionary](#3.-Data-Dictionary)<br>
[4. Key Takeways](#4.-Key-Takeaways)<br>
[5. Next Steps](#5.-Next-Steps)<br>

## 1. Problem Statement

For my capstone project I will build a linear and logistic regression model to predict the opening weekend box office and total revenue for a movie release. These models will provide insight of what features (genre, runtime, critical rating, user rating, release date, etc.) are most predictive of a movie’s financial success. I plan on using linear to get a discrete prediction and logistic to predict whether or not it will cross a certain threshold ($5 million). Three statistics will be used to evaluate model fit: R-squared, the overall F-test, and the Root Mean Square Error (RMSE)


## 2. Executive Summary

Data was gathered from Movie Lens for over 45,000. The data was categorically divided into multiple categories, 
       'Adult', 'Belongs To Collection', 'Budget', 'Genres', 'Homepage', 'ID',
       'IMDB_id', 'Original Language', 'Original Title', 'Overview',
       'Popularity', 'Poster Path', 'Production Companies',
       'Production Countries', 'Release Date', 'Revenue', 'Runtime',
       'Spoken Languages', 'Status', 'Tagline', 'Title', 'Video',
       'Vote Average', 'Vote Count' which totaled almost 45,000 datapoints.  

Using the Kaggle data, supervised and unsupervised learning models were built to predict affluency or identify patterns in the data.



The following packages were imported to conduct this analysis.

|                |            |         |         |            |          |
|----------------|------------|---------|---------|------------|----------|
| Pandas         | Matplotlib | Seaborn | Sklearn | Numpy      | Requests |
|                |            |         | Plotly  | Statsmodel | Scipy    |


## 3. Data Dictionary

Sources:
* https://movielens.org/


|Feature|Type|Description|
|---|---|---|
'Adult', 'Belongs To Collection', 'Budget', 'Genres', 'Homepage', 'ID',
       'IMDB_id', 'Original Language', 'Original Title', 'Overview',
       'Popularity', 'Poster Path', 'Production Companies',
       'Production Countries', 'Release Date', 'Revenue', 'Runtime',
       'Spoken Languages', 'Status', 'Tagline', 'Title', 'Video',
       'Vote Average', 'Vote Count'

## 4. Key Takeaways

The linear regression model that was created
The logistic regression model that was created

## 5. Next Steps

Going back and removing all 0 revenue movies.   
