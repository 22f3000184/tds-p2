Data Analyst Agent

An AI-powered assistant for smarter, faster, and more intuitive data analysis.

What it Does

Instantly generate insights and visual reports from your datasets

Automate repetitive analysis workflows

Support multiple formats: CSV, Excel, JSON, Parquet, TXT

Key Features

AI-driven analysis with Google Generative AI

Clean visualizations with Seaborn & Matplotlib

Web scraping support for live data

Batch processing for multiple queries

FastAPI backend + modern web UI

Quick Start
git clone https://github.com/your-username/data-analyst-agent.git
cd data-analyst-agent
pip install -r requirements.txt


Create a .env file:

GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240


Run:

python -m uvicorn app:app --reload

Visit: http://localhost:8000/
