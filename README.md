# S&P 500 Historical Data Analysis

This repository provides an end-to-end exploratory data analysis (EDA) and trend analysis of the S&P 500 stock market index using five years of historical data.

## Project Overview
The project leverages a dataset of 505 companies listed in the S&P 500 to uncover market trends, identify high-volume trading days, and visualize the performance of tech giants like Apple, Amazon, and Google.

### Key Features
* **Automated Data Ingestion:** Uses `kagglehub` to download the most recent S&P 500 dataset (`camnugent/sandp500`).
* **Market-Wide Statistics:** Identifies the unique companies in the index and ranks them by trading volume.
* **High-Impact Analysis:** pinpoints specific dates of historical significance, such as the highest volume trading days for major corporations like Verizon and GE.
* **Stock-Specific Deep Dives:**
    * **Apple (AAPL):** Performance overview across 1,259 data points.
    * **Amazon (AMZN):** Analysis of "milestone" dates where the stock closed above $1,000.
    * **Google (GOOGL):** Time-series visualization of closing prices over the 5-year period.

## Dataset Information
The analysis is based on the `all_stocks_5yr.csv` dataset, which contains:
* **Date:** Trading date.
* **Open/High/Low/Close:** Daily price movements.
* **Volume:** Number of shares traded.
* **Name:** The stock ticker symbol (e.g., AAPL, AMZN).

## Getting Started

### Prerequisites
You will need Python 3.x and the following libraries:
```bash
pip install pandas numpy matplotlib kagglehub
```

### Usage
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/2BerbyMarty2/sp500-historical-data.git
    cd sp500-historical-data
    ```
2.  **Run the analysis:**
    Open the Jupyter Notebook to execute the cells:
    ```bash
    jupyter notebook Trend_analysis_on_S&P_500_stock_data.ipynb
    ```

## Key Insights from Analysis
* **Volume Peaks:** The analysis identified February 24, 2014, as a significant high-volume day, specifically for Verizon (VZ) with over 618 million shares traded.
* **Price Milestones:** Amazon (AMZN) first crossed the $1,000 closing mark in June 2017, maintaining that level for 95 days within the dataset's range.
* **Growth Trends:** Google's (GOOGL) stock showed a steady upward trajectory over the 5-year period, effectively visualized through Matplotlib time-series plots.

## Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib
* **Data Source:** Kaggle API (`kagglehub`)

