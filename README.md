# 📊 Customer Attrition (Churn) Analysis – Power BI Dashboard

This repository contains a complete **Customer Attrition (Churn) Analysis** project designed using **Power BI**, **Power Query**, and **DAX**.  
The dashboard explores **why customers leave a credit card product**, focusing on behavioral indicators rather than demographic attributes.

🔗 **Live Dashboard Link:**  
https://app.powerbi.com/view?r=eyJrIjoiMjAwMmI4MGEtOTk0Ny00ZGMzLWJmZTQtYTcxMTJjYzcwN2ZjIiwidCI6IjU5MzNiODUwLThhYmMtNDFlMS05ZjgwLWExMDU2NGM0YmZjMSJ9

---

# 🛠 Project Architecture


---

# 📘 Summary

Analysis shows that **customer attrition is behavior-driven, not demographic-driven**.  
Demographics such as gender, age, income, marital status, dependents, and card category do **not meaningfully differentiate** attrited customers from existing ones.

Instead, churn is strongly linked to:

- High inactivity months  
- Sharp decline in transactions (Q1 → Q4)  
- Major drop in total spend  
- Low credit utilization  
- Higher customer service interactions  

📌 **Key Insight:**  
> Customers don’t leave because of who they are — they leave because of how they behave.

---

# 🖼 Dashboard Screenshots & Key Highlights

## 1️⃣ **Overview Page – Customer Demographics & High-Level Metrics**

![image alt](https://github.com/user-attachments/assets/94cb03e2-4f6a-4e45-bfe3-33da50f0342c)


### 🔍 **Key Strengths:**
- Displays **Total Card Holders, Avg Credit Limit, Attrited Count**, Tenure, and Avg Utilization.
- Clear demographic distribution by **Age, Education, Income**, and **Gender**.
- Donut chart clearly shows the **attrition ratio (16%)**.
- Filters allow dynamic slicing by demographic variables.

### 🧠 Insight:
The demographic spreads of existing vs attrited customers are almost identical — proving demographics **did not drive churn**.

---

## 2️⃣ **Existing vs Attrited Dashboard – Behavioral Driver Analysis**

https://github.com/user-attachments/assets/2d8f518d-73a9-46b1-afe1-9e3363e0b6e4

### 🔍 **Key Strengths:**
- KPI cards compare existing vs attrited customers for:
  - Average credit limit  
  - Average transactions  
  - Utilization %  
  - Months inactive  
- Bar chart highlights **Q1→Q4 declines** in both spend and transaction count.
- Engagement Decline Index quantifies behavioral disengagement.
- Customer service interaction comparison highlights friction as a churn driver.

### 🧠 Insight:
Attrited customers show **higher inactivity**, **lower usage**, and **more service interactions** — confirming that churn is caused by **behavioral disengagement**.

---

## 3️⃣ **Attrited Customer Profile – Sankey Flow**

https://github.com/user-attachments/assets/ffdb71fc-321d-468f-b24f-cb80f8803e27

### 🔍 **Key Strengths:**
- Sankey chart shows how attrited customers flow across:
  - Gender → Marital Status → Education → Income Categories
- Helpful for **profiling attrited customers** visually.
- Demonstrates that attrition is **evenly distributed across demographic segments**.

### 🧠 Insight:
No specific demographic group displays disproportionate attrition. Attrition is **consistent across all categories**, reinforcing behavior-driven churn.

---

## 4️⃣ **KPI Comparison Cards – Existing vs Attrited (Top Summary)**

https://github.com/user-attachments/assets/e5697bdf-1e07-496d-8de0-bffe1c5a8b64

### 🔍 **Key Strengths:**
- Direct comparison of:
  - Avg Credit Limit  
  - Utilization %  
  - Avg Transactions  
  - Months Inactive  
- Highlights behavioral gaps:
  - Utilization: **29.64% (Existing) vs 16.25% (Attrited)**
  - Avg Transactions: **68.67 vs 44.93**
  - Inactive Months: **2.27 vs 2.69**

### 🧠 Insight:
Even small gaps in **inactivity** and **utilization** compound into high churn — emphasizing early engagement monitoring.

---

# 🔍 Key Churn Drivers Identified

### **1️⃣ High Inactive Months (Strongest Predictor)**  
### **2️⃣ Sharp Decline in Transaction Count (Q1 → Q4)**  
### **3️⃣ Large Decline in Transaction Amount**  
### **4️⃣ Lower Monthly Engagement (Spend + Frequency)**  
### **5️⃣ Low Credit Utilization (~17%)**  
### **6️⃣ Higher Customer Service Interactions (20–25% more)**  

---

# 🚫 Not Drivers of Churn (Demographics)

- Age  
- Gender  
- Income  
- Education  
- Marital Status  
- Dependents  
- Card Category  
- Tenure  

📌 **Churn is usage-driven, not demographic-driven.**

---

# 📊 Key KPIs Designed

- **Churn Rate**  
- **Inactivity Months (12M)**  
- **Q1 → Q4 Transaction Drop %**  
- **Spend Decline %**  
- **Average Utilization %**  
- **Engagement Decline Index**  
- **Customer Service Interaction Count**

---

## 🎯 Business Recommendations

### ✔ Early Warning Monitoring
- Inactivity  
- Drop in spending  
- Drop in transaction count  
- Low utilization  

### ✔ Reactivation Campaigns
- Personalized offers  
- Usage reminders  
- Spend-based incentives  

### ✔ Improve Customer Service
- Faster issue resolution  
- Minimize repeated contacts  
- Proactive communication  

### ✔ Enhance Engagement
- Spend promotions  
- Benefit education  
- Targeted marketing  

---

## 🧰 Tools Used
- Power BI Desktop  
- Power Query (M Language)  
- DAX  
- Excel  

---

---

## 👨‍💻 Author

**Prakash**  
Data Analyst  
Skills: Power BI • SQL • Excel • Tableau • Python  
LinkedIn: www.linkedin.com/in/prakash-varkala-5a36682a5 

---

## ⭐ Contributions
Suggestions, improvements, and feedback are welcome!  
Feel free to open an issue or submit a pull request.
