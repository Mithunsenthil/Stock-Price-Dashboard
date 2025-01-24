# Stock Price Dashboard

## Overview

The **Real-Time Stock Price Dashboard**, built with **Streamlit** and **yfinance**, provides real-time stock data for major Nifty 50 companies. Users can select a stock, set a time interval (ranging from minutes to years), and explore stock price trends, key metrics, and more. The dashboard combines interactivity with insightful visualizations for stock analysis.

---

## Features

- **Stock Selection**: Pick from a dropdown of Nifty 50 stocks or manually enter a stock ticker.
- **Customizable Time Intervals**: Analyze stock data over various durations (e.g., 1 minute, 1 day, 1 month, up to 5 years).
- **Real-Time Stock Overview**: Get key details such as:
  - Company Name
  - Sector
  - Market Capitalization
  - Open, Close, High, Low, and Volume data
- **Interactive Line Chart**: Visualize closing price trends over the selected time period.
- **Stock Data Table**: Review comprehensive stock data for further analysis.

---

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/stock-price-dashboard.git
cd stock-price-dashboard
```

### 2. Set up a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # For Windows: `venv\Scripts\activate`
```

### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

1. **Run the app**:  
   Start the dashboard using the command:  
   ```bash
   streamlit run app.py
   ```

2. **Interact with the app**:
   - **Stock Selection**: Choose a stock (e.g., TCS.NS) from the dropdown or enter a ticker.
   - **Time Interval**: Set a duration (e.g., 1 year or 3 years).
   - **View Data**: Access key metrics, detailed stock information, and interactive visualizations.

---

## Technologies Used

- **Frontend**: Streamlit for web-based interactivity.
- **Backend**: yfinance for fetching real-time stock data.
- **Data Analysis**: pandas for data processing and manipulation.
- **Visualization**: Streamlit’s plotting capabilities for charts and tables.

---
