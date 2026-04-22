## 🔗 View Notebook
[Click here to view the analysis](./trader_behavior_analysis.ipynb)
# Trader Behavior Analysis using Fear & Greed Index

## 🚀 Project Highlights

* Analyzed over 200,000 trading records to study trader behavior under different market conditions
* Built an end-to-end data pipeline including data cleaning, merging, and exploratory analysis
* Derived insights on how market sentiment impacts profitability, win rate, and trade direction

---

## 📌 Overview

This project analyzes how market sentiment influences trader performance. It combines trading data with the Fear and Greed Index to examine how emotions in the market affect profitability and decision-making.

The objective is to identify patterns in trader behavior across different market conditions such as fear, greed, and neutral phases.

---

## 📊 Dataset

The analysis is based on two datasets. One contains over 200,000 trading records, while the other represents the Fear and Greed Index, which reflects overall market sentiment.

---

## ⚙️ Process

The project begins with loading both datasets and preparing them for analysis. During the data cleaning stage, timestamp formats are standardized and sentiment labels are simplified to ensure consistency.

Once cleaned, the datasets are merged using the date column so that each trade is aligned with the corresponding market sentiment. A new feature called `profit_flag` is created to indicate whether a trade resulted in profit or loss.

Exploratory data analysis is then performed to evaluate how profit, win rate, and trading behavior vary across different market conditions.

---

## 📈 Key Insights

The analysis shows that traders tend to generate higher profits during greedy market conditions, indicating that bullish environments often provide better opportunities.

Sell trades perform particularly well during greed phases, suggesting profit-taking behavior when markets are overbought. In contrast, buy trades perform relatively better during fear periods, indicating accumulation strategies when prices are lower.

Win rates also vary across market sentiment, highlighting the strong influence of trader psychology on performance.

---

## 🛠️ Tech Stack

This project was implemented using Python, with Pandas for data manipulation and Matplotlib for visualization.

---

## 📎 Conclusion

The results demonstrate that market sentiment has a significant impact on trading performance. Understanding these behavioral patterns can help traders make more informed decisions and adapt their strategies to different market conditions.
This project demonstrates how behavioral finance and market sentiment can be leveraged to improve trading strategies using real-world data.
