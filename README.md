# 🧑‍💻 My Data Science Portfolio

Welcome to my Data Science Portfolio! This repository showcases the work I completed during my Data Science bootcamp. The projects here demonstrate my skills in **data analysis**, **machine learning**, **ETL pipelines**, and **data visualization**. I tackle real-world problems using a variety of tools including **Python**, **Pandas**, **SQL**, **Plotly**, **Dash**, and more.

## 📋 Table of Contents

- [Project 1: Stock Analysis of the American Phone Market](#project-1-stock-analysis-of-the-american-phone-market)
- [Project 2: Crowdfunding ETL Pipeline](#project-2-crowdfunding-etl-pipeline)
- [Project 3: Flu Trends Analysis and Visualization](#project-3-flu-trends-analysis-and-visualization)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)

---

## 📈 Project 1: Stock Analysis of the American Phone Market

### Overview:
This project explores the stock performance of **Apple** and **Samsung** during the **Covid-19 pandemic**, comparing their resilience to other tech companies in the market. It aims to understand how external factors, such as lockdowns and supply chain disruptions, influenced stock prices and investor sentiment.

### Key Insights:
- Analyzed stock trends **before, during, and after** the pandemic.
- Examined trading volumes and **volatility changes** for Apple and Samsung.
- Compared stock performance against the broader **technology sector**.
- Gained insights on **business model resilience** and **recovery strategies**.

### Data Sources:
- **Yahoo Finance**
- **Statista**

![my_plot1](https://github.com/user-attachments/assets/cf3f2023-2f28-43c0-b258-8ecff3d49442)




---

## 🔄 Project 2: Crowdfunding ETL Pipeline

### Overview:
This project involves building an **ETL (Extract, Transform, Load) pipeline** for a crowdfunding platform. Using **Python**, **Pandas**, and **PostgreSQL**, I extracted data from provided spreadsheets, cleaned and transformed it into structured DataFrames, and loaded the data into a PostgreSQL database.

### Key Components:
- **ETL Process**: Extracted data from **crowdfunding.xlsx** and **contacts.xlsx**, transformed it, and loaded into CSVs and PostgreSQL.
- **Database Design**: Created an **Entity Relationship Diagram (ERD)** and designed a **PostgreSQL schema** for the crowdfunding database.
- **Data Export**: Exported structured data into **CSV files** for further analysis.

### Data Files:
- `crowdfunding.xlsx` (Crowdfunding campaign data)
- `contacts.xlsx` (Contact information for campaigns)
- **CSV Files**:
  - `category.csv`
  - `subcategory.csv`
  - `campaign.csv`
  - `contacts.csv`
- **SQL Schema**: `crowdfunding_db_schema.sql`

---

## 🌍 Project 3: Flu Trends Analysis and Visualization

### Overview:
This project focuses on creating an interactive **dashboard** to visualize **flu trends** across the United States, based on **age groups** and **virus types**. The dashboard provides insights into flu activity, mortality rates, and regional trends, assisting in **public health decision-making**.

### Key Features:
- **Interactive Dashboards**: Built using **Dash** and **Plotly**, allowing users to interact with flu data through filters.
- **Data Sources**: Data from **CDC FluView Interactive** and the **National Center for Health Statistics**.
- **Ethical Considerations**: All data was anonymized and handled according to **CDC guidelines** to ensure privacy and accuracy.

### Tools Used:
- **Pandas**: Data manipulation and cleaning
- **Matplotlib**: Static visualizations
- **Plotly/Dash**: Interactive visualizations and dashboards
- **SQLAlchemy**: For loading data from a **PostgreSQL database**

### Instructions:
1. Clone this repository and navigate to the project directory.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Dashboard: python app.py

 
