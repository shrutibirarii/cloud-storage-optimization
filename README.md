# ☁️ Cloud Storage Optimization Insights  


A data analytics project analyzing **cloud storage usage** to identify cost-saving opportunities, optimize storage tiers, and recommend archival strategies for AWS S3.  

---

## 📊 Project Overview

- Analyze storage patterns across departments and file types.  
- Detect **unused or cold data** to reduce costs.  
- Recommend strategies for **archival or tier migration** (Standard → IA/Glacier).  
- Visualize trends to support **data-driven decision making**.

---
## ✨ Key Highlights

- **Cold Data Identification:** Detected files not accessed in the last 180+ days, accounting for ~35% of total storage.  
- **Cost Savings Analysis:** Estimated potential savings of **$5,000/month** by migrating cold data to Glacier tier.  
- **Department Insights:** Engineering and Marketing departments held the largest volume of unused storage.  
- **File Type Impact:** Backup and Media files contributed most to monthly storage costs.  
- **Visualization:** Created interactive dashboards showing storage trends, departmental usage, and cost distribution.  
- **Actionable Recommendations:** Suggested archival strategies, tier migration, and deletion policies for cold or redundant files.  

---

## 🗂 Dataset

**Records:** 3,000 synthetic entries  

**Columns:**  

| Column Name        | Description |
|-------------------|-------------|
| `File_ID`         | Unique file identifier |
| `Department`      | Business unit (HR, Finance, Marketing, Engineering, Sales) |
| `File_Type`       | Document, Media, Backup, Log, Other |
| `Size_GB`         | File size in GB |
| `Last_Access_Date`| Date of last access |
| `Storage_Tier`    | Current AWS S3 tier (Standard, IA, Glacier) |
| `Monthly_Cost_USD`| Estimated monthly storage cost |

---

## 🎯 Project Objectives

- Identify **cold/unused data** (last accessed > 180 days).  
- Estimate **cost savings** by migrating cold data to Glacier.  
- Analyze **department-wise storage usage and inefficiencies**.  
- Understand **file type impact** on storage costs.  

---

## 🛠 Tools & Libraries

- **Python:** Pandas, NumPy, Matplotlib  
- **Dashboard/Visualization:** Power BI or Tableau  
- **SQL (Optional):** Querying large datasets  

---

## 🔎 Potential Insights

- **Cost optimization:** Highlight storage tier migration opportunities.  
- **Department inefficiencies:** Identify departments with largest unused storage.  
- **File type analysis:** Determine which file types contribute most to storage costs.  
- **Trend analysis:** Visualize historical storage usage patterns.  

---

## 🚀 Next Steps

1. Perform **Exploratory Data Analysis (EDA)** using the dataset.  
2. Create an **interactive dashboard** for visualization.  
3. Recommend **archival or deletion strategies** for cold data.  
4. Calculate **projected savings** after optimization.  

---

## 💡 Optional Enhancements

- Automate **data ingestion from S3 logs**.  
- Integrate **AWS Cost Explorer API** for real cost estimation.  
- Apply **predictive analytics** to forecast storage growth.  

---
