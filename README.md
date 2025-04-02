# 📰 Personal Project: Web Scraper for News Headlines

This is a personal Python project I built to scrape the latest news headlines from a few selected news websites. It helps me collect article titles, URLs, and publication dates for personal analysis, learning, and fun experiments with data.

---

## 🔍 What It Does

- Scrapes news headlines from predefined websites (e.g., BBC, CNN)
- Extracts title, URL, source, and published date
- Saves everything to a CSV file for easy use
- Simple structure so I can easily extend it later

---

## 🧰 Tools & Libraries Used

- Python 3.x  
- `requests`  
- `BeautifulSoup` (`bs4`)  
- `pandas`  
- `lxml` *(optional for faster parsing)*

---

## 📂 Folder Structure

```
news-scraper/
├── scraper.py           # Main script
├── config.py            # Source definitions
├── utils.py             # Helper functions
├── requirements.txt     # Python dependencies
└── README.md            # This file
```

---

## 🚀 How to Run

1. Clone the repo:

```bash
git clone https://github.com/your-username/news-scraper.git
cd news-scraper
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the script:

```bash
python scraper.py
```

The results will be saved in a file named `headlines.csv`.

---

## ⚙️ Customize Sources

You can add more news websites or change scraping logic in `config.py`.  
Here’s an example format:

```python
news_sources = [
    {
        "name": "BBC",
        "url": "https://www.bbc.com/news",
        "headline_tag": "h3",
        "class": "gs-c-promo-heading__title"
    },
]
```

---

## 📝 Output Format

The CSV file will include:

- `title`  
- `url`  
- `source`  
- `published_date`  
- `scraped_at`

---

## 🧪 Why I Built This

Just a fun way to:

- Learn more about web scraping
- Experiment with data collection
- Possibly build a mini dashboard later

---

## 📌 Notes

- Built for educational and personal use only  
- Be respectful of website terms of service  

---

## 📬 Contact

If you're checking this out and have questions, feel free to reach out at [meenakshi20052003@gmail.com](mailto:meenakshi20052003@gmail.com)

---

Thanks for stopping by! 😊
