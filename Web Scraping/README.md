# H&M Web Scraping Script

## Overview
This folder contains a web scraping script to extract product data from a specified category on the H&M website using Selenium. The script is designed to be reusable—just update the category name and URL without modifying the core logic.

## How to Use
1. Open the Jupyter Notebook (`Web_Scraping.ipynb`).
2. Update the following variable:
   - `category`: Name of the product category (e.g., "Dress").
3. Update the URL in `mydriver.get("")` with the correct category page link.
4. Run the notebook cells sequentially to start scraping.

## Dependencies
Ensure you have the following dependencies installed before running the script:

- Selenium
- Pandas
- NumPy
- Time

You can install them using:

```bash
pip install selenium pandas numpy
```

## Output
The extracted data is saved as a CSV file in the same directory.

## Notes
- The script uses Google Chrome and requires ChromeDriver to be installed and properly set up.
- Verify that the URL in `mydriver.get("")` is correct before running the script.
- If the website structure changes, updates to the scraping logic may be required.
- Respect H&M's terms of service and avoid excessive requests to prevent being blocked.
