# 📊 Google Play Store App Analysis Dashboard (Power BI)

## 📌 Project Overview
This project analyzes the most downloaded Android applications from the Google Play Store using Power BI.  
The goal was to understand download distribution, developer dominance, pricing trends, category performance, and pre-installation impact.

The dataset includes:
- App Name
- Developer
- Downloads Range
- Category
- Free/Paid Type
- Price
- Publishing & Milestone Dates

---

## 🎯 Business Questions Answered
- Which developers dominate high-download categories?
- Are most top-downloaded apps Free or Paid?
- Which categories generate higher paid pricing?
- How are apps distributed across download ranges?
- What percentage of top apps are pre-installed?

---

## 🧹 Data Cleaning & Preparation (Power Query)
- Removed duplicates (App + Developer level)
- Standardized category values (extracted primary category)
- Cleaned download ranges into grouped buckets
- Converted Price from text to numeric
- Replaced missing and unknown date values
- Created calculated columns for download segmentation

---

## 📊 Dashboard Structure

### 1️⃣ Overview
- Total Apps
- Total Developers
- Free vs Paid Distribution
- Pre-installed vs Not Pre-installed

### 2️⃣ Downloads Analysis
- Apps by Downloads Bucket
- Category vs Download Range (Stacked View)
- Top 10 Developers by App Count

### 3️⃣ Category Insights
- App distribution across categories
- Category contribution in high download ranges

### 4️⃣ Paid Apps Analysis
- Average Price by Category (Paid Apps Only)
- Pricing comparison across categories

---

## 📈 Key Insights
- Google leads in total app count, followed by Meta and Microsoft.
- Most 10B+ downloaded apps are free and system-based.
- Games dominate the paid app pricing segment.
- Communication and utility apps achieve massive downloads while remaining free.
- A significant portion of high-download apps are pre-installed.

---

## 🛠 Tools & Technologies Used
- Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Slicers & Filters

---

## 📁 Repository Contents
- `Google Play Store App Analysis Dashboard.pbix`
- `Google_Play_Store_App_Analysis_PowerBI_Dashboard_Demo.mp4`
- `Dataset.csv`
- `README.md`

---

## 🚀 Skills Demonstrated
- Data Cleaning & Transformation
- Dashboard Design & Visualization
- DAX Measure Creation
- Analytical Thinking
- Business Insight Extraction

---

## 📌 How to Use
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use slicers (Type, Category, Downloads Bucket) to explore insights  

---

## 📎 About the Author
Aspiring Data Analyst passionate about transforming raw datasets into meaningful insights using Power BI and SQL.
