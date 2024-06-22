
# Amazon Sales Report Analysis using Pandas and Seaborn

This repository contains Python code for analyzing an Amazon sales report using Pandas and Seaborn. The dataset includes details such as order information, dates, status, fulfillment details, and more.


## Requirements

To run the analysis script, ensure you have the following libraries installed:

- Pandas
- Matplotlib
- Seaborn


You can install these dependencies using pip:

```pip install pandas matplotlib seaborn```

## Dataset

The dataset (Amazon Sale Report.csv) includes the following columns:

- Order ID
- Date
- Status
- Fulfillment
- Sales Channel
- ship-service-level
- Category
- Size
- Courier Status
- Qty
- currency
- Amount
- ship-city
- ship-state
- ship-postal-code
- ship-country
- B2B
- fulfilled-by
## Analysis Steps

1. Data Cleaning and Preparation
- Loading the dataset
- Dropping unnecessary columns (New, PendingS)
- Handling missing values (dropna method)
- Converting data types (astype and pd.to_datetime) 


2. Exploratory Data Analysis
- Visualizing Size distribution using countplot
- Grouping by Size to find total Quantity sold
- Analyzing Courier Status distribution and its relation to Order Status
- Plotting histograms to visualize Category distribution


3. Insights and Visualizations
- Pie chart analysis of B2B vs Retail buyers
- Fulfillment methods analysis using pie chart
- Scatter plot to visualize relationship between Category and Size
- State-wise distribution of sales using countplot


4. Conclusion
- Summary of key insights from the analysis
- Observations such as popular products, buyer demographics, and geographical trends
## How to Use

Clone the repository:

` https://github.com/Akshar2325/Amazon-Sales-Report`