# 🔍 Multi Agent Search-Enabled Chatbot with Groq & Streamlit

This project is a Streamlit-based chatbot that uses LangChain agents to search the web, Wikipedia, and Arxiv in real-time. It is powered by Groq's LLaMA3-8B model and provides interactive responses with reasoning steps.

## 🚀 Features

- Chatbot interface using Streamlit
- Real-time search via DuckDuckGo, Wikipedia, and Arxiv
- LangChain agent with ZERO_SHOT_REACT_DESCRIPTION
- Displays agent thoughts and actions using StreamlitCallbackHandler
- Secure API key input via sidebar

## 🧠 Technologies Used

- LangChain
- Groq API (LLaMA3-8B)
- DuckDuckGo Search Tool
- Wikipedia API Wrapper
- Arxiv API Wrapper
- Streamlit
- Python
- dotenv

## 📁 File Structure

- `app.py`: Main Streamlit application
- `.env`: Stores your Groq API key

## 🔐 Environment Variables

Create a `.env` file with the following key:

GROQ_API_KEY=your_groq_api_key

## 🛠️ How to Run

1. Clone the repository:
```
git clone https://github.com/yourusername/langchain-search-chatbot.git
cd langchain-search-chatbot
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Add your .env file with API keys.


4. Run the Streamlit app:
```
streamlit run app.py
```
