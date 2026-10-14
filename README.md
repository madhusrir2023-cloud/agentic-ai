customer-support-agent
AI-Powered Customer Support Automation System using LangGraph
Project Description
This project is an AI-powered Customer Support Automation System developed using LangGraph. The system automates customer support by classifying customer queries, routing them to the appropriate department, retrieving information using Retrieval-Augmented Generation (RAG), maintaining customer conversation history using SQLite, handling high-risk requests through Human-in-the-Loop approval, and validating responses using a Supervisor Agent.

Features
Accepts customer queries
Intent classification
Department routing
Sales, Technical, Billing, Account and Memory support agents
Retrieval-Augmented Generation (RAG)
ChromaDB vector database
SQLite conversation memory
Human-in-the-Loop approval
Supervisor Agent
Final response generation
Technologies Used
Python
LangGraph
LangChain
ChromaDB
SQLite
Google Gemini API
HuggingFace Embeddings
python-dotenv
Project Structure
CustomerSupportAutomation/
│
├── app.py
├── graph.py
├── state.py
├── classifier.py
├── agents.py
├── rag.py
├── memory.py
├── approval.py
├── supervisor.py
├── documents/
│   ├── pricing.txt
│   ├── policy.txt
│   ├── faq.txt
│   └── technical_manual.txt
├── chroma_db/
├── memory.db
├── requirements.txt
├── .env
└── README.md
Installation
Create Virtual Environment
python -m venv venv
Activate

Windows

.\venv\Scripts\activate
Install Packages
pip install -r requirements.txt
Configure API Key
Create a .env file.

GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
Run the Project
python app.py
Sample Queries
What are the pricing plans available for your software?
I forgot my account password.
My application crashes whenever I upload a file.
I need a refund for my annual subscription.
What was my previous support issue?
Project Workflow
Customer Query

↓

Intent Classification

↓

Department Routing

↓

RAG Retrieval / Memory

↓

Human Approval (if required)

↓

Supervisor Agent

↓

Final Response

Author
R MADHUSRI

Integrated M.Tech Software Engineering

VIT Vellore
