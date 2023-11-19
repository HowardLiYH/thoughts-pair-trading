# WAGMI-pair-trading

![sentiment_pointer](https://crypto.news/app/uploads/2019/04/How-to-Use-Pair-Trading-As-a-Crypto-Investment-Strategy.jpg)



## Project Description:
- Explore the cryptocurrency to find delta neutral strategy on correlated tokens to scalp profit through market turbulence with the expectation that their certain qualitative correlation would be bouncing in between a set of predefined ranges.
- The assumed trading venue will be USDT-margined Perpetual Contract




## Intended Starting Period:
- Late November or Late December 2023 



## Methodology:
### 1. Dimensional Analysis
Inspired by dimensional algorithms used in NLP, as one often uses vector space models to represent words in high-dimensional spaces, where the distance or angle between vectors can represent semantic similarity. For pair trading, a similar approach could involve representing financial instruments as vectors in a multi-dimensional space based on various attributes like price movement, volatility, or other financial indicators. By analyzing the distance or relationship between these vectors, one could potentially identify pairs of tokens that exhibit a suitable level of correlation or divergence for pair trading strategies, such as longing for one asset and shorting the other. This strategy can provide a comprehensive understanding of market dynamics, and, with proper risk management, it will become a valuable tool in a trader's arsenal.
  - Construct a wide range of factors including Market Capitalization, 24h volume, long-short ratio, OI volume, funding rate, price std correlated to Bitcoin, Liquidity Levels etc
  - Use Euclidean distance / Cosine Similarity (essentially similar) to explore correlated pairs
  - Apply PCA to highlight the most important factors
  - K-nearest neighbors, hash tables, etc?
  - TBD

### 2. Mean Reversion
A relative strength strategy in pair trading involves comparing the performance of two similar assets (like cryptocurrencies or stocks) to identify which one is stronger and which one is weaker. The strategy then involves taking a long position in the underperforming asset (betting it will go up) and a short position in the outperforming asset (betting it will go down). The idea is that the relative performance will eventually revert to the mean, allowing for profit from both positions. This strategy is particularly useful in range-bound or sideways markets and aims to be market-neutral, reducing exposure to broader market movements.

**Potential Factors:** Price std, 24h volume, Market Capitalization, Moving Average, News and Market Sentiment, Seasonality and Cycles, Historical Performance, long-short ratio, OI volume, funding rate, Liquidity Levels, token-specific news


### 3. Trend Following 
Trend following in pair trading is a strategy where traders identify pairs of tokens that have shown strong and sustained trends. Traders take positions in these pairs based on the direction of their trends—long positions in assets that are trending upwards, and short positions in those trending downwards. The key idea is that once a trend is established, it's likely to continue due to underlying market momentum or investor sentiment. This strategy requires careful monitoring to identify when a trend is starting to weaken, signaling a potential exit point to maximize gains or minimize losses.

**Potential Factors:** Price std, 24h volume, Market Capitalization, Moving Average, News and Market Sentiment, Seasonality and Cycles, Historical Performance, long-short ratio, OI volume, funding rate, Liquidity Levels, token-specific news




  
