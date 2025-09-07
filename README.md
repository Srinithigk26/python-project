

# 📈 Stock Data Fetcher & Visualizer

A simple Python project to **fetch stock market data**, **save it to CSV**, and **plot stock prices** using [Yahoo Finance API](https://pypi.org/project/yfinance/).

---

## 🚀 Features

* Fetches stock data for a given **ticker symbol** (default: `AAPL`)
* Retrieves stock history for a given **date range**
* Saves data to a **CSV file**
* Plots the **closing price trend** using `matplotlib`

---

## 🛠️ Technologies Used

* [yfinance](https://pypi.org/project/yfinance/) – Fetch stock data
* [pandas](https://pandas.pydata.org/) – Data manipulation
* [matplotlib](https://matplotlib.org/) – Data visualization
* [datetime](https://docs.python.org/3/library/datetime.html) – Date handling

---

## 📂 Project Structure

```
├── stock_data_fetcher.py   # Main Python script
├── AAPL_stock_data.csv     # Generated CSV file (after running)
└── README.md               # Project documentation
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/stock-data-fetcher.git
   cd stock-data-fetcher
   ```

2. Install required dependencies:

   ```bash
   pip install yfinance pandas matplotlib
   ```

3. Run the script:

   ```bash
   python stock_data_fetcher.py
   ```

---

## 📊 Example Output

### Sample Data (CSV Preview)

```
                 Open       High        Low      Close   Volume
Date                                                          
2025-08-08  228.429993  229.979996  227.399994  229.000000  46308100
2025-08-09  229.509995  231.000000  228.199997  230.899994  42325600
...
```

### Plot Output

The program generates a line chart showing the **Closing Price Trend** of the stock for the last 30 days.

---

## 🔮 Future Improvements

* Add support for **multiple ticker symbols** at once
* Include **moving averages** and other technical indicators
* Build an interactive **dashboard with Streamlit**
* Automate **daily stock data updates**

---

## 👨‍💻 Author

Developed by SRINITHI G K ✨
Feel free to fork, improve, and use this project!

