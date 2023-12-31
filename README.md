# Automatic-Ticket-Classification-using-Topic-Modelling
A model that is able to classify customer complaints based on the products/services.

## Problem Statement
We need to build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

## Dataset
The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features.

W will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, we need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:
- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

With the help of topic modelling, we will be able to map each ticket onto its respective department/category. we can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.

## Steps Performed:
- Data loading
- Text preprocessing
- Exploratory data analysis (EDA)
- Feature extraction
- Topic modelling
- Model building using supervised learning
- Model training and evaluation
- Model inference

## libraries used:
- NLTK
- SpaCy
- sklearn
