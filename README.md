# Credit_Score_Classification

Project Overview:

This project aims at predicting credit scores (Good, Standard, Poor) based on various financial behaviors and attributes of individuals. Utilizing a comprehensive dataset containing details such as annual income, monthly salary, number of bank accounts, credit cards, loans, payment delays, and more, we build a machine learning model capable of classifying credit scores. The insights drawn from this analysis can help banks and financial institutions in making informed decisions regarding loan approval processes.

Dataset:

The dataset comprises 100,000 entries with features like Annual Income, Monthly Inhand Salary, Number of Bank Accounts, Credit Cards, Loans, Delay from Due Date, Credit Mix, Outstanding Debt, and Monthly Balance, labeled with Credit Scores (Good, Standard, Poor).

Tech Stack:

Data Analysis and Processing: Pandas, NumPy
Data Visualization: Plotly Express, Plotly Graph Objects
Machine Learning Modeling: Scikit-learn
Development Environment: Jupyter Notebook

Key Findings:

Annual income and monthly in-hand salary positively correlate with better credit scores.
Maintaining 2-3 bank accounts and 3-5 credit cards is optimal for a good credit score.
Delaying credit card payments by 5-14 days from the due date has minimal impact on credit scores.
Having a long credit history and a high monthly balance contributes to better credit scores.

Model Building:

A RandomForestClassifier model was trained with selected features, achieving promising results in credit score classification. The model was evaluated based on accuracy, and insights were drawn on the importance of various features affecting credit scores.


Future Work:

Incorporate additional features such as spending habits and saving patterns.
Explore advanced machine learning algorithms for improved accuracy.
Develop a web application for real-time credit score predictions.
