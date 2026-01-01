Indian Stock Market Dataset (BEL.NS & IITL.NS) – 2014 to 2024
📌 Overview

This repository contains historical daily stock market data for two Indian companies listed on the National Stock Exchange (NSE), India:

BEL.NS – Bharat Electronics Limited

IITL.NS – Indian Infotech and Software Limited

The dataset spans January 2014 to December 2024 and is intended for financial analysis, time-series modeling, and machine learning research.

📊 Dataset Description

Each dataset is provided in CSV format and includes the following attributes:

Column	Description
Date	Trading date
Open	Opening price (INR)
High	Highest price of the day (INR)
Low	Lowest price of the day (INR)
Close	Closing price (INR)
Adj Close	Adjusted closing price (INR)
Volume	Number of shares traded

Frequency: Daily (excluding weekends and NSE holidays)

Currency: Indian Rupees (INR)

🏢 Companies Covered

Bharat Electronics Limited (BEL.NS): A leading public sector enterprise in defense electronics.

Indian Infotech and Software Limited (IITL.NS): A small-cap company operating in IT and financial services.

The combination enables comparative analysis across different market capitalizations and volatility profiles.

📁 Repository Structure
Indian-Stock-Market-Dataset
│
├── data
│   ├── BEL.NS_2014_2024.csv
│   └── IITL.NS_2014_2024.csv
│
└── README.md

🔍 Data Source

The data was collected from publicly available financial sources such as Yahoo Finance, using official NSE ticker symbols.

🧠 Potential Use Cases

Stock price trend analysis

Time-series forecasting (ARIMA, LSTM, GRU, Transformers)

Volatility and risk analysis

Algorithmic trading research

Financial data exploration and visualization

Academic and educational projects

⚙️ Preprocessing Notes

No normalization or feature engineering applied

Missing dates correspond to non-trading days only

Ready for direct use in ML/DL pipelines

📜 License & Disclaimer

This dataset is provided for educational and research purposes only.
It does not constitute financial or investment advice. Users should verify data accuracy before real-world usage.
