# Enterprise-RAG-Chatbot-
An enterprise-grade Retrieval-Augmented Generation (RAG) chatbot designed for internal technical support and intelligent document querying.

The system supports:
- Multimodal querying (text + image)
- OCR-based document understanding
- Context-aware retrieval
- Google OAuth authentication
- Role-based access control
- Admin analytics dashboard
- ChromaDB vector storage
- AWS Bedrock LLM integration
- Dockerized deployment

- ## Tech Stack
- Python
- Streamlit
- ChromaDB
- LangChain
- AWS Bedrock
- OCR (Tesseract)
- Docker
- MySQL
- Google OAuth
- BM25 Retrieval
- Pillow / OpenCV

- ## Features
- Document ingestion & indexing
- Hybrid retrieval (Vector + BM25)
- OCR-enabled image understanding
- Follow-up query understanding
- Source-aware reranking
- Admin dashboard
- File management system
- User analytics
- Role-based authentication
- Google Login
- OTP-based signup & reset
- Docker deployment

- ## Architecture
  User → Streamlit UI → Retrieval Pipeline → ChromaDB/BM25 → AWS Bedrock → Response Generation

  ## Deployment
```bash
docker compose up --build
