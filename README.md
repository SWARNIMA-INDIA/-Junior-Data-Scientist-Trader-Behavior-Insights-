# 📊 Trader Behavior Analysis vs Market Sentiment

## 📌 Overview
This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance.  
The goal is to identify patterns and derive actionable insights that can improve trading strategies.

---

## 📂 Datasets Used

1. **Bitcoin Market Sentiment Dataset**
   - Columns: Date, Classification (Fear/Greed/Neutral)

2. **Historical Trader Data**
   - Includes: Account, Execution Price, Size, Side, Closed PnL, Timestamp, etc.

---

## ⚙️ Project Workflow

### 1. Data Preparation
- Loaded and explored both datasets  
- Checked for missing values and duplicates  
- Converted timestamps into datetime format  
- Extracted date for alignment  
- Merged datasets on date  

---

### 2. Feature Engineering
Created key metrics:
- Daily PnL per trader  
- Win/Loss indicator  
- Average trade size  
- Trade frequency  
- Long/Short distribution  

---

### 3. Analysis

#### 🔹 Performance vs Sentiment
- Compared PnL and win rate across Fear and Greed  

#### 🔹 Behavior Analysis
- Trade frequency  
- Trade size differences  
- Buy/Sell patterns  

#### 🔹 Segmentation
- Frequent vs Infrequent traders  
- Winners vs Losers  
- High vs Low trade size  

---

## 📊 Key Insights

- Traders tend to perform better during **Greed periods**  
- Larger trade sizes are observed during **Fear**, indicating higher risk-taking  
- Frequent traders generate higher overall profit compared to less active traders  

---

## 💡 Strategy Recommendations

1. **Risk Control During Fear**
   - Reduce trade size to minimize losses  
   - Avoid aggressive trading decisions  

2. **Active but Controlled Trading in Greed**
   - Increase trading activity  
   - Maintain disciplined position sizing  

---

## 📈 Visualizations
The project includes:
- PnL distribution by sentiment  
- Trade size comparison  
- Trade frequency analysis  
- Trader segmentation plots  

---

## 🔧 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🎯 Conclusion
Market sentiment plays a crucial role in influencing trader behavior and performance.  
Understanding these patterns helps in designing better, risk-aware trading strategies.
