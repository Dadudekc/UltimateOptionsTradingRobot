# Data Fetchers Directory

The Data Fetchers directory contains scripts for fetching various types of data necessary for the TradingRobotPlug project. Each data type has a dedicated fetcher script to streamline the retrieval process.

## Contents
- `stock_data_fetcher.py`: Retrieves stock price and market data.
- `news_data_fetcher.py`: Gathers financial news data.
- `economic_indicator_fetcher.py`: Fetches economic indicators such as inflation, interest rates, etc.

## Guidelines
1. Keep data fetchers modular, allowing for easy integration or replacement of individual sources.
2. Document data sources and any API-specific details within each fetcher script.
3. Store all fetched data temporarily in the `data/raw/` directory before processing.