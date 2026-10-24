<h1 align="center">Hi 👋, I'm Rimsha Kanwal</h1>

<h3 align="center">AI Engineer · LLMs, RAG & AI Agents · AWS</h3>

<p align="center">I build AI systems that read documents, retrieve evidence and answer with sources, and I deploy and automate them on AWS.</p>

<p align="center">
  <a href="mailto:rimshakanwal7110@gmail.com"><img src="https://img.shields.io/badge/Email-rimshakanwal7110%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/rimsha-kanwal-02a664309/"><img src="https://img.shields.io/badge/LinkedIn-Rimsha%20Kanwal-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://medium.com/@rimshakanwal7110"><img src="https://img.shields.io/badge/Medium-@rimshakanwal7110-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium"></a>
  <img src="https://img.shields.io/badge/Location-Pakistan-2E7D32?style=flat-square" alt="Location: Pakistan">
</p>

---

## About me

- **AI Engineer** focused on **LLM applications**: Retrieval-Augmented Generation, tool-calling agents and evaluation.
- I enjoy the whole path from **data → model → API → cloud**: fine-tuning transformers, building retrieval pipelines and shipping them with Docker and AWS.
- I measure what I build: benchmarks, ablations and honest limitations go in every README.
- **Open to roles:** AI Engineer · Machine Learning Engineer · Generative AI Engineer.

---

## Featured project

### [DocuMind AI: Agentic Multimodal Document Intelligence](https://github.com/RimshaKanwal0/DocuMind_AI_)

Ask questions about PDFs (text, tables, charts and scanned pages) and get answers cited to the exact page, with the source highlighted.

- **Agentic RAG:** a tool-calling LLM agent that searches, reads tables, calculates exactly and inspects charts with a vision model
- **Hybrid retrieval:** BM25 + **pgvector**, fused with Reciprocal Rank Fusion, then a **fine-tuned PyTorch cross-encoder** (top-1 retrieval **37.9% → 62.1%** on unseen documents)
- **Grounding:** citation validation, plus an LLM-as-judge verifier in Agent mode
- **Engineering:** FastAPI · PostgreSQL + pgvector (HNSW) · background workers · 63 tests

`Python` `OpenAI` `PyTorch` `pgvector` `FastAPI` `PostgreSQL` `Docker`

---

## Projects

### 🤖 LLMs, NLP & RAG

| Project | What it does | Stack |
|---|---|---|
| [**FinSentiments (FYP)**](https://github.com/RimshaKanwal0/FinSentiments_FYP) | Financial news sentiment platform: ML + FinBERT/RoBERTa, NewsAPI, Prophet sentiment forecasting, Django dashboards, deployed on AWS EC2 | PyTorch · Transformers · Django · Docker · PostgreSQL · AWS |
| [**Financial Sentiment: RoBERTa (95%)**](https://github.com/RimshaKanwal0/FinancialSentiment-accuracy95) | Fine-tuned RoBERTa for financial sentiment with a class-weighted loss: **95% accuracy, F1 0.95** | Hugging Face · PyTorch |
| [**RAG System**](https://github.com/RimshaKanwal0/rag-system) | A Retrieval-Augmented Generation pipeline from scratch: chunking, BGE embeddings, ChromaDB retrieval and grounded generation | LangChain · ChromaDB · Transformers |

### ☁️ AWS & Data Engineering

| Project | What it does | Stack |
|---|---|---|
| [**Serverless Resume Parser**](https://github.com/RimshaKanwal0/Serverless-Resume-Parser-using-AWS) | Event-driven resume parsing: Textract extraction, structured fields in DynamoDB, SNS notifications, Athena queries | Lambda · Textract · S3 · DynamoDB · SNS · Athena |
| [**YouTube Trending Data Pipeline**](https://github.com/RimshaKanwal0/youtube-trending-data-pipeline) | Serverless daily pipeline for trending-video data from 113 countries, with SQL analytics and dashboards | EventBridge · Lambda · S3 · Athena · QuickSight · SES |
| [**Amazon Books ETL Pipeline**](https://github.com/RimshaKanwal0/amazon-books-data-pipeline) | Airflow DAG that scrapes book listings and loads them into PostgreSQL | Apache Airflow · PostgreSQL · Docker |

### 📊 Machine Learning & Analytics

| Project | What it does | Stack |
|---|---|---|
| [**Customer Churn Prediction**](https://github.com/RimshaKanwal0/Customer-Churn-Prediction) | Churn classification with class-imbalance handling, ML vs deep learning comparison and business recommendations | Scikit-learn · Keras |
| [**Sleep Disorder Prediction**](https://github.com/RimshaKanwal0/Sleep-Disorder-Prediction-using-ML-DL) | Predicts insomnia or sleep apnea from health and lifestyle data, comparing ML models with a Keras network | Scikit-learn · Keras |
| [**LiveNewsLens**](https://github.com/RimshaKanwal0/LiveNewsLens) | Real-time news analytics: NewsAPI ingestion, SQL storage, sentiment analysis and visualizations | R · SQLite · tidytext |
| [**Grants.gov Web Scraper**](https://github.com/RimshaKanwal0/web-scraper) | Paginated Selenium scraper with retries and logging that exports grant opportunities to CSV | Python · Selenium |

---

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,tensorflow,fastapi,django,postgres,mongodb,mysql,docker,aws,git,r&perline=13" alt="Python, PyTorch, scikit-learn, TensorFlow, FastAPI, Django, PostgreSQL, MongoDB, MySQL, Docker, AWS, Git, R">
</p>

| Area | Tools |
|---|---|
| **LLMs & GenAI** | OpenAI API (function calling) · RAG · AI agents · Hugging Face Transformers · LangChain · prompt engineering |
| **Retrieval** | pgvector · ChromaDB · FAISS · BM25 · Reciprocal Rank Fusion · cross-encoder reranking |
| **ML / DL** | PyTorch · Scikit-learn · Keras/TensorFlow · fine-tuning (RoBERTa, cross-encoders) · NLP · computer vision (YOLOv5) |
| **AWS** | Lambda · S3 · EC2 · RDS · DynamoDB · Textract · Athena · EventBridge · SNS/SES · QuickSight · CloudWatch |
| **Data & backend** | FastAPI · Django · PostgreSQL · MongoDB · MySQL · Apache Airflow · Pandas · SQL |
| **Delivery** | Docker · Docker Compose · Git · pytest |

---

## Currently learning

- Agentic AI architectures and LLM evaluation (LLM-as-judge, RAG metrics)
- LLMOps / MLOps: model lifecycle, monitoring and CI/CD
- Advanced AWS data services: Glue, Redshift

---

## Writing

I write on [Medium](https://medium.com/@rimshakanwal7110) about RAG systems, AWS deployments, data pipelines and AI engineering.

---

<p align="center"><b>Let's build reliable AI together.</b> Reach me by <a href="mailto:rimshakanwal7110@gmail.com">email</a> or on <a href="https://www.linkedin.com/in/rimsha-kanwal-02a664309/">LinkedIn</a>.</p>
