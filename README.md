# SQLRAG with Gemini

SQLRAG with Gemini is a Streamlit-based demo for asking natural-language questions over a SQLite database and generating SQL-assisted answers with Gemini through LangChain.

## Features

- Natural-language to SQL workflow
- SQLite database support
- Gemini integration through `langchain-google-genai`
- Streamlit user interface
- Simple local setup for experimentation

## Requirements

- Python 3.10+
- Google Gemini API access
- A local SQLite database

## Setup

```bash
git clone https://github.com/emredeveloper/SQLRAG-with-Gemini.git
cd SQLRAG-with-Gemini
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_gemini_key
```

## Run

```bash
streamlit run main.py
```

## Suggested Improvements

- Add sample database schema and seed data
- Add SQL safety checks before execution
- Add examples for common questions
- Add tests for query generation and database helpers

## License

MIT
