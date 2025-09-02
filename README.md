# Customer-Support-Satisfaction-Prediction-with-Explainable-AI

## Project Objective
To analyze customer support interaction data and classify Customer Satisfaction (CSAT) scores using both Machine Learning and Deep Learning models. The project also aims to identify key drivers of satisfaction and provide Tableau dashboards for actionable business insights.

---

## Dataset
- File: `Customer_support_data.csv`  
- Size: ~5K records  
- Key Fields:  
  - Agent & shift details (`Agent_name`, `Supervisor`, `Manager`, `agent_shift`, `Tenure Bucket`)  
  - Order & issue timestamps (`Order_Date_Time`, `Issue_reported at`, `issue_responded at`, `Survey_response_Date`)  
  - Product & transaction details (`Item_price`, `category`, `Sub-category`, `channel_name`)  
  - Customer feedback (`Customer Remarks`, `csat_score`)  

---

## Tasks Performed
1. Data Cleaning & Exploratory Data Analysis (EDA)  
   - Missing value treatment, outlier detection, distribution checks  
   - CSAT score trends and correlations  

2. Feature Engineering  
   - Response time metrics  
   - Sentiment features from customer remarks  
   - Price bucket and high-value order flag  
   - Agent-wise CSAT averages and category frequencies  
   - Temporal features (order hour, day, part of day, weekends)  

3. Modeling  
   - Machine Learning: Logistic Regression, Random Forest, KNN, XGBoost, LightGBM, CatBoost  
   - Deep Learning: Multilayer Perceptron (Keras/TensorFlow) with EarlyStopping  
   - Imbalance handling with SMOTE  
   - Evaluation with accuracy, F1-score, confusion matrix  

4. Visualization  
   - Python plots (Matplotlib, Seaborn, SHAP)  
   - Tableau dashboards (agent performance, CSAT by category, response time vs CSAT)  

---

## Key Insights
- Longer response times strongly reduce CSAT scores.  
- Certain product categories consistently have lower satisfaction.  
- High-value orders show higher dissatisfaction risk.  
- Significant performance differences exist between agents and shifts.  
- Negative sentiment in remarks is a strong indicator of low CSAT.  

---

## Business Recommendations
- Optimize workflows to reduce response times.  
- Provide focused training for low-performing agents and supervisors.  
- Improve policies for categories with persistent dissatisfaction.  
- Prioritize handling of high-value orders with premium support.  
- Incorporate real-time sentiment analysis in support systems.  

---

## Note
This project is prepared as part of a **Data Analysis CV portfolio** to demonstrate skills in:  
- Data wrangling and visualization  
- Machine Learning and Deep Learning classification  
- Feature engineering for business data  
- Dashboarding with Tableau  

