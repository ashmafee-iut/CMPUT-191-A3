Problem: Predicting customer churn in telecommunications industry
Importance: Customer retention is 5x cheaper than acquisition
Domain: Business/Marketing Analytics
Audience: Telecom company marketing departments
```

**Grading Criteria:**
- ✓ Problem is clearly defined and specific
- ✓ Real-world relevance is established
- ✓ Scope is appropriate for course level

---

#### **1.2 Research Questions/Objectives (2 points)**

**What to include:**
- 2-4 specific questions your project will answer
- Hypotheses you want to test (if applicable)
- Expected outcomes or goals

**Example:**
```
Primary Question: Can we predict which customers will churn within 3 months?
Secondary Questions:
  - What factors most strongly correlate with churn?
  - How does model accuracy compare across different algorithms?
  - What is the cost-benefit of implementing this model?
```

**Grading Criteria:**
- ✓ Questions are specific and measurable
- ✓ Questions are answerable with data science techniques
- ✓ Questions align with problem statement

---

#### **1.3 Data Sources (3 points)**

**What to include:**
- Description of data sources (minimum 2 sources)
- How you will collect/access the data (APIs, web scraping, public datasets, etc.)
- Expected data size and format
- Data availability confirmation (provide URLs or access proof)
- Backup plan if primary data source fails

**Example:**
```
Primary Source: Kaggle Telecom Customer Churn Dataset (7,043 records, CSV)
URL: https://www.kaggle.com/...
Access: Public download

Secondary Source: Economic indicators via World Bank API
URL: https://api.worldbank.org/...
Access: Free API access

Backup: If World Bank API unavailable, use FRED Economic Data
```

**Grading Criteria:**
- ✓ At least 2 distinct data sources identified
- ✓ Data accessibility confirmed
- ✓ Data appears sufficient for proposed analysis
- ✓ Backup plan provided

---

#### **1.4 Methodology Overview (2 points)**

**What to include:**
- High-level approach to solving the problem
- Techniques/algorithms you plan to use (learned in class)
- Analysis workflow diagram (optional but recommended)

**Example:**
```
Approach:
1. Data Collection: Merge customer data with economic indicators
2. Data Cleaning: Handle missing values, outliers, duplicates
3. Feature Engineering: Create new features (customer lifetime value, usage patterns)
4. Modeling: Compare Logistic Regression, Random Forest, and XGBoost
5. Evaluation: Use accuracy, precision, recall, F1-score, ROC-AUC
6. Deployment Plan: Create simple prediction interface
```

**Grading Criteria:**
- ✓ Approach is logical and feasible
- ✓ Techniques align with course content
- ✓ Timeline is realistic

---

#### **1.5 Expected Challenges (1 point)**

**What to include:**
- Anticipated difficulties (technical, data quality, time constraints)
- Mitigation strategies

**Example:**
```
Challenges:
1. Imbalanced dataset (only 27% churn rate)
   → Solution: Use SMOTE oversampling or adjust class weights

2. Missing economic data for some time periods
   → Solution: Interpolation or exclude affected records

3. Limited domain knowledge in telecommunications
   → Solution: Review industry reports, consult with TA
