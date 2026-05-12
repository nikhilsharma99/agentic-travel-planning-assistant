# Agentic Travel Planning Assistant

Agentic Travel Planning Assistant is an AI-powered travel planning application built with Python. It uses an agent-based workflow to process user travel queries, call external tools, and generate structured trip plans.

## Features

- Agentic workflow for travel planning
- FastAPI backend for handling user queries
- Streamlit frontend for interactive user input
- Tool-calling support for weather, places, currency conversion, and expense estimation
- Modular project structure with separate components for tools, prompts, configuration, and utilities
- Environment-based API key configuration

## Tech Stack

- Python
- FastAPI
- Streamlit
- LangGraph / LangChain
- External API integrations
- dotenv

## Environment Variables

Create a local `.env` file using `.env.example` as a reference.

```env
OPENAI_API_KEY=
GROQ_API_KEY=
TAVILY_API_KEY=
GOOGLE_API_KEY=