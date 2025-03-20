# H&M Web Scraping and Exploratory Data Analysis Project

## Overview
This project focuses on web scraping, data cleaning, preprocessing, data combining, and data visualization to extract insights from H&M's product listings and identify the most significant factors affecting fashion product prices. The workflow is divided into four main stages:
1. **Web Scraping** - Extracting product data from the H&M website using Selenium.
2. **Data Combining** - Merging multiple CSV files (from different categories) into a unified dataset.
3. **Data Cleaning & Preprocessing** - Structuring, formatting, and preparing the scraped data for analysis.
4. **Data Visualization & Insights** - Exploring trends and patterns using univariate, bivariate, and multivariate analysis.


### 1️⃣ Web Scraping
- **Description:** Extracts product data from the H&M website using Selenium.
- **Output:** Multiple category-based CSV files.
- **Dependencies:** Selenium, Pandas, NumPy, Time.

### 2️⃣ Data Combining
- **Description:** Merges multiple category-based CSV files into a single dataset for easier analysis.
- **Steps:**
  - After scraping each category, store its data as a separate CSV file.
  - Identify all category CSV files in the specified folder.
  - Read and convert each CSV file into a Pandas DataFrame.
  - Concatenate all data frames while preserving structure.
- **Output:** `Combined_Data.csv` containing all merged product data.
- **Dependencies:** Pandas, OS.

### 3️⃣ Data Cleaning & Preprocessing
- **Description:** Cleans and preprocesses the raw scraped data.
- **Steps:**
  - Exploratory Data Analysis (EDA): Inspect data structure, formats, missing values, and duplicates.
  - Data Cleaning & Preprocessing: Remove unnecessary columns, standardize formats, convert data types, handle missing values, detect outliers, and prepare data for analysis.
- **Output:** `Preprocessed_Data.csv` with structured and clean data.
- **Dependencies:** Pandas, NumPy, AST.


### 4️⃣ Data Visualization & Insights
- **Description:** Analyzes and visualizes the cleaned and combined data.
- **Steps:**
  - **Univariate Analysis:** Examining individual variables.
  - **Bivariate Analysis:** Investigating relationships between two variables.
  - **Multivariate Analysis:** Exploring interactions among multiple variables to uncover deeper insights.
- **Output:** Graphs and charts in `Data_Visualization.ipynb`.
- **Dependencies:** Pandas, NumPy, Matplotlib, Seaborn.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Selenium (for web scraping, if applicable)
- Time
- AST
- OS

## How to Run the Project
1. **Ensure Dependencies Are Installed:**
   ```bash
   pip install selenium pandas numpy matplotlib seaborn
   ```
2. **Run the Web Scraping Notebook (`Web_Scraping.ipynb`) for each category**
3. **Run the Data Combining Notebook (`data_combining.ipynb`)**
4. **Run the Data Cleaning Notebook (`Data Cleaning & Preprocessing.ipynb`)**
5. **Run the Data Visualization Notebook (`Data_Visualization.ipynb`)**
6. **Analyze insights from visualizations**

## Notes
- Make sure `ChromeDriver` is installed and configured properly for Selenium.
- Check website structure before scraping to ensure compatibility.
- Data visualization helps uncover trends and patterns useful for business insights.

---
*This README will be updated as new features are added.*
