
# Retail Sales Exploratory Data Analysis

## OASIS INFOBYTE Data Analytics Internship
**Level 1 - Task 1: EDA on Retail Sales Data**

## 1. Project Overview
This project performs Exploratory Data Analysis (EDA) on retail sales data to understand sales trends, customer behaviour, and product category performance.

## 2. Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 3. Dataset Information
- Total transactions: 1,000
- Total columns: 9
- Dataset format: CSV
- Dataset file: retail_sales_dataset.csv

## 4. Analysis Performed
1. Dataset inspection and descriptive statistics.
2. Monthly and quarterly sales analysis.
3. Customer age distribution.
4. Gender-wise transaction analysis.
5. Revenue and transactions by product category.
6. Customer age group sales analysis.
7. Numerical correlation heatmap.

## 5. Key Findings
- Electronics generated the highest revenue: ₹156,905.
- Clothing recorded the highest number of transactions: 351.
- Customers aged 51–60 generated the highest revenue among age groups.
- Female customers accounted for 510 transactions, compared with 490 male transactions.
- May 2023 recorded the highest monthly sales: ₹53,150.
- Price per Unit and Total Amount showed a strong positive correlation.

## 6. Business Recommendations
1. Maintain sufficient inventory of Clothing and Electronics.
2. Develop targeted promotions for valuable customer age groups.
3. Use offers and product bundles to increase Beauty category sales.

## 7. Data Limitations
- January 2024 contains only two transactions, so it represents an incomplete period.
- Individual product names are unavailable; therefore, analysis focuses on product categories rather than individual products.

## 8. Project Structure
```text
DataAnalytics-L1-EDARetailSales/
├── data/
│   └── retail_sales_dataset.csv
├── notebooks/
│   └── Retail_Sales_Analysis.ipynb
├── outputs/
├── README.md
└── requirements.txt
```

## 9. How to Run
Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open Jupyter Notebook and run:

`notebooks/Retail_Sales_Analysis.ipynb`

## 10. Conclusion
This project demonstrates how exploratory data analysis can help a retail business understand customer behaviour, identify sales patterns, and make data-driven business decisions.
