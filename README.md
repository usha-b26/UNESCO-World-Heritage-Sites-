🌍 UNESCO World Heritage Sites Analysis
========================================
📌 Project Overview

This project analyzes global heritage site data to understand distribution, trends, and patterns across countries and categories. Using Python, I performed data generation, cleaning, exploratory data analysis (EDA), and visualization to derive meaningful insights.

--🎯 Objectives
Analyze global distribution of heritage sites
Identify trends over time
Compare categories (Cultural, Natural, Mixed)
Explore regional and country-wise patterns

--🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly (for interactive map)

--📂 Dataset
Synthetic dataset generated using Pandas and NumPy
Features include:
Country
Category
Year of inscription
Area
Region
Latitude & Longitude

--🧹 Data Preprocessing
Created primary_country column for multi-country entries
Handled missing values using median imputation
Cleaned and structured dataset for analysis

--📊 Exploratory Data Analysis (EDA)
Category-wise distribution of heritage sites
Country-wise site counts
Year-wise trend analysis
Regional comparison of endangered sites

--📈 Visualizations
Count Plot → Category distribution
Histogram → Inscription year trends
Bar Chart → Top countries by site count
Grouped Bar Chart → Danger list comparison by region
Box Plot → Area distribution across categories

--🌍 Interactive Map (Plotly) → Geographic visualization of sites

--🔍 Key Insights
Cultural sites dominate globally
Certain countries have significantly higher site counts
Majority of sites are not on the danger list
Natural sites tend to have larger area sizes

--🧠 Skills Demonstrated
==>Data Generation (Synthetic Data)
==>Data Cleaning & Preprocessing
==>Exploratory Data Analysis (EDA)
==>Data Visualization
==>Interactive Visualization (Plotly)

--🚀 How to Run
--pip install pandas numpy matplotlib seaborn plotly
--python analysis.py
--📎 Project Structure
--├── data/
--├── notebooks/
--├── images/
--├── analysis.py
--└── README.md
--⭐ Conclusion


# UNESCO Heritage Sites Project

A database project tracking global UNESCO heritage sites, including geographical coordinates, categories, regional areas, and danger statuses.

## Database Setup

This project uses a MySQL database named `unesco_sites`. Follow the instructions below to import the database structure and data locally.

### Prerequisites
* MySQL Server (v8.0+ recommended) installed and running.
* Terminal, Command Prompt, or Git Bash.

### Setup Instructions

1. **Log into your MySQL server:**
   Open your command line and execute:
   ```bash
   mysql -u root -p
2.Create the target database:
Run the following commands inside the MySQL shell to set up an empty database container:

CREATE DATABASE unesco_sites;
EXIT;

Import the dataset:
Navigate to the directory where your backup file is saved and execute the import command:


   mysql -u root -p unesco_sites < unesco_sites.sql



This project demonstrates how data analysis and visualization can be used to understand global heritage distribution and support cultural preservation insights.
