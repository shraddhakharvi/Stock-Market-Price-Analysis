# Stock-Market-Price-Analysis
# 📂 Project Overview
## This project scrapes, processes, and analyzes historical stock market data to track trends, volatility, and performance over time. The data is then visualized using Power BI for better insights.

# 📑 Project Workflow
## 1️⃣ Web Scraping
### Source: Alpha Vantage API
### Tools Used: requests, BeautifulSoup, Selenium (if needed), pandas
## Data Collected:
#### Date
#### Open Price
#### High Price
#### Low Price
#### Close Price
#### Volume

## 2️⃣ Data Cleaning & Processing
### Remove missing values
### Convert Date column to datetime format
### Compute daily percentage change
### Save the cleaned data as a CSV file (stock_data.csv)

## 3️⃣ Power BI Visualization
### Visuals Created:

#### Stock Price Trend Over Time → Line Chart
#### Stock Price Distribution → Column Chart
#### Trading Volume Over Time → Area Chart
#### Open vs. Close Price Comparison → Clustered Column Chart
#### Daily Percentage Change → Area Chart

# ⚙️ Setup & Installation
### 🔹 Prerequisites

pip install pandas requests beautifulsoup4 selenium matplotlib seaborn yfinance

# 📜 Running the Script
python AAPL_stock_data.py

# 📊 Power BI Report Steps
#### Open Power BI Desktop
#### Click "Get Data" → "Text/CSV" and import stock_data.csv
#### Clean data in Power Query
#### Create visualizations as described in the project workflow

# 📌 Future Enhancements
#### Automate daily stock data updates
#### Add technical indicators (e.g., Moving Averages, RSI)
#### Predict future stock prices using Machine Learning

# 📞 Contact & Support
For any questions, feel free to reach out! 🚀📊
7829981526 , Shraddhakharvi2024@gmail.com
