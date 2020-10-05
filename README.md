# Saving Your Credit Score: An Analysis of SBA Loans

This repository contains all of the steps in the analysis SBA Loans. This includes a folder containing all the data, a notebook where all the data was cleaned and analyzed, an article, and a presentation. Below, I will go into what you can expect from each of these.

### Data

 The data folder contains two .csv files. The first one named `SBAnational.csv` contains data on every SBA loan taken from 1970-2014 in the United States. An SBA Loan is a loan for small businesses where the majority of the loan is guaranteed to be paid in case of default by the US governemnt. This data has 899,164 rows and 27 columns. 

The second .csv files is called `clean_data.csv`. This data set contains the data that was used for our analysis. This included dropping unwanted columns, making new columns, and dropping rows with missing values for our analysis.

### Notebooks

Our notebook shows all the code used to clean the data as well as some initial analysis to understand which columns we felt were worthy of further evaluation. We then identified the columns industry, bank, term, year, and loan amount as valuable in determining if a loan will default. We then dove deeper into each of these and create multiple graphs that help solidify our findings. We then made a logistic regression model, nearest neighbors model, and an XGBoost model. The XGBoost model performed the best at an accuracy of 80%. This included the fact that the precision of predicting the defaults was 90% as well. This performs extremely well.

### Article

This folder contains an article on Linkedin about our entire analysis.

### Presentation

This folder contains a presentation over the same material the article contains. The visuals are better explained here and there are more uses of charts of data.


This analysis is done by Morgan Allen, Stephanie Lao, Marisol Mondragon and Katalina Rubio.
