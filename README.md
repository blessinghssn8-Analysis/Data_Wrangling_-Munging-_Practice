# DATA WRANGLING (MUNGING)

## Project Overview
This project focuses on practical data wrangling techniques applied to a customer churn dataset, with emphasis on data cleaning, handling missing values, and preparing structured data for downstream machine learning tasks. The work demonstrates a disciplined, production-oriented approach to transforming raw data into analysis-ready datasets.

## Problem Statement
Real-world datasets often contain missing values, inconsistencies, and noise that degrade model performance and bias analytical outcomes. Without systematic data cleaning and preprocessing, machine learning models built on such data are unreliable and difficult to interpret.

## Objectives
- Identify and analyze data quality issues within the dataset  
- Apply effective strategies for handling missing and inconsistent values  
- Engineer clean, structured features suitable for machine learning models  
- Evaluate the impact of data wrangling decisions on model performance  

## Dataset Description
- **Dataset**: Customer Churn Dataset  
- **Content**: Customer demographics, service usage, and account-related attributes  
- **Target Variable**: Customer churn status  
- **Challenges**:
  - Missing numerical and categorical values  
  - Inconsistent data types  
  - Potential outliers and noisy features  

## Methodology
- Initial data exploration and schema validation  
- Detection of missing values and data inconsistencies  
- Imputation strategies for numerical and categorical features  
- Encoding of categorical variables  
- Feature scaling and normalization where appropriate  
- Train-test split for model validation  

## Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  

## Key Insights
- Proper handling of missing values significantly improves model stability  
- Simple imputation strategies can perform competitively when applied correctly  
- Data preprocessing choices have a measurable impact on churn prediction performance  

## Tools & Technologies
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment**: Google Colab  

## How to Run the Project
1. Clone the repository  
2. Open the notebook in Google Colab or a local Jupyter environment  
3. Install required dependencies  
4. Run the notebook cells sequentially to reproduce the analysis and results

## Practical Relevance
This project reflects real-world machine learning workflows used in analytics, business intelligence, and predictive modeling roles. It demonstrates the ability to select, implement, and evaluate machine learning algorithms with a strong emphasis on interpretability, correctness, and practical decision-making.
