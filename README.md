# AI-Driven Prediction Market Arbitrage 🤖💹

An advanced trading bot designed to identify and execute arbitrage opportunities across prediction markets (Polymarket, Kalshi) by leveraging Large Language Models (LLMs) for real-time news analysis and event probability estimation.

## 🌟 Key Features
- **LLM Sentiment Engine:** Uses GPT-4o/Claude-3.5 to analyze global news feeds and social media for event-driving catalysts.
- **Cross-Market Arbitrage:** Identifies price discrepancies between Polymarket (On-chain) and Kalshi (CLOB).
- **Probabilistic Modeling:** Re-calculates event probabilities based on "Wisdom of the Crowd" vs. AI-inferred data.
- **Automated Execution:** High-speed execution using Polymarket SDK and Kalshi API.

## 🏗️ Architecture
1. **Ingestion Layer:** Real-time stream from X (Twitter), News APIs, and Market Orderbooks.
2. **Analysis Layer:** RAG-enhanced LLM processing to filter noise and identify relevant market shifts.
3. **Execution Layer:** Strategy-based order placement with slippage protection.

## 🚀 Quick Start
```bash
pip install -r requirements.txt
python main.py --market "US Election 2024"
```