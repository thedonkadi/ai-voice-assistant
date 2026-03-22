# AI Voice Assistant with Multilingual RAG

## 🚀 Overview
This project is a multilingual voice-based AI assistant that can understand Hindi and Telugu speech, retrieve relevant information from documents, and generate contextual responses.

## 🧠 Features
- Speech-to-text using Whisper / IndicWav2Vec
- Retrieval-Augmented Generation (RAG)
- PDF-based semantic search
- Multilingual support (Hindi, Telugu)
- End-to-end voice pipeline

## ⚙️ Tech Stack
- Python
- LangChain
- FAISS / ChromaDB
- HuggingFace Transformers
- Whisper

## 🔄 Pipeline
Speech → Text → Chunking → Embeddings → Vector Search → LLM → Response → Speech

## ▶️ How to Run
```bash
pip install -r requirements.txt