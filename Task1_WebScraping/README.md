# CodeAlpha Web Scraping Task

## Project Title

**Web Scraping Using Python and BeautifulSoup**

## Objective

The objective of this project is to extract book information from a public website and create a custom dataset for analysis.

## Tools and Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- Jupyter Notebook

## Website Used

https://books.toscrape.com/

## Dataset Fields

- Book Name
- Price

## Steps Performed

1. Sent a request to the website using the Requests library.
2. Parsed the HTML content using BeautifulSoup.
3. Extracted book names and prices.
4. Stored the extracted data in a Pandas DataFrame.
5. Saved the data as a CSV file (`books_data.csv`).

## Output

A custom dataset containing book names and prices was successfully created and stored in CSV format.

### Sample Output

| Book Name | Price |
|-----------|--------|
| A Light in the Attic | £51.77 |
| Tipping the Velvet | £53.74 |
| Soumission | £50.10 |
| Sharp Objects | £47.82 |
| Sapiens: A Brief History of Humankind | £54.23 |

## Files Included

- Web_Scraping_Task.ipynb
- books_data.csv
- Output Screenshot
- README.md

## Conclusion

This project demonstrates the use of web scraping techniques to collect data from a website and create a structured dataset for further analysis.
