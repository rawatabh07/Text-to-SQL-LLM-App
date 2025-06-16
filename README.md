# Text-to-SQL-LLM-App

An end-to-end application that converts natural language questions into SQL queries using Google Gemini LLM , executes them against a database and displaying results via a Streamlit UI.

## Features

Natural Language → SQL: Uses Google Gemini Pro to convert user questions to SQL.

Execute Queries: Runs generated SQL against a local SQLite database.

Interactive UI: Built with Streamlit for fast, intuitive interaction.

Extensible Schema: Swap or extend the database (e.g., student.db) easily.

## Installation
git clone https://github.com/yourusername/text-to-sql-llm-app.git
cd text-to-sql-llm-app
python -m venv venv           # or conda create -n sqlapp python=3.10
source venv/bin/activate      # on Windows: venv\Scripts\activate
pip install -r requirements.txt



