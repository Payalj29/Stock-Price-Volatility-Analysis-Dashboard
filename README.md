# Stock Price & Volatility Analysis Dashboard

## Project Overview

This project presents an end-to-end stock market analysis dashboard built using Python and Power BI.
It analyzes historical stock data to identify trends, volatility patterns, and short-term market behavior using key financial indicators.

---

## Objective

To analyze stock price movements and generate actionable insights by evaluating:

* Price trends over time
* Daily returns (profit/loss)
* Market volatility
* Moving average trends

---

## Tools & Technologies Used

* Python
* Pandas
* Power BI

---

## Project Workflow

1. **Data Collection**

   * Stock data fetched using Python (`yfinance` API)

2. **Data Processing**

   * Cleaned and transformed data using Pandas
   * Created new analytical columns:

     * Daily Return (%)
     * Moving Averages (MA_5, MA_10)
     * Volatility (High - Low)

3. **Data Visualization**

   * Built an interactive dashboard in Power BI

---

## Dashboard Features

### Stock Price Trend

* Visualizes price movement over time
* Helps identify overall trend direction

### Moving Average Analysis

* Compares short-term and medium-term trends
* Detects potential bullish or bearish signals

### Daily Returns

* Highlights profit and loss days
* Uses conditional formatting (Green = Profit, Red = Loss)

### Volatility Analysis

* Measures daily price fluctuations
* Identifies high-risk trading periods

### KPI Metrics

* Maximum Closing Price
* Minimum Closing Price
* Average Trading Volume

---

## Key Insights

* Significant volatility spike observed around April 6 indicates strong market uncertainty and selling pressure
* Stock exhibits a gradual recovery trend after mid-month decline, indicating potential bullish reversal
* Moving averages suggest emerging short-term bullish momentum
* Price consistently remained above MA_5 in the last week, indicating strengthening upward trend
* Volatility decreased after initial spike, suggesting market stabilization before upward movement

---

## Dashboard Preview

(Added Power BI dashboard screenshot)

---

## Project Structure

```
├── data/
│   └── stock_data_updated.csv
├── scripts/
│   └── data_processing.py
├── dashboard/
│   └── stock_dashboard.pbix
└── README.md
```

---

## How to Run

1. Clone the repository
2. Install required Python libraries:

   ```
   pip install pandas yfinance
   ```
3. Run the Python script to fetch and process data
4. Open the `.pbix` file in Power BI to view the dashboard

---

## Future Improvements

* Add real-time data integration
* Compare multiple stocks
* Implement predictive modeling
* Add alert system for price spikes

---

## Conclusion

This project demonstrates the ability to:

* Work with real-world financial data
* Perform data cleaning and feature engineering
* Build interactive dashboards
* Generate business insights from data

---

## Author

Payal Jagtap

---
