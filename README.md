# Maternal_Health_Risk_Classifier

## Table of Contents  
- [Objective](#objective)  
- [Methodology](#methodology)  
- [Key Highlights](#key-highlights)
- [Technologies Used](#technologies-used)  
- [Feature Analysis](#feature-analysis)  
- [Future Improvements](#future-improvements)
## Objective
Maternal health risks, when not identified early, can lead to severe complications during pregnancy, affecting both the mother and the child. Traditional methods of assessing maternal health risks are often imprecise or delayed in identifying critical risk factors. This project employs machine learning techniques to predict maternal health risk levels based on key vital signs, including Age, Blood Pressure (Systolic and Diastolic), Blood Sugar, Body Temperature, and Heart Rate.

## Methodology
The goal of this project is to ensure the successful classification of the most important feature affecting maternal health and to evaluate the best-predicted model. The methodology involves data cleaning, outlier detection, encoding, feature scaling, model training, and evaluation.
![Block_Diagram](https://github.com/user-attachments/assets/cb02376c-8276-428b-b53b-a2a780df9e2e)

## Key Highlights:
* **Dataset:** Utilized a dataset from the UCI Machine Learning Repository containing 1,013 instances with 6 features related to maternal health indicators and risk levels.
* **Techniques:** Applied data preprocessing techniques like imputation, scaling, and encoding, followed by exploratory data analysis using visual tools like heatmaps and pie charts.
* **Machine Learning Models:** Implemented Logistic Regression, Decision Tree, and Random Forest, with hyperparameter tuning enhancing the Random Forest model, achieving 82% accuracy.
* **Feature Importance:** Identified Blood Sugar (35.6%), Systolic BP (18.1%), and Age (17.9%) as critical predictors.
* **Impact:** Demonstrated the utility of machine learning in supporting healthcare professionals by integrating predictive models into clinical decision systems for real-time risk assessment.

## Technologies Used

**Programming Language:** Python<br>
**Libraries Used:** 
* **Data Pre-processing:** Scikit-learn and Pandas for handling missing values, scaling, encoding, and feature selection.<br>
* **Machine Learning:** Logistic Regression, Decision Tree, Random Forest & Tuned Random Forest Classifier for model selection, evaluation & validation.<br>
* **Visualization:** Seaborn and Matplotlib for plots.<br>
* **Performance Metrics:** Classification Report, Confusion Matrix, Correlation Matrix.<br>
* **Development Environment:** Google Colab, Jupyter Notebook.

## Feature Analysis
Blood Sugar (BS) is the most significant feature, contributing over 35% to the prediction, highlighting its dominant role in assessing maternal health risks.
Age and Systolic Blood Pressure follow as moderately important features, while Body Temperature has the least impact, suggesting it plays a minimal role in determining risk levels.
![image](https://github.com/user-attachments/assets/1e4f28d0-7c2b-48de-a8e8-4ee3f45f7a4c)

## Future Improvements
* Creating advanced decision-making systems from these findings can improve early detection of risks and enable healthcare providers to implement precise and effective interventions for maternal health care.
* Broadening regional datasets and integrating longitudinal insights can strengthen model robustness and practical utility.
* These techniques can help healthcare professionals identify high-risk patients and tailor treatment plans to improve patient outcomes.

