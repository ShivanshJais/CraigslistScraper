This is a Python-based web scraper designed to extract rental accommodation listings from eBay and provide a consolidated list of available properties. With this tool, you can quickly gather information about rental accommodations listed on eBay, allowing you to find the best options for your needs.

Table of Contents:
Getting Started
Prerequisites
Installation
Usage
Configuration
Contributing
License
Getting Started
To get started with the eBay Rental Accommodation Web Scraper, follow the instructions below.

Prerequisites
Make sure you have the following prerequisites installed on your system:

Python (version 3.6 or higher)
pip (Python package installer)
Installation
Clone the repository to your local machine or download the source code as a ZIP file.
Open a terminal or command prompt and navigate to the project's directory.
bash
Copy code
cd ebay-accommodation-scraper
Install the required Python packages by running the following command:
bash
Copy code
pip install -r requirements.txt
Usage
To use the web scraper, follow these steps:

Open a terminal or command prompt and navigate to the project's directory.
Run the scraper.py script using the following command:
bash
Copy code
python scraper.py
The scraper will start searching for rental accommodation listings on eBay based on your predefined search criteria.
Once the scraping process is complete, the program will generate a list of available accommodation listings, including relevant details such as title, price, location, and description.
The generated list will be displayed on the terminal, and you can also find the results saved in a CSV file named accommodation_listings.csv.
Configuration
Before running the scraper, you can modify the configuration file to customize your search criteria. Open the config.py file and adjust the following parameters:

SEARCH_KEYWORD: The keyword used to search for rental accommodation listings on eBay.
MAX_RESULTS: The maximum number of results to retrieve.
LOCATION_FILTER: The location filter to narrow down the search results. Use the format {"name": "Location Name", "value": "Location Value"}. You can remove this parameter if you want to search for listings across all locations.
