# Agentic Chatbot using LangGraph

## Setup

Create and activate a Python 3.11 environment, then install the dependencies:

```powershell
conda create -n langgraph-test python=3.11 -y
conda activate langgraph-test
pip install -r requirements.txt
```

Copy `.env.example` to `.env` and add the API keys for the services you use. Keep `.env` private; it is excluded from Git.

Stock price lookup reads `ALPHAVANTAGE_API_KEY` from the environment. Weather lookup reads `OPENWEATHER_API_KEY`.