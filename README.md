# Brainwave_Matrix_Intern
Sales Performance Analysis Dashboard –This project is a comprehensive sales analysis dashboard built using Tableau, designed to visualize and analyze business performance based on sales transactions. The data is sourced from two main tables: Details.csv and Orders.csv and includes key metrics and dimensions to support actionable insights.

## 📊 Sales Performance Analysis Dashboard 

This project is a sales analysis designed to provide interactive insights into business performance using transactional data. 

The dashboard combines product, customer, and geographic data to support strategic decision-making through rich visualizations.

📁 Data Sources

This project uses two CSV files:

###  `Details.csv`
Contains item-level transaction details:
- **Category**
- **Sub-Category**
- **Order ID**
- **Payment Mode**
- - **Amount**
- **Profit**
- **Quantity**

### `Orders.csv`
Contains order-level customer and geographic data:
- **Customer Name**
- **Order Date**
- **Order ID**
- **State**
- **City**

The relationship between the tables is managed through the `Order ID` field.

## 📐 Measures I Calculated
- **Profit Margin %**
- - **Revenue per Unit**
- **Total Orders**
- **Total Revenue**

These are calculated fields used to drive KPIs and summarize performance.

## 📈 Dashboard Features

- **Sales Trends**: Visualize revenue and order trends over time.
- **Geographic Breakdown**: Analyze performance by state and city.
- **Product Analysis**: Identify top-performing categories and sub-categories.
- **Customer Insights**: Highlight high-value customers.
- **Payment Mode Review**: Understand customer preferences for payment.

## 🛠 Tools Used
- **Tableau Desktop** for data visualization
- **Python** for data cleaning


## 🚀 Getting Started

1. Clone this repo or download the `.twb` / `.twbx` Tableau file.
2. Open the Tableau file in Tableau Desktop.
3. Make sure the data sources are correctly mapped to `Details.csv` and `Orders.csv`.
4. Explore the dashboards and customize as needed.
