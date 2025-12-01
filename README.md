# 📊 Telecom Customer Churn Analysis Dashboard  
**Data Analytics Portfolio**

This project focuses on analyzing and visualizing customer churn behavior within a telecom company. Using a cleaned dataset and an AI-enhanced dashboard, the project identifies key churn drivers, high-risk customer segments, and actionable strategies to improve retention.

---

## 🔍 Project Overview  
The dataset includes customer demographics, contract details, service usage, billing information, and churn labels. The project covers:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- KPI generation
- Churn segmentation
- Billing & payment risk analytics
- Decision path analysis
- Strategic business recommendations

---

## 🎯 Objectives  
- Understand churn behavior across different customer segments  
- Identify risk factors affecting churn  
- Quantify financial impact (Revenue at Risk, CLV)  
- Propose targeted retention strategies  
- Build a professional and interactive dashboard  

---

## 📌 Key KPIs  
- Overall Churn Rate  
- Active vs Churned Customers  
- Revenue at Risk (Monthly)  
- Average Monthly Charges of Churned Customers  
- Average Tenure of Churned Customers  
- Customer Lifetime Value (CLV)  
- High-Risk Customer Percentage  

---

## 📈 Dashboard Insights  

### **1. Contract Type Impact**
Month-to-month customers churn the most, indicating contract flexibility leads to higher churn.

### **2. Service-Related Churn Drivers**
- Fiber optic users churn at higher rates.  
- Customers without Online Security or Tech Support show significantly higher churn.

### **3. Tenure Behavior**
Early lifecycle customers (0–12 months) have the highest churn.

### **4. Billing & Payment Risk**
- Electronic check users show extreme churn risk.
- Non-autopay customers churn more.
- Higher monthly charges correlate with churn.

### **5. Decision Path (High-Risk Segment)**
The highest-risk churn pathway is:

**Month-to-month → Fiber Optic → No Online Security**

---

## 🛠 Tools Used  
- Julius.ai (Dashboard & Analysis)  
- Python (pandas)  
- ChatGPT / Claude (EDA & preprocessing support)  
- Excel / Google Sheets  
- GitHub (Version control & documentation)

---

## 📂 Project Structure  
telecom-churn-analysis/
│
├── data/
│ ├── raw_telco_churn.csv
│ ├── telco_customer_churn_cleaned.csv
│
├── dashboard/
│ ├── telecom_churn_dashboard.html
│ ├── screenshots/
│ ├── kpi_section.png
│ ├── churn_by_contract.png
│ ├── billing_risk.png
│
├── notebooks/
│ ├── data_cleaning.ipynb
│ ├── churn_insights.ipynb
│
├── docs/
│ ├── project_summary.pdf
│ ├── recommendations.pdf
│
├── README.md
└── LICENSE


---

## 📄 How to View the Dashboard  
Open:

dashboard/telecom_churn_dashboard.html


Works in any browser.

---

## 💡 Future Enhancements  
- Build a machine learning churn prediction model  
- Segment customers using clustering  
- Add retention recommendation engine  

---

## 🤝 Acknowledgements  

Thanks to AI tools and open datasets for enabling rapid analytical development.
