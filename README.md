# Portfolio Project in Python

This repository showcases a collection of Python projects demonstrating various skills in data analysis, web scraping, and automation. Each project is contained within its own subdirectory and includes all necessary code and, where applicable, data files.

## Projects

### 1. Web Scraping & Email Automation

* **File:** [Web Scrapping in Python](https://github.com/tafafa/Portfolio-Projects-in-Python/blob/main/Web%20Scrapping%20with%20Python.ipynb)
* **Description:** This Jupyter Notebook contains a Python script designed to scrape product information (specifically, product title and price) from a given e-commerce website (e.g., Walmart). It then demonstrates how to set up an automated email notification using the `smtplib` library to alert the user if the price of the monitored item drops below a certain threshold.
* **Key Libraries Used:**
    * `BeautifulSoup`: For parsing HTML and extracting data from web pages.
    * `requests`: For making HTTP requests to fetch web page content.
    * `time`, `datetime`: For handling time-related operations and scheduling.
    * `smtplib`: For sending emails.
* **Features:**
    * Dynamic web scraping of product details.
    * Price monitoring.
    * Automated email notifications for price drops.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
