# Glassdoor Job Scraper with Selenium

## 📌 Project Overview
This project automates the process of collecting job postings from **Glassdoor** using **Selenium**.  
It extracts job-level and company-level details into a structured CSV file, making it easier to analyze job market trends such as skills in demand, salary ranges, and industry breakdowns.

---

## 🔍 Features
- Search jobs by **keyword** and scrape across multiple pages  
- Extracts the following fields:
  - Company name  
  - Job title  
  - Location  
  - Job description text  
  - Salary estimate (if available)  
  - Company metadata (size, type, sector, industry, founded year, revenue)  
- Handles pop-ups, missing data, and interaction issues with Glassdoor’s interface  
- Outputs results into a **CSV file** named after the keyword  

---

## ⚙️ Tools & Libraries
- **Python 3.x**  
- [Selenium](https://www.selenium.dev/) for browser automation  
- [pandas](https://pandas.pydata.org/) for data structuring  
- Google Chrome + [ChromeDriver](https://sites.google.com/chromium.org/driver/)  

---

## 🚀 How to Use
1. Clone or download this repository.  
2. Install requirements:  
   ```bash
   pip install selenium pandas
3. Download ChromeDriver and update the script with its path:
   ```bash
   chrome_path = r"C:\path\to\chromedriver.exe"
4. Run the script:
   ```bash
   python glassdoor_scraper.py
5. Call the function with a keyword and number of pages:
   ```bash
   fetch_jobs("Data Scientist", 5)
6. The scraper will output a CSV file:
   ```bash
   Data Analyst.csv


## Output
<img src="https://imgur.com/r92kJKi.png" alt="Output" width="600"/>
   



