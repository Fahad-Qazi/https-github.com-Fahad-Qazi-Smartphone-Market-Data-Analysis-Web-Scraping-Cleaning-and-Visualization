# 📱 Smartphone Market Data Analysis – Web Scraping, Cleaning, and Visualization

## 📌 Overview
This project demonstrates an end-to-end data pipeline for acquiring, processing, and analyzing smartphone specifications from the **Smartprix** website.  
The workflow covers **dynamic web scraping with Selenium**, **HTML parsing with BeautifulSoup**, **data cleaning & transformation using Pandas**, and **insight generation through visualization**.

---

## 🛠 Tech Stack
- **Languages:** Python  
- **Libraries & Frameworks:**  
  - Web Scraping: `Selenium`, `undetected-chromedriver`, `BeautifulSoup`, `lxml`  
  - Data Processing: `Pandas`, `NumPy`  
  - Visualization: `Matplotlib`, `Seaborn`  
- **Other Tools:** Git, GitHub  

---

## 📂 Project Workflow

### 1️⃣ Data Acquisition (Web Scraping)
- Implemented a **Selenium-based scraper** with `undetected-chromedriver` to handle JavaScript-rendered pages and bypass anti-bot detection.
- Applied **automated filters** (New Mobiles, Upcoming Mobiles) and **infinite scrolling** to dynamically load all smartphone listings.
- Captured the **entire HTML source** once all products were loaded.

### 2️⃣ Data Parsing & Extraction
- Parsed HTML using **BeautifulSoup** (`lxml` parser).
- Extracted structured smartphone attributes including:
  - Name, Price, Rating, Specs Score
  - SIM type, Processor details
  - RAM & Storage
  - Battery capacity, Display specifications
  - Camera details, OS type, Memory card support

### 3️⃣ Data Cleaning & Transformation
- Converted raw text into **analysis-ready formats**:
  - Removed currency symbols and converted prices to integers
  - Extracted numeric values for battery capacity, RAM, and storage
  - Standardized feature naming conventions
- Handled missing values and normalized data types.

### 4️⃣ Data Analysis & Visualization
- Formulated **10 analytical questions** to uncover market insights, such as:
  - Feature-to-price correlations
  - Specs score vs. price trends
  - Feature popularity (5G, NFC, AMOLED)
  - Brand-wise feature distribution
- Visualized findings with:
  - **Price distribution histograms**
  - **Correlation heatmaps**
  - **Bar charts** for brand and feature counts
  - **Scatter plots** to highlight value-for-money devices

---

## 📊 Example Insights
- Identified **top-performing smartphones** by specs score-to-price ratio.
- Found clear trends in **flagship vs. budget devices**:
  - Higher refresh rates and battery capacities in flagship models
  - Budget devices focusing on battery life over display performance
- Revealed **brand strategies** through feature combinations.

---

## 🚀 How to Run the Project

### Prerequisites
- Python 3.8 or above installed
- Google Chrome browser
- ChromeDriver (matching your Chrome version)

### Install Dependencies
```bash
pip install selenium undetected-chromedriver beautifulsoup4 lxml pandas numpy matplotlib seaborn


### Connect:
LinkedIn: https://www.linkedin.com/in/muhammadfahadqazi27/
