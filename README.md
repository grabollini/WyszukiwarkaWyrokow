Semantic Legal Search Engine (Django + Faiss) ⚖️🔍

An AI-powered search engine designed for legal documents (court judgments). Unlike traditional keyword-based systems, this application understands the semantic context of queries, allowing users to find relevant legal cases even if they don't use exact legal terminology.

🚀 Key Features

Hybrid Search Engine: Combines Semantic (Vector) search with a Keyword (Textual) fallback.
Vector Embeddings: Utilizes the sentence-transformers (all-MiniLM-L6-v2) model to convert legal text into dense vectors.
Fast Similarity Search: Powered by Faiss (Facebook AI Similarity Search) for high-performance indexing.
SQLite Integration: Efficiently stores metadata and document content in SQLite.
Similarity Thresholding: Intelligent filtering to ensure that only relevant results are returned (avoiding noise).

🛠️ Tech Stack

Backend: Python 3.10+, Django 5.x
AI/ML: Sentence-Transformers, Faiss
Database: SQLite
Frontend: Django Templates (HTML/CSS)
