# IPL-Score-Prediction
#  IPL First Innings Score Prediction using Machine Learning

##  Project Overview
This project predicts the **final first-innings score** of an IPL (Indian Premier League) cricket match using **machine learning regression techniques**.  
The prediction is made based on match conditions such as venue, batting team, bowling team, overs completed, runs scored, wickets fallen, etc.

The aim of this project is to help understand how **data science and machine learning** can be applied to real-world sports analytics problems.

---

##  Problem Statement
In T20 cricket, predicting the first innings score is challenging due to multiple influencing factors like team strength, venue, and match progress.

This project answers the question:
> *“Given the current match situation, what will be the final first innings score?”*

---

##  Machine Learning Approach
- Problem Type: **Regression**
- Model Used: **Linear Regression**
- Evaluation Metric: **R² Score, Mean Absolute Error (MAE)**

---

##  Dataset Information
- Dataset contains historical IPL match data
- Features include:
  - Batting Team
  - Bowling Team
  - Venue
  - Overs completed
  - Runs scored
  - Wickets fallen
  - Runs in last 5 overs
  - Wickets in last 5 overs
- Target variable:
  - **Final First Innings Score**

Dataset source: Kaggle IPL Dataset

---

##  Technologies & Tools Used
- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**

---

##  Project Workflow
1. Data Loading and Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Selection  
4. Encoding Categorical Variables  
5. Train-Test Split  
6. Model Training using Linear Regression  
7. Model Evaluation  
8. Score Prediction  

---

##  Results
- The model successfully predicts the **first innings score** with good accuracy.
- Performance metrics indicate the model generalizes well on unseen data.
- This project demonstrates practical usage of regression in sports analytics.
