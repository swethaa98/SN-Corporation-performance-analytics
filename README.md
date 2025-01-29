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
- A total of238 orders were placed in the third quarter of 2024 through the Economy shipping mode. Economy shipping has consistently been the most preferred option each year while Immediate shipping mode was the least preferred.
- 


![PB Dashboard](https://github.com/user-attachments/assets/80557d15-88ae-4075-a7ad-94e499223dea)



### Executive Summary





