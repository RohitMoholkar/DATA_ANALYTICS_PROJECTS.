This repository contains two data analytics projects implemented in Python, focusing on real-world datasets and end-to-end workflows. 

### Project1 Name: PROPERTY RENTAL EXPLORATION WITH WEB SCRAPING.  

### 📌 Project Overview

- Extracted and compiled ~2,500 rental property listings from dynamic platform NoBroker.com using Selenium (for JS-rendered pages) and BeautifulSoup (for HTML parsing).
- Captured multiple attributes including rent, deposit, area, maintenance, tenure, amenities, furnishing type, and location.
- Processed and validated the dataset (~2,478 rows × 10 columns) with pandas, handling missing values, duplicates, inconsistencies, and formatting issues.
- Conducted Exploratory Data Analysis (EDA) with Matplotlib and Seaborn, analyzing distributions, relationships, and outliers.
- Created visualizations to uncover key housing trends: Furnished vs unfurnished → clear difference in median rents. Prime localities → higher rent ranges but more variability. Deposit vs Rent → positive correlation with notable outliers.
- Provided actionable insights into housing trends, enabling tenants and landlords to better understand the market.

### 📂 Repository Contents

- Project1.ipynb → Full Jupyter notebook covering web scraping, cleaning, and exploratory data analysis (EDA).
- Project1.pdf → Project report summarizing methodology, analysis, and findings.
- Project1_Scrape_Data.csv → Structured dataset (~2,478 rows × 10 columns) after cleaning and preprocessing.
- Project1_webscraping_op.zip → Raw scraping output (large file, ~38MB) containing detailed HTML and intermediate data for reference.

### 📊 Results

- Project Workflow:
<img width="1024" height="354" alt="Workflow" src="https://github.com/user-attachments/assets/ca4de51a-5128-4fec-95ac-b08fe4e051cf" />

- Furnished properties had higher median rents and greater variability than unfurnished ones.
- Prime localities showed higher rent ranges but also greater spread, reflecting both luxury and budget markets.
- Rent and deposit were positively correlated, with outliers where deposits were disproportionately high.

### 🔮 Future Scope

- Automating periodic scraping with schedulers (cron/GitHub Actions).
- Expanding dataset to multiple cities for broader market insights.

### 💻 Tech Stack 

• Python  • Pandas  • Matplotlib  • Seaborn  • BeautifulSoup (bs4)  • Selenium  • lxml

### Project2 Description. 
- Project Name: **EXPLORING JOB POSTINGS DATA: UNVEILING PATTERNS AND TRENDS.**
- The project aims to analyze a large dataset of job postings, spanning two years, to uncover insights and trends in job sectors, industries, and roles.
- This project is divided into three important data analytics project steps: Step 1 involves loading and gaining a basic understanding of the dataset, Step 2 focuses on data cleaning and processing and Step 3 entails proper data analysis. 
- Initially, imported all necessary libraries for the project for data analysis and visualization, including NumPy, Pandas, Matplotlib, Seaborn, and JSON. Obtained the dataset from Kaggle.com, which contains detailed job posting-related information. Loaded the dataset into the 'df' variable. The dataset contains 1,615,940 rows and 23 columns, making it considerably large data.
- I performed comprehensive data preprocessing, I proceeded with several essential tasks to ensure the dataset's integrity and suitability for analysis. Initially, I focused on removing unnecessary columns and eliminating rows with missing values to streamline the dataset. Additionally, I introduced new columns to enrich the dataset's insights. Following this, I corrected the datatype of columns to ensure accurate analysis. One column, presented in JSON format, required special attention. I parsed the data and extracted valuable information to create new columns, enhancing the dataset's depth. To improve comprehension during analysis, I rearranged the columns. As a result of these preprocessing steps, the dataset now boasts 1,610,462 rows and 15 columns, primed for effective analysis and insightful discoveries. 
- In the main data analysis section, I uncovered numerous insights by conducting in-depth exploration of the dataset. Using various analytical techniques, I plotted diverse graphs, created informative dataframes, and detailed key findings derived from the analysis. The dataset encompasses two years of job postings, spanning from September 15, 2021, to September 15, 2023. Across the analyses, I utilized a range of visualization methods including bar graphs, pie charts, and heatmaps to depict trends and patterns. Insights were gleaned regarding job sectors, industries, job roles, and more. For a comprehensive overview, please refer to the accompanying ipynb file named Project2 located above.  
