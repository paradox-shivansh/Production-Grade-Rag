# Agentic Operations
## Learning the base development, deployment and scalability of the agentic AI.
### Architecture
            -> Data-Ingestion (AIR-FLOW) (CI-CD)
            -> Data-Base (Neon DB)
            -> DAG Workflow
            -> Guard-rails implementation (NeMo Guard-rails)
            -> MCP Server for the necessary Tools (Fast-MCP)
            -> Scaling Queries Using Upstash-REDIS (TTL 6-hours), Docker, Kuberneties
            -> BM25 Keyword search
            -> METADATA Filtering (intent based search)
            -> Hybrid Search (BM25+Vector+RRF)
            -> Monitoring Cache (query, model, top_k, catagorical_dorted list ... (Learning)) to REDIS
            -> LangSmith Monitoring
            -> LangGraph for conversion of whole rag application
            -> Backend (fast-api)
            -> Frontend (web-app or telegram bot)
            -> Telegram Integration
            -> Deployment