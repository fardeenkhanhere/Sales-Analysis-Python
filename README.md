Diwali Sales Data Analysis
📊 Project Overview
This project performs Exploratory Data Analysis (EDA) on Diwali sales data using Python. The analysis focuses on understanding customer demographics, purchasing behavior, sales performance, and the most popular product categories.

The project uses Pandas for data cleaning and analysis and Matplotlib/Seaborn for visualization.
🎯 Objectives
The main objectives of this analysis are to:

Clean and prepare the Diwali sales dataset.
Analyze customer demographics.
Compare purchasing behavior by gender and age group.
Identify the states generating the highest orders and sales.
Analyze customers by marital status and gender.
Analyze customers by occupation.
Identify the highest-selling product categories.
Identify the most frequently ordered products.
Derive useful customer and sales insights.
🛠️ Technologies Used
Python
Pandas – Data cleaning and analysis
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Jupyter Notebook
📁 Dataset
The notebook reads the following CSV file:

Diwali Sales Data.csv

The analysis uses fields including:

Gender
Age
Age Group
State
Marital Status
Occupation
Product Category
Product ID
Orders
Amount
🔄 Data Cleaning
The following preprocessing steps are performed:

Load the CSV dataset using Pandas.
Inspect the dataset shape and first few records.
Review column information and data types.
Remove unrelated/blank columns:
Status
unnamed1
Check for missing values.
Remove rows containing null values.
Convert the Amount column to integer type.
Generate descriptive statistics using describe().
📈 Exploratory Data Analysis
1. Gender Analysis
The project analyzes:

Number of buyers by gender.
Total sales amount by gender.

Finding: Female customers represent the larger buyer group and have higher purchasing power in the analyzed dataset.
2. Age Group Analysis
The project analyzes:

Customer count by age group and gender.
Total sales amount by age group.

Finding: Customers in the 26–35 years age group, particularly females, represent the strongest buyer segment in the analysis.
3. State Analysis
The project identifies the top 10 states based on:

Total number of orders.
Total sales amount.

Finding: Uttar Pradesh, Maharashtra, and Karnataka are identified as the leading states in terms of orders and sales in the analysis.
4. Marital Status Analysis
The project compares:

Buyer count by marital status.
Sales amount by marital status and gender.

Finding: Married women form a strong customer segment and show high purchasing power in the analyzed data.
5. Occupation Analysis
The project analyzes:

Number of buyers by occupation.
Total sales amount by occupation.

Finding: Customers working in IT, Healthcare, and Aviation are among the prominent buyer groups identified in the analysis.
6. Product Category Analysis
The project analyzes:

Number of products sold by category.
Total sales amount by product category.

Finding: Food, Clothing, and Electronics are among the leading product categories in the analysis.
7. Product Analysis
The project identifies the top products based on total number of orders using Product_ID.
💡 Key Business Insight
Based on the analysis performed in the notebook:

Married women aged 26–35 years, particularly from Uttar Pradesh, Maharashtra, and Karnataka, working in sectors such as IT, Healthcare, and Aviation, are a strong customer segment for Food, Clothing, and Electronics products.
▶️ How to Run the Project
1. Clone the repository
git clone <YOUR-GITHUB-REPOSITORY-URL>

cd <YOUR-REPOSITORY-FOLDER>
2. Install required libraries
pip install numpy pandas matplotlib seaborn jupyter
3. Place the dataset
Make sure the following file is available in the project directory:

Diwali Sales Data.csv
4. Open the notebook
jupyter notebook

Open the project .ipynb file and run the cells sequentially.
📂 Suggested Project Structure
Diwali-Sales-Analysis/

│

├── Diwali Sales Data.csv

├── Diwali_Sales_Analysis.ipynb

├── README.md

└── images/

    └── charts/
📌 Project Workflow
Raw Dataset

     ↓

Data Loading

     ↓

Data Inspection

     ↓

Data Cleaning

     ↓

Missing Value Handling

     ↓

Data Type Conversion

     ↓

Descriptive Statistics

     ↓

Exploratory Data Analysis

     ↓

Data Visualization

     ↓

Business Insights
📊 Visualizations Included
The notebook creates visualizations for:

Gender distribution
Gender vs. sales amount
Age group and gender
Age group vs. sales amount
Top 10 states by orders
Top 10 states by sales amount
Marital status distribution
Marital status vs. sales by gender
Occupation distribution
Occupation vs. sales amount
Product category distribution
Product category vs. sales amount
Top 10 products by orders
👨‍💻 Project Reference
The original notebook contains references to the following project resources:

YouTube: https://www.youtube.com/@RishabhMishraOfficial
GitHub: https://github.com/rishabhnmishra/Python_Diwali_Sales_Analysis
📜 License
No specific license information was provided in the original notebook. Add a license to this repository if you intend to distribute or reuse the project publicly.



Thank you for visiting this project!
