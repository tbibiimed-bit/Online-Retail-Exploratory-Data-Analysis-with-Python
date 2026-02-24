# Online-Retail-Exploratory-Data-Analysis-with-Python
This project performs Exploratory Data Analysis (EDA) on an online retail dataset using Python.
The goal is to analyze customer purchasing behavior, identify trends, detect anomalies, and extract actionable business insights from transactional retail data.

This project was completed as part of the Coursera guided lab:

Perform Exploratory Data Analysis on Retail Data with Python

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- Objectives:

1- Clean and preprocess retail transaction data

2- Handle missing values and duplicates

3- Detect and treat outliers

4- Perform descriptive statistical analysis

5- Analyze customer purchasing behavior

6- Explore sales trends over time

7- Identify top-performing products and countries

8- Generate visual insights using Python libraries    

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- Dataset Information :

The dataset contains transactional data for an online retail store, including:

InvoiceNo – Invoice number (transaction ID)

StockCode – Product code

Description – Product description

Quantity – Number of products purchased

InvoiceDate – Date and time of purchase

UnitPrice – Price per unit

CustomerID – Unique customer identifier

Country – Country of customer

The dataset includes transactions from multiple countries, with the majority coming from the United Kingdom.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- Tools & Technologies Used:

-> Python 3

-> Jupyter Notebook

-> Pandas – Data manipulation

-> NumPy – Numerical operations

-> Matplotlib – Data visualization

-> Seaborn – Statistical visualization


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- Project Workflow:


1️- Data Loading

 -- Imported dataset using Pandas

 -- Examined structure and summary statistics

2️- Data Cleaning

-- Removed missing CustomerID values

-- Filtered out negative quantities (returns)

-- Removed duplicates

-- Converted date columns to datetime format

3️- Exploratory Data Analysis

-- Revenue calculation (Quantity × UnitPrice)

-- Monthly sales trend analysis

-- Country-wise revenue comparison

-- Top-selling products identification

-- Customer purchasing frequency analysis

4️- Visualization

-- Sales trends over time

-- Top countries by revenue

-- Most purchased products

-- Distribution of order quantities


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- Key Insights :

> The UK generates the highest revenue, significantly more than other countries.

> Sales show seasonal trends, with peaks during certain months.

> A small number of products contribute to a large share of total revenue.

> Some transactions include returns (negative quantities), which affect revenue calculations.

> Customer purchasing behavior varies significantly across regions.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- How to Run This Project

Clone this repository:

git clone [https://github.com/yourusername/online-retail-eda.git](https://github.com/tbibiimed-bit/Online-Retail-Exploratory-Data-Analysis-with-Python.git)

Navigate into the project directory:

cd online-retail-eda

Install required libraries:

pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook:

jupyter notebook

Run online_retail.ipynb


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- Project Structure :

online-retail-eda/

── online_retail.ipynb                     # Main Jupyter notebook
── README.md                               # Project documentation
── Online Retail.xlsx                      # Dataset 
── Online_Retail_Dashboard_Web.html        # Dashboard (web version)
── Online_Retail_Dashboard.pptx            # Dashboard (power-point version)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- Business Value:

This analysis can help businesses:

>> Optimize inventory management

>> Identify high-value customers

>> Improve marketing strategies

>> Understand seasonal sales patterns

>> Reduce revenue loss from returns

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


- Skills Demonstrated:

~ Data Cleaning & Preprocessing

~ Exploratory Data Analysis (EDA)

~ Data Visualization

~ Business Insight Extraction

~ Python for Data Analysis

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- License :

This project is for educational purposes as part of a Coursera guided lab.

