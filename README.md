# 📊 Naukri.com Job Market Analysis
### *End-to-End Web Scraping, Data Engineering & EDA*

## 🚀 Project Overview
This project is a comprehensive analysis of the Indian job market for Data professionals (Data Science, Engineering, and Analytics). It features a robust **Web Scraping** engine that handles dynamic content, followed by a data engineering pipeline to transform unstructured data into actionable insights.

## 🛠️ Tech Stack
* **Language:** Python
* **Web Scraping:** Selenium, WebDriver Manager
* **Data Engineering:** Pandas, NumPy, Regular Expressions (Regex)
* **Visualization:** Matplotlib, Seaborn, WordCloud

## 🏗️ Technical Implementation

### 1. Automated Web Scraping
* Developed a custom scraper using **Selenium** to navigate dynamic content.
* Implemented pagination logic to extract over **1,500 job listings** across 100+ pages.
* Integrated random delays and user-agent headers to ensure stable data extraction.

### 2. Data Cleaning & Engineering
Real-world data is messy. I implemented several standardization layers:
* **Experience Normalization:** Converted text ranges (e.g., "5-10 Yrs") into numeric fields for calculation.
* **Location Cleaning:** Used **Regex** to split multi-city strings and standardize over 1,000 unique location entries.
* **Role Classification:** Normalized hundreds of varying job titles into core categories: Data Engineer, Analyst, and Scientist.

### 3. Exploratory Data Analysis (EDA)
* **High Demand:** Identified **Data Engineering** as the most in-demand role by volume.
* **Tech Hubs:** Mapped demand hotspots, with **Bengaluru** leading, followed by Hyderabad and Pune.
* **Skill Analysis:** Identified **Python, SQL, and Data Pipelines** as the most requested skills via frequency analysis.

## 📊 Key Insights
* **Market Trend:** Data Engineering roles significantly outpace Data Science roles in current volume.
* **Hiring Logic:** Analysis shows hiring is driven more by business scale and immediate operational needs than company ratings alone.

## 📂 Repository Structure
```text
├── Naukri(1).ipynb    # Main Jupyter Notebook (Scraping + EDA)
├── naukri_jobs_dataset1.csv  # Raw/Cleaned Dataset
└── README.md                # Project Documentation
```
## 💡 How to Run

Follow these steps to set up the project and run the analysis on your local machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/MalayBhunia/Naukri-Jobs-Data-Analysis-Using-Web-Scraping.git](https://github.com/MalayBhunia/Naukri-Jobs-Data-Analysis-Using-Web-Scraping.git)
cd Naukri-Jobs-Data-Analysis-Using-Web-Scraping
```
### 2. Install requirements:
```bash
pip install selenium pandas matplotlib seaborn wordcloud webdriver-manager
```
### 3. WebDriver Setup
This project uses Selenium with **webdriver-manager**.
* You do not need to download ChromeDriver manually.
* The script will automatically detect and install the correct version for your Chrome browser.

### 4. Run the Analysis
* Open the Jupyter Notebook:
```bash
jupyter notebook "Naukri(1).ipynb"
```
* Step 1: Run the scraping cells to fetch live data (Note: This requires a stable internet connection).
* Step 2 & 3: Run the Data Cleaning and Visualization cells to generate insights from the scraped dataset.
---
Author: Malay Bhunia <br>
LinkedIn: https://www.linkedin.com/in/malay-bhunia-14ab712a6/ <br>
GitHub: https://github.com/MalayBhunia
