# Lead scoring case study

## Problem statement :-
X Education wants to improve its lead conversion rate, which is currently at 30%. They acquire leads through various channels, such as website visits, forms, and referrals. However, only a small portion of these leads convert into paying customers.
To improve this, the company wants to identify "Hot Leads"—those with a higher chance of converting. By focusing on these leads, the sales team can increase their efficiency, aiming for a conversion rate of around 80%.
Your task is to build a model that assigns a lead score to each lead. Higher scores should represent leads more likely to convert into customers. This way, the sales team can prioritize their efforts and improve the conversion rate.

## Data 
You have been provided with a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted. You can learn more about the dataset from the data dictionary provided in the zip folder at the end of the page. Another thing that you also need to check out for are the levels present in the categorical variables. Many of the categorical variables have a level called 'Select' which needs to be handled because it is as good as a null value.  convert in simple n short manner. 

## Goals of the Case Study :-
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

## Results Expected :-
A well-commented Jupyter note with at least the logistic regression model, the conversion predictions and evaluation metrics.
The overall approach of the analysis in a presentation
Mention the problem statement and the analysis approach briefly
Explain the results in business terms
Include visualisations and summarise the most important results in the presentation

