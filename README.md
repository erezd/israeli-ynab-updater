# Israeli YNAB Updater
A tool for updating YNAB using israeli-bank-scrapers

## Getting started

### Prerequisites 
In order to start using this tool, you will need to have Node.js running environment installed on your machine.
Go [here!](https://nodejs.org/en/download/) to download and install the latest Node.js for your operating system.

### Installation
Once Node.js is installed, run the following command to fetch the code:
```bash
git clone https://github.com/eshaham/israeli-ynab-updater
cd israeli-ynab-updater
```

Next you will need to install dependencies by running
```bash
npm install
```

### Saving credentials
The credentials for each scraper are encrypted and saved in an dedicated file on your system. 
To save credentials for a specific scraper, run the following command and choose the scraper:
```bash
npm run credentials
```

### Scraping
Once you save the credentials for relevant scrapers, run the following command to start scraping:
```bash
npm start
```

The CSV file should be created under `YNAB-Transactions` folder in your Downloads folder.
