# Agentic-AI-App-Generation-

This project showcases a full-stack **Agentic AI system** that converts natural language prompts into complete backend and frontend code using real-world API specifications. It combines **LLMs**, **semantic search**, and **CrewAI agents** to accelerate application development.

## 🔍 Project Objective

To build an intelligent assistant capable of:
- Understanding user intent via natural language
- Retrieving relevant APIs using semantic search
- Generating backend and frontend code with agent collaboration
- Providing an interactive UI for previewing and downloading output

## 📁 Project Structure

```bash
project/
├── api_embeddings.csv              # Structured dataset of API endpoints
├── faiss_search.py                 # Semantic search module using FAISS
├── crew_app.py                     # CrewAI workflow with planning and code generation
├── api_integration.py             # Modular pipeline with logging and orchestration
├── streamlit_app.py               # Streamlit frontend interface
├── notebook.ipynb                 # Jupyter notebook demo and experimentation
└── README.md                      # Project overview and usage instructions
🚀 How It Works
User Prompt: Example - "create patient dashboard" or "add payment method".

Semantic API Search: FAISS returns top relevant APIs using SentenceTransformers.

CrewAI Agent Pipeline:

TaskAnalyzer: Understands intent

APIFinder: Retrieves APIs

Planner: Plans logic flow

CodeWriter: Outputs FastAPI + React code

Preview & Export: Streamlit app displays and lets users download full app code.

🛠 Tech Stack
Python, FastAPI, React, Tailwind CSS

LangChain, CrewAI, FAISS, SentenceTransformers

Streamlit for user interaction

OpenAI GPT-4.5 for advanced reasoning

📦 Installation
bash
Always show details

Copy
git clone https://github.com/your-username/App-Generation-with-Agentic-AI.git
cd App-Generation-with-Agentic-AI
pip install -r requirements.txt
Requirements:

Python 3.9+

OpenAI API Key

streamlit, faiss-cpu, langchain, crewai, etc.

🧪 Run the App
bash
Always show details

Copy
streamlit run streamlit_app.py
🖥 Sample Prompt
"Add a secure payment method for a user"

Output:

FastAPI backend with endpoints

React frontend with styled UI

Downloadable full-stack code bundle

📚 References
LangChain

CrewAI

FAISS

Streamlit

📜 License
MIT License © 2025 Piyush Anil Patil
"""

