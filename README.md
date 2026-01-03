# AI Web Scraper 🤖🕷️

An AI-powered web scraping application that extracts website content and enables **intelligent, natural-language-based parsing** using **Large Language Models (LLMs)**.  
Built with **Python, Streamlit, Selenium, and LangChain + Ollama**.

---

## 🚀 What This Project Does

This project allows users to:

- Enter any website URL
- Scrape dynamic, JavaScript-rendered web pages
- Extract and clean DOM content
- Ask custom natural-language questions about the scraped data
- Get AI-generated answers strictly based on the website content

All through an interactive **Streamlit UI**.

---

## 🧠 Why This Project Matters

This project demonstrates **real-world AI engineering skills**, including:

- Practical web scraping using Selenium
- DOM parsing and data cleaning
- Handling large web pages using chunking
- Prompt-controlled LLM extraction to reduce hallucinations
- End-to-end AI workflow: **Web → Processing → LLM → User**

It reflects applied problem-solving, not just model usage.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – Interactive UI
- **Selenium** – Dynamic web scraping
- **BeautifulSoup** – HTML parsing
- **LangChain**
- **Ollama** – Local LLM inference
- **webdriver-manager**

---

## 📂 Project Structure

```text
ai_web_scraper/
├── main.py          # Streamlit application
├── scrape.py        # Web scraping & DOM processing
├── parse.py         # LLM-based parsing logic
├── requirements.txt
└── .gitignore

---

## ⚙️ Prerequisites (Important)

This project uses **Ollama for local LLM inference**.

⚠️ **Requirement:**  
The Ollama model used in this project **must be available locally** before running the application.

### Install Ollama
Download and install from:
https://ollama.com
### Pull the required model

```bash
ollama pull llama3.2:1b
Start Ollama service

pip install -r requirements.txt
streamlit run main.py
