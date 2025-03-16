# UK Bridging Finance Market Report Generator

This Python script generates a comprehensive PDF report on the UK Development and Bridging Loan Finance Market, including detailed historical data for 2022-2024.

## Features

- **Market Volume Analysis**: Tracks the growth of the UK bridging loan market from 2022 to 2024
- **Borrower Types Breakdown**: Analyzes the changing composition of borrowers using bridging finance
- **Lender Types Analysis**: Examines the market share of different lender categories over time
- **Data Visualization**: Includes charts and graphs to illustrate market trends
- **Web Scraping**: Attempts to collect current market data from relevant sources with fallback to stored data

## Requirements

The script requires the following Python packages:
- requests
- selenium
- beautifulsoup4
- matplotlib
- numpy
- fpdf

## Usage

```bash
python generate_bridging_finance_report.py
```

The script will generate a PDF report named `UK_Bridging_Finance_Market_Report.pdf` in the current directory.

## Output

The report includes:
- Executive summary
- Market volumes data (2022-2024)
- Borrower types breakdown
- Lender types by volume
- Conclusion and future outlook

## Author

Christos Ploutarchou
