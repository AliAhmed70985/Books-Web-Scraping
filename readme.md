# Books Data Web Scraping

## Project Overview
This project uses web scraping to collect book information from [Books to Scrape](https://books.toscrape.com/).

The goal is to extract book details from all 50 pages of the website and store the collected data in a structured CSV file.

## Tools & Libraries
- Python
- Requests
- BeautifulSoup
- Pandas
- Google Colab

## Data Collected
The dataset contains the following columns:

| Column | Description |
|---|---|
| Category | The book's category |
| Name | The book's title |
| Price | The book's price |
| Availability | The book's availability status |

## Project Steps
1. Send HTTP requests to the website.
2. Parse the HTML content using BeautifulSoup.
3. Extract book titles, prices, and availability.
4. Visit each book's page to extract its category.
5. Use loops to scrape all 50 pages.
6. Store the extracted data in a Pandas DataFrame.
7. Export the final dataset to a CSV file.

## Dataset
- **Total Records:** 1,000 books
- **Total Columns:** 4
- **Output File:** `books_data.csv`

## How to Run
1. Download or clone this repository.
2. Open `Scraping_data_task.ipynb` using Google Colab or Jupyter Notebook.
3. Run the notebook cells in order.
4. The scraped data will be exported as `books_data.csv`.

## Source
[Books to Scrape](https://books.toscrape.com/)