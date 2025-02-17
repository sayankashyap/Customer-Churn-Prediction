# 📊 Customer Churn Prediction – Data Engineering Project using Databricks  

## 📌 Project Overview  
This project focuses on predicting and analyzing **customer churn** in the **telecom industry** using **Databricks**. By leveraging **big data processing, machine learning, and real-time dashboards**, we provide actionable insights to help businesses **reduce churn and improve customer retention strategies**.  

---

## 🚀 Technologies Used  
- **Databricks** (Apache Spark, PySpark, Databricks SQL)  
- **Python** (pandas, NumPy, scikit-learn, XGBoost)  
- **SQL** (Data querying and transformation)  
- **MLflow** (Model tracking and drift monitoring)  
- **Power BI** (Data visualization and dashboarding)  

---

## 📂 Dataset  
- **Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)  
- **Description:** Customer demographics, subscription details, service usage, and churn status.  
- **Key Features:**  
  - `CustomerID` - Unique customer identifier  
  - `Tenure, Contract, Payment Method` - Subscription details  
  - `MonthlyCharges, TotalCharges` - Financial details  
  - `Churn` - Target variable (Yes/No)  

---

## 🛠️ Project Workflow  

### 1️⃣ **Data Engineering Pipeline (Databricks)**  
- **Data ingestion, cleaning, and transformation** using **Apache Spark**  
- **Handling missing values & data type conversion**  
- **Feature engineering (categorical encoding, scaling)**  

### 2️⃣ **Machine Learning Modeling**  
- **Models Used:** Logistic Regression, Random Forest, XGBoost  
- **Best Model:** XGBoost (**AUC-ROC: 0.85**)  
- **Hyperparameter tuning** using Grid Search  

### 3️⃣ **Survival Analysis & A/B Testing**  
- **Kaplan-Meier Curve:** Customer retention probabilities over time  
- **Cox Proportional Hazards Model:** Identified churn risk factors  
- **A/B Testing:** Evaluated **retention strategies** (discounts, offers, incentives)  

### 4️⃣ **Model Drift Monitoring**  
- **Drift detection** using **MLflow tracking**  
- **Kolmogorov-Smirnov & Chi-Square tests** for feature distribution monitoring  

### 5️⃣ **Interactive Dashboard (Databricks + Power BI)**  
- **KPIs Tracked:** Overall Churn Rate, Monthly Recurring Revenue, Customer Retention Rate  
- **Visualizations:** Heatmap, Line Chart, Scatter Plot, Pivot Table  

---

## 📊 Business Insights  
✅ **Month-to-month contracts have the highest churn**  
✅ **Customers with high monthly charges are more likely to churn**  
✅ **Long-term contracts improve customer retention**  
✅ **Early churn can be predicted using survival analysis**  
✅ **Retention strategies (discounts, offers) significantly reduce churn**  

---

## 🏗️ How to Run the Project  

### 🔹 **1. Setup Environment in Databricks**  
- Upload dataset to **Databricks File Store**  
- Load data using **Apache Spark (`pyspark.sql`)**  

### 🔹 **2. Run Data Processing & ML Pipeline**  
- Execute **EDA, Feature Engineering, and ML model training**  
- Run **churn predictions** and **evaluate models**  

### 🔹 **3. Deploy ML Model & Dashboard**  
- Deploy trained model for **real-time churn prediction**  
- Use **Power BI** or **Databricks SQL Dashboard** for visualization  

---

## 🔮 Future Enhancements  
📌 **Automate churn prediction pipeline** for real-time scoring  
📌 **Integrate customer feedback analysis** using NLP  
📌 **Expand A/B testing** for personalized retention offers  
📌 **Deploy model using REST API for business integration**  

---

## 📜 Conclusion  
This project successfully demonstrates a **data-driven approach** to predicting **customer churn** using **Databricks and machine learning**. The insights help businesses **optimize retention strategies** and **reduce churn rates**. **The dashboard enhances these insights by providing real-time visualization for data-driven decision-making.**  

---

## ✨ Author  
**👤 Sayan Kashyap**  
🔗 [https://www.linkedin.com/in/sayankashyap/]

---

## 💡 Contributing  
Feel free to **open issues**, **submit PRs**, or **suggest improvements**! 🚀  

---
