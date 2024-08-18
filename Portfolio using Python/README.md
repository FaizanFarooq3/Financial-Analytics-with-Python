
# Financial Portfolio Analysis using Python

## Project Overview

This project is designed to analyze a financial portfolio consisting of FAANG stocks—Facebook (META), Amazon (AMZN), Apple (AAPL), Netflix (NFLX), and Alphabet (GOOG)—using Python. The primary aim is to provide a comprehensive understanding of how a stock portfolio behaves over time, focusing on key financial metrics such as simple returns, daily returns, and volatility.

## Aim & Purpose

The purpose of this project is to create a tool that can be used to assess the performance and risk of a stock portfolio. By leveraging historical stock price data from Yahoo Finance, we aim to extract meaningful insights that help in evaluating the profitability and volatility of the portfolio. Specifically, we seek to provide users with:

- An understanding of the **cumulative returns** of a portfolio over time.
- Insights into the **daily price changes and returns** of the selected stocks.
- An evaluation of the **volatility** (risk) associated with holding these stocks in a portfolio.

This tool can be extended to any set of stocks, making it valuable for personal investors or analysts who need to assess their portfolios.

## Features

- **Portfolio Simple Returns**: Calculate and visualize the overall returns of the portfolio.
- **Daily Returns**: Compute and plot daily percentage changes in stock prices to understand daily performance.
- **Volatility Assessment**: Quantify portfolio risk by calculating the standard deviation of daily returns.
- **Data Extraction**: Use Pandas Data Reader to fetch historical stock price data from Yahoo Finance.
- **Customizable Timeframe**: Analyze stock performance starting from January 1, 2013, considering Facebook's IPO timeline.

## What Are We Trying to Achieve?

The project aims to answer several key financial questions, including:
- How does the portfolio perform over time in terms of returns?
- What is the daily variability of the stock prices?
- How volatile is the portfolio compared to individual stocks?
- Can we visualize trends or patterns that indicate potential risks or rewards?

By answering these questions, we provide a framework for better decision-making regarding stock investments and portfolio management.

## Outcomes & Results

Upon completing the analysis, the project delivers several important outcomes:
- **Cumulative Returns Visualization**: A visual representation of how the portfolio's value changes over time, helping investors understand overall performance.
- **Daily Returns Analysis**: Calculation and plotting of daily percentage changes in stock prices, allowing for a more granular look at stock performance and portfolio volatility.
- **Volatility Assessment**: The standard deviation of daily returns is used to quantify the portfolio's volatility, giving insight into the risk associated with the portfolio.

## Findings

- **Performance Trends**: Highlights trends in stock performance, such as which stocks contribute the most to portfolio growth and which ones introduce more risk.
- **Risk Evaluation**: Identifies periods of high or low volatility, helping to assess the stability of the portfolio.
- **Investment Insights**: Findings can be used to make informed decisions on rebalancing the portfolio, increasing investment in certain stocks, or diversifying into other sectors.

## Data Source

Data for this analysis is extracted from Yahoo Finance using Pandas Data Reader. The analysis starts from January 1, 2013, due to Facebook’s IPO timing.

This project is a starting point for more advanced financial analysis, allowing users to experiment with different stocks, timeframes, and financial metrics to develop their investment strategies.



