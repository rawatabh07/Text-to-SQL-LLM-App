# 🧠 Text-to-SQL LLM App using Google Gemini Pro

This project is an end-to-end application that converts natural language questions into SQL queries using **Google Gemini Pro**, executes them on a SQLite database, and displays the results in a **Streamlit** web interface.


---

## 🔥 Features

- Convert user queries in plain English to SQL
- Uses Google Gemini Pro for SQL generation
- Executes SQL on an SQLite database (`student.db`)
- Display results instantly on a Streamlit dashboard

---

## 📦 Tech Stack

- [Python 3.10+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Google Generative AI Python SDK](https://pypi.org/project/google-generativeai/)
- [SQLite](https://www.sqlite.org/index.html)
- [dotenv](https://pypi.org/project/python-dotenv/)

---

## 🚀 Getting Started

### 1. Create and activate a virtual environment
conda create -p venv python==3.10 -y

### 2. Install dependencies
pip install -r requirements.txt

### 3. Add your Gemini API key
GEMINI_API_KEY=your_gemini_api_key_here

### 4. Run the app
streamlit run app.py




