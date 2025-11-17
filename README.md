# Web Scraper for News Headlines

## 📌 Objective
The goal of this task is to build a simple Python web scraper that extracts the latest news headlines from a public website and saves them into a text file.  
This demonstrates skills in HTTP requests, HTML parsing, and basic automation.
Scrape top news headlines from a public website using Python.

## Tools Used
- Python
- requests
- BeautifulSoup

## Files
- scraper.py — main script
- headlines.txt — scraped output


## 📘 What I Learnt

### 🔹 1. How HTTP Requests Work
I learned how a Python script sends a GET request to a website using the `requests` library, and how servers respond with status codes like 200 (OK) or 404 (Not Found).

### 🔹 2. HTML Structure & Tags
I understood how webpages are built using HTML tags such as `<h1>`, `<h2>`, `<p>`, `div`, etc., and how to target specific tags to extract useful information.

### 🔹 3. Web Scraping Basics
I learned how to scrape data from a website responsibly, including:
- Selecting the correct tags
- Extracting text from HTML elements
- Avoiding overloading servers
- Using a User-Agent to mimic a browser

### 🔹 4. BeautifulSoup Functions
I understood how to:
- Parse webpage HTML using `BeautifulSoup()`
- Use `soup.find_all()` to extract multiple elements
- Use `.text` or `.get_text()` to clean raw data

### 🔹 5. File Handling in Python
I learned how to create and write into a text file using Python:
- `with open(...) as file:`  
- Writing cleaned headlines line-by-line

### 🔹 6. Error Handling With Try-Except
I learned how to use `try-except` blocks to handle exceptions such as:
- Network failures  
- Wrong URLs  
- Parsing issues  

### 🔹 7. Automating Data Collection
I learned how Python can automate repetitive tasks like collecting news headlines, which can help in data analysis, monitoring trends, and saving time.


