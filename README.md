# Customer Drop-Off Analysis

This project explores the reasons behind customer drop-off (churn) using Python. The goal is to identify behavioral patterns and features that influence when and why users stop engaging with a service or platform. It’s a practical example of how data science can support retention strategies, especially in both commercial and social impact settings.

---

## Problem Statement

High customer drop-off affects growth and sustainability. By analyzing user behavior, we aim to:
- Understand what leads to disengagement
- Predict potential drop-offs
- Suggest actionable strategies to improve retention

---

## Dataset

- **Type:** Simulated or anonymized real-world customer dataset
- **Features:** User demographics, usage history, login frequency, etc.
- **Target Variable:** Drop-off status (0 = retained, 1 = dropped off)

*(https://www.kaggle.com/datasets/blastchar/telco-customer-churn)*

---

## Tools & Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Models:** Random Forest Classifier  
- **IDE:** Jupyter Notebook  
- **Version Control:** Git/GitHub

---

## Process & Workflow

1. **Data Cleaning** – Handled missing values, standardized formatting  
2. **Exploratory Data Analysis (EDA)** – Identified key trends and correlations  
3. **Feature Engineering** – Created meaningful variables for prediction  
4. **Modeling** – Built and trained a Random Forest Classifier to predict customer drop-off, achieving strong performance and interpretable feature importance rankings.  
5. **Evaluation** – Assessed model accuracy and explained key metrics  
6. **Insights & Recommendations** – Summarized findings and business implications

---

## Insights

- Drop-off was highest among users who had shortest subscriptions.
- Analysis shows that people with shorter tenure are more likely to churn
- Contract analysis shows that month-to-month contracts have the highest churn rate, while two-year contracts have the lowest churn rate.
- Internet service analysis shows that customers with fiber optic internet service have the highest churn rate, while those with DSL have a lower churn rate.
- Customers with no internet service have the lowest churn rate.
- monthly charges analysis shows that churners tend to have higher monthly charges compared to non-churners.
- Gender analysis shows that there is no significant difference in churn rates between male and female

---

## Key Learnings

- Data preprocessing is essential for accurate modeling.
- Visualization helps communicate complex patterns clearly.
- Machine learning can help forecast behavioral outcomes in real-world settings.

---
## Model Performance

- Accuracy: 80%  
- Precision: 83%  
- Recall: 91%  
- Top 3 important features in predicting customer churn:
  1. Monthly Charges 
  2. Tenure 
  3. Total Charges
 
  ### Confusion Matrix Breakdown

|              | Predicted: Stay | Predicted: Leave |
|--------------|------------------|------------------|
| **Actual: Stay** | ✅ 944 correct  | ❌ 92 wrong     |
| **Actual: Leave** | ❌ 192 wrong   | ✅ 181 correct   |

> The model correctly predicted 80% of the cases — the robot was right most of the time!

## Business Recommendations

Based on the insights and model findings, here are data-driven actions to reduce churn:

1. **Offer incentives for long-term contracts**  
   Encourage customers to switch from month-to-month to annual or two-year plans using discounts or bundled offers.

2. **Target customers with short tenure**  
   Design onboarding and engagement campaigns to retain customers during their first 3 months — the most vulnerable period for churn.

3. **Reassess pricing models for high-charge users**  
   Churners tend to pay more monthly. Consider flexible plans or loyalty rewards for high-value customers.

4. **Enhance fiber optic service satisfaction**  
   Since fiber optic users are churning more, investigate and address service quality, outages, or customer service issues.

5. **Automate churn prediction alerts**  
   Integrate the Random Forest model into CRM systems to flag high-risk users for proactive customer retention efforts.

6. **Continue monitoring, retraining, and validating**  
   Regularly retrain the model with new data to keep predictions current and actionable.

---

## How to Run This Project

1. Clone the repo  
   ```bash
   git clone https://github.com/ImpactIntel-AI/drop-off-analysis.git
   cd drop-off-analysis

   Launch the Jupyter notebook



✅ Status

✔️ Completed – Open to improvements and feedback

📌 Future Work – Deploy model via Flask / Streamlit for web-based demo


🤝 Connect With Me
LinkedIn - www.linkedin.com/in/stephanie-savai-pmp-meal-dpro-mph-5466b51b5
