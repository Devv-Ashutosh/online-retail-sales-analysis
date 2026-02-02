# Online Retail Sales Analysis

This project is an end-to-end data analysis of an online retail dataset using Python.
The goal was to clean messy transactional data and extract meaningful business insights
around revenue, geography, products, and customers.

## Dataset Overview
The dataset contains transactional-level retail data including:
- Invoice details
- Product information
- Quantity and pricing
- Customer and country details

The raw data included returns, cancellations, missing values, and invalid prices,
which required careful validation and cleaning before analysis.

## Project Workflow
The analysis was carried out in the following steps:

1. **Data Understanding**
   - Checked data structure, data types, and missing values
   - Identified sales vs returns using quantity and invoice patterns

2. **Data Cleaning**
   - Removed invalid records (negative prices, cancellations)
   - Separated sales and returns
   - Created clean, analysis-ready datasets

3. **Exploratory Data Analysis (EDA)**
   - Analyzed revenue trends over time
   - Identified country-wise revenue contribution
   - Evaluated product-level revenue distribution
   - Analyzed customer-level revenue concentration

## Key Insights
- Revenue is highly concentrated in the United Kingdom (~84.6%)
- Product-level revenue is diversified (top 10 products contribute ~11.6%)
- Customer-level concentration is moderate (top 10 customers contribute ~17.3%)
- Revenue risk is primarily geographic rather than product- or customer-driven



## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Notes
Processed CSV files are generated through the data cleaning notebook.
Large files may not be uploaded to GitHub due to size constraints.

## Future Scope
- Customer segmentation (RFM analysis)
- Cohort analysis
- Revenue forecasting
- Dashboarding using Power BI or Tableau
