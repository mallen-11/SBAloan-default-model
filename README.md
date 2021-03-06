# Saving Your Credit Score: An Analysis of SBA Loans

A article on this repo can be found at this link https://www.linkedin.com/pulse/saving-your-credit-score-analysis-small-business-loans-morgan-allen/?trackingId=%2BPUXbkl2QZu15i6bRcfSPQ%3D%3D.

This repository contains all of the steps in the analysis SBA Loans. This includes a folder containing all the data, a notebook where all the data was cleaned and analyzed, an article, and a presentation. Below, I will go into what you can expect from each of these.

### Data

 The data folder contains a link to the original website containing the data. Named `SBAnational.csv` it contains data on every SBA loan taken from 1970-2014 in the United States. An SBA Loan is a loan for small businesses where the majority of the loan is guaranteed to be paid in case of default by the US governemnt. This data has 899,164 rows and 27 columns. 
 
https://www.kaggle.com/mirbektoktogaraev/should-this-loan-be-approved-or-denied


### Notebooks

Our notebook shows all the code used to clean the data as well as some initial analysis to understand which columns we felt were worthy of further evaluation. We then identified the columns industry, bank, term, year, and loan amount as valuable in determining if a loan will default. We then dove deeper into each of these and create multiple graphs that help solidify our findings. We then made a logistic regression model, nearest neighbors model, and an XGBoost model. The XGBoost model performed the best at an accuracy of 90%. This included the fact that the precision of predicting the defaults was 90% as well. This performs extremely well.

### Article

This folder contains an article on Linkedin about our entire analysis.

### Presentation

This folder contains a presentation over the same material the article contains. The visuals are better explained here and there are more uses of charts of data.


This analysis is done by Morgan Allen, Stephanie Lao, Marisol Mondragon and Katalina Rubio.
