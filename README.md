# Automated Product Data Scraping from Tiki.vn

## Description
This script utilizes Selenium to automatically browse the Tiki.vn website and gather information about products in the "Books" category. The data is then stored in a Pandas DataFrame.

## Usage
1. Install Python and the necessary libraries: Selenium, Pandas.
2. Install the Chrome browser and the corresponding WebDriver.
3. Run the Python script and wait for the data collection process to complete.

## Details
- The script will open the Tiki.vn website and navigate to the "Books" category.
- It will iterate through the products, opening each product in a new tab, and collect information such as product name, price, and quantity sold.
- The collected data is then stored in a Pandas DataFrame and saved to a CSV file.

## Note
- This is an automated approach and may violate the terms of use of the website. Please use this script for educational and research purposes only.
- Always adhere to legal and ethical standards when using data from public sources.
