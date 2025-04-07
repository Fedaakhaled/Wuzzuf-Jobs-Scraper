# Wuzzuf-Jobs-Scraper
This Jupyter Notebook contains a Python script that scrapes job listings from Wuzzuf.net for "Data Analyst" positions in Egypt. The script extracts key job information and saves it to a CSV file for analysis.

Features:
Web scraping using BeautifulSoup

Data extraction for job titles, company names, and job types

CSV export functionality

Pandas integration for data viewing

Code Structure
Dependencies:

requests for HTTP requests

BeautifulSoup for HTML parsing

pandas for data manipulation

Main Components:

Web request to Wuzzuf job search page

HTML parsing and container identification

Data extraction from job listings:

Job titles

Company names

Job types (Full Time/Part Time)

CSV file creation and data writing

Pandas DataFrame display of scraped data

Output
The script generates a CSV file (Wuzzuf_jobs.csv) containing:

Job_Title

Company_Name

Job_Type

Sample data includes positions like:

Data Analyst

Senior Data Analyst

Marketing Data Analyst

Manager - Data Intelligence Analyst

Usage
Run all cells sequentially

The script will:

Scrape the Wuzzuf website

Create a CSV file with the results

Display the data in a pandas DataFrame
