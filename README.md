# Heliang Gao

Turning financial documents and business data into answers people can act on, with AI, Python, and SQL.

MSIS @ Santa Clara University (Dec 2026) · 5+ years in mutual funds & asset management · San Jose, CA

## What I'm Building

**[AI Competitive Intelligence Platform](https://github.com/hgao1023/ai-competitive-intelligence)**: SCU × Flex industry practicum, led design and prototype delivery
A RAG-based research assistant for EMS executives and analysts. It tracks CapEx, operating strategy, and market positioning across 6 EMS companies, plus infrastructure spending by 5 hyperscalers as a downstream demand signal.
- Indexed **551 documents / 51,501 passages** (SEC filings, earnings call transcripts, news, facility pages), split along section, paragraph, and table boundaries instead of fixed-length chunks
- Hybrid retrieval: structured financial lookup + keyword + semantic search, passage screening, and recency weighting (news decays faster than filings), with source citations on every answer
- Routes tasks across OpenAI, Anthropic, and Google models with automatic provider failover
- Built FinBERT sentiment analysis, CapEx anomaly flags against each company's history, and a global map of 219 facilities
- Stack: Python, FastAPI, Next.js, SQLite, ChromaDB
- Case selected for *AI for Supply Chain Finance*, Ch. 11 (in preparation)

**[Bank Marketing Prediction & Outreach Strategy](https://github.com/hgao1023/bank-marketing-prediction)**: Machine learning team project (led a 6-person team)
Predicted term-deposit subscriptions from 45,211 customer records. Removed post-call variables to prevent data leakage, compared logistic regression / decision tree / random forest / XGBoost with stratified cross-validation (ROC-AUC, precision, recall, F1), and ran threshold analysis comparing subscriber coverage and net return under assumed contact costs.

**[RAG Meal Recommendation Assistant](https://github.com/hgao1023/rag-meal-recommender)**: Generative AI team project
A lightweight RAG web prototype that retrieves menu data, ranks dishes, and explains each recommendation based on budget, dietary preferences, and natural-language requests.

## Background

Before switching to tech, I spent 5+ years at Chinese fund and asset management firms:
- **Fund operations**: ran full-lifecycle operations for 100+ concurrent products (RMB 40B+ AUM): transfer agency, fund accounting, NAV valuation, distributions
- **Compliance & risk**: product compliance policies and design-stage risk assessments
- **Equity research**: TMT and consumer sector coverage, earnings reviews, company reports and investment recommendations

That's why my projects keep coming back to financial data: I know what the numbers mean and what questions analysts actually ask.

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logo=database&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## Connect

[LinkedIn](https://linkedin.com/in/heliang-gao-b76587165) · San Jose, CA
