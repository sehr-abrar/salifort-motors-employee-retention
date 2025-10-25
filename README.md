# Salifort Motors Employee Retention Analysis

### Google Advanced Data Analytics Capstone Project  

This project analyzes employee data from **Salifort Motors** to understand the key factors influencing employee turnover and predict which employees are most likely to leave the company. Using **machine learning models** such as logistic regression, decision trees, and random forests, this analysis provides data-driven insights to support HR decision-making and improve employee retention.

---

## Project Overview

**Business Problem:**  
Salifort Motors has experienced high employee turnover, leading to increased hiring costs and reduced productivity. The goal of this project is to identify which factors most influence employee attrition and to develop a predictive model that can help HR proactively address retention challenges.

**Key Question:**  
> What factors are most likely to make an employee leave the company?

---

## Objectives
- Analyze HR data to uncover patterns in employee satisfaction, workload, and tenure  
- Build predictive models to determine the likelihood of attrition  
- Evaluate model performance and select the best approach  
- Recommend actionable strategies to improve retention  

---

## Methodology

### 1. Data Exploration
- Performed **Exploratory Data Analysis (EDA)** using Python (Pandas, Seaborn, Matplotlib)  
- Analyzed variables such as satisfaction level, last evaluation, number of projects, average monthly hours, and years at the company  

### 2. Modeling
- Built and compared three models:  
  - **Logistic Regression**  
  - **Decision Tree Classifier**  
  - **Random Forest Classifier**  
- Evaluated models using accuracy, precision, recall, and F1-score  

### 3. Model Selection
- The **Random Forest model** slightly outperformed the Decision Tree and Logistic Regression models  
- Feature importance was used to identify key drivers of employee attrition  

---

## Key Insights

1. **Satisfaction Level** — The strongest predictor of whether an employee leaves  
2. **Number of Projects** — Too many concurrent projects increase the likelihood of attrition  
3. **Tenure (Years at Company)** — Turnover peaks around 4 years of service  
4. **Average Monthly Hours** — Both extremely high and low workloads relate to higher attrition  
5. **Evaluation Scores** — High scores combined with long hours suggest burnout risk  

---

## Recommendations
- Cap the number of projects per employee to prevent overload  
- Investigate dissatisfaction among 4-year employees — consider promotions or new opportunities  
- Reward employees fairly for overtime or clarify pay and workload policies  
- Encourage work-life balance and clarify expectations around time off  
- Revisit performance evaluation metrics to ensure fairness and sustainability  

---

## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Jupyter Notebook**: Data cleaning, EDA, and model development  
- **Tableau**: Data visualization and dashboard creation  
- **GitHub**: Version control and portfolio presentation  

---

## Results
- **Best Model:** Random Forest Classifier  
- **Model Accuracy:** ~0.98 (varies by run)  
- **Most Influential Features:** Satisfaction lev

---

## Files in This Repository
- `HR_capstone_dataset.csv` — HR dataset used for the project (if shareable).  
- `salifort_motors_executive_summary.pdf` — Executive summary outlining findings, insights, and business recommendations for stakeholders.  
- `salifort_motors_lab.ipynb` — Jupyter Notebook containing full data analysis, exploratory data analysis (EDA), model building, and evaluation.  
- `salifort_motors_PACE_strategy_document.pdf` — Completed PACE strategy document detailing planning, analysis, construction, and execution stages of the project.
- `README.md` — Project overview and documentation
