# project_4
Project 4 Box Office Predictions

Objectives:
- Find correlations/relationships between film characteristics and film revenue
- Create machine learning models to predict movie revenue based on film characteristics
- Evaluate model performances and determine optimization techniques

Dataset selection:
- Chosen from Kaggle with 7398 rows

Data cleaning:
- Used Pandas through Jupyter notebook

Visualizations:
- Created 3 charts using Tableau (Popularity vs Revenue, Budget vs All Genres, Revenue vs Movie Title)

ML models:
- Linear regression to predict revenue from budget
- Logistic regression to predict revenue from budget and encoded genres

Model evaluation:
1) Linear regression
   R-Squared score around 53%

2) Logistic regression
   Accuracy score approximately 0.1%

Model optimization:
1) Logistic Regression Model
     - More cleaning of the revenue column to include binary outcomes 
     - Run micro-models on smaller revenue rates
  
2) Linear Regression Model
     - Remove outliers 
     - Resample the data


