# Trader Behavior Analysis using Fear & Greed Index

## 📌 Overview

This project explores how market sentiment influences trader performance. I combined trading data with the Fear and Greed Index to understand how emotions in the market affect profitability and decision-making. The aim was to identify patterns in how traders behave during different market conditions such as fear, greed, and neutral phases.

## 📊 Dataset

The analysis is based on two datasets. The first contains over 200,000 trading records, and the second represents the Fear and Greed Index, which reflects overall market sentiment.

## ⚙️ Process

The project begins with loading both datasets and preparing them for analysis. During the cleaning stage, I standardized timestamp formats and simplified sentiment labels to make them easier to work with.

After cleaning, I merged both datasets using the date column so that each trade could be matched with the corresponding market sentiment. I then created a new feature called profit_flag to indicate whether a trade resulted in profit or loss.

Finally, I performed exploratory data analysis to understand how profit, win rate, and trading behavior vary across different market conditions.

## 📈 Key Insights

The analysis revealed that traders tend to generate higher profits during greedy market conditions. This suggests that bullish environments often provide better opportunities for gains.

It was also observed that sell trades perform particularly well during greedy phases, which may indicate profit-taking behavior when markets are overbought. On the other hand, buy trades show relatively better performance during fear periods, suggesting that traders may be entering positions when prices are lower.

Win rates also change depending on market sentiment, highlighting how trader psychology plays an important role in outcomes.

## 🛠️ Tech Stack

This project was implemented using Python with libraries such as Pandas for data manipulation and Matplotlib for visualization.

## 📎 Conclusion

Overall, the results show that market sentiment has a strong influence on trading performance. By understanding these behavioral patterns, traders can make more informed decisions and better adapt their strategies to different market conditions.
