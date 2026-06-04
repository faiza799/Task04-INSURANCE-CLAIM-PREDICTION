# Task04-INSURANCE-CLAIM-PREDICTION
# Internship

DevelopersHub Corporation
Data Science & Analytics Internship

# 🎯 Objective

The objective of this task is to build a regression model that predicts medical insurance charges based on personal attributes such as age, BMI, smoking status, and region.

This helps in understanding how different lifestyle and demographic factors influence insurance costs.

# 📂 Dataset

The dataset used for this task is the Medical Cost Personal Dataset:

Medical Cost Personal Dataset

It contains the following features:

Age
Sex
BMI
Number of children
Smoking status
Region
Medical charges (Target variable)

# 🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
# 📊 Project Workflow
1. Data Loading
Dataset loaded using Pandas (read_csv)
Initial structure explored using .head(), .shape, and .info()
2. Data Preprocessing
Categorical variables were converted into numerical format:
Gender → Label Encoding
Smoker → Binary Encoding
Region → One-Hot Encoding
3. Exploratory Data Analysis (EDA)

The following visualizations were performed:

📌 BMI vs Insurance Charges

To analyze the relationship between body mass index and medical costs.

📌 Age vs Insurance Charges

To understand how age affects insurance expenses.

📌 Smoking Status vs Charges

To observe the impact of smoking on insurance costs.

4. Model Training

A Linear Regression model was trained using:

80% training data
20% testing data
5. Model Evaluation

The model was evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
# 📈 Results
The model successfully predicts insurance charges based on input features.
Smoking status has the strongest impact on insurance costs.
BMI and age also significantly influence medical charges.
Linear Regression provides a good baseline for regression problems.
# 🔑 Key Insights
Smokers have significantly higher insurance charges than non-smokers.
Higher BMI is associated with increased medical costs.
Age positively correlates with insurance charges.
Lifestyle factors strongly influence insurance pricing.
# 🚀 Conclusion

This task demonstrates how regression techniques can be used to predict continuous values such as insurance charges. Data preprocessing and feature analysis played an important role in model performance.

# Author

DevelopersHub Data Science Intern
Faiza Memon
