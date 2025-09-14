# AI-project-with-LLM-Chat-QA-System
@malcoyuewu's AI project with LLM-Chat/QA System: Interface with FastAPI to send user request to LLM (OpenAI REST), and return result; Frontend with Vite + React; Security: .env no submission with API key in /Github Secerets; Warpped up with Docker)
'''
my-llm-app/
├─ backend/
│  ├─ main.py
│  ├─ requirements.txt
│  └─ Dockerfile
├─ frontend/
│  ├─ package.json
│  ├─ index.html
│  └─ src/
│     └─ App.jsx
├─ .gitignore
└─ README.md
'''

-- cd backend
export OPENAI_API_KEY="sk-xxxx"   # 或用 .env 加载
uvicorn main:app --reload --port 8000
