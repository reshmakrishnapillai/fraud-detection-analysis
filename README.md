# 🚨 Fraud Detection Analysis Dashboard

An interactive **Power BI Fraud Detection Analysis Dashboard** designed to analyze transaction activity, identify fraudulent transactions, and uncover fraud patterns across transaction types, device types, locations, transaction amounts, and time.

---

## 📌 Project Overview

Fraud detection is an important part of financial transaction monitoring. Large transaction datasets can contain patterns that are difficult to identify through raw data alone.

This project uses **Power BI** to transform transaction-level data into an interactive dashboard that provides a clear overview of fraud activity and helps identify areas requiring further investigation.

The dashboard focuses on:

- Overall transaction volume
- Genuine vs fraudulent transactions
- Fraud rate
- Fraud amount
- Monthly fraud trends
- Fraud by transaction type
- Fraud by device type
- Fraud by location

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Monitor total transaction activity
- Identify fraudulent transactions
- Calculate the overall fraud rate
- Analyze fraud trends over time
- Compare fraud across transaction types
- Analyze fraud by device type
- Identify locations with higher fraud transaction counts
- Compare fraudulent amounts across transaction types
- Present fraud-related insights through an interactive dashboard

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI and analytical calculations |
| **Data Modeling** | Relationships and analytical structure |
| **CSV / Excel** | Source data |

---

## 🧹 Data Preparation

The dataset was prepared using **Power Query** before building the dashboard.

The preparation process included:

- Checking data types
- Handling missing values
- Removing duplicate records where required
- Standardizing categorical fields
- Preparing date fields
- Creating fields required for analysis
- Validating transaction and fraud-related values

---

## 📊 Key Performance Indicators

The final dashboard contains five main KPIs:

| KPI | Value |
|---|---:|
| **Total Transactions** | 1,200 |
| **Genuine Transactions** | 1,117 |
| **Fraud Transactions** | 83 |
| **Fraud Rate** | 6.92% |
| **Fraud Amount** | 149.15K |

These KPIs provide an immediate overview of the transaction and fraud situation.

---

## 📈 Dashboard Visualizations

### 1. Monthly Transaction & Fraud Trend

A trend visualization showing transaction activity and fraudulent transactions across months.

**Purpose:**  
To identify changes and patterns in transaction and fraud activity over time.

---

### 2. Fraud Transactions by Transaction Type

A **Treemap** comparing fraudulent transaction counts across transaction types.

**Purpose:**  
To identify which transaction types contribute more to fraudulent transaction volume.

---

### 3. Fraud Transactions by Device Type

A **Donut Chart** showing the distribution of fraudulent transactions across device types.

The dashboard shows:

- Mobile — 44 transactions
- Web — 31 transactions
- ATM — 8 transactions

**Purpose:**  
To understand which device categories account for a larger share of fraud activity.

---

### 4. Top 5 Locations by Fraud Transactions

A ranked bar chart showing the locations with the highest number of fraudulent transactions.

The displayed locations include:

- Kolkata
- Kochi
- London
- Bengaluru
- Dubai

**Purpose:**  
To identify locations with relatively higher fraud transaction activity.

---

### 5. Fraud Amount by Transaction Type

A pie chart comparing the amount associated with fraudulent transactions across transaction types.

**Purpose:**  
To understand where the financial impact of fraud is concentrated.

---

### 6. Fraud Rate Gauge

A gauge showing the overall fraud rate against a reference target.

- Current Fraud Rate: **6.92%**
- Reference Target: **5%**

**Purpose:**  
To quickly determine whether the observed fraud rate is above the selected benchmark.

---

## 🔍 Key Insights

### Fraud Volume

The dashboard contains **1,200 total transactions**, of which **83 are fraudulent transactions**.

### Fraud Rate

The overall fraud rate is **6.92%**, which is above the dashboard's **5% reference target**.

### Device Pattern

Mobile transactions represent the largest share of fraudulent transactions, followed by Web and ATM transactions.

### Location Pattern

The Top 5 Locations visual highlights locations with comparatively higher fraudulent transaction counts, allowing analysts to focus attention on those areas.

### Transaction Type Pattern

The Treemap shows differences in fraud transaction volume across transaction types, helping identify transaction categories with greater fraud activity.

### Financial Impact

The Fraud Amount visualization helps identify transaction types contributing a larger share of the total fraudulent amount.

---

## 💼 Business Value

This dashboard can support fraud and risk analysis by helping users:

- Monitor fraud KPIs
- Identify high-fraud transaction categories
- Analyze device-related fraud patterns
- Identify locations requiring further investigation
- Monitor financial impact
- Track fraud activity over time
- Support data-driven fraud investigation

---

## 🧮 DAX Measures

The dashboard uses DAX measures for KPI and analytical calculations.

Example:

```DAX
Fraud Transactions =
[Total Transactions] - [Genuine Transactions]

🗃️ Data Model

The Power BI model is structured to support:

Transaction analysis
Fraud analysis
Time-based analysis
Transaction-type analysis
Device-type analysis
Location analysis

A date structure is used to support monthly trend analysis and correct chronological sorting.

🎨 Dashboard Design

The final dashboard uses a single-page executive layout.

The design includes:

Highlighted KPI cards
Consistent visual theme
Clear section hierarchy
Multiple visualization types
Interactive filtering
Compact presentation of fraud KPIs and insights

The dashboard was designed to provide important fraud information without overcrowding the page.
Fraud Transactions =
[Total Transactions] - [Genuine Transactions]

📂 Project Structure
fraud-detection-analysis/
│
├── README.md
│
├── Power BI/
│   └── Fraud_Detection_Analysis.pbix
│
├── Dataset/
│   └── fraud_detection_dataset.csv
│
├── Dashboard PDF/
│   └── Fraud_Detection_Analysis_Dashboard_Documentation.pdf
│
└── Screenshots/
    └── fraud_detection_dashboard.png

🚀 Future Enhancements

Possible future enhancements include:

Advanced fraud risk scoring
Customer-level fraud analysis
More detailed time-based analysis
Additional fraud segmentation
Automated reporting
Predictive fraud analytics
Machine learning-based fraud prediction

👩‍💻 Author

Reshma Krishnapillai

Aspiring Data Analyst | Excel | SQL | Power BI | Python

⭐ Project Highlights

Domain: Financial / Fraud Analytics
Tool: Power BI
Focus: Fraud Detection & Risk Analysis
Dashboard: Interactive One-Page Dashboard
KPIs: 5
Visuals: 6+
Analysis: Transaction, Device, Location, Amount & Time

