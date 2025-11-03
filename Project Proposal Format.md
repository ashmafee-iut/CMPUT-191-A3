# **Project Proposal: Predicting Customer Churn in the Telecommunications Industry**

---

## **1.1 Problem Definition (2 points)**

**Problem:** Predicting customer churn in the telecommunications industry.  
**Importance:** Customer retention is **5× cheaper** than customer acquisition.  
**Domain:** Business / Marketing Analytics  
**Audience:** Telecom company marketing departments  

**Grading Criteria:**
- ✓ Problem is clearly defined and specific  
- ✓ Real-world relevance is established  
- ✓ Scope is appropriate for course level  

---

## **1.2 Research Questions / Objectives (2 points)**

**Primary Question:**  
- Can we predict which customers will churn within 3 months?

**Secondary Questions:**  
- What factors most strongly correlate with churn?  
- How does model accuracy compare across different algorithms?  
- What is the cost-benefit of implementing this model?

**Grading Criteria:**
- ✓ Questions are specific and measurable  
- ✓ Questions are answerable with data science techniques  
- ✓ Questions align with the problem statement  

---

## **1.3 Data Sources (3 points)**

**Primary Source:**  
- **Dataset:** [Kaggle Telecom Customer Churn Dataset](https://www.kaggle.com/)  
- **Records:** 7,043 (CSV format)  
- **Access:** Public download  

**Secondary Source:**  
- **Dataset:** Economic indicators via [World Bank API](https://api.worldbank.org/)  
- **Access:** Free API access  

**Backup Source:**  
- **Dataset:** [FRED Economic Data](https://fred.stlouisfed.org/) (if World Bank API unavailable)

**Grading Criteria:**
- ✓ At least 2 distinct data sources identified  
- ✓ Data accessibility confirmed  
- ✓ Data appears sufficient for proposed analysis  
- ✓ Backup plan provided  

---

## **1.4 Methodology Overview (2 points)**

**Approach:**
1. **Data Collection:** Merge customer data with economic indicators  
2. **Data Cleaning:** Handle missing values, outliers, and duplicates  
3. **Feature Engineering:** Create new features (e.g., customer lifetime value, usage patterns)  
4. **Modeling:** Compare Logistic Regression, Random Forest, and XGBoost  
5. **Evaluation:** Use Accuracy, Precision, Recall, F1-score, and ROC-AUC metrics  
6. **Deployment Plan:** Build a simple churn prediction interface  

**Grading Criteria:**
- ✓ Approach is logical and feasible  
- ✓ Techniques align with course content  
- ✓ Timeline is realistic  

---

## **1.5 Expected Challenges (1 point)**

**Challenges:**
1. **Imbalanced Dataset:** Only ~27% churn rate  
   → *Solution:* Use SMOTE oversampling or adjust class weights  

2. **Missing Economic Data:** Some time periods may lack indicators  
   → *Solution:* Apply interpolation or exclude affected records  

3. **Limited Domain Knowledge:** Lack of telecom-specific expertise  
   → *Solution:* Review industry reports and consult with TA  

**Grading Criteria:**
- ✓ Challenges identified and mitigation strategies proposed  

---
