<h1 align="center">Hi, I'm Rimsha Kanwal 👋</h1>

<h3 align="center">AI Engineer | LLM Applications, RAG & AI Agents</h3>

<p align="center">
  I build document intelligence and conversational AI systems, with a focus on retrieval quality, grounded answers and deployment on AWS.
</p>

<p align="center">
  <a href="mailto:rimshakanwal7110@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email Rimsha"></a>
  <a href="https://www.linkedin.com/in/rimsha-kanwal-02a664309/"><img src="https://img.shields.io/badge/LinkedIn-Rimsha_Kanwal-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://discord.com/users/1485359820889526272"><img src="https://img.shields.io/badge/Discord-Message_me-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://medium.com/@rimshakanwal7110"><img src="https://img.shields.io/badge/Medium-Articles-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium"></a>
  <img src="https://img.shields.io/badge/Based_in-Pakistan-2E7D32?style=flat-square" alt="Based in Pakistan">
</p>

## About me

I'm an AI engineer building LLM applications that turn unstructured information into useful, source-backed answers.

My work spans retrieval pipelines, tool-calling agents, model fine-tuning and backend development with Python, FastAPI, PostgreSQL and AWS. I evaluate what I build with retrieval benchmarks and automated tests, and I document the limitations.

**Open to opportunities:** AI Engineer · Generative AI Engineer · Machine Learning Engineer

## Featured projects

### 📄 DocuMind AI: Multimodal Document Intelligence

An agentic RAG application that answers questions across PDF text, tables, charts and scanned pages, with page-level citations and highlighted source evidence.

- Built a tool-calling agent for document search, table extraction, numerical calculations and chart interpretation.
- Combined BM25 and pgvector retrieval using Reciprocal Rank Fusion, followed by a fine-tuned PyTorch cross-encoder.
- Improved top-1 retrieval accuracy from 37.9% to 62.1% on a held-out synthetic evaluation set.
- Implemented citation validation, LLM-based answer verification, background workers and 63 automated tests.
- Built the backend with FastAPI and PostgreSQL, using pgvector HNSW indexing.

**Stack:** Python · OpenAI API · PyTorch · FastAPI · PostgreSQL · pgvector · Docker

### 🎙️ AI Voice Agent: Hospital Receptionist

A conversational voice assistant that answers hospital questions and manages appointments through API tools.

- Integrated Vapi with Deepgram speech recognition, GPT-4o and ElevenLabs voice synthesis.
- Developed four FastAPI tools for knowledge-base Q&A, appointment booking, appointment listing and cancellation.
- Built RAG-based answers with source citations, a local fallback when no LLM key is configured, and automated tests.

**Stack:** Python · FastAPI · Vapi · OpenAI API · RAG · SQLAlchemy · Streamlit

### 📈 [FinSentiments: Financial News Sentiment Platform](https://github.com/RimshaKanwal0/FinSentiments_FYP)

A final-year project combining financial news ingestion, sentiment analysis, forecasting and interactive dashboards.

- Integrated NewsAPI with machine learning models and transformer-based sentiment models, including FinBERT and RoBERTa.
- Used Prophet to forecast sentiment trends.
- Built Django dashboards and deployed the application with Docker on AWS EC2.

**Stack:** Python · PyTorch · Transformers · Django · PostgreSQL · Docker · AWS EC2

## More projects

<details>
<summary><b>LLMs, NLP & retrieval</b></summary>

<br>

