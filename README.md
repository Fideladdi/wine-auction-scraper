# 🍷 Wine Auction Scraper

This project uses Python and Selenium to scrape wine lot data from a wine auction site. The data includes wine name, vintage, region, bottle count, estimate range, and hammered price. It's exported into a CSV file for further analysis.

## 📦 Features

- Scrapes data for 500+ wine lots
- Extracts:
  - Lot number
  - Wine name
  - Vintage
  - Bottle count
  - Region
  - Low/High estimates
  - Hammered price
- Stores results in a CSV file
- Randomized sleep time to avoid being flagged as a bot

## 🛠 Tech Stack

- Python
- Selenium (with Firefox WebDriver)
- BeautifulSoup (for HTML parsing)
- Regex (for text extraction)

## 🚀 How to Run

1. Clone the repo:

```bash
git clone https://github.com/your-username/wine-auction-scraper.git
cd wine-auction-scraper
