# 📈 Extracting and Visualizing Stock Data

This project is a comprehensive Jupyter Notebook assignment that walks through the process of retrieving, cleaning, analyzing, and visualizing stock market data. It demonstrates practical data science skills by working with real-time stock data using the `yfinance` API and web scraping techniques using `BeautifulSoup`. It also includes insightful data visualization using `plotly`.

The notebook is part of IBM’s Skills Network Data Science course, designed to build hands-on experience with data wrangling, analysis, and interactive plotting in Python.

---

## 🧠 Objective

To extract historical stock data for a list of companies, process it using data analysis techniques, and visualize key trends and patterns that could be useful for financial decision-making or investment research.

---

## 🔍 Key Components

### 1. **Data Extraction**
- Download historical stock data using the `yfinance` Python library.
- Extract data for companies like Tesla, Apple, and GameStop.
- Use `requests` and `BeautifulSoup` to scrape financial news or company info from the web.

### 2. **Data Cleaning & Structuring**
- Convert raw datasets into structured formats using `pandas`.
- Align and merge datasets from different sources.
- Handle missing values and time-based indexing for accurate time series analysis.

### 3. **Data Analysis**
- Compare stock performance across multiple companies.
- Calculate daily returns and cumulative returns.
- Identify key trends in price movement, volatility, and volume.

### 4. **Data Visualization**
- Generate interactive plots using `plotly` and `plotly.graph_objects`.
- Create subplots for open, close, high, and low prices.
- Use line charts, candlestick charts, and area plots to communicate insights.

---

## 🛠️ Technologies Used

| Tool/Library       | Purpose                             |
|--------------------|-------------------------------------|
| `yfinance`         | Historical stock price extraction   |
| `pandas`           | Data manipulation and analysis      |
| `BeautifulSoup`    | Web scraping                        |
| `plotly`           | Interactive visualization           |
| `Jupyter Notebook` | Environment for analysis and plotting |

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have the following libraries installed:

```
pip install yfinance pandas plotly beautifulsoup4
▶️ How to Run
Clone the repository:


git clone https://github.com/yourusername/stock-data-visualization.git
cd stock-data-visualization
Open the notebook:


jupyter notebook "Final Assignment.ipynb"
Run all cells to generate stock data and visualizations.

📊 Sample Output
Here are a few types of charts included in the notebook:

📉 Line Plot of closing stock prices over time

📊 Bar Plot comparing trading volume

🕯️ Candlestick Chart for daily open-high-low-close prices

📚 Learning Outcomes
By completing this notebook, you'll gain hands-on experience with:

Using APIs for real-time data extraction.

Web scraping fundamentals with BeautifulSoup.

Time-series data analysis with pandas.

Visual storytelling using plotly.

🧾 License
This project is part of IBM Skills Network coursework and is intended for educational purposes.

---
