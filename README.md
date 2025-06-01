# 📊 Data Professional Survey Breakdown

## 📌 Overview

![Image](https://github.com/user-attachments/assets/db75dd34-7a60-4b91-a923-faf07afb4867)


This Power BI dashboard explores key insights into the **data professional landscape**, including salary trends, job roles, and career patterns based on a global survey. The goal was to transform raw survey data into a clean, interactive, and insightful report that helps:

- Understand salary distributions
- Compare job roles and experience levels
- Analyze employment types and country-based data patterns

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **Power Query Editor**
- **Excel (Source File)**
- **DAX (for custom measures)**

---

## 🧼 Data Cleaning & Transformation

**Performed in Power Query:**

1. **Removed unnecessary columns** and rows with null values.
2. **Standardized ‘Other’ responses** by splitting columns using delimiters like `(`.
3. **Cleaned salary data:**
   - Duplicated the salary column.
   - Split it using digit-to-non-digit logic.
   - Removed non-numeric characters (`+`, `k`, `year`, etc.).
   - Converted text to whole numbers.
   - Calculated a new column called `Average Salary`.
4. Cleaned multiple categorical columns (Q1, Q4, Q5, etc.) for better filter performance.
5. Applied changes and loaded the cleaned data into Power BI for visualization.

---

## 📊 Visualizations & Features

### ✅ KPIs (Card Visuals)
- Total number of survey participants
- Average salary
- Average age

### 📉 Bar Charts
- Job Title vs. Average Salary
- Country-wise Salary Comparison

### 🔥 Additional Visuals
- Age vs. Job Role Heatmap
- Job Satisfaction vs. Salary
- Slicers for interactivity:
  - Country
  - Job Title
  - Employment Type
  - Experience Level

### 🧠 Design Enhancements
- Clean theme and layout
- Added footer and branding logo
- Optimized for storytelling and easy navigation

---

## 📈 Key Insights

- **Total Respondents**: 630
- **Average Salary**: ~$95,000
- **Top Job Roles**: Data Analyst, Data Scientist, ML Engineer
- **Highest Paying Roles**: ML Engineer, Data Architect
- **Work Experience**: Most respondents had 1–5 years experience
- **Employment Type**: 88% are full-time employees
- **Top Countries**: USA, UK, Canada, India, Germany
- **Highest Salary**: Reported by US-based professionals

---

## ✅ Outcome

This dashboard highlights how structured analysis and visual storytelling can bring raw survey data to life. It also demonstrates proficiency in:

- Power Query & Data Cleaning
- Data Modeling & DAX
- Report Design & User Experience

---

## 📁 Folder Structure

