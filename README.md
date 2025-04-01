# Capstone Project Description  

## Predicting Student Performance in Writing, Reading, and Math  

### Objective  
This capstone project aims to develop a predictive model that determines whether a student will pass or fail in writing, reading, and math based on various demographic and academic factors. Initially, the project classifies students as either passing or failing overall, but it evolved to predict performance in each subject separately to provide a more detailed analysis.  

### Dataset  
The dataset, sourced from Kaggle, contains student performance data, including attributes such as gender, parental education level, lunch type, and test preparation course completion. This study is inspired by research from the University of California, Irvine, and seeks to explore the effectiveness of machine learning models in educational prediction tasks.  

### Methodology  

#### Data Preprocessing:  
- Handling and normalizing numerical features, splitting columns, and ingesting data into Google Colab.  
- Splitting data into training and testing sets.  

#### Initial Model:  
- Implemented a Random Forest classifier to predict overall pass/fail status.  
- Observed high misclassification rates, prompting a more granular approach.  

#### Refined Approach:  
- Instead of an overall classification, models are trained separately for writing, reading, and math.  
- Evaluating feature importance for each subject.  

### Expected Outcomes  
- Identification of key factors influencing student performance in different subjects.  
- Development of an optimized predictive model that provides more accurate and interpretable results.  
- Insights into potential interventions to support at-risk students in specific subjects.  
