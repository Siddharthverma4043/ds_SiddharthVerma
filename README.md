# Web3 Trading Team - Data Science Assignment  

## Candidate: Siddharth Verma  

---

## 📌 Project Overview  

This project analyzes the relationship between **Bitcoin trader behavior** and **market sentiment** using two datasets:  
- **Bitcoin Market Sentiment (Fear & Greed Index)**  
- **Historical Trader Data from Hyperliquid**  

The objective is to explore how trading metrics such as **profitability, trade volume, and leverage** vary with market sentiment, and to uncover hidden patterns that can guide smarter trading strategies.  

---

## 📂 Directory Structure  

ds_SiddharthVerma/
├── notebook_1.ipynb
├── notebook_2.ipynb
├── csv_files/
│ ├── fear_greed_index.csv
│ ├── historical_data.csv
│ └── merged_trader_sentiment_daily.csv
├── outputs/
│ ├── daily_net_pnl.png
│ ├── netpnl_by_sentiment.png
│ ├── avg_leverage_by_sentiment.png
│ └── ... (all other saved plots)
├── ds_report.pdf
└── README.md


---

## ▶️ How to Run  

1. Open the notebooks in **Google Colab** using the links below:  
   - [Notebook 1: Data Loading, Cleaning, and Initial EDA](https://colab.research.google.com/drive/1HKtvGsDT4vRHtdn2Ntv77_qpbx6U9_7B?usp=sharing)  
   - [Notebook 2: Data Merging and Advanced Analysis](https://colab.research.google.com/drive/1n_JZichnPfJ_LpRlH8cnLQqVpUWjeYS8?usp=sharing)  
 
2. Ensure the required CSV files are placed in the `csv_files/` directory or uploaded to Colab when prompted.  
3. Run the notebook cells sequentially to reproduce the **analysis and visualizations**.  
4. Generated plots are automatically saved in the `outputs/` folder.  

---

## 📊 Key Insights  

- **Market sentiment strongly influences trader profitability and trade volume.**  
- **Greed phases** → higher profits and more trades, but also riskier leverage.  
- **Fear phases** → reduced profitability, potential panic-driven trading.  
- Sentiment momentum: Previous day’s sentiment can indicate next day outcomes.  
- Statistical tests confirm **significant differences** in trading behavior across sentiment states.  

---

## 🛠️ Technologies Used  

- **Python 3**  
- **Pandas, NumPy** → Data manipulation  
- **Matplotlib, Seaborn** → Visualization  
- **SciPy** → Statistical testing  
- **Google Colab** → Notebook execution environment  

---

## 📄 Notes  

- All notebooks are shared with *“Anyone with the link can view”* access.  
- Please refer to **`ds_report.pdf`** for a detailed analysis, insights, and conclusions.  

---

