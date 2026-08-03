Superstore Sales Analysis
Project Overview

This project performs Exploratory Data Analysis (EDA) on the Sample Superstore dataset using Python. The notebook analyzes sales data, performs preprocessing, creates new features, and visualizes business insights using charts.

Objectives
Load and explore the Superstore dataset.
Understand the structure of the data.
Perform data preprocessing.
Convert date columns into proper datetime format.
Calculate delivery time for each order.
Analyze sales by product category.
Visualize sales distribution and category-wise sales.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / Google Colab
Dataset

The project uses the Sample Superstore dataset containing information such as:

Order Date
Ship Date
Category
Sales
Customer details
Product details
Region
State
Profit
Quantity
Discount
Project Workflow
1. Import Libraries

The following libraries are imported:

pandas
numpy
matplotlib.pyplot
seaborn
2. Load Dataset

The dataset is loaded using:

pd.read_csv()
3. Data Exploration

The notebook checks:

First few records (head())
Dataset information (info())
Statistical summary (describe())
4. Data Preprocessing
Converted Order Date to datetime format.
Converted Ship Date to datetime format.
Checked for missing values.
Created a new column:
Delivery Days = Ship Date − Order Date
5. Exploratory Data Analysis (EDA)

The notebook performs:

Category-wise total sales analysis
Sales distribution analysis
6. Data Visualization

The following visualizations are created:

Bar Chart: Total Sales by Category
Histogram: Sales Distribution
Project Structure
Superstore-Sales-Analysis/
│
├── superstore.ipynb
├── samplesuperstore.csv
└── README.md
Output

The notebook provides:

Dataset summary
Missing value analysis
Delivery time calculation
Category-wise sales analysis
Graphical visualizations for better business insights
Future Enhancements
Region-wise sales analysis
State-wise profit analysis
Customer segmentation
Monthly sales trends
Profit vs Discount analysis
Interactive dashboard using Power BI or Tableau
Conclusion

This project demonstrates the basic steps of Exploratory Data Analysis (EDA) on a retail dataset. It helps understand sales performance, preprocess data effectively, calculate delivery time, and visualize important business metrics using Python.
