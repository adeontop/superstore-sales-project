# Superstore Sales Analysis & Sales/Profit Prediction

## Project Overview

In today's highly competitive retail landscape, businesses must make data-driven decisions to maximize profitability and customer satisfaction. This project analyzes the Superstore dataset to uncover valuable insights into sales performance, customer behavior, regional trends, and product profitability. Additionally, the project explores the use of machine learning to predict Sales or Profit using regression techniques.

The objective is to identify which products, customer segments, categories, and regions contribute most to business success and provide actionable recommendations that can improve overall performance.

---

## Business Problem

A leading Superstore is experiencing increasing market competition and wants to better understand its business performance. The company seeks answers to key business questions, including:

* Which products generate the highest sales and profits?
* Which product categories and sub-categories should be promoted or avoided?
* Which customer segments are the most profitable?
* Which regions and states perform best and worst?
* How do discounts affect sales and profitability?
* Can future Sales or Profit be predicted using historical data?

The insights generated from this analysis will support strategic business decisions, inventory planning, pricing strategies, and marketing efforts.

---

## Project Objectives

* Perform exploratory data analysis (EDA) to understand sales trends and business performance.
* Analyze customer purchasing behavior across different segments.
* Evaluate product categories and sub-categories based on sales and profit.
* Identify high-performing and underperforming regions and states.
* Investigate the relationship between discounts and profitability.
* Develop a regression model to predict Sales or Profit.
* Provide business recommendations based on analytical findings.

---

## Dataset Description

The dataset contains historical order information for a retail superstore.

### Features

| Column        | Description                              |
| ------------- | ---------------------------------------- |
| Row ID        | Unique identifier for each record        |
| Order ID      | Unique order identifier                  |
| Order Date    | Date the order was placed                |
| Ship Date     | Date the order was shipped               |
| Ship Mode     | Shipping method selected by the customer |
| Customer ID   | Unique customer identifier               |
| Customer Name | Customer's name                          |
| Segment       | Customer segment                         |
| Country       | Customer's country                       |
| City          | Customer's city                          |
| State         | Customer's state                         |
| Postal Code   | Customer postal code                     |
| Region        | Geographic region                        |
| Product ID    | Unique product identifier                |
| Category      | Product category                         |
| Sub-Category  | Product sub-category                     |
| Product Name  | Product name                             |
| Sales         | Revenue generated                        |
| Quantity      | Number of units sold                     |
| Discount      | Discount applied                         |
| Profit        | Profit or loss generated                 |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly / Seaborn (optional)
* Scikit-learn
* Jupyter Notebook

---

## Methodology

1. Data Cleaning

   * Handle missing values
   * Remove duplicates
   * Convert date columns
   * Verify data types

2. Exploratory Data Analysis (EDA)

   * Sales and profit trends
   * Regional performance
   * Category and sub-category analysis
   * Customer segment analysis
   * Discount analysis
   * Shipping mode analysis

3. Feature Engineering

   * Extract Year, Month, Quarter
   * Create profit margin metrics
   * Encode categorical variables

4. Machine Learning

   * Data preprocessing
   * Train-test split
   * Regression model development
   * Model evaluation using:

     * R² Score
     * Mean Absolute Error (MAE)
     * Mean Squared Error (MSE)
     * Root Mean Squared Error (RMSE)

---

## Exploratory Data Analysis

The analysis focuses on answering the following business questions:

* Which categories generate the highest sales?
* Which sub-categories are most profitable?
* Which states consistently incur losses?
* Which customer segments contribute the most revenue?
* Which regions should receive more investment?
* What is the impact of discounting on profit?
* Which products should be discontinued or promoted?

Visualizations include:

* Sales by Region
* Profit by Region
* Sales by Category
* Profit by Category
* Top Performing Products
* Bottom Performing Products
* Monthly Sales Trends
* Customer Segment Distribution
* Discount vs Profit Analysis

---

## Business Insights

Potential insights from the analysis may include:

* High discounts often reduce profitability despite increasing sales.
* Certain product sub-categories consistently generate losses.
* A small number of products contribute significantly to total revenue.
* Some regions outperform others in both sales and profit.
* Consumer and Corporate customer segments may contribute differently to overall profitability.
* Seasonal sales trends can guide inventory planning.

---

## Business Recommendations

Based on the findings, the Superstore can:

* Increase inventory for high-performing products.
* Reduce or eliminate excessive discounts on low-margin products.
* Reevaluate or discontinue consistently unprofitable products.
* Focus marketing efforts on profitable customer segments.
* Allocate additional resources to high-performing regions.
* Improve logistics by optimizing shipping methods.
* Use predictive analytics to forecast future sales and improve demand planning.

---

## Machine Learning

A regression model can be developed to predict either:

* Sales
* Profit

Possible algorithms include:

* Linear Regression
* Random Forest Regressor
* Decision Tree Regressor
* Gradient Boosting Regressor
* XGBoost (optional)

Model performance should be evaluated using standard regression metrics and compared to identify the best-performing algorithm.

---

## Project Structure

```text
Superstore-Sales-Analysis/
│
├── data/
│   └── Superstore.csv
│
├── notebooks/
│   └── Superstore_Analysis.ipynb
│
├── images/
│   └── visualizations
│
├── models/
│   └── regression_model.pkl
│
├── README.md
└── requirements.txt
```

---

## Expected Outcomes

By completing this project, stakeholders will gain:

* Better understanding of business performance
* Data-driven decision support
* Improved inventory management
* Enhanced pricing strategies
* Increased profitability
* Sales forecasting capabilities through machine learning

---

## Data Source

The dataset used in this project is publicly available for educational purposes.

**Acknowledgement**

This dataset was originally sourced from the Tableau Sample Superstore dataset. Credit belongs to the original authors and creators. This project is intended solely for educational and analytical purposes.

---

## License

This project is intended for educational, learning, and portfolio purposes only. Please respect the licensing terms of the original dataset providers.

---

## Author

**Saheed Aderibigbe**

Data Analyst | Business Intelligence Enthusiast | Python & Machine Learning Practitioner

Feel free to fork this repository, explore the analysis, and contribute improvements.
