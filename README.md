# 📊 NVIDIA Stock Trend Analysis and Insights

This project dives into historical daily stock data for NVIDIA Corporation, analyzing over two decades of market activity. The goal is to extract meaningful insights through exploratory data analysis, feature engineering, and trend visualization.

---

## 📁 Project Structure

```
Nvidia-Stock-Analysis/
├── data/                      # Raw and processed datasets
│   └── Nvidia_stock_data.csv
├── notebooks/                 # Jupyter notebooks with all code
│   └── Nvidia_Stock_Analysis_Complete.ipynb
├── images/                    # Charts and figures for insights
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies
```

---

## 🎯 Project Objectives

- Clean and preprocess raw stock market data.
- Perform detailed exploratory data analysis (EDA).
- Engineer features such as moving averages and volatility.
- Visualize price and volume trends over time.
- Identify key performance insights across different years.
- Analyze seasonal patterns and market behavior.

---

## 🧮 Key Features Created

| Feature            | Description |
|--------------------|-------------|
| `Daily Range`      | Difference between daily high and low |
| `Price Change %`   | Percent change from open to close |
| `MA_7 / MA_30 / MA_90` | Moving averages for trend smoothing |
| `Volatility_30`    | 30-day rolling standard deviation |
| `Year`             | Extracted from the date for YOY analysis |

---

## 📊 Exploratory Data Analysis (EDA)

The notebook explores:
- Line plots of daily closing prices and volumes.
- Correlation heatmaps of numeric features.
- Moving average overlays to understand smoothed trends.
- Monthly and yearly aggregation to detect patterns.

### 📌 Sample Visualizations
- 📈 NVIDIA stock price from 1999–present
- 📉 Trading volume over time
- 📊 Heatmap showing correlation between price/volume metrics
- 📆 Year-over-year average returns

---

## 🔍 Key Insights

- 📈 **Highest Close Price**: Detected and visualized.
- 📉 **Lowest Close Price**: Identified historically.
- 💹 **Biggest One-Day Gain/Drop**: Based on price change %.
- 📊 **Yearly Return Trends**: Which years performed best?
- 🔁 **Volatility Analysis**: When was the market most volatile?

---

## 🛠 Technologies Used

- **Python 3.8+**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Jupyter Notebook** – Interactive analysis

---

## 📬 Contact

**Author:** NISHANT 
**LinkedIn:**(https://www.linkedin.com/in/nishant-singh-2684901a5/)

---

## 📄 License

This project is licensed under the MIT License.
