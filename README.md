# Revenue-Data-and-Building-a-Dashboard
Analyzed Tesla and GameStop stock and revenue data by extracting tables with BeautifulSoup, cleaning and structuring them using Pandas, and visualizing trends with Matplotlib. The project highlights steady Tesla growth versus volatile GameStop pricing while strengthening practical Python data analysis skills.

## Overview

This project compares historical stock price behaviour with company revenue trends for Tesla and GameStop. The aim was to build a reproducible workflow for collecting financial data, preparing it for analysis, and visualizing patterns to understand how market pricing aligns with underlying business performance.

## Technical Approach

* **Problem Definition** — Investigated the relationship between stock price movement and revenue trends using time-series analysis.
* **Data Acquisition** — Retrieved stock data programmatically and collected revenue data from structured web tables.
* **HTML Parsing** — Used BeautifulSoup to locate and extract relevant table rows and columns from raw HTML.
* **Data Structuring** — Converted extracted values into Pandas DataFrames for manipulation and analysis.
* **Cleaning** — Removed formatting characters, standardized dates, and filtered incomplete records.
* **Validation** — Checked dataset schema and previews to ensure correct sources were processed.
* **Visualization** — Generated comparative plots using Matplotlib.
* **Interpretation** — Examined growth patterns, seasonality, and divergence between fundamentals and pricing.

## Installation

```bash
pip install pandas matplotlib beautifulsoup4 requests yfinance
```

## Usage

1. Clone the repository
2. Open the notebook in Jupyter
3. Run cells sequentially to fetch data, process it, and generate visualizations
4. Review generated plots and observations

## Project Structure

```
├── notebook.ipynb
├── README.md
└── data_outputs/
```

## Results Summary

* Tesla shows steady revenue expansion with generally aligned stock growth
* GameStop revenue reflects seasonal patterns and later decline
* GameStop stock price volatility diverges from revenue behavior
* Demonstrates impact of market sentiment beyond financial fundamentals

## Tools & Environment

* Python
* Pandas
* Matplotlib
* BeautifulSoup
* Requests
* Jupyter Notebook

## Future Improvements

* Automate periodic data refresh
* Extend comparison to additional companies
* Add statistical correlation metrics
* Improve visualization interactivity

---

Developed as part of hands-on practice in financial data extraction, cleaning, and visualization workflows.
