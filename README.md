# Amazon Web Scraper

This Python script scrapes data from an Amazon product page and saves it to a CSV file. It retrieves the product's title, price, and the date of the scraping.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- BeautifulSoup4
- requests
- pandas

Install the required packages using:

```
pip install beautifulsoup4 requests pandas
```

## Usage

1. Clone the repository:

```
git clone https://github.com/your_username/amazon-web-scraper.git
```

2. Navigate to the project directory:

```
cd amazon-web-scraper
```

3. Run the script:

```
python scraper.py
```

The script will periodically scrape the Amazon product page and update the CSV file with the latest data.

## Configuration

- Modify the `URL` variable in the script to target a different Amazon product page.
- Adjust the `time.sleep()` duration in the script to change the frequency of scraping.

## CSV Output

The script saves the scraped data to a CSV file named `AmazonWebScraperDataset.csv` in the project directory. Each row contains the product's title, price, and the date of scraping.

## Email Notification (Optional)

If you want to receive an email notification when the price drops below a certain level, follow these steps:

1. Uncomment the `send_mail()` function in the script.
2. Modify the email credentials (`server.login()`) and the email message (`subject` and `body`) accordingly.

Note: Email functionality requires a Gmail account and enabling less secure app access.

## Contributors

- Your Name <your_email@example.com>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
