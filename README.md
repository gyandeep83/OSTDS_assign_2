# Job Market Analysis


## Overview
This project aims to analyze job market trends by scraping job postings from websites like Indeed. The extracted data is stored in a JSON file and then processed using Python to identify in-demand skills, salary ranges, and job trends.

## Features
1. Web scraping of job postings (Indeed)

2. Data cleaning and preprocessing

3. Extraction of in-demand skills from job titles

4. Salary range analysis

5. Visualization of job trends using Matplotlib

## Technologies Used

Python (Data Processing & Scraping)

Selenium (Web Scraping)

Pandas (Data Analysis)

Matplotlib (Data Visualization)

JSON (Data Storage)


## Project Structure
```
OSTDS_Assign2/
│── job_analysis.ipynb         # Jupyter Notebook for job market data analysis
│── job_postings.json          # Scraped job postings dat
a in JSON format
│── job_scrapper.ipynb         # Jupyter Notebook for web scraping job listings
│── README.md                  # Project documentation
│── requirements.txt           # Dependencies required for the project
```


## Setup Instructions

1. Clone the repository:
git clone https://github.com/gyandeep83/OSTDS_assign_2.git
cd OSTDS_assign_2

2. Create and activate a virtual environment:
python -m venv .venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`

3. Install dependencies:
pip install -r requirements.txt

4. Run the scraper to fetch job postings:
Open job_scrapper.ipynb in Jupyter Notebook and execute the cells.

5. Analyze the data:
Open job_analysis.ipynb in Jupyter Notebook and run the analysis

## Contribution
Feel free to fork the repository and make improvements! 🚀
