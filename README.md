# Customer Segmentation Report for Arvato Financial Solutions [(Full Report)](Report.pdf)

## Project Overview

The objective of this project is to analyze demographics data of customers of a mail-order sales company in
Germany that sells organic products and compare that to demographics data of the general population of
Germany. The end goal is to be able to predict, based on demographics data, which individuals from the general
population should be targeted in the mail-order campaign.
Both unsupervised and supervised learning techniques will be used. Unsupervised learning will be used to help
identify segments of the general population of Germany that best matches the existing customer base of the
company. A supervised learning prediction model will be developed to predict the likelihood of whether or not an
individual of the general population will become a customer. The dataset was provided by a real business -
Bertelsmann Arvato Analytics and represents a real-life data science task.
This project was provided by Udacity in cooperation with Arvato Financial Services. The final Jupyter Notebook
is titled [Arvato_Financial_Project_Amiri_McCain.ipynb](Arvato_Financial_Project_Amiri_McCain.ipynb). However, the datasets provided for this project,
courtesy of Arvato Financial Solutions, are private and cannot be made public.

**Completion of this capstone project includes four parts:**
1. Create a customer segmentation report for Arvato Financial Solutions.
2. Create a supervised learning model and verify this prediction model with training data.
3. Submit the prediction model to the “Udacity+Arvato: Identify Customer Segments” Kaggle competition for
testing here.
4. Create a report detailing my analysis and results.

## Domain Background
Arvato Bertelsmann Financial Solutions is an IT service management company headquartered in Baden-Baden,
Germany that specializes in optimizing the financial backbone of businesses and provides professional B2B
(business-to-business) financial services. Arvato provides expertise in automation and data analytics that provide
a comprehensive overview of an entire business and the business’s client’s journey.

## Problem Statement
Arvato Financial Solutions wants their client to be able to analyze attributes to identify payment behavior, predict
payment behavior, recommend credit scores and calculate credit scores of their clients. This will allow Arvato’s
client to more efficiently target the right type of clients for their organic mail order catalog. This appears to be a
clustering and classification problem.
The list below indicates how the results of the customer segmentation analysis report will be used and the
questions Arvato’s client desires to answer:
*How can the client, a mail order company acquire new clients more efficiently for its organic mail order
catalog?
*The mission of the engagement with the client is to make decisions based on data instead of gut feel.
*Arvato’s client will be using resultant datapoints to improve decisions and show rational behind decisions.
*Arvato wants their client to use and request reports more often.

## Datasets
**There are four data files connected with this project:**
* Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons
(rows) x 366 features (columns).
* Udacity_CUSTOMERS_052018.csv: Demographics data for CUSTOMERS of a mail-order company; 191 652
persons (rows) x 369 features (columns).
* Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a
marketing campaign; 42 982 persons (rows) x 367 (columns).
* Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing
campaign; 42 833 persons (rows) x 366 (columns).

In addition to the four data files listed above, two Excel spreadsheet files were included to provide more
information about the columns (features) depicted in the data files. The file names are “DIAS Attributes - Values
2017.xlsx” and “DIAS Information Levels - Attributes 2017.xlsx.” These Excel files provide additional information,
such as descriptions of attributes and a detailed mapping of data values for each feature and in alphabetical
order, about the columns in the primary data files.

The datasets provided for this project, courtesy of Arvato Financial Solutions, are private and cannot be made public.

## Evaluation Metrics
The prediction model predicted which people are most likely to respond to the advertising that they will receive
through the mail. In addition to evaluating this model with training data, this prediction model was also submitted
to the “Udacity+Arvato: Identify Customer Segments” Kaggle competition. The evaluation metric that Kaggle uses
for this competition is the Area Under the Curve (AUC) for the Receiver Operating Characteristic (ROC) curve. The
AUC ROC is immune to class imbalance and this dataset will be highly imbalanced.
The LGBMRegressor classifier was used for the final score. My top Kaggle score was 0.79542. The Leaderboard can
be viewed at the link: https://www.kaggle.com/c/udacity-arvato-identify-CUSTOMERS/leaderboard.

This capstone project was completed as part of Udacity's Machine Learning Engineer nanodegree program.
