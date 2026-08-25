# Store Sales Analysis

## 📌 Project Overview

Store Sales Analysis is a **Data Analytics and Exploratory Data Analysis (EDA) project** focused on analyzing store sales data to understand sales performance, profitability, customer segments, products and regional trends.

The project explores order information, shipping details, customer segments, product categories, sales, quantity, discounts and profit using Python and data visualization libraries.

## 🎯 Objectives

* Analyze store sales data.
* Understand sales and profit performance.
* Explore customer segments and purchasing patterns.
* Analyze product categories and sub-categories.
* Examine regional sales performance.
* Study the relationship between sales, quantity, discount and profit.
* Perform exploratory data analysis.
* Create meaningful data visualizations.
* Identify patterns and trends in the sales data.

## 📊 Dataset

The project uses the `stores_sales_forecasting.csv` dataset.

The dataset contains **2,121 records and 21 columns**.

### Main Features

| Column          | Description                         |
| --------------- | ----------------------------------- |
| `Row ID`        | Unique row identifier               |
| `Order ID`      | Unique order identifier             |
| `Order Date`    | Date on which the order was placed  |
| `Ship Date`     | Date on which the order was shipped |
| `Ship Mode`     | Shipping method used                |
| `Customer ID`   | Unique customer identifier          |
| `Customer Name` | Customer name                       |
| `Segment`       | Customer segment                    |
| `Country`       | Country                             |
| `City`          | Customer city                       |
| `State`         | Customer state                      |
| `Postal Code`   | Postal code                         |
| `Region`        | Sales region                        |
| `Product ID`    | Product identifier                  |
| `Category`      | Product category                    |
| `Sub-Category`  | Product sub-category                |
| `Product Name`  | Product name                        |
| `Sales`         | Sales amount                        |
| `Quantity`      | Quantity ordered                    |
| `Discount`      | Discount applied                    |
| `Profit`        | Profit generated                    |

These columns are present in the notebook's dataset.

## 🔍 Data Exploration

The project performs several exploratory operations, including:

* Loading the dataset using Pandas
* Checking dataset dimensions
* Inspecting data types
* Viewing column names
* Generating descriptive statistics
* Examining sales values
* Analyzing quantities
* Studying discounts
* Examining profit
* Exploring customer segments
* Analyzing regions
* Exploring product categories and sub-categories

The dataset contains 21 columns, with numerical variables including Sales, Quantity, Discount and Profit.

## 📈 Sales Analysis

The project analyzes sales performance across different dimensions, including:

* Customer segment
* Region
* Category
* Sub-category
* Products
* Order dates
* Shipping modes

The analysis helps identify patterns in sales and understand how different business factors relate to overall performance.

## 💰 Profit Analysis

Profit is analyzed along with sales, quantity and discount.

The dataset contains both positive and negative profit values, allowing the analysis to explore profitable and loss-making transactions. The notebook's descriptive statistics show an average profit of approximately **8.70** for the analyzed records.

## 🏷️ Discount Analysis

The project examines the discount applied to orders and explores its relationship with sales and profit.

Discount values in the dataset range from **0 to 0.70** in the displayed descriptive statistics.

## 📦 Quantity Analysis

The quantity of products ordered is also analyzed to understand purchasing patterns.

The dataset contains order quantities ranging from **1 to 14** in the descriptive statistics.

## 📊 Data Visualization

The project uses data visualization to understand sales-related patterns and relationships.

Visualizations are used to explore:

* Sales distribution
* Profit distribution
* Quantity
* Discount
* Customer segments
* Regions
* Categories
* Sub-categories
* Product performance
* Relationships between numerical variables

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualization

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Inspection
   ↓
Data Understanding
   ↓
Exploratory Data Analysis
   ↓
Sales Analysis
   ↓
Profit Analysis
   ↓
Quantity & Discount Analysis
   ↓
Customer & Product Analysis
   ↓
Regional Analysis
   ↓
Data Visualization
   ↓
Business Insights
```

## 📁 Project Structure

```text
Store-Sales-Analysis/
│
├── Sales_forecasting.ipynb
├── stores_sales_forecasting.csv
├── README.md
└── requirements.txt
```

## 💡 Key Learnings

Through this project, I gained practical experience in:

* Loading and exploring sales datasets
* Understanding structured business data
* Performing Exploratory Data Analysis
* Analyzing sales and profit
* Working with customer and product information
* Analyzing categorical and numerical variables
* Understanding the impact of discounts
* Creating different types of visualizations
* Using Pandas for data manipulation
* Using Matplotlib, Seaborn and Plotly for visualization
* Extracting meaningful patterns from sales data

## 🚀 Future Improvements

* Build a proper time-series sales forecasting model.
* Analyze monthly and yearly sales trends.
* Apply forecasting algorithms such as ARIMA or other suitable time-series methods.
* Compare actual sales with predicted sales.
* Create an interactive sales dashboard.
* Add region-wise and category-wise business KPIs.

## 👩‍💻 Author

**Priyadharshini**

Computer Science Engineering Student

---

⭐ If you find this project useful, feel free to explore the repository and my other Data Analytics projects.

