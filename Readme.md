## Overview
This project focuses on building a machine learning model to predict customer conversions for a bank's term deposit marketing campaigns. By analyzing customer data, the model identifies the most promising leads, enabling the bank to optimize its marketing efforts, reduce costs, and increase the conversion rate.
## Dataset
Kaggle Link: https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets
## Key Features
- Utilizes a RandomForestClassifier to predict the likelihood of a customer subscribing to a term deposit
- A scikit-learn Pipeline and ColumnTransformer are used to automate and streamline data cleaning, numerical scaling, and one-hot encoding for categorical variables.
- he model's effectiveness is evaluated using key metrics and visualizations, including a classification report, confusion matrix, gains chart, and lift chart
- The model identified the following factors as most influential in predicting a customer's conversion
   - duration
   - pdays 
   - poutcome_success 
   - month_mar 
   - month_oct 
   - month_sep
   - month_dec 
   - contact_cellular 