# Amazon Product Search Automation with Selenium

## Automate e-commerce product purchase on Amazon: 


## Overview

This project is an automation script that utilizes Selenium to perform product searches on the Amazon website. The script navigates to Amazon, searches for a specified product, and extracts information about the first search result, demonstrating the capabilities of web automation.

## Features

- **Automated Product Search:** The script automates the process of navigating to Amazon and performing a product search.

- **Flexible Configuration:** You can easily configure the script to search for different products by modifying the search query in the code.

- **Selenium Integration:** The project leverages Selenium, a powerful web automation library, to interact with the Amazon website.

## Requirements

- Python 3.x
- Selenium library (`pip install selenium`)
- ChromeDriver executable (Download from https://sites.google.com/chromium.org/driver/)

### Preferred IDE to be used - Eclipse or IntelliJ
### Automation tool to be used – Selenium

## Setup

1. Install Python 3.x on your system.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Download the appropriate version of ChromeDriver and place it in the specified directory.

## Usage

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the script using the command: `python automazon.py`

## Configuration

You can customize the script by modifying the following parameters in the `automazon.py` file:

- `webdriver_path`: Path to the ChromeDriver executable.
- `search_query`: The product you want to search for on Amazon.

## Working

1. Navigate to https://www.amazon.in/ 
2. Verify landing on the correct page
3. Print the URL and Title of the Page
4. Search for "mobile"
5. Select 4 stars under customer review filter section
6. Select the price range between ₹10,000 - ₹20,000
7. Click on the first search result
8. Add the phone to the cart
9. Click on the Go to cart button



## Acknowledgments

- The script uses Selenium, an open-source web automation tool. (https://www.selenium.dev/)

Feel free to contribute, report issues, or suggest improvements by creating GitHub issues or pull requests.

