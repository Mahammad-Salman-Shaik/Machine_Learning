
# Telco Customer Churn Analysis and Prediction

## Overview
This project focuses on analyzing customer churn in a telecommunications company using exploratory data analysis (EDA) and machine learning techniques. By identifying the factors leading to churn, we develop a predictive model that can help the company retain customers by taking proactive measures.

The project is split into two key phases:
- **Exploratory Data Analysis (EDA)**: This phase involves understanding the data, identifying patterns and trends in customer churn, and using visualizations to gain insights.
- **Machine Learning Model**: The second phase uses machine learning techniques to predict customer churn, with a particular focus on handling class imbalance.

## Key Features
- **EDA and Insights**: 
  - Comprehensive data exploration with visualizations to identify key churn drivers.
  - Segmentation of customers based on tenure, payment methods, and service usage.
  - Univariate and bivariate analysis to assess the correlation between features and churn.

- **Predictive Modeling**:
  - Use of Decision Tree classifiers to predict churn.
  - Handling class imbalance with the SMOTEENN technique.
  - Detailed evaluation of model performance through confusion matrices, recall scores, and classification reports.

## Motivation
Customer churn is a critical problem in the telecommunications industry. This project aims to provide data-driven insights and a reliable predictive model that can assist the company in reducing customer churn and increasing customer retention.

## Tech Stack
- **Python**: Core libraries such as `pandas`, `numpy`, and `matplotlib` for data manipulation and visualization.
- **Machine Learning**: Using `scikit-learn` for model building and evaluation, and `imbalanced-learn` for handling class imbalance.
- **Visualization**: Using `matplotlib` and `seaborn` for creating insightful visualizations to uncover churn trends.

## Data
The dataset used in this project consists of customer data, including:
- **Demographic Information**: Gender, age, and senior citizenship.
- **Account Information**: Contract type, payment methods, tenure, and charges.
- **Service Usage**: Internet service type, phone service, and additional services.
- **Target Variable**: Whether the customer churned or not.

## Results
The model successfully predicts customer churn with a balanced approach to handling class imbalance. Key findings include:
- Customers with shorter tenure and electronic check payments have higher churn rates.
- Monthly charges are positively correlated with churn.

## How to Run the Project
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/telco-churn-analysis.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the EDA notebook:
   ```
   jupyter notebook 'Churn Analysis - EDA.ipynb'
   ```
4. Run the model building notebook:
   ```
   jupyter notebook 'Churn Analysis - Model Building.ipynb'
   ```

## Future Work
- **Model Enhancement**: Explore more sophisticated models like Random Forest and XGBoost for better prediction accuracy.
- **Feature Engineering**: Derive new features such as customer engagement scores.
- **Deployment**: Build a web app to make predictions based on customer inputs in real-time.



## Contact
For any questions or feedback, please contact [Mahammad Salman Shaik](mailto:youremail@example.com).
