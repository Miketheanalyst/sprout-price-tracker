# Sprout Price Tracker

A Python script to track product prices from alsuper.com and update them in a Google Sheet. It also sends email notifications when price changes are detected.

## Features

- **Automated Price Tracking**: Scrapes product prices from specified URLs.
- **Google Sheet Integration**: Logs prices with timestamps in a Google Sheet.
- **Email Notifications**: Sends alerts via Gmail when prices change.
- **Scheduled Execution**: Designed to run periodically (e.g., via cron job or Google Colab scheduler).

## Setup

### Dependencies
- Python libraries: `gspread`, `oauth2client`, `requests`, `beautifulsoup4`, `smtplib`.
- Google Service Account credentials (JSON file) for Google Sheets API access.
- Gmail app password for email notifications.

### Installation
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install gspread oauth2client requests beautifulsoup4


