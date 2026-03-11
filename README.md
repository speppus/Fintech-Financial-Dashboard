# 💳 Fintech Analytics Dashboard – Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Data Modeling](https://img.shields.io/badge/Data%20Model-Star%20Schema-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📊 Project Overview

This project presents an **interactive Fintech Analytics Dashboard built with Power BI** to analyze financial transactions, customer activity, product performance, and account management.

The dashboard transforms raw transactional data into **clear and actionable insights**, supporting performance monitoring and data-driven decision-making in a fintech context.

The report is structured around five main analytical areas:

- Financial Performance Monitoring
- Transaction Behavior Analysis
- Customer Activity Analysis
- Product Performance Analysis
- Account Portfolio Analysis

---

## 🧠 Business Objective

The main objective of this project is to provide a complete analytical view of a fintech ecosystem by monitoring:

- transaction volumes and performance
- inflows, outflows, and total balance
- customer activity and regional distribution
- product profitability and usage patterns
- account lifecycle and balance distribution

This dashboard is designed to support both **operational monitoring** and **strategic analysis**.

---

## 🗂 Data Model

The project is based on a **Star Schema** model to ensure efficient reporting and analytical performance.

### Fact Table
**FactTransaction**

Contains transactional data such as:

- Transaction ID
- Transaction Amount
- Transaction Type
- Transaction Channel
- Date
- Account ID
- Product ID
- Customer ID

### Dimension Tables

- **DimAccount**
- **DimCustomer**
- **DimCustomerUSA**
- **DimProduct**
- **DimProductCategory**
- **DimProductSubCategory**
- **Calendar Table**

These tables enable multi-dimensional analysis across **time, customers, products, accounts, and regions**.

---

## 🖥 Report Pages

### 1️⃣ Executive Overview

![Executive Overview](images/1_Executive%20Overview.png)

The **Executive Overview** page provides a high-level summary of the overall financial performance.

#### Main KPIs
- Total Transactions
- Total Inflows
- Total Outflows
- Total Balance
- Successful Transactions %

#### Main Visuals
- **Total Balance by Year** to monitor the balance trend over time
- **Average Transaction Amount by Year and Month** to evaluate changes in the average transaction value
- **Positive vs Negative Balance by Year** to compare inflows and outflows across years

This page allows stakeholders to quickly assess the **financial health and performance trend** of the system.

---

### 2️⃣ Transaction Analysis

![Transaction Analysis](images/2_Transaction%20Analysis.png)

The **Transaction Analysis** page focuses on transaction performance and operational behavior.

#### Main KPIs
- Total Transactions
- Average Transaction
- Outflows
- Failure Rate
- Successful Transactions

#### Main Visuals
- **Inflows vs Outflows (%) Trend** to compare percentage variations over time
- **Transactions by Year and Month** to analyze transaction volume trends
- **Success vs Failed Transactions** to evaluate system reliability
- **Transaction by TransactionChannel** to identify the most used channels
- **Transaction by TransactionType** to compare debit and credit operations

This section helps identify **usage trends, operational efficiency, and transaction patterns**.

---

### 3️⃣ Customer Analysis

![Customer Analysis](images/3_Customer%20Analysis.png)

The **Customer Analysis** page explores customer behavior and regional distribution.

#### Main KPIs
- Total Transactions
- Transactions Last Year
- Average Transaction
- Average Transaction by Client
- Total Customers

#### Main Visuals
- **Top 10 Customers by Transactions** to identify the most active customers
- **N Customer per Region** to analyze customer distribution geographically
- **Customer Transactions Trend** to monitor customer activity over time
- **Top Customer Card** to highlight the best-performing customer with region and value indicators

This page supports the identification of **high-value customers and regional concentration patterns**.

---

### 4️⃣ Product Analysis

![Product Analysis](images/4_Product%20Analysis.png)

The **Product Analysis** page evaluates the performance of financial products.

#### Main KPIs
- Number of Products
- Total Inflows
- Total Outflows
- Average Transaction

#### Main Visuals
- **Average Transaction Value by Product (Ascending vs Descending)** to compare product-level transaction averages
- **Amount of Inflows and Outflows by Product** to assess product profitability
- **Product Category / Subcategory Flow Analysis** to analyze product hierarchy and contribution
- **Top Product by Inflows** to highlight the best-performing product
- **Best Product with Lowest Outflows** to identify the most efficient product from an outflow perspective

This section is useful for understanding **product contribution, profitability, and value generation**.

---

### 5️⃣ Account Analysis

![Account Analysis](images/5_Account%20Analysis.png)

The **Account Analysis** page focuses on account balances, status, and lifecycle.

#### Main KPIs
- Number of Accounts
- Open Accounts
- Closed Accounts
- Total Balance
- Average Balance per Account

#### Main Visuals
- **Total Balance by Region** to identify geographical concentration of balance
- **Total Balance by Status** to compare open vs closed account balances
- **Opened vs Closed Accounts by Year** to monitor account lifecycle trends
- **Average Balance per Account** to evaluate balance distribution across accounts
- **Total Account Balance by Year** to analyze yearly contribution
- **Opened Accounts by Region** to visualize account distribution geographically

This page supports **portfolio monitoring and account lifecycle analysis**.

---

## 🧮 DAX Measures

The report includes custom DAX measures developed to support KPI monitoring, time intelligence, customer analysis, product analysis, and account performance evaluation.

### Financial Measures
- `% transazioni riuscite`
- `avg saldo per conto`
- `balance`
- `Entrate Positive`
- `Entrate YoY%`
- `entrate YTD`
- `Saldo generale`
- `saldo YTD`
- `uscite negative`
- `transazioni YTD`

### Transaction Measures
- `AVG Transaction Label`
- `avg transazine x cliente`
- `conteggio entrate positive`
- `N transazioni`
- `N transazioni LY`
- `N transazioni YoY %`
- `N transazioni YoY Diff`
- `N transazioni YoY freccia`
- `N transazioniFallite`
- `N transazioniSucces`
- `Transazioni KPI`

### Customer & Account Measures
- `N accountID`
- `N conti Aperti`
- `N conti Chiusi`
- `N Customer`

### Product Measures
- `N category`
- `N prodotti`
- `N SubCategory`
- `Rank Product`
- `Top Product`
- `Top Product outflout`

These measures enable dynamic analysis across the dashboard and support both **descriptive and comparative financial reporting**.

---

## 📈 Key Insights

Some of the main insights emerging from the dashboard include:

- transaction activity remains consistently high over time
- digital channels such as **mobile and web** dominate transaction activity
- a relatively small group of customers contributes significantly to transaction volume
- some financial products generate substantially higher inflows than others
- regional differences affect both customer concentration and balance distribution
- account lifecycle analysis highlights the relationship between opened and closed accounts over time

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Interactive dashboard development |
| **DAX** | KPI and analytical calculations |
| **Power Query** | Data transformation and preparation |
| **Data Modeling** | Star schema design |
| **Financial Analytics** | Business performance analysis |

---

## 🎯 Project Value

This project demonstrates practical skills in:

- data modeling
- KPI design
- DAX development
- financial reporting
- dashboard storytelling
- business-oriented data visualization

It is designed as a **portfolio project for Data Analyst / BI Developer roles** with a focus on financial and operational analytics.

---

## 👨‍💻 Author

**Business Intelligence Portfolio Project**  
Developed using **Power BI** for fintech and financial analytics.

---

⭐ If you found this project interesting, feel free to **star the repository**.

