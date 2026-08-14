# Day 8 – E-commerce Sales Analysis

## Overview

This project performs exploratory and business-oriented analysis on an e-commerce sales dataset using **Python** and **Pandas**.

The notebook demonstrates:

- Loading a CSV dataset into a Pandas DataFrame
- Inspecting rows, columns, shape, index, data types, and descriptive statistics
- Selecting rows and columns
- Filtering records using conditions
- Sorting orders by sales and quantity
- Using `groupby()` and aggregation functions
- Analyzing sales by category, city, product, and payment method
- Identifying high-value and low-value orders
- Finding top-performing products and categories
- Writing meaningful observations from the results

## Files

| File | Description |
|---|---|
| `Day8_Ecommerce_Sales_Dataset.csv` | Original e-commerce sales dataset |
| `Ecommerce_Sales_Analysis.ipynb` | Completed Google Colab/Jupyter Notebook |
| `README.md` | Project documentation |

## Dataset

The dataset contains **100 orders** and **13 columns**:

- `Order_ID`
- `Order_Date`
- `Customer`
- `City`
- `Region`
- `Category`
- `Product`
- `Quantity`
- `Unit_Price`
- `Discount_Percent`
- `Total_Sales`
- `Rating`
- `Payment_Method`

## Key Results

| Metric | Result |
|---|---:|
| Total Sales | ₹447,262.95 |
| Average Sales per Order | ₹4,472.63 |
| Highest Order Sales | ₹13,995.00 |
| Lowest Order Sales | ₹449.10 |
| Total Quantity Sold | 294 |
| Number of Orders | 100 |

### Top performers

- **Top category by sales:** Sports
- **Top city by sales:** Hyderabad
- **Top product by sales:** Coffee Maker
- **Payment method with highest total sales:** Credit Card
- **Payment method with highest average order value:** Net Banking

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab

## Main Pandas Operations

The notebook specifically demonstrates:

```python
df.head()
df.tail()
df.sample()
df.shape
df.columns
df.dtypes
df.info()
df.describe()
df.loc[]
df.iloc[]
df.sort_values()
df.groupby()
.sum()
.mean()
.max()
.min()
.count()
```

## How to Run

### Google Colab

1. Upload `Day8_Ecommerce_Sales_Dataset.csv` to the Colab working directory.
2. Open `Ecommerce_Sales_Analysis.ipynb` in Google Colab.
3. Run the cells from top to bottom.

### Local Jupyter Notebook

Make sure Python, Pandas, NumPy, and Jupyter are installed, then open the notebook and run all cells.

## Observations

The analysis shows that:

1. The dataset contains 100 orders with total sales of approximately **₹447,262.95**.
2. **Sports** is the strongest category by total sales.
3. **Hyderabad** is the strongest city by total sales.
4. **Coffee Maker** is the highest-selling product by revenue.
5. **Credit Card** contributes the most total sales among payment methods.
6. The product/category with the highest sales is not necessarily the same as the one with the highest quantity sold, showing why multiple performance metrics should be considered.

## Conclusion

This project demonstrates how basic Pandas operations can transform raw e-commerce transactions into useful business insights. Grouping, aggregation, filtering, and sorting make it possible to compare different dimensions of sales performance and identify areas that contribute most to revenue.
