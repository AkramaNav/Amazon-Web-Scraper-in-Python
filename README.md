Amazon Product Web Scraper

Introduction
This project is a Python-based tool designed to help users monitor Amazon product prices. Users are notified via email when the price of a product drops to their desired range, ensuring they never miss a deal.

Features
  Scrapes Amazon product details, including price and availability.
  Tracks changes in price over time.
  Sends automated email notifications using an SMTP server.

Tools & Technologies
  Programming Language: Python
  Libraries: BeautifulSoup, Requests, smtplib

How It Works
  Input the Amazon product URL and your target price.
  The scraper checks the product page periodically.
  If the price meets your target, an email notification is sent automatically.

Installation
  Clone the repository.
  Install required libraries with pip install -r requirements.txt.
  Set up your email credentials in the script.
