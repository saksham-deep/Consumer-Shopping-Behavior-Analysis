# 📊 Customer Shopping Behavior Analysis

## 📌 Overview
This project presents an end-to-end data analytics workflow focused on understanding customer shopping behavior using transactional data.  
The analysis covers data cleaning, exploratory analysis, SQL-based business queries, interactive dashboard creation, and business recommendations.

The goal is to transform raw transactional data into actionable insights that support data-driven business decisions.

---

## 📂 Dataset
- Records: 3,900 customer transactions
- Features: 18 columns
- Includes:
  - Customer Demographics (Age, Gender, Location, Subscription Status)
  - Purchase Details (Category, Item Purchased, Purchase Amount)
  - Shopping Behavior (Discount Applied, Frequency, Shipping Type, Review Rating)
- Data Quality:
  - Missing values present in Review Rating column
  - Data cleaned and standardized during preprocessing

---

## 🛠️ Tools & Technologies
- **Python:** Data Cleaning, EDA, Feature Engineering
- **SQL (PostgreSQL/MySQL/SQL Server):** Business Analysis Queries
- **Power BI:** Dashboard Development
- **Gamma:** Presentation Creation
- **Python Libraries:** pandas, numpy, matplotlib
- **Other Tools:** Git, Jupyter Notebook

---

## ⭐ Key Contributions & Work Performed
- Processed and **analyzed 3,900** customer transaction records.
- Conducted full **Exploratory Data Analysis** (EDA) using Python.
- Handled **37** missing values using median imputation grouped by product category.
- Standardized column names into **snake_case** for clean data practices.
- Performed feature engineering:
  - Created **age_group** for customer segmentation.
  - Built **purchase_frequency_days** to analyze buying patterns.
- Performed data consistency checks and removed redundant columns.
- Built **Python-to-MySQL** pipeline for structured SQL analysis.
- Wrote advanced **SQL queries** to answer business-focused questions:
  - Revenue comparison by gender
  - High-spending discount users
  - Top-rated products
  - Shipping type purchase comparison
  - Subscribers vs non-subscribers revenue
  - Discount-dependent product analysis
  - Customer segmentation (New / Returning / Loyal)
  - Top 3 products per category
  - Repeat buyers and subscription correlation
  - Revenue contribution by age group
- Designed interactive **Power BI dashboard** for stakeholders.
- Delivered business-driven recommendations based on analysis.

---

## ⚙️ Project Workflow
1. Loaded raw dataset using Python.
2. Conducted initial exploration using info() and descriptive statistics.
3. Cleaned data and handled missing values.
4. Performed feature engineering and transformation.
5. Loaded cleaned dataset into SQL database.
6. Executed SQL queries for business insights.
7. Built Power BI dashboard with KPIs and interactive visuals.
8. Created presentation and business report using Gamma.

---

## 📊 Dashboard Highlights
- KPI Summary Cards
- Customer Segmentation Analysis
- Product Performance Trends
- Revenue & Purchase Analysis
- Shipping & Discount Insights
- Interactive Filters & Slicers

---

## 🖼️ Dashboard Screenshots

### 📍 Overview Dashboard
![Dashboard Overview](](images/dashboard_overview.png)

### 📍 Customer Insights Dashboard
![Customer Insights](images/customer_insights.png)

### 📍 Product Performance Dashboard
![Product Performance](images/product_performance.png)

> ⚠️ Place your screenshots inside a folder named **images** in your GitHub repository and replace file names accordingly.

---

## 📈 Results & Insights
- Identified top-performing products and categories.
- Discovered high-value customer segments.
- Analyzed spending behavior across demographics.
- Evaluated subscription and discount effectiveness.
- Highlighted revenue-driving customer groups.

---

## 💼 Business Impact
- Suggested targeted marketing based on high-revenue age groups.
- Recommended loyalty programs to convert returning buyers into loyal customers.
- Proposed subscription promotion strategies.
- Advised review of discount policies to maintain profit margins.
- Recommended highlighting top-rated products in campaigns.

---

## 👤 Author
Saksham Deep
