# ds_Bilal_Ahmad

## Overview
This project analyzes **trading performance** across various **market sentiments**, **trader types** (whale vs. retail), **strategies** (long vs. short), and **leverage levels**.  
It uses historical market data and sentiment indexes to extract actionable insights for traders.
Google Collab Link: https://colab.research.google.com/drive/175-XoZwIObrE60yilb3Be5ugO1kTJS9_?usp=sharing

The analysis includes:
- Profitability trends by market sentiment
- Whale vs retail performance comparison
- Strategy profitability in different market moods
- Impact of leverage on trade outcomes
- Data visualizations for all metrics

---

## 📂 Project Structure
```
ds_Bilal_Ahmad/
│
├── csv_files/ # Raw input datasets
│ ├── fear_greed_index.csv
│ ├── historical_data.csv
│
├── outputs/ # Generated visualizations
│ ├── long vs short corr by sentiments.png
│ ├── profit vs leverage and sentiment.png
│ ├── profit vs sentiment.png
│ ├── whale vs retail.png
│
├── Prime Trade.ipynb # Main analysis notebook
├── prime_trade_report.pdf # PDF report of findings
├── README.md # Project documentation
```




## 🚀 How to Run
Clone this repository:
   ```
   git clone https://github.com/bilalahmad0210/ds_Bilal_Ahmad.git
   cd ds_Bilal_Ahmad
   ```
```
pip install pandas matplotlib seaborn
```
```
jupyter notebook "Prime Trade.ipynb"
```

##📜 Report
A full professional report is available in prime_trade_report.pdf, containing:

Data-driven insights

Charts and explanations

Key trading recommendations
