📊 Stock Market News Sentiment Analyzer & AI-Driven Portfolio Simulator

A news-driven stock sentiment analysis system that uses FinBERT (NLP) to analyze real-time financial news, generate BUY / SELL / HOLD trading signals
and simulate a paper-trading portfolio with live market prices — all presented through an interactive Streamlit dashboard.
🚀 Features
📰 News Sentiment Analysis

Fetches real-time financial news using NewsAPI

Uses FinBERT (Transformer-based NLP model) for accurate financial sentiment classification

Classifies each article as Bullish, Bearish, or Neutral

📈 Trading Signal Generation

Aggregates sentiment across multiple news articles

Generates BUY / SELL / HOLD signals using configurable sentiment thresholds

Displays confidence levels and clear reasoning behind each signal

💼 Paper Trading Portfolio Simulator

Simulates real trading without financial risk

Automatically executes trades based on signals

Tracks:

Portfolio equity

Cash balance

Open positions

Realized & unrealized PnL

Uses live stock prices via YFinance

📊 Interactive Dashboard (Streamlit)

Color-coded trade signals (BUY / SELL / HOLD)

Per-stock sentiment breakdown

Sentiment trends over time

Portfolio equity curve visualization

Auto-refresh support for near-real-time updates

📄 Report Generation

Generate and download a text-based analysis report

Includes:

Watchlist

Signals

Portfolio snapshot

Sentiment summary and explanations

🛠️ Tech Stack
Programming & Frameworks

Python

Streamlit

Machine Learning / NLP

FinBERT (HuggingFace Transformers)

PyTorch

APIs & Data

NewsAPI (financial news)

YFinance (real-time stock prices)

Data & Visualization

Pandas

NumPy

Altair

Deployment

Streamlit Cloud

🧠 System Architecture (High Level)

News Fetching

Collects recent articles for each stock symbol using NewsAPI

Sentiment Analysis

FinBERT analyzes article text and outputs sentiment + confidence score

Sentiment Aggregation

Combines multiple articles into a single sentiment score per stock

Signal Generation

Rule-based logic converts sentiment score → BUY / SELL / HOLD

Portfolio Simulation

Executes trades virtually and updates portfolio state

Visualization

Streamlit dashboard renders all insights interactively
