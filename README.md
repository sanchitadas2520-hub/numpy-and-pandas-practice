# NumPy and Pandas Practice

A structured collection of exercises and experiments for learning **NumPy and Pandas**, two foundational Python libraries for data analysis.

## About

This repository focuses on developing practical proficiency with numerical computing and tabular data manipulation using real-world inspired datasets.

It forms part of my preparation for Data Analytics, Machine Learning, and later Privacy-Preserving Data Analytics work.

The goal is not just to learn functions, but to understand how these tools are used in real data systems such as:

* business analytics dashboards
* healthcare data processing
* financial reporting systems
* user behaviour analysis
* large-scale data cleaning pipelines

---

## NumPy Topics 

NumPy is used when data is **numerical, large-scale, and needs fast computation**.

### Arrays

Used to store structured numerical data efficiently.

Real-world use:

* sensor readings (temperature, heart rate, IoT devices)
* stock prices over time
* image pixel values

---

### Array Creation

Creating structured datasets from raw values or external sources.

Real-world use:

* converting raw logs into structured numerical format
* preparing datasets for ML models

---

### Indexing

Accessing specific data points.

Real-world use:

* retrieving a specific day’s stock price
* selecting a single sensor reading from a stream

---

### Slicing

Extracting subsets of data.

Real-world use:

* analysing last 7 days of sales data
* extracting a time window from sensor data

---

### Reshaping

Changing data structure without changing values.

Real-world use:

* converting flat image data into 2D/3D format
* preparing ML input features

---

### Vectorized Operations

Performing operations on entire datasets without loops.

Real-world use:

* calculating profit margins for thousands of transactions instantly
* scaling large datasets in ML preprocessing

---

### Aggregation

Summarizing data (sum, mean, min, max).

Real-world use:

* average monthly sales
* total revenue per region
* maximum CPU usage in servers

---

### Boolean Indexing

Filtering data using conditions.

Real-world use:

* finding customers with high spending
* detecting anomalies in system logs
* filtering failed transactions

---

### Broadcasting

Performing operations on arrays of different shapes.

Real-world use:

* normalizing datasets
* applying scaling factors across features

---

### Basic Numerical Operations

Mathematical transformations on datasets.

Real-world use:

* financial calculations
* scientific data processing
* ML feature engineering

---

## Pandas Topics 

Pandas is used when data is **tabular, messy, and needs cleaning + analysis**.

### Series

A single column of data.

Real-world use:

* temperature readings over time
* user ratings for products

---

### DataFrames

Full table-like structure.

Real-world use:

* Excel-like business datasets
* customer databases
* hospital patient records

---

### Reading CSV Files

Loading real-world datasets.

Real-world use:

* importing sales reports
* loading Kaggle datasets
* reading system logs

---

### Selecting Columns

Choosing relevant features.

Real-world use:

* selecting only “price” and “date” from sales data
* extracting relevant medical attributes

---

### Filtering Rows

Extracting meaningful subsets.

Real-world use:

* customers from a specific region
* transactions above a threshold
* failed login attempts

---

### Sorting

Ordering data for analysis.

Real-world use:

* top-selling products
* highest risk transactions
* fastest delivery times

---

### Missing Values

Handling incomplete data.

Real-world use:

* missing user profile information
* incomplete survey responses
* sensor data dropouts

---

### GroupBy

Grouping data for analysis.

Real-world use:

* total sales per region
* average marks per student
* user activity per day

---

### Aggregation

Summarizing grouped data.

Real-world use:

* monthly revenue reports
* average hospital wait time
* total app usage per user

---

### Merging

Combining datasets.

Real-world use:

* joining customer data with transaction data
* combining multiple CSV reports

---

### Joining

Relational data combination.

Real-world use:

* database-style table relationships
* linking user profiles with activity logs

---

### Pivot Tables

Reshaping data for reporting.

Real-world use:

* business dashboards
* sales breakdown by category and region
* academic performance summaries

---

### Data Transformation

Cleaning and modifying data.

Real-world use:

* standardizing formats (dates, currency)
* encoding categorical values
* preparing ML datasets

---

### Exporting Data

Saving processed datasets.

Real-world use:

* generating cleaned datasets for ML models
* exporting reports for dashboards
* saving processed analytics results

---

## Projects (Real-World Inspired)

These projects are designed to simulate real data analysis workflows used in industry.

---

### 1. Student Performance Analysis

📌 Uses Pandas + GroupBy + Aggregation

* analyse marks across subjects
* find top performers
* detect weak areas
* compare performance across classes

Real-world analogy:
education analytics dashboards used by institutions

---

### 2. Sales Data Analysis Dashboard

📌 Uses Pandas + NumPy + Pivot Tables

* total revenue analysis
* monthly trends
* top products
* regional performance

Real-world analogy:
e-commerce analytics systems (Amazon-style dashboards)

---

### 3. Customer Behaviour Analysis

📌 Uses filtering + grouping + aggregation

* identify high-value customers
* analyse purchase patterns
* segment users

Real-world analogy:
Netflix / Amazon recommendation systems (basic level)

---

### 4. Data Cleaning Pipeline Project

📌 Uses Pandas heavily

* handle missing values
* remove duplicates
* standardize formats
* prepare clean dataset

Real-world analogy:
data preprocessing pipelines in ML companies

---

### 5. Mini Financial Analysis System

📌 Uses NumPy + Pandas

* profit/loss calculation
* expense tracking
* trend analysis

Real-world analogy:
personal finance apps or accounting systems

---

## Repository Structure

```text
numpy-and-pandas-practice/
│
├── numpy/              # NumPy concept exercises
├── pandas/             # Pandas concept exercises
├── notebooks/          # Jupyter notebooks (main work)
├── datasets/           # Real-world datasets
├── mini_projects/      # Project implementations
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Status

🚧 **In Progress**

This repository will evolve as I move from basic operations → real datasets → full analytical projects.

---

## Author

**Sanchita Das**
