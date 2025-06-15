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

### 2. Exploratory Data Analysis (EDA)

* **File:** [Exploratory Data Analysis(EDA)](https://github.com/tafafa/Portfolio-Projects-in-Python/blob/main/Exploratory%20Data%20Analysis(EDA).ipynb)
* **Description:** This Jupyter Notebook presents an in-depth Exploratory Data Analysis of a dataset (likely related to Electric Vehicle Population Data based on the snippets provided). The notebook covers data loading, cleaning, inspection, and visualization to uncover insights and patterns within the data.
* **Key Libraries Used:**
    * `pandas`: For data manipulation and analysis.
    * `numpy`: For numerical operations.
    * `seaborn`: For statistical data visualization.
    * `matplotlib.pyplot`: For creating static, interactive, and animated visualizations.
* **Features:**
    * Data loading and initial inspection (`.head()`, `.info()`, `.describe()`).
    * Handling missing values (`.isna().sum()`, `.dropna()`).
    * Checking for duplicate rows (`.duplicated().sum()`).
    * Analysis of unique values (`.nunique()`) and value counts for key categorical columns (e.g., 'Model', 'Make', 'County', 'City', 'Electric Vehicle Type').
    * Data visualization to illustrate distributions and relationships.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
