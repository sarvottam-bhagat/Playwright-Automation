# Browser Automation Agent with LLMs

A Streamlit-based web interface for automated browser tasks using large language models (LLMs) from Anthropic, Google Gemini, and OpenAI.

## Features

- 🖥️ Interactive web interface with Streamlit
- 🤖 AI-powered browser automation using LLMs
- 🔄 Supports multiple providers: Claude 3.5 Sonnet, gemini-2.0-pro-exp-02-05, GPT-4o
- 🌐 Real browser interaction (requires Chrome)
- 🔍 Vision capabilities for web page understanding

## Prerequisites

- Python 3.9+
- Google Chrome installed
- API keys for your chosen LLM provider(s)

## Installation

1. Clone repository:
```bash
git clone https://github.com/sarvottam-bhagat/Playwright-Automation.git
cd Playwright-Automation
```

2. Install dependencies:
```bash
pip install streamlit python-dotenv langchain playwright

3. Set up environment variables:
```bash
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key

4. Run the Streamlit app:
```bash
streamlit run app.py
