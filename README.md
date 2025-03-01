# Case Study: Automatic Ticket Classification


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business goal](#business-goal)
* [Dataset](#dataset)
* [Expected tasks](#expected-tasks)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## Problem Statement

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

## Business goal

You need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, you will be able to identify the topics of the customer complaints. 

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others 

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.


## Dataset

[Download The Dataset](https://drive.google.com/file/d/1Y4Yzh1uTLIBLnJq1_QvoosFx9giiR1_K/view)

The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features. You need to convert this to a dataframe in order to process the given complaints.


## Expected tasks

You need to perform the following eight major tasks to complete the assignment:

- Data loading
- Text preprocessing
- Exploratory data analysis (EDA)
- Feature extraction
- Topic modelling 
- Model building using supervised learning
- Model training and evaluation
- Model inference


Note: Once you have finalised the clusters/categories for customer complaints, the next step is to create a data set that contains the complaints and labels (which you found using NMF). This labelled data set will be used for model building using supervised learning. 

You need to try at least any three models from logistic regression, naive Bayes, decision tree and random forest. 

You need to select the model that performs the best according to the evaluation metrics.


## Technologies Used :-
- pandas - 1.3.4
- numpy - 1.20.3
- matplotlib - 3.4.3
- seaborn - 0.11.2
- plotly - 5.8.0
- sklearn - 1.1.2
- tensorflow - 2.11.0
- wordcloud - 1.8.1
- swifter - 1.3.4
- nltk - 3.6.7
- spacy - 3.2.1
- en_core_web_sm - 3.2.1

## Acknowledgements :-
This project was an assignment provided by the Upgrad.
Reference taken for this assignment are:-
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://www.tensorflow.org/


## Contact
Created by [Kuldeep Lodha](https://github.com/kuldeeplodha) - feel free to contact me!
