# Trader Behavior Insights

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear and Greed) and trader performance on the Hyperliquid platform. The objective is to uncover behavioral patterns, performance trends, and strategic insights that can drive smarter trading decisions.

## Dataset Description

The analysis uses two primary datasets:

1. **Bitcoin Market Sentiment (Fear/Greed Index)**
   - Columns: `Date`, `Classification` (Fear/Greed)
   - Provides daily sentiment classification for the Bitcoin market.

2. **Historical Trader Data from Hyperliquid**
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, among others.
   - Contains detailed trade execution records for individual traders.

## Objective

The main objective is to explore:

- How trader performance (measured by closed profit and loss) varies during Fear vs Greed market conditions.
- Behavioral patterns such as trading volume, leverage usage, and side preference under different sentiments.
- Symbol-wise trading behavior and performance across sentiment phases.
- Potential insights for building trading strategies that align or counteract market sentiment.

## Approach

1. **Data Cleaning and Preprocessing**
   - Converted date columns to datetime format.
   - Merged both datasets on date for sentiment tagging.
   - Handled missing values.

2. **Exploratory Data Analysis (EDA)**
   - Calculated average and total closed PnL during Fear and Greed days.
   - Analyzed trade counts, leverage distribution, and side (long/short) preferences.
   - Explored symbol-wise performance patterns across sentiment phases.

3. **Visualization**
   - Plotted bar charts to compare average PnL across sentiments.
   - Created distribution plots for leverage usage.
   - Visualized the number of trades executed per sentiment type.
   - Displayed win ratio and performance metrics by sentiment.

4. **Key Findings**
   - Identified differences in trader profitability during Fear and Greed periods.
   - Observed behavioral shifts in leverage and position size based on market sentiment.
   - Highlighted specific trading patterns that emerge during sentiment extremes.



