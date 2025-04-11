# 🛳 Titanic Survival Prediction

Predict survival on the Titanic and uncover the patterns behind who was more likely to survive the tragic shipwreck of 1912.

## 📌 Project Overview
This project involves building a classification model to predict which passengers survived the Titanic disaster using machine learning techniques. Alongside model building, a Power BI dashboard was created to provide interactive data insights.

## 📂 Dataset
- **train.csv** - Contains 891 labeled records of passengers with survival info.
- **test.csv** - Contains 418 records without survival labels (used for prediction).
- Source: [Kaggle Titanic - Machine Learning from Disaster](www.kaggle.com/competitions/titanic/overview/description)

## 🧠 Skills Covered
- Data Cleaning & Preprocessing  
- Feature Engineering  
- Supervised Classification Models (Logistic Regression, Decision Tree, Random Forest)  
- Model Evaluation  
- Power BI Dashboard Design  

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Power BI
- Jupyter Notebook

## 📊 Dashboard Preview
> **Built with Power BI to visualize survival rates, demographics, class distribution, and predictions.**

![Titanic Power BI Dashboard](Dashboard/Titanic%20Survivor%20Dashboard.png)

## 🚀 Project Workflow
1. **Data Exploration & Cleaning**
2. **Feature Engineering**
   - Extracted Titles from names  
   - Created FamilySize, IsAlone, AgeGroup, etc.
3. **Model Building**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest
4. **Model Evaluation**
   - Accuracy scores  
   - Compared performance of each model
5. **Visualization with Power BI**
   - Survival rates by gender, class, age group  
   - Heatmaps and slicers for interactivity

## 📈 Results
- **Best Model:** Random Forest  
- **Accuracy:** ~84.9% on training data
