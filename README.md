# Project Background
Tetco company, established in 2023, is a global e-commerce company that sells consumer goods from popular brands and help distribute them worldwide via its website.

The company is planning to reinvest some of its revenue to run a Targeted Advertising Campaign. Currently it has significant amounts of data of its sales since launch, service feedback and loyalty programs. This project thoroughly analyzes and synthesize this data in order to uncover critical insights that will improve Tetco's commercial success.

Insights and recommendations are provided on the following key areas:
- **Customer Base Trends Analysis**: Evaluation of historical sales data to uncover the customer group with the most potential to like the brand and use its services, focusing on Revenue, Order Volume, and Average Order Value (AOV).
- **Customer Retention**: An evaluation of customer churn rate.
- **Marketing Budget Recomendation**: An assesment of the expected Revenue per Conversion and recomended Cost per Conversion.
  
An interactive PowerBI dashboard can be downloaded [here](https://drive.google.com/file/d/1aiJ6fb9Y8FE0w5kx-iPBCM5b9X8NAqrR/view?usp=sharing).

The Python code utilized to clean, organize and prepare data for the dashboard can be found [here](https://github.com/QuinnNgo97/Project-Ecommerce-Marketing-Target/blob/20d15cdf00995c340c2cfb8bdd1df019c2380bd6/ecommerce_analysis.py).

The original Kaggle dataset for perfoming this analysis can be found [here](https://www.kaggle.com/datasets/sahilprajapati143/retail-analysis-large-dataset/data?select=new_retail_data.csv).

# Data Structure & Initial Checks

Tetco's database structure as seen below consist of three tables: dim_products and dim_customers, fact_orders with a total row counts of 293,911 records.

<div align="center">
  <img src="https://github.com/QuinnNgo97/githubtest/blob/2f63a850e6520fa73cb4ac89bfac8c49c796ad77/relations.jpg">
</div>

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets. The Python code utilized to inspect and perform quality checks can be found [here](https://github.com/QuinnNgo97/Project-Ecommerce-Marketing-Target/blob/20d15cdf00995c340c2cfb8bdd1df019c2380bd6/ecommerce_analysis.py).

# Excecutive summary

### Overview of Findings

Over the past year since the company’s launch, the revenue and order volume has remained stable. These trends highlight a steady performance in both sales and revenue generation, suggesting a solid customer base and reliable demand for our products and services. However, the lack of significant growth within these metrics may indicate potential areas for strategic improvement to drive future expansion.

Below is the overview page from the PowerBI dashboard and more examples are included throughout the report. The more interactive dashboard can be downloaded [here](https://drive.google.com/file/d/1aiJ6fb9Y8FE0w5kx-iPBCM5b9X8NAqrR/view?usp=sharing).

<div align="center">
  <img src="https://github.com/QuinnNgo97/githubtest/blob/5cfa2145594bde1f9a53296520e30cb40058b9db/Dashboardoverview.png">
</div>

### Customer Base Trends Analysis

- **Revenue by Customer Segment**: Mid-income customers make up 51% of the customer base and account for 54% of the $402M revenue, highlighting their significant contribution.

- **Regional Highlights**: The UK leads with $131M from 25.4K customers, followed by the USA with $115.7M from 26.1K customers. Together, these two regions contribute 61% of total revenue.

- **Gender and Age Spending**: Males, primarily aged 18–25, spent $249M (62% of revenue), making them the largest spending group, while females in the same age range contributed $153M (38% of revenue).

The largest and most valuable customer group is mid-income males aged 18–25, especially in regions like the UK and the USA. These findings highlight the need to tailor marketing and engagement strategies toward this demographic to further capitalize on their spending potential.

<div align="center">
  <img src="https://github.com/QuinnNgo97/githubtest/blob/efa90b20fa7f95d938fb43849275f842676bc13a/Dashboard4.png">
</div>

<div align="center">
  <img src="https://github.com/QuinnNgo97/githubtest/blob/efa90b20fa7f95d938fb43849275f842676bc13a/Dashboard2.png">
</div>


### Customer Retention

- **Customer Retention**: After the first month, only 23–25% of customers remained with the company in the second month. However, retention stabilized from months 2–11, indicating that customers who stayed beyond the first month were likely to remain loyal for at least a year.

- **Customer Acquisition**: New customer acquisition has steadily declined since launch, dropping from 21,6K new customers in the first month to just over 1K per month in the most recent month.

- **Key Insights**: While retention beyond the first month signals strong brand loyalty, the sharp decline in new customer acquisition highlights the need for strategies to attract new customers and sustain growth.

<div align="center">
  <img src="https://github.com/QuinnNgo97/githubtest/blob/efa90b20fa7f95d938fb43849275f842676bc13a/Dashboard3.png">
</div>


### Recommendations

Based on the uncovered insights, the following recommendations have been provided:

- **Target Demographics**: Our primary customer base consists of **male** customers (62% of revenue) **aged 18–25**, who are **mid-income** earners residing in the **USA or UK**. To maximize conversion rates, targeted advertising campaigns should focus on this demographic, leveraging the brand’s strong alignment with their preferences and needs.

- **Improving Customer Retention**: Addressing the low retention rate requires a deeper understanding of customer behavior. Collecting feedback from customers will help identify pain points and areas for improvement. Additionally, a pilot loyalty program could be introduced, offering rewards for repeat purchases on the second month after registration to encourage long-term engagement.

- **Increasing New Customer Acquisition**: Implement a referral program to incentivize existing customers to bring in new customers. This approach is particularly effective, as referred customers are likely to belong to similar demographic groups, ensuring alignment with the company’s target audience.

- **Marketing Budget Allocation**: Considering an average annual spend of **$4,650 per customer** and a **25% retention rate**, the marketing budget should allow for a cost per conversion of approximately $290 (which assumes an ideal return on investment (ROI) of 5:1). Matching this target allocation ensures effective utilization of resources while maintaining profitability.


# Caveats and assumptions
