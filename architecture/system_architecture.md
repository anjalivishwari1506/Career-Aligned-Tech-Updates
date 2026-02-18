## High-Level Architecture

Pipeline Layers:

1. Ingestion Layer
2. Silver Cleaning & Deduplication
3. Deterministic Scoring Engine
4. Vector Retrieval Layer
5. Controlled LLM Summarization
6. Validation Engine
7. Delivery API Layer

Flow:
Sources → Bronze → Silver → Scoring → Retrieval → LLM → Validation → Gold → API

Key Separation:
Deterministic processing is isolated from generative components.

--------------------------------------------------------------------
