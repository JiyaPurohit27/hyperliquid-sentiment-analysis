Hyperliquid Market Sentiment Analysis

Objective
Analyze how market sentiment (Fear/Greed Index) relates to trader behavior and performance on Hyperliquid to uncover actionable trading insights.

Methodology
Cleaned and standardized timestamp formats
Removed missing/null values
Merged Hyperliquid trader dataset with Fear & Greed Index on date
Categorized sentiment into Fear, Neutral, and Greed
Calculated win rate, trade frequency, and profitability
Performed grouped and correlation analysis

Key Insights
Trader profitability varies significantly across sentiment regimes.
Extreme Greed periods show increased trading activity but inconsistent win rates.
Fear periods show more cautious behavior but relatively stable performance.
Sentiment can act as a macro-level filter for risk management.

Strategy Recommendations
Reduce exposure during extreme greed phases.
Increase selective allocation during controlled fear conditions.
Use sentiment regime as a position sizing filter.
Avoid aggressive entries during rapid sentiment transitions.

How to Run
Clone repository: git clone https://github.com/JiyaPurohit27/hyperliquid-sentiment-analysis.git
Install dependencies: pip install -r requirements.txt
Run notebook: jupyter notebook notebooks/sentiment_analysis.ipynb