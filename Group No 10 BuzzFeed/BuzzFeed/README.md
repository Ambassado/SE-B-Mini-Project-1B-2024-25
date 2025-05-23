# BuzzFeed 📰

BuzzFeed is a Python desktop application that fetches the latest news from [Bing.com](https://bing.com) and displays them in a sleek, custom-styled GUI. Built using `customtkinter` for the interface and `BeautifulSoup (bs4)` for web scraping, it offers a simple and effective way to stay updated.

---

## 🚀 Features

- Custom desktop GUI built with `customtkinter`
- Scrapes real-time news headlines from Bing using `bs4`
- MySQL backend integration for storing news data
- Clean, user-friendly interface

---

## 📦 Requirements

- Python 3.8+
- MySQL server (e.g., via MySQL Workbench)

Install dependencies listed in `requirements.txt` (see steps below).

---

## 🛠️ Setup and Execution

Follow these steps to get the project up and running:

1. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up MySQL:**
   - Replace `YOUR_PASSWORD` in `BuzzFeed.py` with your actual MySQL root/user password.
   - Open MySQL Workbench (or your preferred MySQL client).
   - Run the script inside `my_db.sql` to create the necessary database and tables.

4. **Run the application:**
   ```bash
   python BuzzFeed.py
   ```

---

## 🧠 Tech Stack

- **Frontend:** customtkinter
- **Backend:** Python + MySQL
- **Web Scraping:** BeautifulSoup4
- **Database:** MySQL

---

## 🤝 Contributions

Pull requests and suggestions are welcome! For major changes, please open an issue first to discuss what you would like to change.