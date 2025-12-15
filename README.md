## **Future Interns: Data Science & Analytics Internship**

# **📊 Task 2 – Social Media Campaign Performance Tracker**

### **🚀 Project Overview**
#### ◆ This repository contains the completed work for **Task 2** of the **Future Interns – Data Science & Analytics Internship**.  
#### ◆ The objective was to analyze Facebook ad campaign data (Kaggle source) and build a **fully interactive performance dashboard** using **Power BI**.  
#### ◆ The dashboard provides insights into campaign performance, audience engagement, CTR, cost, conversions, and ROI using visually clean KPIs and charts.
---
### **📁 Dataset Used**
#### ◆ The dataset was downloaded from **Kaggle – Facebook Ads Performance Dataset**
#### ◆ Key fields include ad_id, reporting dates, campaign_id, age, gender, impressions, clicks, spend, total conversion, approved conversion, and interest IDs.
---
### **🛠️ Data Cleaning & Transformation (Power Query)**
#### ✔ Data Cleaning & Preparation (Power Query)
- Standardized and validated date fields
- Converted numeric columns and handled errors
- Corrected and cleaned demographic entries
- Removed duplicates
- Ensured consistent formatting across all fields
### 🔎 Data Quality Note
### “Records with invalid gender values were excluded to maintain demographic accuracy and prevent analytical distortion.”
---

### **📊 Dashboard & Insights (Power BI)**
#### 🧩 Key Marketing KPIs
- Total Spend
-  Total Impressions 
-  Total Clicks 
-  CTR (%)
-   Cost per Conversion
-    Approved Conversions
#### 📈 Visual Insights Included
- Daily Impressions Trend  
- CTR (%) by Age Group  
- Click Distribution by Gender  
- Top Ads Comparison (Spend vs Approved Conversions)  
- Campaign ID & Interest-based filtering
#### 🔄 ROI Simulation (What-If Analysis)
- Created a What-If parameter Avg Order Value (AOV) to dynamically calculate Estimated ROI (%)  
- When AOV = 0, Estimated ROI becomes negative because revenue becomes zero while cost remains positive — helping simulate realistic low-revenue scenarios
---
### **🛠 Tools Used**
Power BI | Power Query | DAX | CSV Data (Kaggle)

---

### **📸 Dashboard Preview**
<img width="1048" height="640" alt="DS 2" src="https://github.com/user-attachments/assets/e1099d82-2a07-4ce1-99bd-4c9f6bd8f126" />

---
### **📂 Repository Structure**
```
FUTURE_DS_02/
│
├── dataset/
│ └── data.csv
├── visuals/
│ ├── DS 2.mp4
│ └── DS 2.png
├── DS_02.pbix
├── README.md
```
---

### **📦 Dataset Extraction Instructions**
1. Open the **`dataset/`** folder in this repository  
2. Download the file: **`data.csv`**  
3. Use this CSV in Power BI for all cleaning, DAX measures, and dashboard creation

### **💡 Key Learning Outcomes**
- Understanding digital ad performance metrics  
- Creating marketing KPI calculations using DAX  
- Designing interactive dashboards for clearer insights  
- Applying Power Query for structured data cleaning  
- Building scenario-based simulations using parameters
