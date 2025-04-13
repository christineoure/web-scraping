#Web-scraping
```markdown
# 🕸️ Quotes Web Scraper

This project is a simple web scraper built with Python using `requests` and `BeautifulSoup`. It extracts quotes, authors, and tags from [quotes.toscrape.com](https://quotes.toscrape.com), a website designed for practicing web scraping.

## 📌 Features

- Scrapes quotes from the main page and multiple paginated pages.
- Extracts:
  - Quote text
  - Author name
  - Tags associated with each quote
- Outputs scraped data directly to the console.

## 🛠️ Installation

Before running the script, install the required Python packages:

```bash
pip install requests
pip install beautifulsoup4
```

## 🚀 Usage

Run the code in a Python environment (e.g., Jupyter Notebook or Google Colab):

```python
# Example entry point
python webscraping.ipynb
```

The script will:
1. Make a request to the website.
2. Parse the HTML content.
3. Loop through up to 100 pages.
4. Print out quotes, authors, and tags in a formatted manner.

## 📄 Example Output

```
Quote 1:
“The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.”
By: Albert Einstein
Tags: change,deep-thoughts,thinking,world
--------------------
```

## 📎 Notes

- The site is designed for scraping practice—no legal or ethical concerns.
- No data is saved; for persistence, modify the script to write to a `.csv` or `.json` file using `pandas`.

## 📚 Dependencies

- Python 3.x
- requests
- beautifulsoup4
- pandas (optional, not currently used for output)

## 🧠 Future Improvements

- Export data to CSV or JSON
- Handle pagination dynamically based on the site’s structure
- Add error handling and logging
