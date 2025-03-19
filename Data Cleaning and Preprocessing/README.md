# Data Cleaning and Preprocessing

## Overview
This folder contains a Jupyter Notebook for data cleaning and preprocessing. The notebook explores the dataset, handles missing values, formats data types, and processes outliers to prepare the data for further analysis. Additionally, it stores the cleaned and preprocessed data.

## How to Use
1. Open the Jupyter Notebook (`Data Cleaning & Preprocessing.ipynb`).
2. Load the dataset into the notebook.
3. Follow the steps in the notebook:
   - **Exploratory Data Analysis (EDA):**
     - View dataset structure using `.head()`, `.shape`, `.info()`.
     - Check data types and format of each feature.
     - Identify missing values and duplicate rows.
   - **Data Cleaning and Preprocessing:**
     - Drop excessive null values and unrelated columns.
     - Handle data type conversions and format inconsistencies.
     - Impute missing values appropriately.
     - Detect and handle outliers.
4. Run the notebook cells sequentially to process the data.

## Dependencies
Ensure you have the following dependencies installed before running the notebook:

- Pandas
- NumPy
- AST (built-in Python module)

You can install Pandas and NumPy using:

```bash
pip install pandas numpy
```

## Output
- The cleaned and preprocessed data is saved as `Preprocessed_Data.csv` in the same folder.
- The folder contains both the preprocessing notebook (`Data Cleaning & Preprocessing.ipynb`) and the resulting `Preprocessed_Data.csv` file.
