 Customer Retention Strategy: Telco Churn Dashboard (Power BI)

 Business problem
A telecom company is losing customers. This dashboard shows how many customers
churn and which groups leave most, so the business can focus its retention efforts.

 Dataset
Telco Customer Churn sample dataset (IBM sample data, shared on Kaggle):
7,043 customers and 21 columns, including contract type, payment method,
internet service, tenure, monthly charges and whether the customer churned.
Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

 What I built
- KPI cards: total customers, churned customers and churn rate
- Churn vs non-churn breakdown
- Customers by contract type, payment method and internet service
- Churn rate by contract type
- Gender slicer for filtering

 Key findings
- 26.5% of customers (1,869 of 7,043) churned.
- Month-to-month contracts have a 42.7% churn rate, compared with 11.3% for
  one-year contracts and 2.8% for two-year contracts.
- Average customer tenure is 32.37 months and the average monthly charge is 64.76.

 Recommendation
Offer incentives, such as a discount or added benefits, to move month-to-month
customers onto longer contracts. Contract length is strongly linked to lower churn.
This dashboard shows an association, not proof of cause, so the offer should be
tested on a small group first.

 Dashboard
![Dashboard](dashboard-overview.png)

 Tools
Power BI Desktop, DAX

## What I learned
- Found and fixed an inverted ratio in my churn rate measure (it divided total by
  churned instead of churned by total) and checked it against the pie chart.
