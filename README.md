# Mutual Fund Allocation Tracker

## Overview
This Python-based framework helps in tracking and analyzing changes in mutual fund allocations over a specified time period. The framework processes data from monthly mutual fund portfolio files (e.g., from Zerodha) and calculates key metrics such as quantity changes and market value changes for each instrument in the portfolio.

## Features
- **Input Parameters**: 
    - Fund name
    - Start and end date range
    - Directory containing mutual fund data files
- **Data Handling**: Dynamically loads and processes Excel files from a specified directory.
- **Insights Generation**: Provides insights on allocation changes by fund and by month, with detailed market value changes.
- **Output**: Results are displayed in the notebook and saved to an Excel file (`Mutual_Fund_Analysis.xlsx`).

## Prerequisites
To run this project, you need to install the following Python libraries:
- `pandas`
- `matplotlib`
- `re`
- `glob`
- `os`
- `datetime`

You can install the required libraries using pip:

```bash
pip install pandas matplotlib
