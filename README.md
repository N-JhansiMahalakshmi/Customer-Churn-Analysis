# Customer-Churn-Analysis
# 📉 Churnlytics: Customer Churn Analysis Dashboard  

A dynamic, interactive Power BI dashboard built to analyze customer churn in the telecommunications sector—focusing on churn drivers, customer segmentation, risk factors, and revenue impact.  

---

## 📝 Short Description / Purpose  

The Customer Churn Analysis Dashboard is designed to help telecom companies identify, visualize, and understand customer attrition patterns. It enables decision-makers to analyze churn across multiple dimensions—contracts, payments, services, and demographics—while quantifying revenue loss and customer risk levels.  

---

## ⚙️ Tech Stack  

The dashboard was built using the following tools and technologies:  
- 📊 **Power BI Desktop** – Main data visualization platform for dashboard creation.  
- 📂 **Power Query** – Data cleaning, integration, and transformation pipeline.  
- 🧠 **DAX (Data Analysis Expressions)** – For calculated fields, KPIs, and churn-specific measures.  
- 📝 **Data Modeling** – Established relationships across customer demographics, contracts, services, and churn labels.  
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard preview.  

---

## 📂 Data Source  

**Source**: Telecommunications Customer Dataset (simulated industry dataset).  

The dataset includes ~7,000 customers with attributes such as:  
- **Demographics**: Gender, Senior Citizen status, Family status.  
- **Account Info**: Tenure, Contract type, Payment method, Billing preference.  
- **Services**: Internet service type, streaming subscriptions, device protection.  
- **Churn Label**: Customer retention status (Yes/No).  
- **Revenue Metrics**: Monthly charges, total charges, and revenue lost from churn.  

---

## 🌟 Features / Highlights  

### • Business Problem  
Telecom companies face high customer turnover, especially among month-to-month contract users. Churn erodes profitability and increases acquisition costs. Traditional retention efforts often lack data-driven targeting.  

### • Goal of the Dashboard  
To deliver an interactive analytics solution that:  
- Identifies **key drivers of churn**.  
- Quantifies **revenue loss due to churn**.  
- Enables segmentation by contract, payment method, risk category, and service usage.  
- Provides actionable insights to improve **retention strategies**.  

### • Walkthrough of Key Visuals  

- **Key KPIs (Top-Level)**  
   - Total Customers: `7,042`  
   - Churned Customers: `1,869`  
   - Total Revenue Lost: `$139.12K`  
   - New Customers: `1,062`  

- **Churn Distribution (Bar & Pie Charts)**  
   - Breakdown of churn by **gender, tenure, contract type, and family status**.  
   - High churn observed in **month-to-month contracts** and **new customers (0–12 months tenure)**.  

- **Risk & Revenue Analysis**  
   - Churn by **Risk Category (High, Medium, Low)**.  
   - **Average monthly revenue** per contract type shows month-to-month users generate high revenue but are most unstable.  

- **Service Usage Insights**  
   - Customers using **multiple services** churn less, showing engagement reduces attrition.  
   - **Electronic check payments** and **no paperless billing** linked to higher churn.  

- **Revenue Impact**  
   - Visuals highlight **Total Revenue Lost** and monthly charges distribution by churn status.  

### • Business Impact & Insights  

- **Customer Retention**: Pinpoints high-risk churn groups (month-to-month, electronic check, low tenure).  
- **Revenue Protection**: Helps prioritize retention strategies for **high-value at-risk customers**.  
- **Product Strategy**: Encourages bundling services to increase stickiness.  
- **Payment Optimization**: Promotes secure and automatic payment methods to reduce churn.  

---

## 📸 Screenshots / Demos  

- **Churn Distribution Dashboard**  
  ![Churn Dashboard 1](D:/BA_Projects/Telco/Customer churn analysis snapshot.jpg)  

- **Risk and Revenue Dashboard**  
  ![Churn Dashboard 2](D:/BA_Projects/Telco/Customer Churn Analysis Snapshot(2).jpg)  

---

👉 This dashboard empowers telecom decision-makers to **move from reactive churn analysis to proactive churn prevention**—maximizing customer lifetime value while reducing attrition.  
