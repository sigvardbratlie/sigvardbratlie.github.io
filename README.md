# Sigvard Bratlie TEST

**Data Scientist & AI Engineer**  
Building intelligent systems — from legal agents to market valuation platforms

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sigvardbratlie/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sigvardbratlie)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sigvardbratlie@gmail.com)

## About Me

I'm passionate about **LLMs**, **computer vision**, **data pipelines** and turning complex data into actionable insights or autonomous agents.  
Currently exploring agentic AI, multimodal models, scalable ETL and production-grade ML systems — mostly in Python, with heavy use of Google Cloud, LangChain/LangGraph and modern MLOps.

Master's thesis focused on **Agentic Legal AI** — building LLM-powered assistants for lawyers.

## 🚀 Project Portfolio

Here are some of my key projects:

### ⚖️ Agentic Legal AI (Master's Thesis)
**LLM-powered legal case management agent**  
Intelligent agent that helps lawyers with case summarization, structured fact extraction, document analysis, RAG on Norwegian law and real-time chat assistance.

- **Tech stack**: LangGraph, LangChain, Gemini / GPT / Claude, FastAPI, Streamlit, Supabase (Auth + PostgreSQL + Storage), BigQuery Vector Store, Tavily Search  
- **Highlights**: Structured Factsheet (Pydantic), multi-phase document processing pipeline, streaming SSE chat, Supabase auth + JWT  
- **GitHub**: [sigvardbratlie/master-thesis](https://github.com/sigvardbratlie/master-thesis)

### 📊 Weather & Electricity Dashboard
Interactive multi-page Streamlit dashboard exploring Norwegian electricity production/consumption vs historical weather data.

- **Features**: Time-series & pie charts (Plotly), STL decomposition, forecasting, outlier detection (LOF), Folium map of price areas (NO1–NO5), correlation heatmaps, snow drift calculations  
- **Data sources**: Elhub API, Open-Meteo (ERA5)  
- **Tech stack**: Streamlit, Plotly, Pandas, scikit-learn, statsmodels, Folium, River  
- **GitHub**: [sigvardbratlie/ind320-dashboard](https://github.com/sigvardbratlie/ind320-dashboard)

### 🌾 Rumex Detection Model
YOLO11-based object detection of dock weed (Rumex) in drone imagery for automated grassland monitoring.

- **Key result**: Data augmentation boosted recall from ~5% to ~70% (mAP@50 up to 0.587)  
- **Models compared**: YOLO11n vs YOLO11s, with/without heavy augmentation  
- **Tech stack**: Ultralytics YOLO11, Albumentations, Label Studio, Jupyter  
- **GitHub**: [sigvardbratlie/rumex-detection](https://github.com/sigvardbratlie/rumex-detection)

### 📈 Market Data ETL Pipeline
End-to-end scraping & enrichment pipeline for Norwegian marketplace data (Finn.no).

- **Categories**: Cars, homes, rentals, jobs, boats, motorcycles  
- **Enrichment**: Geonorge (Nominatim), Statens Vegvesen, Kartverket/Grunnbok  
- **Tech stack**: Scrapy + Playwright, XGBoost/CatBoost/LightGBM, Google Cloud (BigQuery, Vertex AI, Kubeflow Pipelines), uv  
- **GitHub**: [sigvardbratlie/sibr-market-data-etl](https://github.com/sigvardbratlie/sibr-market-data-etl)

### 🏠💰 SIBR Market – AI Valuation Platform
Conversational AI platform for real estate and vehicle valuations using LLM agents + public Norwegian registries.

- **Features**: Chat-based valuation, Google OAuth, streaming responses, PDF reports, BigQuery analytics, multi-LLM support (Gemini / GPT-4o / Claude)  
- **Tech stack**: LangGraph agents, Streamlit UI, FastAPI backend, Google Cloud Run, Firestore, WeasyPrint, Plotly  
- **GitHub**: [sigvardbratlie/sibr-market](https://github.com/sigvardbratlie/sibr-market)

---

