Titanic Survival Analysis – Data Science Project
Overview
This project performs data science–based analysis on the Titanic passenger dataset to understand the factors that influenced survival during the Titanic disaster.
The main focus of this project is data cleaning, exploratory data analysis (EDA), and insight generation, rather than building complex machine learning models.
Dataset
The dataset used in this project is the Kaggle Titanic Dataset, which contains historical passenger information.
Dataset Attributes
Survived – Survival status (0 = Did not survive, 1 = Survived)
Pclass – Passenger class (1st, 2nd, 3rd)
Sex – Gender of passenger
Age – Age of passenger
SibSp – Siblings/Spouses aboard
Parch – Parents/Children aboard
Fare – Ticket fare
Embarked – Port of embarkation
Features Used
Pclass
Sex
Age
SibSp
Parch
Fare
Embarked
Target Column: Survived (used only for analysis)
Data Preprocessing
The following preprocessing steps were applied:
Removed irrelevant columns: Name, Ticket, Cabin
Filled missing Age values using the median
Filled missing Embarked values using the mode
Converted categorical values (Sex and Embarked) into numerical format
Models Used
This is a Data Science (EDA) project, not a Machine Learning project.
No predictive models were used as the main objective
Analysis was done using statistical summaries and visualizations
(Optional) Logistic Regression may be used only for trend observation
Results
Key insights from the analysis:
Female passengers had a higher survival rate
First-class passengers were more likely to survive
Children showed better survival chances
Higher fare passengers had higher survival probability
How to Run
Open Google Colab or Jupyter Notebook
Upload the Titanic dataset (Titanic_dataset.csv)
Install required libraries (pandas, matplotlib, seaborn)
Run the notebook cells step by step
Analyze the visual outputs and conclusions
Conclusion
This project demonstrates how data science techniques can be used to analyze real-world datasets and extract meaningful insights.
It is suitable for beginners to understand data preprocessing, EDA, and interpretation.
Author


Name: Hari Dharini
Domain: Data Science
Internship: CodSoft