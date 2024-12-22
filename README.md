
# 🌐 AI-Web-Scraper
An AI web scraper using **Ollama**, **BrightData**, **Selenium**, and other libraries.

## Project Overview
This project is an **AI-powered web scraper** built using **Python**. The application allows you to scrape websites based on the URL you provide, extract the DOM content, and interact with the website using AI. By passing a prompt to the AI, you can automatically extract specific information from the webpage. The project leverages tools such as **Selenium**, **BeautifulSoup**, **LangChain**, **Ollama**, and **BrightData** for scraping and AI integration.

## Features
- **Ollama** and **LangChain** for natural language processing and AI interaction.
- Uses **Selenium** to interact with dynamic web content.
- Extracts data from HTML DOM and allows AI-driven prompts for data extraction.
- Supports real-time web scraping and information retrieval based on user-defined criteria.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/AI_Web_Scraper.git
   cd AI_Web_Scraper
2. **Create and activate a virtual environment**:
``` bash
python3 -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```
2. **Install the required packages:**
``` bash
pip install -r requirements.txt

```
3. **Run the Streamlit application 🎬:**
``` bash
streamlit run main.py
```