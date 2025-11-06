# Customer_Behavior_Analysis
Data analytics project showcasing customer behavior analysis using python,sql and power bi

# Customer Shopping Behavior Analysis

## Dataset

1. **Rows:** 3,900
2. **Columns:** 18
3. **Contains:** demographics, purchase details, shopping behavior, shipping info, ratings
4. **Missing Values:** 37 ratings (filled with category-median)



## Tools Used

1. **Python:** Jupyter Notebook (Pandas)
2. **Database:**  MySQL Workbench
3. **Dashboard:** Power BI

## Steps

### 1. Data Cleaning & EDA (Python)

1. Imported dataset in Jupyter Notebook
2. Checked structure using `.info()` & `.describe()`
3. Cleaned missing values (category-wise median for ratings)
4. Removed redundant columns
5. Created `age_group` and `purchase_frequency_days` features
6. Exported cleaned dataset

### 2. SQL Analysis (MySQL)

1. Imported cleaned data into MySQL
2. Executed queries for:

  a. Revenue by gender
  b. Top-rated products
  c. Subscriber vs non-subscriber performance
  d. Shipping type spending comparison
  e. Discount-dependent customers/products
  f. Customer segmentation
  g. Age-group revenue contribution

### 3. Dashboard (Power BI)

1. Connected cleaned data
2. Built interactive charts and KPIs
3. Added filters for dynamic analysis

## Key Insights

1. Female customers contributed higher revenue
2. Express shipping users spent more
3. Loyal & returning customers drove majority of sales
4. Discounts influenced buying behavior but high spenders still used them
5. Younger & mid-age groups were top spenders
  
## How to Run

1. Open Jupyter Notebook and run EDA script
2. Import cleaned data into **MySQL Workbench** and execute queries
3. Open Power BI dashboard file (`.pbix`)


