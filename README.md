# 📊 Telecom Customer Churn Analysis – Power BI Dashboard

## 🔎 Project Overview

This project analyzes **customer churn in a telecom company** using **Power BI**.
The goal is to identify **why customers leave**, **who is at high risk**, and **how much revenue is being lost**, enabling business teams to take **data-driven retention actions**.

---

## 🎯 Business Problem

Customer churn directly impacts revenue and growth.
The company wanted to answer:

* How many customers are churning?
* Which customers are most likely to leave?
* What services or contracts cause higher churn?
* How much revenue is lost due to churn?
* Which segments need immediate retention strategies?

---

## 🧰 Tools & Technologies

* **Power BI**
* **Power Query (ETL)**
* **DAX**
* **Data Modeling**
* Dataset: Telecom Customer Churn dataset

---

## 📈 Dashboard Pages Overview

### 1️⃣ Executive Overview

Provides a high-level snapshot of business performance and churn impact.

**Key KPIs**

* Total Customers: **7043**
* Average CLV: **2.28K**
* Total Monthly Revenue: **456.12K**
* Churn Rate: **26.54%**
* Revenue Lost: **139.13K**

**Insights**

* Nearly **1 in 4 customers churn**.
* Revenue loss from churn is **significant** and needs urgent action.
* Most churn comes from **month-to-month contracts**.

---

### 2️⃣ Churn Analysis

Deep dive into churn drivers.

**Key Findings**

* **Month-to-month contracts** have the highest churn.
* Customers in **0–1 year tenure** churn the most.
* **Fiber optic users** churn more than DSL users.
* **Electronic check** payment users have the highest churn.

**Interpretation**
New customers with flexible contracts and electronic payments are **high-risk segments**.

---

### 3️⃣ Customer Segmentation

Breaks churn into meaningful customer segments.

**Key Metrics**

* New Customer Churn: **1037**
* High Value Churn: **906**
* Avg Charges (Churned): **74.44**

**Segment Insights**

* Customers without **online security** churn significantly more.
* **Non-senior citizens** form the majority of churned users.
* Fiber optic + Month-to-Month = **highest revenue loss combination**.

---

### 4️⃣ High-Risk Customers Table

A detailed table showing customers most likely to churn.

Includes:

* Customer ID
* Tenure
* Monthly Charges
* Contract Type
* Internet Service

**Purpose**

* Helps retention teams target customers for **offers and interventions**.

---

## 💡 Key Business Insights

1. **Contract Type is the biggest churn driver**

   * Month-to-month customers are the most unstable.

2. **Early churn is critical**

   * Majority of churn happens within the **first year**.

3. **Fiber Optic customers are at higher risk**

   * Possibly due to **pricing or service quality issues**.

4. **Payment method matters**

   * Electronic check users churn the most.

5. **Security services reduce churn**

   * Customers with online security stay longer.

---

## 🚀 Business Recommendations

### 📌 Retention Strategies

* Offer **discounted yearly contracts** to month-to-month users.
* Provide **welcome offers** for first-year customers.
* Improve **fiber service experience**.
* Encourage **auto-payment methods**.
* Bundle **online security services**.

---

## 📂 Project Structure

```
Telecom-Churn-PowerBI/
│
├── Dataset
├── PowerBI Dashboard (.pbix)
├── Screenshots
└── README.md
```

---

## 🏁 Conclusion

This dashboard helps businesses:

* Identify churn drivers
* Reduce revenue loss
* Improve customer retention
* Make data-driven decisions

---

## 👤 Author

**Rampelly Nikhil**
Aspiring Data Analyst | Power BI Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
