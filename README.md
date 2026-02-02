# Wine-Quality-Prediction-XGBoost
Predictive modeling of wine quality using XGBoost in R.

## About me
I work as a Data Analyst and AI Engineer concentrating on using statistical modeling to address environmental and societal issues. I focus on R, machine learning, and predictive analysis. Don't hesitate to reach out to me on LinkedIn or check out my additional projects

##  Project Overview

This project aims to develop a predictive model to assess wine quality using advanced tree-based methods. By moving beyond basic decision trees, which are prone to overfitting, this study utilizes XGBoost to achieve more resilient and accurate predictions.   

## Key Features

**EDA & Visualization:** Analyzed the relationship between chemical properties, specifically alcohol content, and perceived quality.   

**Advanced Modeling:** Implementation of Gradient Boosting (XGBoost) for regression.   

**Performance Evaluation:** The model achieved a final submission accuracy of 0.60652. 

## Analytical Insights

The analysis revealed a marginally positive correlation between alcohol content and wine quality:   
Higher-grade wines generally possess a higher median alcohol content.   
Quality is influenced by a complex interplay of various chemical characteristics, requiring advanced modeling to capture nuances.   

## Technical Stack

**Language:** R

**Key Libraries:** xgboost, caret, ggplot2, corrplot. 

## How to Run

Ensure you have R and the required libraries installed.

**Clone the repository**: git clone https://github.com/YOUR_USERNAME/Wine-Quality-Prediction-XGBoost.git
Run analysis. R to train the model and generate the submission file.

## Data Sources

When this project was orignally created the data sources were directly fed into the code structure to obtain the results but due to copyright and data availabilty issues the orignal source data is not being provided in this repository. Instead a special provision is made in the code, providing set parameters to replice the results.

## Results

**Note:** These are baseline results that can be imporved via feature and code optimization.
**Accuracy:** 0.60652    
**Validation Metric:** RMSE (Root Mean Square Error)

## Technical Appendix: Feature Definitions

The following chemical features are utilized as predictors (independent variables) in the regression model to determine the target response variable (wine quality).

<img width="3999" height="2764" alt="image" src="https://github.com/user-attachments/assets/61c538ff-7e32-4bf6-a78e-b780f0ccecbc" />
(Image sourced from shutterstock)

Apart from alcohol content the features include:

<img width="564" height="376" alt="image" src="https://github.com/user-attachments/assets/de187886-9617-4c26-8e87-71fb8cfb9e0b" />
