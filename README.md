# Internship-task-15---Customer-Segmentation-RFM-Analysis-Python

## Project Overview
This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis on the Online Retail II dataset.
RFM analysis helps businesses identify high-value customers and design targeted marketing strategies to improve retention and revenue.

## Tools & Technologies
- Python
- pandas
- numpy
- matplotlib
- Jupyter Notebook

## Dataset
- Online Retail II – E-Commerce Transaction Data

## Main Columns Used:
- Invoice
- InvoiceDate
- Customer ID
- Quantity
- Price

## Project Workflow
## Data Cleaning
- Removed null Customer IDs
- Removed cancelled invoices
- Removed negative/zero quantities
  
## Feature Engineering
- Created TotalAmount = Quantity × Price
- Converted InvoiceDate to datetime format

## RFM Calculation
- Recency = Days since last purchase
- Frequency = Number of unique invoices
- Monetary = Total spending per customer

## RFM Scoring
- Used quartiles (qcut) to assign scores (1–4)
- Created combined RFM Score

## Customer Segmentation
- Customers were grouped into:
- Champions
- Loyal Customers
- Potential Loyalists
- New Customers
- At Risk
- Hibernating

##  Visualization
- Bar chart showing number of customers per segment
  
## Export
- rfm_segments.csv → Final customer segmentation table
- segment_actions.txt → Business strategies per segment

## Final Outcome

- Learned customer segmentation techniques
- Understood marketing analytics concepts
- Applied business targeting strategies
- Gained real-world e-commerce analytics experience
