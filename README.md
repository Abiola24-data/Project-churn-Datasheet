
# 📊 **Customer Churn Analysis using Excel & Power BI**  

### **Author:** Abiola Yussuf  
### **Date:** August 31, 2024  

## **📌 Project Overview**  

In this project, I analyzed a **telecommunications churn dataset** using **Excel** and **Power BI** to uncover insights into customer behavior, retention trends, and revenue optimization strategies. The goal was to answer critical business questions and provide data-driven recommendations to reduce churn and enhance customer engagement.  

This analysis demonstrates my expertise in **data visualization, data modeling, and business intelligence tools**, with a strong focus on **data-driven decision-making**.  

> **Disclaimer:** This is a learning-based project designed to showcase my analytical skills in **Excel and Power BI** and is not based on real-world company data.  

---

## **📂 Data Source & Preparation**  

The dataset was obtained from a **Churn Datasheet**, which contains customer demographic data, account details, and service subscriptions.  

- Data imported into **Excel & Power BI** from a local disk.  
- Schema analysis and data dictionary review to ensure accurate insights.  

🔗 **Dataset Link:** [Download Here](https://cdn.theforage.com/vinternships/companyassets/4sLyCPgmsy8DA6Dh3/02%20Churn-Dataset.xlsx)  

---

## **📈 Key Business Questions Addressed**  

### **1️⃣ Customer Churn & Service Usage Analysis**  
- Identifying customers who **left in the last month** and understanding their service usage.  
- Analyzing **contract types, payment methods, and service subscriptions** affecting churn.  
- Evaluating demographic insights (age, gender, partner status) influencing retention.  

### **2️⃣ Executive-Level KPI Dashboard**  
A high-level dashboard was designed to give decision-makers a quick overview of:  
- **Total Revenue** & financial trends.  
- **Active Subscribed Customers** vs. churned customers.  
- **Contract Services Breakdown** (Month-to-month, One-year, Two-year).  
- **Customer Demographics & Preferences.**  

---

## **🛠️ Data Transformation & Modeling**  

### **🔹 Data Cleaning (Excel & Power BI)**  
- Handled missing values & formatted data for consistency.  
- Created calculated columns (e.g., **Loyalty Score** & **Risk Category**) to classify customer groups.  

### **🔹 DAX Measures & Business Calculations**  
- Created **custom KPIs** using DAX formulas to track churn rate, revenue, and subscription trends.  
- Used **filters, tooltips, and calculated fields** to enhance dashboard insights.  

### **🔹 Data Modeling & Relationships**  
- Established **relationships between tables** to connect customer data with services and financial details.  
- Overridden **Power BI’s automated relationships** to ensure accurate data connections.  

📌 **Example DAX Measures Created:**  
```DAX
Churn Rate = 
DIVIDE(
    COUNTROWS(FILTER(Customers, Customers[Churn] = "Yes")),
    COUNTROWS(Customers)
)
```

---

## **📊 Key Insights & Business Findings**  

### **1️⃣ Customer Retention & Churn Patterns**  
- **30% of churned customers left within the first 6 months**, indicating a need for stronger **onboarding and engagement programs**.  
- Customers subscribed for **2+ years** had a **higher retention rate**, showing **long-term contracts** help reduce churn.  

### **2️⃣ Demographics & Behavioral Trends**  
- **51% of customers are male**, but they have a **slightly higher churn rate** compared to female customers.  
- Customers aged **25-40** are **most likely to churn**, possibly due to flexible service options from competitors.  

### **3️⃣ Service Subscriptions & Revenue Impact**  
- **Fiber Optic Internet users have the highest monthly bills ($283K)** but also a **higher churn rate** than DSL users.  
- Customers subscribed to **both streaming TV & movies** are **40% less likely to churn**, suggesting **bundled services improve retention**.  

### **4️⃣ Financial Insights & Payment Behavior**  
- **Electronic Check payments account for 57% of churned customers**, highlighting a need to **incentivize auto-pay** or credit card billing.  
- Customers on **monthly contracts** have the highest churn rate, reinforcing the need to **promote annual contracts**.  

---

## **📌 Business Recommendations**  

Based on these insights, the following strategic actions are recommended to reduce churn and increase revenue:  

### **1️⃣ Strengthen Customer Retention Efforts**  
✅ Implement **targeted promotions** for new customers (first 6 months) to improve retention.  
✅ Offer **personalized customer support** for at-risk customers based on **contract length & payment behavior**.  

### **2️⃣ Improve Subscription & Upselling Strategies**  
✅ Introduce **family & group plans** to encourage multiple-line and bundled service subscriptions.  
✅ Bundle **streaming services with internet & phone plans** to enhance customer stickiness.  

### **3️⃣ Optimize Payment & Pricing Strategies**  
✅ Offer **discounts for auto-pay & credit card users** to reduce churn caused by manual payments.  
✅ Provide **tiered pricing & loyalty rewards** for long-term customers.  

---

## **📊 Power BI Dashboards & Visualizations**  

🚀 **Churn Dashboard:**  
- Shows **churn rate trends, customer demographics, and service usage patterns**.  
- Visual breakdown of **high-risk customer segments** for retention planning.  

📸 ![Churn Dashboard](https://github.com/user-attachments/assets/de325534-7473-4f5c-a04e-e47345cd5d5e)  

🚀 **Risk Analysis Dashboard:**  
- Analyzes **churn risks based on customer profiles, service usage, and payment preferences**.  
- Identifies high-value customers at risk of leaving.  

📸 ![Risk analysis Dashboard](https://github.com/user-attachments/assets/f1f3ae4d-a11b-4d86-912b-28f3cbb3a612)  

---

## **💼 Conclusion: Business Value of Data Analytics**  

This project highlights how **data analytics can provide actionable insights** to:  
✔ Reduce customer churn.  
✔ Optimize pricing & subscription models.  
✔ Enhance customer engagement strategies.  

By leveraging **Excel & Power BI**, I transformed raw data into **business intelligence** that supports decision-making.  

🔎 **Interested in a Data Analyst role?** Let’s discuss how I can bring these skills to your company!  

📌 **Let’s Connect:**  
📍 [LinkedIn](#) | 📍 [Portfolio](#) | 📍 [GitHub](#)  






