# My Data Science Portfolio
Welcome to my Data Science Portfolio! This repository contains the work I've completed during my Data Science boot camp. 
It shows a series of projects demonstrating my data analysis, machine learning, ETL pipelines, and data visualization skills. Each project focuses on real-world problems and uses various tools, including Python, Pandas, SQL, Plotly, Dash, and more.
Table of Contents
•	Project 1: Stock Analysis of the American Phone Market
•	Project 2: Crowdfunding ETL Pipeline
•	Project 3: Flu Trends Analysis and Visualization
•	Technologies Used
•	How to Run
________________________________________
# Project 1: Stock Analysis of the American Phone Market
Overview:
This project explores the stock performance of Apple and Samsung during the Covid-19 pandemic, comparing their resilience to other tech companies in the market. The goal was to understand how external factors such as lockdowns, supply chain disruptions, and changing consumer behavior influenced stock prices and investor sentiment.
Key Insights:
•	Analyzed stock trends before, during, and after the pandemic.
•	Examined trading volumes and volatility changes for Apple and Samsung.
•	Compared stock performance against the broader technology sector.
•	Unveiled insights on business model resilience and recovery strategies.
Data Sources:
•	Yahoo Finance
•	Statista
________________________________________
# Project 2: Crowdfunding ETL Pipeline
Overview:
In this project, I built an ETL (Extract, Transform, Load) pipeline for a crowdfunding platform. Using Python, Pandas, and PostgreSQL, I extracted data from provided spreadsheets, cleaned and transformed it into structured DataFrames, and loaded the data into a PostgreSQL database.
Key Components:
•	ETL Process: Extracted data from crowdfunding and contacts spreadsheets, transformed and cleaned it, and loaded the results into CSV files and a PostgreSQL database.
•	Database Design: Created an Entity Relationship Diagram (ERD) and designed a PostgreSQL schema for the crowdfunding database.
•	Data Export: Exported structured data into CSV files for further analysis.
Data Files:
•	crowdfunding.xlsx (Crowdfunding campaign data)
•	contacts.xlsx (Contact information for the campaigns)
•	CSV Files:
o	category.csv
o	subcategory.csv
o	campaign.csv
o	contacts.csv
•	SQL Schema: crowdfunding_db_schema.sql
________________________________________
# Project 3: Flu Trends Analysis and Visualization
Overview:
This project involves the creation of an interactive dashboard to visualize flu trends across the United States, focusing on various age groups and virus types. The dashboard provides real-time insights on flu activity, mortality rates, and regional trends, helping to inform public health decisions.
Key Features:
•	Interactive Dashboards: Built using Dash and Plotly, allowing users to interact with flu data through filters.
•	Data Sources: Data from the CDC FluView Interactive and National Center for Health Statistics.
•	Ethical Considerations: All data was anonymized and handled in accordance with CDC guidelines to ensure privacy and accuracy.
Tools Used:
•	Pandas: For data manipulation and cleaning.
•	Matplotlib: For static visualizations.
•	Plotly/Dash: For interactive visualizations and dashboards.
•	SQLAlchemy: For loading data from a PostgreSQL database.
Instructions:
1.	Clone this repository and navigate to the project directory.
2.	Install the necessary dependencies using pip install -r requirements.txt.
3.	Run the dashboard by executing the app.py file. The app will launch on a local port, and you can interact with the flu trends data.
________________________________________
Technologies Used:
•	Python (Pandas, NumPy, Matplotlib, Plotly, Dash)
•	SQL (PostgreSQL, SQLAlchemy)
•	Jupyter Notebooks
•	Data Cleaning and Transformation (Regex, DataFrame Manipulation)
•	ETL Pipeline Development
•	Interactive Web Dashboards
________________________________________

# How to Run:
1.	Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
2.	Install Dependencies: Make sure you have Python 3.8 or higher installed. Then, install the required packages:
bash
Copy code
pip install -r requirements.txt
3.	Run the Project:
o	For Project 1 and Project 2, simply run the Jupyter notebooks in the respective directories.
o	For Project 3, run the dashboard application:
bash
Copy code
python app.py
4.	View in Browser:
o	For Project 3, open a browser and go to http://127.0.0.1:8050/ to explore the interactive dashboard.

# Feel free to contact me on LinkedIn or reach out via email at anthonylopez0097@gmail.com.
