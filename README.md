# PRODIGY_SD_05
Task 5 - Extracts product information, such as names, prices, and ratings, from an online e- commerce website and stores the data in a structured format like a CSV file.

# Product Information Scraper

## Project Overview

This project is a web scraper designed to extract product information, such as names, prices, and ratings, from an e-commerce website (Amazon in this example). The extracted data is then stored in a structured format, specifically a CSV file. 

### The script uses the following Python libraries:
- `requests`: For making HTTP requests to the website.
- `BeautifulSoup` (from `bs4`): For parsing HTML content and extracting data.
- `pandas`: For storing the extracted data in a CSV file.

### Prerequisites

To run this project, you need to have Python installed on your system along with the following libraries:

### Installation

1. Clone the repository or download the `scrape_amazon.py` file to your local machine.

### Usage

1. Open a terminal or command prompt.
2. Navigate to the directory where the `scrape_amazon.py` file is located.
3. Run the program using the following command:

  bash
pip install requests beautifulsoup4 pandas.

## Project Structure

- `scrape_amazon.py`: The main script that performs the scraping and data storage.
- `products.csv`: The output file where the extracted product data is stored.

## Running the Script

1. Ensure the required libraries are installed by running:
- `pip install requests beautifulsoup4 pandas`.
2. Save the script scrape_amazon.py to your local directory.
3. Open your terminal or command prompt and navigate to the directory containing scrape_amazon.py.
4. Run the script:
- `python scrape_amazon.py`.
5. The script will fetch product information from the specified URL, process the data, and save it to a CSV file named products.csv in the same directory.

## Sample Output
The products.csv file will contain data similar to the following:

![image](https://github.com/user-attachments/assets/bbf77874-dd1d-4493-b1b0-bb8f4d417811)

## Results
The script successfully extracts the following product information from the given e-commerce website:

- `Name`: The name of the product.
- `Price`: The price of the product.
- `Rating`: The user rating of the product.

This information is stored in a CSV file (products.csv), making it easy to analyze or integrate with other data processing tools.

## Conclusion

This project demonstrates the basic principles of web scraping and data extraction using Python. By utilizing libraries such as requests, BeautifulSoup, and pandas, it is possible to efficiently scrape and store data from web pages. However, it is essential to respect the terms of service of the websites being scraped and ensure compliance with any legal or ethical guidelines.
