# CryptoTrader-Behavior-Study
Analyzing trader behavior vs Bitcoin market sentiment (Fear/Greed). Includes Colab notebooks, processed datasets, visual outputs, and a summary report.

##  Project Overview
This project analyzes the relationship between **trader behavior** and **market sentiment** (Fear, Neutral, Greed, Extreme Greed, Extreme Fear).  
Using Bitcoin sentiment data and Hyperliquid trader activity, the goal is to identify **profitability, volume, risk, and participation patterns** across different market moods.

---

##  Directory Structure
ds_<yourname>/<br>
├── notebook_1.ipynb # Main analysis notebook (Google Colab)<br>
├── csv_files/ # Raw & processed CSV files<br>
│ └── merged_trader_sentiment.csv<br>
├── outputs/ # Visual outputs (plots, charts)<br>
├── ds_report.pdf # Final summarized report<br>
└── README.md # Project description & instructions<br>


---

## Key Findings
- **Profitability:** No consistent improvement during Greed phases; overextension often reduces profits.  
- **Volume:** Total traded volume tends to decrease with high greed, even though individual trade sizes grow.  
- **Active Accounts:** Fewer traders participate in extreme greed, but they place larger trades.  
- **Risk Behavior:** Extreme Greed produces volatile profits and losses, while Extreme Fear results in minimal activity.  
- **Correlation:** Sentiment index shows **no strong link with profitability** but a **negative relationship with trading volume**.  

---

## How to Run
1. Open `DSTask.ipynb` in **Google Colab** [Click here] (https://colab.research.google.com/drive/10rjFij8IXhAZi8Nt766s3NMxGAq53fVB?usp=sharing) to view the colab notebook itself.  
2. Make sure datasets are in `/csv_files/`.  
3. Run all cells to reproduce outputs in `/outputs/`.  
4. Final insights are compiled in `ds_report.pdf`.  

---

## Dataset Links
- [Historical Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)  
- [Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)  

---

##  Contact
For any questions, reach out at: `aayushagashe@gmail.com`  
