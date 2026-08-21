# Institutional Factor Investing Engine

## Project Overview

This project develops a comprehensive Python-based "Institutional Factor Investing Engine." It demonstrates the end-to-end process of building a quantitative investment strategy, from data acquisition and cleaning to factor estimation, portfolio optimization, backtesting, and performance attribution. The engine focuses on implementing Fama-French factor models to identify and exploit systematic risk premiums in equity markets.

## Real-World Finance Use Case

This engine enhances equity portfolio management with factor insights, providing a systematic approach to:

1.  **Strategic Asset Allocation:** Constructing portfolios with desired risk-return characteristics by targeting specific factors (e.g., Value, Size, Momentum, Quality).
2.  **Risk Management:** Gaining a deeper understanding of portfolio risk beyond traditional asset-level diversification by monitoring and managing factor exposures.
3.  **Performance Attribution:** Explaining portfolio performance by attributing returns to market exposure, specific factor exposures (e.g., Fama-French factors), and idiosyncratic alpha.
4.  **Portfolio Construction & Optimization:** Optimizing portfolios based on factor exposures to maximize risk-adjusted returns (e.g., Sharpe Ratio) while adhering to practical constraints.
5.  **Quantitative Strategy Development:** Serving as a foundation for developing and backtesting more advanced quantitative strategies.

## Key Components

*   **Data Collection:** Acquiring historical stock prices (Yahoo Finance) and Fama-French factor data (Kenneth French Data Library).
*   **Data Cleaning & Feature Engineering:** Calculating returns, merging datasets, and creating excess returns.
*   **Factor Estimation:** Implementing rolling multi-factor regression to estimate stock factor exposures (betas).
*   **Portfolio Optimization:** Performing monthly rebalancing using `PyPortfolioOpt` to achieve objectives like Maximum Sharpe Ratio.
*   **Backtesting & Performance Analysis:** Simulating portfolio performance and calculating key metrics such as annualized returns, volatility, Sharpe ratio, and Maximum Drawdown.
*   **Attribution Analysis:** Decomposing returns using CAPM and multi-factor models to understand performance drivers.
*   **Visualizations:** Generating professional plots to illustrate cumulative returns, rolling performance, and factor exposures over time.
