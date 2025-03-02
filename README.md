Financial Research AI Agent

Welcome to my Financial Research AI Agent project! 🚀

This project marks my first Agentic AI system, designed to explore how autonomous AI agents can collaborate to perform financial data analysis and web search tasks. Built using Phidata, Groq API, and other advanced tools, this agent is a step towards developing more complex AI systems from scratch.

🌐 Project Overview

The Financial Research AI Agent is a multi-agent system capable of:

Fetching real-time stock market prices 📊

Searching the web for latest financial news 🌐

Summarizing analyst recommendations from financial data

Displaying all gathered information in a structured tabular format

The system uses two AI agents:

Web Search Agent: Gathers the latest news and information from the web using the DuckDuckGo API.

Finance Agent: Fetches stock prices, company news, and analyst recommendations using YFinanceTools.

These agents work collaboratively under the Phidata multi-agent system to generate comprehensive financial reports.

🔑 How It Works

Data Fetching: The Web Search Agent queries the internet for the latest news, while the Finance Agent collects stock market data.

Data Processing: Both agents process their respective data and generate summaries.

Collaboration: The agents collaborate to merge their results into a final structured report.

Presentation: The final output is displayed in tabular format with proper citations.

🔍 Code Implementation

How to Connect

Simply run the following command to start the application:

python playground.py

The app will be available at http://localhost:7777.

🛠️ Tech Stack

Technology

Purpose

Phidata

Agent orchestration and collaboration

Groq API (LLaMA 3)

Core language model for summarization and analysis

YFinanceTools

Stock market data retrieval

DuckDuckGo API

Real-time web search

FastAPI + Uvicorn

Backend API server

Python dotenv

Environment variable management

🔥 Features

Real-time stock price tracking

Web-based financial news search

Analyst recommendations with proper citations

Tabular data representation

Collaborative multi-agent system

🧠 Challenges Faced

Synchronizing two autonomous agents efficiently

Merging financial data with live web search results

Displaying data in an organized, readable format

🔍 Future Roadmap

Build AI agents without frameworks from scratch

Deploy the project on cloud platforms

💪 What I Learned

How to create multi-agent systems

Integration of APIs for web search and financial data

Backend development using FastAPI

This project is part of my journey into Generative AI and autonomous systems. I'm excited to explore more and connect with like-minded individuals.

Thank you for checking out my project!




