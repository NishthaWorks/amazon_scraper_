Amazon Best Sellers Scraper
A Python script using Selenium to scrape Amazon's Best Sellers section. Extracts product details and stores them in CSV or JSON format. The script automates the login process and collects data from top-selling products across various categories.

Features:
Scrapes details like product name, price, discount, rating, description, and more.
Saves data in CSV or JSON format.
Handles Amazon login and supports multiple categories.
Requirements:
Python 3.x
Install dependencies:
bash
Copy code
pip install selenium webdriver_manager pandas
Setup:
Replace Amazon login credentials in the script.
Modify category URLs as needed for different product categories.
Run the script:
bash
Copy code
python amazon_scraper.py
Data Output:
Scraped data is saved in CSV or JSON format.
Error Handling:
Includes checks for timeouts, missing elements, and browser crashes.
Compliance:
Educational use only. Ensure compliance with Amazon's terms of service before running the scraper.
