# 📈 Stock Market Dashboard

A real-time stock market analysis web application built with Python and Streamlit. Enter any stock symbol and instantly visualize price trends, key metrics, and moving averages.

---

## 🚀 Features

- 🔍 Search any stock by symbol (e.g. AAPL, TSLA, GOOGL)
- 📊 Interactive price trend chart
- 📉 20-Day Moving Average (MA20) indicator
- 💰 Live KPI cards: Current Price, Price Change, and Volume
- 🗓️ Flexible time periods: 7 days, 1 month, 3 months, 6 months, or 1 year
- 🌙 Dark mode UI with a clean purple theme

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| [Streamlit](https://streamlit.io/) | Web application framework |
| [yfinance](https://pypi.org/project/yfinance/) | Fetching real-time stock data from Yahoo Finance |
| [Pandas](https://pandas.pydata.org/) | Data manipulation and cleaning |
| [Plotly](https://plotly.com/python/) | Interactive data visualization |

---

## 📁 Project Structure

```
Current-Issues-Project/
│
├── app.py                  # Main application entry point
│
└── utils/
    ├── fetch_data.py       # Fetches stock data using yfinance
    ├── process_data.py     # Cleans and prepares the data
    └── visualize.py        # Builds the interactive Plotly chart
```

---

## ⚙️ Installation & Setup

**1. Clone the repository**
```bash
git clone https://github.com/AlyKhaled21/Current-Issues-Project.git
cd Current-Issues-Project
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the app**
```bash
streamlit run app.py
```

The app will open automatically in your browser at `http://localhost:8501`

---

## 📸 How to Use

1. Enter a stock symbol in the sidebar (e.g. `AAPL` for Apple)
2. Select the time period you want to analyze
3. View the KPI cards, price trend chart, and moving average
4. Toggle "Show Raw Data" to see the underlying data table

---

## 👤 Author

**Aly Khaled**  
GitHub: [@AlyKhaled21](https://github.com/AlyKhaled21)
