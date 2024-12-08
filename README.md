![Modern Business Trading Investment Instagram Post](https://github.com/user-attachments/assets/adc18c1c-a4f2-465b-86b6-7f0935d474b3)

# Introduction

My goal with this project is to deeply understand the dynamics of the stock market and provide insights that help investors make more informed decisions. By analyzing 20 years of historical Google stock data, I aim to uncover trends, measure volatility, and predict future price movements using advanced machine learning techniques. This analysis is designed to deliver actionable insights that enhance investment and trading strategies.

## Goal

The primary objective of my project is to predict Google’s future stock prices based on historical data. Leveraging advanced algorithms such as Long Short-Term Memory (LSTM) models, I aim to identify patterns and trends that guide investment decisions and minimize risks. By doing so, my goal is to empower investors and traders to make data-driven decisions with confidence.

### Methodology

**1. Data Source:**
 
- I worked with 20 years of Google stock data, including daily opening, closing, high, and low prices, along with trading volumes.
- The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/coderpanda010/google-stock-data-20-years): Google Stock Data 20 Years. 

**2. Data Preparation:**

- I processed raw data by handling missing values and removing anomalies.
- The data was scaled and transformed into time-series sequences to ensure compatibility with LSTM models.


**3. Baseline Models:**

- I started with basic machine learning models like Linear Regression and Random Forest to establish initial benchmarks for performance.

**4. Advanced Modeling:**

- To capture complex temporal patterns, I implemented LSTM models and optimized them using hyperparameter tuning and callback methods such as EarlyStopping.

**5. Evaluation and Visualization:**

- I evaluated my models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R².

- I visualized predictions alongside actual stock prices to provide clear insights into model performance.

### Scope

This project helped me develop a strong understanding of stock market analysis. I believe it can be especially useful for investors and traders in the following areas:

**Identify Historical Trends**  Gaining insights into long-term and short-term market movements.

**Anticipate Volatility**  Predicting price fluctuations to minimize risks.

**Enhance Strategies:** Using data-driven insights to optimize investment and trading strategies.

The methods and analyses I developed in this project bridge the gap between technical analysis and actionable financial strategies. This allows for a robust tool to understand Google stock behavior and predict future price movements effectively.
### Key Benefits for Investors and Traders:
- **Optimized  Timing**: Gain insights into high-liquidity periods (e.g., December) for executing trades efficiently.
- **Risk  Mitigation**: Use volatility trends and event-based analysis to prepare for potential market fluctuations.
- **Strategic  Planning**: Leverage historical patterns to predict future behavior, aiding in buy/sell/hold decisions.

This analysis equips investors with the tools to minimize risks and maximize returns by aligning their strategies with historical market patterns and predictive analytics. Whether you are a risk-averse trader or a long-term investor, these insights provide the confidence to make data-driven decisions in a dynamic stock market environment.

## Descriptive Analysis Questions and Results:


1. What is the overall trend in Google stock closing prices over the years?

- Google stock showed an upward trend in closing prices from 2004 to 2024, with some fluctuations during financial crises like 2008 and 2020.
- Visualizations like line charts highlighted these trends and demonstrated periods of rapid growth (e.g., post-2015).
 
2 .Which months exhibit the highest trading volume?

- December consistently had the highest trading volumes, likely due to end-of-year market activities and portfolio adjustments.
- Boxplots and bar charts helped identify these monthly patterns.

3. What is the relationship between daily high and low prices?

- Daily high and low prices showed a strong positive correlation (r ≈ 0.99), as expected in a consistent market.
- This finding was validated using scatterplots.

4. How does the trading volume vary over different years?

-Trading volumes were highest during market crises and tech booms, with significant spikes in 2008, 2020, and 2023.
-Year-over-year bar charts effectively communicated these patterns.

5. Are there any significant outliers in trading volume or stock prices?

- Several outliers in trading volume were observed, corresponding to major market events or earnings announcements. These were detected using boxplots.

7. What is the average daily price change across years?

- Average daily price changes were highest during volatile years like 2008 and 2020, indicating market uncertainty.
- A detailed table of yearly averages was presented for clarity.

## Inferential Analysis Questions

1. Are closing prices significantly different between two periods (e.g., before and after 2015)?

- A two-sample t-test revealed significant differences in closing prices before and after 2015 (p<0.05).

- The mean closing price post-2015 was substantially higher, reflecting Google’s growth as a major tech giant.

2. Is there a significant relationship between trading volume and price volatility?

- A Pearson correlation test indicated a moderate positive relationship (𝑟=0.35), suggesting that higher volatility often corresponds to increased trading volume.

- This insight was visualized through scatterplots and regression lines.

3. Are stock prices significantly more volatile during specific months?

- An ANOVA test showed significant differences in monthly stock price volatility (p<0.05).
- March and November had the highest volatility, while July and August were more stable. This finding can guide investors in timing their trades.

4. Does trading volume vary significantly across years or months?

- Tukey HSD post hoc tests confirmed significant differences in trading volumes across both years and months.
- December consistently showed higher trading volumes compared to other months, as depicted in heatmaps and summary tables.

5. Do stocks exhibit higher volatility after large trading volumes?

- A t-test revealed that days with higher trading volumes experienced significantly higher volatility (p<0.05).

- This finding emphasizes the importance of monitoring trading volume as an indicator of risk.

6. Is there a significant difference in trading volume between months?

- ANOVA results indicated that trading volumes vary significantly across months (p<0.05).

- Tukey HSD tests identified December as having significantly higher trading volumes compared to most other months.

7. Does the volatility in Google stock significantly differ during market crashes?

A t-test comparing crash periods (2008, 2020) with non-crash periods showed significantly higher volatility during crashes (p<0.05).

- Density plots illustrated these differences, showing increased risk during economic downturns.
# Key Insights and Recommendations

### Trading Volume Trends:

December stands out as a high-volume month, potentially driven by end-of-year trading activities. Investors may capitalize on liquidity during this time.

### Volatility Insights:

Volatility spikes during market crashes (2008, 2020) and specific months (March, November). Traders should exercise caution and consider hedging strategies during these periods.

### Significant Differences Across Periods:

Stock prices and trading volumes exhibit significant differences over time, influenced by market events and economic conditions. Long-term investors should prioritize stable periods for safer investments.

### Practical Applications:

Insights from this analysis can inform investment strategies, particularly in terms of timing trades to align with stable or high-liquidity periods.

The correlation between trading volume and volatility offers a valuable indicator for risk management.
