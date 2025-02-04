# 📊 Financial Anomalies Detection Dashboard

## 📝 Introduction
This project is a **Tableau dashboard** designed to detect **financial anomalies and potential fraud** in banking transactions. Using data visualization techniques, the dashboard helps identify unusual patterns such as **high-risk transactions, multiple IP usage, self-transactions, and outliers in transaction amounts**.

## 🚀 Project Overview
### **📂 Dataset**
- **Source**: Kaggle – Bank Transaction Dataset for Fraud Detection
- **Data Fields**:
  - **Transaction ID, Account ID, Transaction Amount**
  - **Transaction Type (Credit/Debit)**
  - **Transaction Date & Time**
  - **Location, Device ID, IP Address**
  - **Merchant ID, Channel (Online/ATM)**
  - **Account Balance, Customer Age, Occupation**
  - **Login Attempts & Previous Transactions**

### **📊 Key Dashboard Features**
✅ **Time Series Analysis**  
   - Trends of transaction volume over time  
   - Sudden spikes indicating fraud clusters  

✅ **Box Plot for Outlier Detection**  
   - Identifies unusually high-value transactions  
   - Highlights potential fraudulent activities  

✅ **Customer Spending Analysis**  
   - Displays high-spending customers  
   - Uses **color-coded risk levels** (Low → Blue, Medium → Orange, High → Red)  

✅ **Multiple IP Address Usage**  
   - Detects accounts using **multiple IPs**  
   - Flags high-risk accounts for security concerns  
 

### **📊 Technology Stack**
- **🔹 Data Cleaning & Preprocessing:** Power Query (Excel)  
- **🔹 Data Visualization & Analysis:** Tableau  
- **🔹 Version Control & Sharing:** GitHub  

## 📂 How to Use
1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/Financial-Anomalies-Dashboard.git
