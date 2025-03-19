# CSV Files Merger

## Overview
This folder contains a Jupyter Notebook for merging multiple CSV files from a specified folder into a single combined CSV file using Pandas.

## How to Use
1. Open the Jupyter Notebook (`data_combining.ipynb`).
2. Update the `folder_path` variable with the path to the folder containing the CSV files.
3. Run the notebook cells sequentially.
4. The script will find all CSV files in the specified folder, merge them, and save the combined data as `Combined_Data.csv` in the same directory.

## Dependencies
Ensure you have the following dependencies installed before running the notebook:

- Pandas
- OS (built-in Python module)

You can install Pandas using:

```bash
pip install pandas
```

## Output
- The combined data is saved as `Combined_Data.csv` in the same directory as the script.
- A success message is displayed upon completion.

## Notes
- Ensure that all CSV files in the folder have a consistent structure (same columns) to avoid errors during merging.
