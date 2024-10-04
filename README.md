# Amazon Price Tracker with Web Scraping and Email Alerts

## Project Overview
This project involved the development of a web scraping tool using Python to monitor prices of products on Amazon. The primary objective was to track the price of a specified product and log updates into a CSV file. Additionally, the project integrated an email notification system to alert users when the product price drops below a set threshold, facilitating timely purchasing decisions.

## Key Responsibilities

### 1. Web Scraping
- **Developed a Web Scraping Tool**: Utilized Python and the BeautifulSoup library to scrape product details from Amazon's website, focusing on:
  - **Product Title**: Extracted the name of the product dynamically from the webpage.
  - **Product Price**: Scraped the current price of the product to log historical price data.
- **Data Storage**: Logged the scraped data into a CSV file for ongoing tracking and analysis.

### 2. Email Notifications
- **Integrated Email Alerts**: Implemented functionality to send email notifications when the product price falls below a predefined threshold.
  - **SMTP Configuration**: Set up SMTP server connection to send emails using a Gmail account, ensuring that users receive timely alerts.

### 3. Automation
- **Scheduled Price Checks**: Created a loop that checks the product price at regular intervals (daily) to keep the data up-to-date, allowing users to act quickly on favorable price changes.

### 4. Data Management
- **Data Logging**: Utilized CSV files to store price data, facilitating easy access and historical analysis. This included appending new data with each price check to maintain a comprehensive record of price changes over time.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: BeautifulSoup, Requests, Pandas, SMTP
- **Data Storage**: CSV file

## Outcomes
- Successfully tracked Amazon product prices and logged updates in a CSV file, enabling users to monitor price trends over time.
- Implemented an alert system that notifies users via email when product prices drop below a set threshold, enabling informed purchasing decisions.
- Enhanced familiarity with web scraping techniques and automation using Python, leading to improved skills in data collection and analysis.

## Conclusion
This project demonstrates the practical application of web scraping for price monitoring and the utility of automation in consumer behavior. The integration of email notifications adds significant value, ensuring users are promptly informed about price changes. Future enhancements could include a user interface for setting thresholds and monitoring multiple products simultaneously.

---
