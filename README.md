# 💳 Bank Credit Risk Assessment Project

A machine learning project for case study 1 that predicts **Bank Customer Credit Risk Assessment** 
based on financial features such as Income, Scoring Marks, Debt, Credit History Rating, Family status, Gender, Possibility of Default and more.
Adding statistical analysis to gain more insight into the datasets.
Built using Python, Pandas, scikit-learn, and visualised with matplotlib & seaborn. 
    
---
    
## 📌 Project Goals
    
- To predict Customer Credit Risk Assessment (PDN) using income, debt, family status, Credit History Rating, SEX, and Scoring Mark.
- To build predictive models using:
- Linear Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- K-nearest neighbours Regressor
- Ada Boosting Regressor
- Bagging Regressor
- Evaluate model performance and select the best one.
    
## 📁 Dataset
    
- **Name**: `final_Project_bank_credit_scoring.csv`
- **Size**: ~19,000 entries
- **Features**: 
- `INCOME`
- `Debt`
- `SEX`
- `Family status`
- `PDN` *(target)*
- `Age`
- `Credit History Rating`
- `Initial Limit`
- `Scoring Mark` 

## 📁 Data Cleaning And Wrangling 

- Checked for positively and negatively skewed columns and transformed them to fit for prediction and visualisation. 
- Checked for the relationship between numerical and categorical columns using the Chi-Square Test.
- Checked for the relationship between averages using the ANOVA test.
- Checked and removed NaN values 
- Translation of Column names from Russian to English
- Conversion of column datatypes from float to string (object)
- Translation of column values from Russian to English, e.g Male and Female values, Family status, etc.
        
## 📁 Statistical analysis for Machine Learning
      
- Used Pandas to determine the mean, maximum and minimum values 

## 📁 Machine Learning And Data Visualisation
      
- Using Scikit Learn models like (Linear Regression, KNN, etc.) to predict outcomes according to selected columns.
- Using Matplotlib.pyplot and seaborn models (Histograms, Barchart, Heatmap, Boxplot, Scatterplot, etc.) to visualise the data.

## 📁 How To Run
      
- First and foremost, used UV to install Python libraries in the UV lock for assessment, e.g, uv add scikit learn, seaborn, matplotlib, etc
- Cloned Repository from https://github.com/UgoChikezie2/ugo-final-project
- Run Jupyter Notebook: Ugo_Chikezie_Final-Project.ipynb