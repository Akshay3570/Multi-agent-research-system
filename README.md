# ResearchMind 🤖🔬

A powerful AI-powered multi-agent research system that turns a simple topic into a well-structured research report. Built with Python, LangChain, Streamlit, and modern LLM tools, this project simulates a research team where different agents collaborate to search, read, write, and review information.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![LangChain](https://img.shields.io/badge/LangChain-AI%20Agents-green)
![Mistral](https://img.shields.io/badge/Mistral-AI%20Model-orange)

## ✨ Features

- Multi-agent workflow for research automation
- Web search for recent and reliable information
- Content scraping from relevant sources
- Structured report generation
- Built-in critique and feedback loop
- Clean and interactive Streamlit UI

## 🧠 How It Works

The system uses specialized agents to perform the following tasks:

1. Search Agent
   - Finds relevant online sources for a given topic.

2. Reader Agent
   - Scrapes the most relevant pages for deeper context.

3. Writer Agent
   - Generates a detailed research report with sections like:
     - Introduction
     - Key Findings
     - Conclusion
     - Sources

4. Critic Agent
   - Reviews the report and gives constructive feedback.

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Mistral AI
- Tavily Search API
- BeautifulSoup
- Requests

## 📦 Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/AkarshVyas/Multi-agent-research-system.git
cd Multi-agent-research-system
pip install -r requirements.txt
