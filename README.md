# 🧠 Text-to-SQL Streamlit App

This is a Streamlit web application that lets users interact with a student database using natural language. The app converts the input into SQL queries, executes them on an SQLite database, and displays the results instantly.

## 🚀 Features

- Query student data using plain English
- SQLite-backed database with student info
- Simple, interactive Streamlit interface
- Easy to extend and customize

## 🛠️ Tech Stack

- Python
- Streamlit
- SQLite
- LangChain + Groq for LLM-based SQL generation

## 🗃️ Table Schema can be modified according to the user's use

```sql
CREATE TABLE STUDENT (
    NAME    VARCHAR(25),
    COURSE  VARCHAR(25),
    SECTION VARCHAR(25),
    MARKS   INT
);
