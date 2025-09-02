# customer-churn-analysis
Predicting telecom customer churn using Python, SQL, and Tableau. Includes data cleaning, EDA, modeling, and retention insights.

# 📊 Customer Churn Prediction & Retention Insights

## 🔍 Business Problem
Telecom companies lose millions every year due to customer churn.  
The goal of this project is to **predict which customers are at risk of leaving** and provide **data-driven retention strategies**.  

---

## ⚙️ Tools & Technologies
- **Python:** pandas, NumPy, scikit-learn, matplotlib, seaborn  
- **SQL:** Data extraction & cohort analysis (CTEs, window functions)  
- **Visualization:** Tableau (interactive dashboard)  
- **Other:** Jupyter Notebook, Git  

---

## 📈 Approach
1. **Data Wrangling & Cleaning**  
   - Handled missing values, normalized categorical fields.  
   - Engineered features (contract type, tenure groups, monthly charges).  

2. **Exploratory Data Analysis (EDA)**  
   - Churn distribution by demographics, contract type, and monthly charges.  
   - SQL queries for churn by customer cohort.  

3. **Modeling**  
   - Built a **Logistic Regression model** to predict churn probability.  
   - Compared performance with Random Forest & Gradient Boosting.  
   - Achieved **83% accuracy and 0.79 ROC-AUC**.  

4. **Visualization & Insights**  
   - Developed **Tableau dashboard** to visualize churn KPIs.  
   - Highlighted **segments with 20% higher churn risk** (month-to-month contracts, high monthly charges).  

---

## 📊 Key Insights
- Customers with **month-to-month contracts** have the **highest churn** rate.  
- **High monthly charges** strongly correlate with churn risk.  
- **Retention strategy suggestion:** Offer discounts & loyalty rewards to at-risk groups.  

---

## 🚀 Results
- **Predictive churn model** with 83% accuracy.  
- Identified at-risk customer groups → **potential 12% churn reduction** if retention actions applied.  
- Interactive Tableau dashboard created for **business stakeholders**.  

---

## 📂 Project Structure


📂 customer-churn-analysis
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┣ 📂 data
 ┃ ┣ raw_data.csv
 ┃ ┗ cleaned_data.csv
 ┣ 📂 notebooks
 ┃ ┣ 01_data_cleaning.ipynb
 ┃ ┣ 02_EDA.ipynb
 ┃ ┣ 03_modeling.ipynb
 ┃ ┗ 04_visualization.ipynb
 ┣ 📂 sql
 ┃ ┗ churn_analysis_queries.sql
 ┗ 📂 tableau
   ┗ churn_dashboard.twbx

