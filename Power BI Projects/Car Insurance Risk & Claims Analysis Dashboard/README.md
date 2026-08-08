# Insurance Risk & Claims Analysis – Power BI Dashboard

![Domain](https://img.shields.io/badge/Domain-Insurance%20Analytics-000000)

![Tech Stack](https://img.shields.io/badge/Tech%20Stack-DAX%20%7C%20Data%20Modeling%20%7C%20ETL-blue) ![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-F2C811?logo=powerbi&logoColor=black)

![Dataset](https://img.shields.io/badge/Records-7.5K%20Policies-purple)

![Author](https://img.shields.io/badge/Author-Asha%20Topagi-black)

---

## 📌 Project Overview
This Power BI dashboard provides a comprehensive analysis of car insurance policies, customer demographics, vehicle attributes, and claim patterns.  
It centralizes scattered policy and claims data into a single interactive report, enabling data‑driven decisions for underwriting, pricing, and risk management.

---

## 🎯 Business Requirements
The dashboard answers key business questions:

- How many policies are active?
- What is the total financial impact of claims?
- Which customer groups file more claims?
- How do vehicle characteristics influence risk?
- Which demographic segments show higher claim severity?
- How do education, marital status, and household factors affect claims?

---

## 📊 Key KPIs
- **Total Policies**
- **Total Claim Amount**
- **Claim Frequency**
- **Average Claim Amount**
- **Gender‑wise Policies**

---

## 📈 Dashboard Insights

### 1. Total Claim Amount by Car Use
Commercial vehicles show significantly higher claim amounts compared to private use.

### 2. Total Claim Amount by Car Make
Brands like Ford, Chevrolet, Toyota, and Dodge dominate claim totals, indicating repair cost and risk variations.

### 3. Total Claim Amount by Coverage Zone
Urban and highly urban zones show higher claim amounts due to traffic density and accident likelihood.

### 4. Total Claim Amount by Age Group
Drivers aged **36–55** contribute the highest claim amounts.

### 5. Total Claim Amount by Car Year
Cars manufactured between **2005–2015** show higher claim totals due to age‑related wear and repair costs.

### 6. Total Claim Amount by Kids Driving
Households with **2+ young drivers** show significantly higher claim amounts.

### 7. Total Claim Amount by Education
Bachelor’s degree holders contribute the highest claim totals, followed by high‑school graduates.

### 8. Claim Amount by Education & Marital Status
A combined matrix reveals:
- Single + Bachelor’s → highest claim totals  
- Married + High School → strong policy volume  
- PhD holders → lowest claim totals  

---

## 📚 Domain Knowledge Summary
This dataset includes:

- Customer demographics: age, gender, marital status, education, income  
- Vehicle details: make, model, year, color, usage type  
- Risk factors: coverage zone, kids driving, parental status  
- Claims data: claim amount, claim frequency  

### Key Domain Insights
- Younger drivers → higher accident probability  
- Commercial vehicles → higher exposure → higher claims  
- Urban zones → more accidents and theft  
- Households with multiple young drivers → higher risk  
- Education level correlates with income and driving behavior  
- Car age strongly influences claim severity  

---

## 🛠️ Technical Implementation

### Data Modeling
- Star schema  
- Fact table: Claims  
- Dimension tables: Customers, Vehicles, Zones, Education, Marital Status  

### DAX Measures
- Total Policies  
- Total Claim Amount  
- Claim Frequency  
- Average Claim Amount  
- Gender‑wise Policies  
- Car Make Claim Amount  
- Age Group Claim Amount  

### Power BI Features
- Donut Charts  
- Bar Charts  
- Area Charts  
- Ribbon Charts  
- Matrix Heat Grid  
- KPI Cards  
- Slicers  

---

## 📁 Project Files
- Power BI Report (`.pbix`)  
- Dataset (`.csv` / `.xlsx`)  
- Documentation (`.docx` / `.pptx`)  

---

## 🚀 How to Use
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Refresh data if needed  
4. Use slicers to explore risk segments  

---

## 🤝 Connect With Me
I love collaborating on BI, data engineering, and analytics projects.

- **LinkedIn:** https://www.linkedin.com/in/asha-topagi  
- **Email:** asha.topagi@example.com

