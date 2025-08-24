 AI Web Scraper

An **AI-powered web scraping tool** that extracts, cleans, and parses website content using **Selenium, BeautifulSoup, and LLMs (LangChain + Ollama)**.  
Built with a **Streamlit UI** for easy interaction.

---

## 🚀 Features
- 🌐 **Automated Scraping**: Uses Selenium with proxy support to handle dynamic websites.
- 🧹 **Content Cleaning**: Extracts body content and removes scripts/styles with BeautifulSoup.
- 🤖 **AI Parsing**: Query scraped data using natural language via LangChain + Ollama.
- 📑 **Chunked Processing**: Splits large DOMs to handle LLM token limits.
- 🎛️ **Interactive UI**: Streamlit-based interface for inputting URLs, viewing DOM, and parsing results.

---

## 🛠️ Tech Stack
- **Python 3.10+**
- [Streamlit](https://streamlit.io/) – UI
- [Selenium](https://www.selenium.dev/) – Web scraping
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/) – HTML parsing
- [LangChain](https://www.langchain.com/) + [Ollama](https://ollama.com/) – AI parsing
- [dotenv](https://pypi.org/project/python-dotenv/) – Environment variable management
