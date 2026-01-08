# Income Classification using PySpark

This project focuses on predicting an individual's income class based on demographic and socio-economic attributes using PySpark machine learning pipelines.  


## Objective
To classify individuals into income classes using demographic, educational, and employment-related features.

## Features Used
- age  
- workclass  
- weight  
- education  
- education_years  
- marital_status  
- occupation  
- relationship  
- race  
- sex  
- capital_gain  
- capital_loss  
- hours_per_week  
- citizenship  

Target variable:
- income_class

## Methodology
The project follows a standard machine learning workflow using PySpark:
- Data loading and inspection
- Data preprocessing and schema validation
- Categorical feature encoding using StringIndexer
- Feature vector assembly using VectorAssembler
- Train-test split (70% training, 30% testing)
- Model training using classification algorithms
- Model evaluation using accuracy and confusion matrix

## Models Implemented
- Random Forest Classifier
- Decision Tree Classifier

## Evaluation
Model performance was evaluated using classification accuracy and a confusion matrix.  
The Random Forest classifier demonstrated stronger predictive performance compared to the Decision Tree model.

## Tools & Technologies
- Python
- PySpark (MLlib)
- Machine Learning Classification
