# Customer-Churn-Probability

## Introduction

As businesses strive to maximize their profitability, one important metric that they must keep track of is customer churn (customer attrition). This refers to the percentage of customers who stop using a company's service or product for a duration. High customer churn rate can be detrimental to a business, as they can indicate high dissatisfaction levels and reduce revenue to the company.

To mitigate customer churn, businesses can employ various strategies,including loyalty programs and high targeted market campaign but without accurate insights into customer behaviour, the company may not know which approach to take and this is where machine learning becomes useful. 

Machine learning can be used to predict which customers are at risk of churning by analyzing historical data, identifying patterns and other statistical techniques. This article will delve into the use of the CRISP-DM frame work to build a classification model that can predict customer churn using customer data and behavioral characteristics. 

### Objective

To build a classifaction model that accurately predict if a cutomer will churn or not.

### Resources and Tools

1. A dataset  

2. Jupyter Notebook: scikit learn, pandas profiling, pandas, matplolib, seaborn and other machine learning libraries.

## Exploratory Data Analysis (EDA)

One of the biggest challenge in building a classifiaction model that make prediction is to identify the relevant features in your data. Identifying relevant features can help you differentiate between churn and non churn customers, this requires a deep business understanding and extensive data analysis to identify patterns and trends in data. Using the approach of asking questions and coming up with hypothesis helps in data understanding. The hypothesis and questions below was formulated to help understand the data.

##### Hypothesis

Null: 25% of customers are likely to Churn.
Alternative: 75% of customers does not churn

1. What is the churn to not churn ratio?

2. Which gender group is likely to churn?

3. How many customers have our phoneService?

4. How many customer have online security?

5. How many customers have tech Support?

Before answering the questions or affriming the hypothesis, let's dig for information on the data such as how many colums do we have, are they any missing values , what are the datatypes etc.

![image](https://user-images.githubusercontent.com/74463676/226120167-3c4c1b4f-0057-41a7-89dc-a5830d93b245.png)

The above image shows the data loaded into jupyter notebook, then data is being expored and questions answered

![image](https://user-images.githubusercontent.com/74463676/226120759-4a057a21-137e-4171-b36d-34b481102747.png)

![image](https://user-images.githubusercontent.com/74463676/226120783-1ed28c77-4e29-4d86-b214-b6b3adf9e69c.png)

![image](https://user-images.githubusercontent.com/74463676/226120811-3447ac8b-698c-4dd5-820e-b0f7e583d227.png)

Find more insights found and qnswer to questions in the attached jupyter notebook file


## Data Processing and Building Model

Before building the model, the model is being processed. Preparing raw data to be acceptable for a machine learning model is known as data preprocessing. In order to build a machine learning model, it is the first and most important stage.

It is not always the case that we come across the clean and prepared data when developing a machine learning project. Also, any time you work with data, you must clean it up and format it.

Real-world data typically includes noise, missing values, and may be in an undesirable format, making it impossible to build machine learning models on it directly. Data preprocessing is necessary to clean the data and prepare it for a machine learning model, which also improves the model's accuracy and effectiveness.

To process the data, all coategorical data was encoded into numerical data and data is plit into train and test data. The data is then being trained by the model as seen below
![image](https://user-images.githubusercontent.com/74463676/226123446-31c48a43-b821-47ca-b2a7-97f21e5c9840.png)

![image](https://user-images.githubusercontent.com/74463676/226123574-f120c60a-d783-4732-9146-f55d48283f1f.png)

![image](https://user-images.githubusercontent.com/74463676/226123601-faabf36b-d459-4f3d-b4ba-ca2cfaf8e598.png)


## Model Evaluation
Model evaluation is done on a trained machine learning model to find out how well the model is performing. For a binary classification model like our churn prediction model, we need to find the true negetives, false negetives, true positves and false positives. Also there other evaluation metrics such as the precision, recall, accuracy, confusion metrics and the F1 score.
![image](https://user-images.githubusercontent.com/74463676/226125835-dfde9322-f811-41d4-a074-5871814053dd.png)

![image](https://user-images.githubusercontent.com/74463676/226125859-ee72fe51-f984-4034-acb8-94955fcf258e.png)


## Conclusion

Using historical data to build classification model that predict customer churn is a helpful machine learning application especially in today's competitive business world where customer retention is key to the success of a company. Aside the machine learning model algorithm used in this project there are other classification model such as decision tree, K nearest neighbour, naive bayes, support vector machine etc.

