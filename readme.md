# Multi-Agent Business Automation System

## Features

- Research Agent
- Strategy Agent
- Content Agent
- Review Agent
- Gemini AI Integration
- Demo/Fallback Mode
- Intelligent Failover System

## Intelligent Failover System

If API quota is exceeded or the AI provider is unavailable,  
the system automatically switches to fallback business workflow mode,  
ensuring uninterrupted demo and recruiter evaluation.

This prevents application crashes and improves production reliability.

## Tech Stack

- Python
- Streamlit
- Gemini API
- Google GenAI SDK
- Python Dotenv

## Run Project

```bash
pip install -r requirements.txt
streamlit run code.py