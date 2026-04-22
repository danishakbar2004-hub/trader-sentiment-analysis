# Trader Behavior Analysis using Fear & Greed Index

## 🚀 Project Highlights

* Analyzed over 200,000 trading records to study market behavior
* Built a complete data pipeline including cleaning, merging, and analysis
* Derived insights on how market sentiment impacts trader performance

---

## 📌 Overview

This project explores how market sentiment influences trader performance. It combines trading data with the Fear and Greed Index to understand how emotions in the market affect profitability and decision-making.

The goal is to identify patterns in how traders behave under different market conditions such as fear, greed, and neutral phases.

---

## 📊 Dataset

The analysis uses two datasets. The first contains over 200,000 trading records, and the second represents the Fear and Greed Index, which reflects overall market sentiment.

---

## ⚙️ Process

The project begins by loading both datasets and preparing them for analysis. During the data cleaning stage, timestamp formats are standardized and sentiment labels are simplified for consistency.

Once the data is cleaned, both datasets are merged using the date column so that each trade is aligned with the corresponding market sentiment. A new feature called `profit_flag` is then created to indicate whether a trade resulted in profit or loss.

Finally, exploratory data analysis is performed to understand how profit, win rate, and trading behavior vary across different market conditions.

---

## 📈 Key Insights

The analysis shows that traders tend to generate higher profits during greedy market conditions, suggesting that bullish environments often provide better opportunities.

Sell trades perform particularly well during greed phases, which may indicate profit-taking behavior when markets are overbought. In contrast, buy trades perform relatively better during fear periods, suggesting that traders may be entering positions at lower prices.

Win rates also vary across market sentiment, highlighting how trader psychology plays an important role in trading outcomes.

---

## 🛠️ Tech Stack

This project was implemented using Python, with Pandas for data manipulation and Matplotlib for visualization.

---

## 📎 Conclusion

The results demonstrate that market sentiment has a strong influence on trading performance. By understanding these behavioral patterns, traders can make more informed decisions and adapt their strategies to different market conditions.