| Project | Focus | Stack |
|---|---|---|
| LoRA-RAG Chatbot | Research-PDF Q&A using synthetic training data, LoRA fine-tuning of GPT-Neo 125M and embedding-based retrieval | Python · Hugging Face · PEFT · FAISS · LangChain |
| RAGTube | YouTube transcript ingestion, overlapping chunks, near-duplicate filtering and Q&A with a LoRA fine-tuned GPT-Neo model | Python · OpenAI API · FAISS · LoRA |
| [Financial Sentiment: RoBERTa](https://github.com/RimshaKanwal0/FinancialSentiment-accuracy95) | Financial sentiment classification with fine-tuned RoBERTa and a class-weighted loss: **95% accuracy, F1 0.95** | PyTorch · Hugging Face |
| [RAG System](https://github.com/RimshaKanwal0/rag-system) | Retrieval pipeline with chunking, BGE embeddings, ChromaDB and grounded generation | LangChain · ChromaDB · Transformers |

</details>

<details>
<summary><b>AWS & data engineering</b></summary>

<br>

| Project | Focus | Stack |
|---|---|---|
| [Serverless Resume Parser](https://github.com/RimshaKanwal0/Serverless-Resume-Parser-using-AWS) | Event-driven resume extraction, structured storage, notifications and SQL queries | Lambda · Textract · S3 · DynamoDB · SNS · Athena |
| [YouTube Trending Data Pipeline](https://github.com/RimshaKanwal0/youtube-trending-data-pipeline) | Daily trending-video data pipeline covering 113 countries, with analytics and dashboards | EventBridge · Lambda · S3 · Athena · QuickSight · SES |
| [Amazon Books ETL Pipeline](https://github.com/RimshaKanwal0/amazon-books-data-pipeline) | Airflow workflow that scrapes book listings and loads them into PostgreSQL | Python · Apache Airflow · PostgreSQL · Docker |

</details>

<details>
<summary><b>Machine learning & analytics</b></summary>

<br>

| Project | Focus | Stack |
|---|---|---|
| [Customer Churn Prediction](https://github.com/RimshaKanwal0/Customer-Churn-Prediction) | Churn classification, class-imbalance handling, and a comparison of ML and deep learning approaches | Scikit-learn · Keras |
| [Sleep Disorder Prediction](https://github.com/RimshaKanwal0/Sleep-Disorder-Prediction-using-ML-DL) | Health and lifestyle classification comparing ML models with a neural network | Scikit-learn · Keras |
| [LiveNewsLens](https://github.com/RimshaKanwal0/LiveNewsLens) | News ingestion, SQL storage, sentiment analysis and visualizations | R · SQLite · tidytext |
| [Grants.gov Web Scraper](https://github.com/RimshaKanwal0/web-scraper) | Paginated grant-opportunity extraction with retries, logging and CSV export | Python · Selenium |

</details>

## Technical skills

| Area | Technologies |
|---|---|
| **LLMs & agents** | OpenAI API · tool calling · RAG · Hugging Face Transformers · LangChain · LoRA / PEFT |
| **Retrieval & evaluation** | pgvector · FAISS · ChromaDB · BM25 · Reciprocal Rank Fusion · cross-encoder reranking · LLM-as-judge |
| **Machine learning** | PyTorch · Scikit-learn · TensorFlow / Keras · NLP · transformer fine-tuning |
| **Backend & data** | FastAPI · Django · PostgreSQL · MongoDB · MySQL · SQL · Pandas · Apache Airflow |
| **AWS** | EC2 · Lambda · S3 · RDS · DynamoDB · Textract · Athena · EventBridge · SNS · SES · QuickSight · CloudWatch |
| **Development & delivery** | Docker · Docker Compose · Git · pytest |

## Currently learning

- Agentic architectures and systematic evaluation of LLM applications
- LLMOps and MLOps: model lifecycle, monitoring and CI/CD
- AWS Glue and Amazon Redshift

## Writing

I share practical lessons on RAG systems, AWS deployments, data pipelines and AI engineering on [Medium](https://medium.com/@rimshakanwal7110).

<p align="center">
  <b>Let's build reliable AI systems.</b><br>
  <a href="mailto:rimshakanwal7110@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/rimsha-kanwal-02a664309/">LinkedIn</a> ·
  <a href="https://discord.com/users/1485359820889526272">Discord</a>
</p>
