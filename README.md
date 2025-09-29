A portfolio of data analytics projects implemented in Python, focusing on real-world datasets and complete workflows, including data wrangling, exploration, visualization, and reporting. 📈

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

Key Insights:
- Furnished properties had higher median rents and greater variability than unfurnished ones.
- Prime localities showed higher rent ranges but also greater spread, reflecting both luxury and budget markets.
- Rent and deposit were positively correlated, with outliers where deposits were disproportionately high.

### 🔮 Future Scope

- Automating periodic scraping with schedulers (cron/GitHub Actions).
- Expanding dataset to multiple cities for broader market insights.

### 💻 Tech Stack 

• Python  • Pandas  • Matplotlib  • Seaborn  • BeautifulSoup (bs4)  • Selenium  • lxml

___________________________________________________________________________________________________________________________________________________________________________________


### Project2 Name: JOB MARKET EXPLORATION (2021–2023).  

### 📌 Project Overview

- Analyzed a large-scale dataset of 1.6M job postings from Kaggle to uncover patterns across sectors, industries, and roles.
- Reduced raw dataset (1,615,940 rows × 23 columns) to a clean, analysis-ready structure (1,610,462 rows × 15 columns).
- Performed data preprocessing: removed redundant columns, handled missing values, corrected datatypes, and standardized features.
- Parsed a JSON-formatted column to extract skills and attributes, enriching the dataset with new insights.
- Conducted exploratory data analysis (EDA) using Matplotlib and Seaborn, applying bar charts, pie charts, and heatmaps.
- Discovered hiring trends over time, most in-demand roles, and sector-specific job patterns.

### 📂 Repository Contents

- Project2.ipynb → Jupyter notebook with full preprocessing + EDA.

### 📊 Results

- Dataset scale: 1.6M rows spanning Sept 2021 – Sept 2023.
- Tech and healthcare sectors dominated postings, showing consistent demand.
- Seasonal hiring trends evident in peaks and troughs across months.
- JSON parsing revealed deeper insights into job requirements and skills.
- Visual Outputs: Bar charts (sector distribution), pie charts (roles), heatmaps (correlations).

### 🔮 Future Scope

- Build predictive models to forecast sectoral job demand.
- Extend analysis to salary insights if compensation data is available.

### 💻 Tech Stack 

• Python  • Pandas  • Matplotlib  • Seaborn  • BeautifulSoup (bs4)  • JSON

