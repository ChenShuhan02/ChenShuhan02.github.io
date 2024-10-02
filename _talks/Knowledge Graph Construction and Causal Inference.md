---
title: "Knowledge Graph Construction and Causal Inference"
collection: talks
type: "📚 Research Projects"
permalink: /talks/2012-03-01-talk-1
date: 2024-9
---

### 1. [Knowledge Graph Construction and Causal Inference](https://github.com/ChenShuhan02/Knowledge-Graph-Construction-and-Causal-Inference)

**Author**: Shuhan Chen  
**Date**: 2024  
**Focus**: Financial News Sentiment Analysis, Knowledge Graph Construction, and Causal Inference  
**Target Stock**: Apple Inc. (AAPL)  

#### 📜 Overview
This project explores the relationship between financial news and stock price movements by constructing a **knowledge graph** and conducting **causal inference** analysis. The goal is to determine if and how financial news sentiment influences the stock price of Apple Inc.

Key components include:
- **Data Collection**: Financial news and Apple stock price data.
- **NLP Analysis**: Sentiment analysis using **TextBlob** and entity extraction with **spaCy**.
- **Knowledge Graph**: Built with **Neo4j** to visualize relationships between financial entities.
- **Causal Inference**: Conducted using **Granger causality tests** to establish any potential causal links.

#### 🔗 Links
- **GitHub Repository**: [Knowledge Graph Construction and Causal Inference Project](https://github.com/ChenShuhan02/Knowledge-Graph-Construction-and-Causal-Inference)

#### 🔑 Key Highlights
- Used web scraping to collect financial news articles related to Apple Inc.
- Conducted sentiment analysis on the news articles to determine the impact on stock price.
- Developed a knowledge graph to model relationships among entities, enabling a deeper understanding of the financial domain.
- Granger causality analysis showed no significant evidence that news sentiment drives stock prices during the selected period.

#### 🛠️ Methodology Summary
- **Data Collection**: Financial news was gathered using NewsAPI, while Apple stock price data was retrieved from Yahoo Finance API.
- **Data Processing**: Normalized publication dates, performed sentiment analysis, and extracted key entities.
- **Knowledge Graph Construction**: Used **Neo4j** for storing entities and relationships.
- **Causal Analysis**: Applied Granger causality testing to assess if sentiment scores influence stock prices.

#### 📊 Results Overview
- The knowledge graph successfully mapped relationships between key financial entities such as corporations, products, and partnerships.
- Causal inference testing revealed no significant causal impact of news sentiment on stock price during the studied period.

#### 🚀 Future Work
- **Expand Data Collection**: Incorporate additional historical data and include more financial events.
- **Advanced NLP**: Use state-of-the-art models such as **BERT** or **FinBERT** for improved sentiment analysis.
- **Real-Time Integration**: Extend the project to include real-time analysis and dynamic knowledge graph updates.

---

