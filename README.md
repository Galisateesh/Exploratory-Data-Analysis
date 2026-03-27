# Exploratory-Data-Analysis

Data Analytics Project: Digital Payments Performance & Risk Analytics

Data Analytics Project Showing Digital Payments Performance And Risk Analytics Using Python, MySQL, Power Bi

### **Overview**

This project presents an end-to-end data analytics workflow focused on analyzing digital payment transactions. It covers data loading, exploratory data analysis (EDA), data cleaning, SQL-based querying, and interactive dashboard creation using Power BI.

The objective is to extract meaningful insights related to transaction performance, customer behavior, and risk patterns.

### **📂 Dataset**

The dataset contains transaction-level data for digital payments.

Key attributes include:

- Transaction amount
- Merchant name
- Bank details
- Device type
- Customer demographics (age group, gender)
- Transaction status (Success/Failure)
  
Data was initially processed using Python and later stored in MySQL for querying.

### **🛠️ Tools & Technologies**
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- MySQL Server (Data storage and SQL queries)
- Power BI (Dashboard and visualization)
- Jupyter Notebook (EDA and data preprocessing)

### **🔄 Project Steps**

1. Data Loading
- Imported dataset using Pandas Inspected structure, columns, and data types
2. Exploratory Data Analysis (EDA)
- Analyzed distributions and trends
- Visualized relationships between variables
- Identified patterns in transactions and user behavior
4. Data Cleaning
- Handled missing values and inconsistencies
- Removed duplicates
- Standardized formats for analysis
  (Refer to the data cleaning notebook: )
5. SQL Analysis (MySQL)
- Loaded cleaned data into MySQL Server
- Executed queries for:
- Aggregations (SUM, AVG, COUNT)
- Grouping by city, bank, and merchant
- Performance and failure rate analysis
6. Dashboard Creation (Power BI)
- Built an interactive dashboard to visualize:
- Transaction trends over time
- Success vs Failure rates
- Merchant and bank performance
- Demographic insights

### **📊 Dashboard**


The Power BI dashboard provides a comprehensive overview of transaction performance.


### **Key Highlights (from dashboard):**


- Total Transactions: 19,987
- Total Amount: 19.85M
- Average Transaction Value: 993.35
- Success Rate: 80%
- Failure Rate: 20%


### **According to the dashboard on page 1, it includes:**


1. Monthly transaction trends
2. Merchant-wise transaction distribution (Flipkart, Zomato, Swiggy, IRCTC, Amazon)
3. Bank-wise success and failure rates (HDFC, SBI, Axis, ICICI)
4. Device usage (Mobile, Laptop, Tablet ~33% each)
5. City-wise performance (Bangalore, Delhi, Hyderabad, Mumbai)
6. Age group analysis (Young, Adult, Old)

### **📈 Results & Insights**

1. Majority of transactions are successful (80% success rate)
2. Transaction distribution is consistent across months
3. Equal usage across device types suggests platform accessibility
4. Major merchants contribute evenly to transaction volume
5. Banks show similar performance in success/failure rates
6. Younger and adult users dominate transaction activity

