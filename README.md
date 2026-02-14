# Quotes Web Scraping & Analysis Project

**Project Overview**

This project demonstrates web scraping, data cleaning, and exploratory data analysis using Python.
Quotes were scraped from Quotes to Scrape, structured into a dataset, and analyzed to identify patterns in authors and tags.

The goal of this project was to:

* Extract structured data from multiple web pages

* Clean and organize scraped data

* Perform frequency analysis

* Create meaningful visualizations

  **Data Source**

Data was scraped from:

🔗 https://quotes.toscrape.com/

**Tools & Libraries Used**

1. Python

2. requests

3. BeautifulSoup4

4. pandas

5. matplotlib

6. seaborn

7. collections (Counter)

⚙️ **Project Workflow**

- Web Scraping

Sent HTTP requests to 10 pages of the website

Extracted:

Quote text

Author name

Tags associated with each quote

Stored scraped data in structured dictionaries

- Data Structuring

Converted scraped data into a pandas DataFrame

Ensured tags were stored as lists for proper analysis

- Exploratory Data Analysis (EDA)

Performed the following analyses:

🔝 Top 10 most frequent tags

✍️ Top 10 authors by number of quotes

📊 Distribution of number of tags per quote

🥧 Share of top 5 authors (pie chart)

🥧 Distribution of top 5 tags (pie chart)

📊 **Key Insights**

* Some authors contributed significantly more quotes than others.

* Certain themes such as life, love, and inspirational content appear most frequently.

* Most quotes contain between 2–5 tags.

📌 **Skills Demonstrated**

- Web scraping with BeautifulSoup

- Handling multi-page scraping

- Data cleaning and transformation

- Frequency analysis using Counter

- Data visualization

- **Visuals**

- 

