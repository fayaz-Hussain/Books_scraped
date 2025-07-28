# 📚 BookScraper – 1000-Page Web Scraping Project

This project is a complete scraping solution for [Books to Scrape](https://books.toscrape.com) — a demo site made for web scraping practice. Using Python, Selenium, and BeautifulSoup, I scraped all **50 listing pages** and **1000 individual book detail pages**, extracting clean and structured data.

✅ Includes features like **headless browsing**, **random delays**, **custom user-agent**, and **error handling** for a production-style scraping workflow.

---

## 🚀 Features

- 🔍 Scraped **1000 total pages** (50 listings + 950 product detail pages)
- 🧠 Extracted complete book info including **stock quantity**
- ⚡ **Headless browser** mode using Selenium
- 🕵️‍♂️ **Custom User-Agent** to mimic real browser requests
- ⏱️ **Random delay** between requests (1–5 seconds)
- 🛑 **Retry and error logging** for failed pages
- 🧼 Fixed **encoding issues** (e.g., `Â£` symbol bug)
- 📁 Exports clean data to `CSV` format

---

## 📊 Data Fields

For each book:

- **Title**
- **Price (£)**
- **Rating** (converted from word to number)
- **Stock** (quantity available, e.g., `22`)
- **Category**
- **Product Description**
- **Product Page URL**

---

## 🧪 Sample Output

| Title                     | Price | Rating | Stock | Link            |  Description              |
|---------------------------|-------|--------|-------|-----------------|---------------------------|
| The Grand Design          | 13.76 | 3      | 22    | catalogue.page1 | A popular explanation...  |
| The New Brand You         | 51.77 | 4      | 5     | catalogue.page2 | Discover how personal...  |

🔗 View full dataset here: [`books_data.csv`](./books_data.csv)

---

## 🛠️ Tech Stack

- `Python 3.x`
- `Selenium` (headless mode)
- `BeautifulSoup4`
- `pandas`
- `re`, `time`, `random`, `logging`

---

## 📂 Project Structure

books_scraper/
├── scrape_books.py # Main scraping logic
├── books_data.csv # Final output (1000 rows)
├── requirements.txt # Dependencies
└── README.md # Project overview


---

## ⚙️ Setup & Run

```bash
git clone https://github.com/fayaz-Hussain/books_scraper.git
cd books_scraper
pip install -r requirements.txt
python scrape_books.py


👤 Author
Fayaz Hussain
Data Analyst | Web Scraping Enthusiast

