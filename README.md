# Portfolio Project in Python

This repository showcases a collection of Python projects demonstrating various skills in data analysis, web scraping, and automation. Each project is contained within its own subdirectory and includes all necessary code and, where applicable, data files.

## Projects

### 1. Web Scraping & Email Automation

* **File:** `Web Scrapping in Python.ipynb`
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

* **File:** `Exploratory Data Analysis(EDA).ipynb`
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

## Important Notes for Web Scraping Project

* **Email Configuration:** For the `Web Scrapping in Python.ipynb` notebook, you will need to replace placeholder values for email credentials and potentially adjust SMTP server settings. **Be extremely cautious with your email credentials and never push them directly to a public repository.** Consider using environment variables or a separate configuration file ignored by Git.
* **Website Structure Changes:** Web scraping scripts are highly dependent on the structure of the target website. If the website's HTML changes, the scraping script might need updates to function correctly.
* **Ethical Considerations:** Always ensure you comply with the website's `robots.txt` file and terms of service when performing web scraping. Avoid making too many requests in a short period to prevent IP blocking.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
