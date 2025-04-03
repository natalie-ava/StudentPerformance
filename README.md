# Capstone Project Description  

## Predicting Student Performance in Writing, Reading, and Math  

# Abstract  

The **Student Performance Prediction** project aims to classify student performance in writing, reading, and math based on demographic and academic factors. Initially, the project sought to determine overall pass/fail status, but it evolved to predict performance in each subject separately for a more detailed analysis. Using the **Student Performance Dataset** from Kaggle, this study explores the effectiveness of machine learning in educational prediction tasks, leveraging various classification models to identify key predictors of student success.  

# Introduction  

Understanding the factors that influence student performance is critical for designing effective educational interventions. While standardized test scores offer a measure of academic proficiency, various demographic and socio-economic factors also play a role in shaping student outcomes. **Student Performance Prediction** applies machine learning techniques to analyze these factors and predict whether a student will pass or fail in writing, reading, and math.  

This project builds upon the **Student Performance Dataset** sourced from Kaggle, which includes attributes such as gender, parental education level, lunch type, and test preparation course completion. Inspired by research from the **University of California, Irvine**, the project aims to uncover patterns that influence academic success and provide actionable insights to educators.  

Initially, a **Random Forest classifier** was implemented to predict overall pass/fail status. However, high misclassification rates led to a refined approach—developing separate predictive models for each subject. This approach improves interpretability and allows for targeted interventions for at-risk students in specific subjects.  

The **Student Performance Predictive Model**, developed in the accompanying Jupyter Notebook (`StudentPerformance_PredictiveModel.ipynb`), demonstrates an accuracy of approximately **XX%** for each subject. The classification results highlight key features influencing student success and provide a foundation for improving educational strategies.  

# Methods  

## Data Collection and Cleaning  

The dataset contains student performance data sourced from **Kaggle**, including key demographic and academic attributes. The preprocessing steps included:  

- Handling missing values and normalizing numerical features  
- Splitting categorical variables into separate encoded columns  
- Dividing data into training (80%) and testing (20%) sets  
- Feature engineering to improve model performance  

## Feature Selection  

The predictive model considers the following features:  

- **Gender** – Whether the student is male or female  
- **Parental Education Level** – The highest level of education attained by the student’s parents  
- **Lunch Type** – Whether the student receives standard or free/reduced lunch  
- **Test Preparation Course Completion** – Whether the student completed a test preparation course  
- **Subject-Specific Scores** – Performance in writing, reading, and math  

## Model Development  

The project utilizes **Random Forest classifiers** to predict student performance in writing, reading, and math. The dataset was split into **80% training and 20% testing**, with models trained separately for each subject to improve accuracy. Performance was assessed using:  

- **Accuracy**  
- **Precision, Recall, and F1-Score**  
- **Feature Importance Analysis**  

# Results  

The refined models achieved XX% accuracy on the test dataset, with notable differences in performance across subjects. Feature importance analysis revealed that test preparation course completion and parental education level had significant impacts on student success.  

The classification reports indicated that the model performed best in predicting reading scores, with strong precision and recall. However, math scores showed greater variability, likely due to broader disparities in student preparation and subject difficulty. The confusion matrix suggests that misclassification occurs most frequently between students on the borderline of passing or failing.  

Overall, the findings demonstrate that machine learning can effectively predict student outcomes, highlighting key factors that influence performance in different subjects.  

# Conclusion  

The Student Performance Prediction project illustrates the potential of machine learning in education. By leveraging demographic and academic data, the model achieves a reasonable predictive accuracy, offering insights into factors that influence student success.  

### Key findings include:  

- Parental education and test preparation courses** play a crucial role in academic performance  
- Math scores are more difficult to predict accurately compared to reading and writing  
- Granular subject-specific models** outperform overall pass/fail classification  

These results underscore the importance of targeted interventions to support students at risk of failing specific subjects. Future work will explore expanding feature selection, balancing the dataset, and optimizing classification algorithms for improved accuracy.  

# Future Work  

Enhancements for future iterations of the project include:  

- **Expanding Features** – Incorporating additional factors such as study habits, school environment, and attendance records  
- **Larger Dataset** – Collecting data from diverse student populations to improve generalization  
- **Real-Time Predictions** – Developing an interactive dashboard for educators to assess student performance  

# Contributions  

[List contributors here]  

# References  

1. **Kaggle Dataset**: [Student Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data)  
2. **Breiman, L.** (2001). "Random Forests." *Machine Learning, 45(1), 5-32.*  
3. **University of California, Irvine** – "Educational Data Mining: Predicting Student Success."  

# Appendix  

## Reports  

- **[Confusion Matrix](#)**  
- **[Classification Report](#)**  

## Graphs and Charts  

- **[Feature Importance Visualization](#)**  
- **[Accuracy and Performance Metrics](#)**  
 
