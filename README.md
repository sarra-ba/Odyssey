# Sustainability AI Agent

This project evaluates the sustainability of Ethereum-based projects by scraping data from various online sources, analyzing it with Natural Language Processing (NLP), and generating ESG (Environmental, Social, Governance) scores. The project includes automated alerts and tracking systems for monitoring sustainability claims and changes in real-time.

## Use Case 3: Sustainability AI Agent

### Technologies and Tools Used

#### Web Scraping
- **Scrapy / BeautifulSoup (Python)**: For scraping static web pages.
- **Selenium / Puppeteer**: For scraping JavaScript-rendered content.
- **APIs (GraphQL)**: For querying Ethereum-based project data and ESG databases.
- **IPFS/Arweave Access**: To access documents stored on decentralized storage.

#### Natural Language Processing (NLP) Analysis
- **Purpose**: Identify and evaluate sustainability claims, keywords, and sentiment in extracted data.
- **Technologies**:
  - **DeepSeek, ChatGPT, or Llama-based Models**: For NLP text understanding.
  - **spaCy & NLTK**: For text preprocessing (tokenization, named entity recognition).
  - **BERT/RoBERTa**: ESG keyword classification.
  - **FinBERT**: Sentiment analysis for financial sustainability statements.

#### ESG Scoring Model
- **Purpose**: Evaluate sustainability metrics based on predefined ESG criteria.
- **Key ESG Metrics for Crypto Projects**:
  - **Energy Consumption**: Blockchain energy usage (Ethereum vs. Layer 2).
  - **Carbon Offsets**: Use of carbon credits, partnerships (e.g., KlimaDAO).
  - **Governance**: Decentralization score, DAO governance structure.
  - **Transparency**: Frequency of sustainability updates, partnerships.
- **Technologies**:
  - **AI-driven ESG Scoring Models**: Custom ML models trained on sustainability reports.
  - **Explainable AI (XAI)**: SHAP, LIME for ESG decision transparency.
  - **Data Sources**: Carbon tracking APIs (e.g., Greenly, KlimaDAO).

#### Scoring System & Report Generation
- **Purpose**: Generate sustainability scores and insights for Ethereum-based projects.
- **Technologies**:
  - **Scikit-learn / XGBoost**: For ESG score modeling.
  - **Power BI / Tableau**: For data visualization dashboards.
  - **Matplotlib / Plotly**: For visualizing ESG score trends.
  - **Markdown/PDF Report Generation**: Automated ESG report generation.

#### Automated Alerts & Tracking System
- **Purpose**: Monitor and alert on changes in sustainability statements, ESG policies, and project updates.
- **Technologies**:
  - **Cron Jobs / Cloud Functions**: For scheduled re-scraping and analysis.
  - **Webhook Integrations**: Alerts via Telegram, Slack, or Email.
  - **Vector Databases (FAISS, Pinecone)**: For tracking document history and changes.

---

## Project Flow

1. **Web Scraping**: 
   - Scrape relevant data from Ethereum-based projects (e.g., sustainability reports, updates, governance documents).
   - Use Scrapy, Selenium, and APIs for real-time data fetching.

2. **NLP Analysis**: 
   - Extract relevant text data from scraped content.
   - Perform NLP tasks like entity recognition, sentiment analysis, and keyword classification.
   - Analyze sustainability claims, financial transparency, and governance aspects.

3. **ESG Scoring**: 
   - Evaluate projects against key ESG metrics using AI-driven models.
   - Assign scores based on environmental impact, governance, transparency, and other sustainability factors.
   - Use explainable AI methods for decision transparency.

5. **visualization**: 
   
---

## Installation

### Steps to Install
1. Clone this repository
   cd web3scraper 
   
