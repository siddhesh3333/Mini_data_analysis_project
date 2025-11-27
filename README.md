📊 Mini Data Analysis Project

This repository contains a beginner-friendly data analysis project built using Python, Pandas, and Matplotlib.
The project demonstrates essential data-analysis workflows including data cleaning, merging datasets, and visualizing insights.

📁 Project Overview

The aim of this project is to analyze sample sales data across different regions and months.
The dataset includes:

Sales data (Region, Month, Sales)

Advertisement spending data

Regional manager information


The project walks through:

Loading and inspecting datasets

Cleaning and standardizing data

Merging multiple DataFrames

Exploratory Data Analysis (EDA)

Visualizing trends and relationships

🧹 Step 1 — Data Cleaning

Performed several cleaning operations such as:

Checking for missing values

Removing duplicate entries

Standardizing region names (e.g., converting north / NORTH / North into consistent format).
These steps help ensure reliable results 

🔗 Step 2 — Merging Datasets

Three DataFrames were combined using pd.merge():

sales

region_info

ads

The merged dataset provided a unified table containing region, month, sales, managers, and ad spend 


📈 Step 3 — Visualizations

Several charts were created to extract insights:

1. Total Sales by Region

A bar chart showing North region leading in total sales

2. Monthly Sales Trend

A line plot comparing sales in January vs February


3. Ad Spend vs Sales (Scatter Plot)

Helps visualize relationship between marketing spend and performance 

4. Enhanced Chart with Design Principles

Improved bar chart using Seaborn style & clearer formatting

🛠️ Technologies Used

Python 3

Pandas — data manipulation

Matplotlib — visualization

Seaborn style — cleaner chart design

📦 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Install required libraries:

pip install pandas matplotlib


Run the notebook or Python script:

python main.py


or open the Jupyter Notebook.

📚 Key Learning Outcomes

How to structure real-world data for analysis

How to merge datasets for richer insights

How to use charts effectively to communicate findings

Applying design principles for clearer visualizations
