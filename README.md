# Capstone_3_M_Fauzi_Hakim_JCDS_2304
"The completion of Capstone Project Module 3 is aimed at building a machine learning (ML) model that fits the data and business needs."
*`This notebook uses the CRIPS-DM workflow`*
- Business Understanding
- Data Understanding
- Data Preparation
- Model Building & Testing
- Evaluation
- Deployment

> #### **Context**

Customer churn rate refers to the rate at which customers stop subscribing to a service. This dataset belongs to a leading online E-commerce company. An online retail (E-commerce) company wants to identify customers who are likely to churn so they can offer promotions to retain them.

`Data Context: The dataset is divided into two parts: data_train and data_val, with data_val reserved for evaluating the modeling results from data_train. However, during the exploratory phase to understand relationships between columns (customer behavior), the data team uses the entire dataset to ensure the exploration is representative of the full dataset provided.`

> #### **Problem Statement**

The marketing team has asked the data team to build a model to predict which customers are likely to churn. Additionally, the data team will explore factors contributing to customer churn.


> #### **Goal**

The goal of the data team is to predict customer churn and offer promotions to those customers. Additionally, the data team aims to identify patterns of churn based on the predictive model.

> #### **Metric Evaluation**

Since the objective of this prediction is to minimize false negatives (customers incorrectly predicted not to churn) to avoid losing customers, and false positives (customers incorrectly predicted to churn) to avoid unnecessary promotion costs, the evaluation metrics used are:

**F1-Score**: This metric balances true positive and true negative predictions. It is the harmonic mean of precision and recall, making it suitable for cases where a balance between precision and recall is desired.

**ROC AUC Score**: This metric shows the model's ability to distinguish between classes.
