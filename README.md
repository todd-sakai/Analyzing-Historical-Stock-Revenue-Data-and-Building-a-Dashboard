# Stock Price vs. Revenue: Tesla and GameStop

This project pulls daily share prices with the `yfinance` API, scrapes quarterly revenue from HTML tables with `requests` and BeautifulSoup, and plots price above revenue for Tesla and GameStop up to mid-2021. It then matches each quarter's revenue to the quarter-end share price to test whether price follows revenue.

| Company | Correlation of revenue with quarter-end price | Mean year-over-year revenue growth, last 4 quarters |
|---|---|---|
| Tesla | 0.76 | +38.3% |
| GameStop | 0.16 | -25.6% |

Tesla's price rose with its revenue. GameStop's price jumped in January 2021 while its revenue was falling, so revenue does not explain that move.

Files:
- `Tesla_GameStop_Stock_vs_Revenue.ipynb`: Code and outputs
