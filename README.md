# UK Bridging Finance Market Report Generator

This Python script generates a comprehensive PDF report on the UK Development and Bridging Loan Finance Market, including detailed historical data for 2022-2024.

## Features

- **Market Volume Analysis**: Tracks the growth of the UK bridging loan market from 2022 to 2024 with year-on-year percentage changes
- **Borrower Types Breakdown**: Analyzes the changing composition of borrowers using bridging finance (corporate, developers, HNW individuals, investors)
- **Lender Types Analysis**: Examines the market share of different lender categories (retail banks, challenger banks, non-bank lenders) over time
- **Data Visualization**: Includes charts and graphs to illustrate market trends with clear annotations
- **Web Scraping**: Collects current market data from relevant sources with fallback to stored data when scraping fails
- **Full Data Source Transparency**: Includes full URLs of all data sources used in the report

## Data Sources

The report uses data from multiple authoritative sources:
- Association of Short Term Lenders (ASTL): https://www.theastl.org/
- Bridging Trends: https://bridgingtrends.co.uk/
- UK Finance: https://www.ukfinance.org.uk/
- Financial Conduct Authority (FCA): https://www.fca.org.uk/
- Savills Research: https://www.savills.co.uk/research/
- EY Financial Services: https://www.ey.com/en_uk/financial-services
- And other industry sources

## Installation

1. Clone the repository:
```bash
git clone https://github.com/cploutarchou/uk-bridging-finance-report.git
cd uk-bridging-finance-report
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Install Chrome WebDriver for Selenium (if not already installed):
   - Download the appropriate version for your Chrome browser from: https://sites.google.com/chromium.org/driver/
   - Add the WebDriver to your system PATH

## Usage

```bash
python generate_bridging_finance_report.py
```

The script will generate a PDF report named `UK_Bridging_Finance_Market_Report.pdf` in the current directory.

## Output

The report includes:
- Executive summary
- Market volumes data (2022-2024)
- Regional distribution of bridging finance
- Borrower types breakdown with three-year trend analysis
- Lender types by volume with year-by-year trends
- Distribution channels and regulatory considerations
- Conclusion and future outlook
- Complete list of data sources with full URLs

## Report Structure

1. **Cover Page**: Title, date, and author information
2. **Table of Contents**: Organized by chapter with page numbers
3. **Introduction**: Overview of the UK bridging finance market
4. **Market Volumes**: Transaction volumes for 2022-2024 with growth analysis
5. **Borrower Types**: Detailed breakdown of borrower categories
6. **Lender Types**: Analysis of lender categories by market share
7. **Conclusion**: Summary of key findings and future outlook
8. **Data Sources**: Complete list of all data sources with full URLs

## Author

Christos Ploutarchou

## License

MIT License
