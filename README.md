# SN-Corporation-performance-analytics
### Project Overview
SN Corp is a company that sells products worldwide. 
The company has significant amounts of data on its sales, operational efficiency and product offerings. This project thoroughly analyzes this data in order to uncover critical insights that will improve the company's success.

### Data Sources
Sales Data: The primary dataset used for this analysis is the "SN Corp Dataset.xlsx" file, containing detailed information about each sale made by the company.
Power BI [Dashboard]("C:\Users\sweth\OneDrive\Desktop\Data Analysis\SN Corp Dashboard.pbix")

### Tools Used
- Excel and Python for Data cleaning
- Power BI for Data Visualization

### Data cleaning using Python

![Screenshot 2025-01-29 215243](https://github.com/user-attachments/assets/d9a93cbf-70d2-42e4-867d-ad7fde26d2bc)

```python
df.drop_duplicates
```
```python
df["Customer Name"]= df["Customer Name"].str.lstrip["..."]
df["Customer Name"]= df["Customer Name"].str.rstrip["/"]
df["Customer Name"]= df["Customer Name"].str.strip["123._"]
df
```
```python
df["Ship Mode"]= df["Ship Mode"].str.replace('Ecnmy','Economy')
```

### Features
- KPI tracking for sales, cost and profit.
- Customer and sub-category performance insights
- Geographic visualization of business operations.
- Regional quantity analysis
- Trends in orders by time and shipping mode.
  
### Insights Deep Dive

- The count of orders through the Economy shipping mode shows a steady growth pattern over the years, making it the most preferred shipping mode, whereas the Immediate shipping mode is the least preferred by customers. This suggests that customers tend to favor cost-effective shipping options with occasional demand for faster delivery services.
- Bookcases recorded the highest sales, totaling 274K units. France contributed the most to these sales with 59K units sold. They were sold the most in the year 2024. Lower-performing categories include Labels and Fasteners.
- Business is heavily concentrated in France, Germany, and the UK.
- The Central region accounted for 55.11% of sales, while the North and South contributed 22.72% and 22.17%.
- Ashton Charles is the most profitable customer.


![PB Dashboard](https://github.com/user-attachments/assets/80557d15-88ae-4075-a7ad-94e499223dea)

### Recommendations
- Optimize costs for immediate and priority shipping modes to make them more attractive to customers.
- Launch marketing campaigns to attract more customers in the Central and North regions.
- Allocate more resources to top performing sub-categories(Bookcases and Chairs) to further boost revenue and investigate underperforming categories for potential optimization or discontinuation.
- Create loyalty programs for big customers and encourage smaller ones to buy more.





