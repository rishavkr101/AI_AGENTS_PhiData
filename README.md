# Analyst and News Aggregator

This project uses a team of agents to fetch and display analyst recommendations and the latest news for any public listed company. It leverages the `phi.agent` framework along with the `YFinanceTools` for financial data and `DuckDuckGo` for news searches.

## Overview

The application creates three agents:
- Web Agent:Uses the DuckDuckGo tool to fetch news related to NVIDIA.
- Finance Agent: Uses YFinance tools to retrieve stock price, analyst recommendations, and stock fundamentals.
- Agent Team: Combines both agents, setting instructions to include sources and display data using tables.

The final result is printed to the console using a streaming Markdown output.

## Features

- Analyst Recommendations:Summarizes recommendations (e.g., Strong Buy, Buy, Hold) over various time periods.
- Latest News:Retrieves recent news articles about NVIDIA.
- Markdown Output:Uses Markdown formatting to present the data neatly.
- Tool Integration: Demonstrates the integration of financial data and web search tools.

## Prerequisites

- Python 3.
