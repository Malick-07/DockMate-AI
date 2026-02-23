# DockMate AI 🤖

DockMate AI is a personal AI assistant API built using FastAPI and LangGraph.  
It allows users to interact with powerful LLM models and retrieve intelligent responses.

## 🔹 Why I Built This
I created DockMate AI to learn how AI agents, APIs, and LLM orchestration work in real-world applications.

## 🚀 Features
✔ Chat API powered by Groq LLM  
✔ Agent workflow using LangGraph  
✔ Real-time response system  
✔ Clean FastAPI backend  
✔ Environment-based API key management  

## 🛠 Tech Stack
- Python
- FastAPI
- LangGraph
- Groq API
- Tavily Search
- Docker

## ⚙️ Run Locally

1. Clone repo
2. Install dependencies:
   pip install -r requirements.txt
3. Create `.env` file:

   GROQ_API_KEY=your_key  
   TAVILY_API_KEY=your_key  

4. Start server:
   python app.py

5. Open:
   http://127.0.0.1:8000/docs

## 📌 API Endpoint

POST `/chat`

## 📚 What I Learned
- Building AI agents
- FastAPI backend development
- LLM integration
- Environment variable management
- Docker containerization

