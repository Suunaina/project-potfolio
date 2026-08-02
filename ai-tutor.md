# 🤖 AI Tutor for Subject-Specific Learning using LLM

> **Status:** ✅ Completed

A Retrieval-Augmented Generation (RAG) based AI learning assistant that answers questions from uploaded academic PDFs. Instead of relying solely on a language model's knowledge, the system retrieves relevant information from user-provided documents and generates context-aware responses.

---

## 🚀 Overview

The AI Tutor enables users to upload academic PDFs and interact with them through natural language questions. By combining semantic search with Retrieval-Augmented Generation (RAG), the application ensures that responses are grounded in the uploaded document, improving accuracy and reducing hallucinations.

---

## ✨ Features

- Upload academic PDF documents
- Automatic text extraction and preprocessing
- Semantic search using vector embeddings
- Retrieval-Augmented Generation (RAG)
- Context-aware question answering
- Interactive Streamlit interface
- Efficient document indexing with FAISS

---

## 🛠 Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### AI & Machine Learning
- FLAN-T5
- Sentence Transformers (all-MiniLM-L6-v2)

### Vector Database
- FAISS

### NLP
- PDF Text Extraction
- Text Chunking
- Semantic Search

---

## ⚙️ How It Works

1. The user uploads an academic PDF.
2. The document text is extracted and divided into smaller chunks.
3. Sentence Transformers generate vector embeddings for each chunk.
4. The embeddings are stored in a FAISS vector database.
5. When a question is asked, semantic search retrieves the most relevant document chunks.
6. FLAN-T5 generates a context-aware answer using only the retrieved content.

---

## 🧠 System Architecture

### Document Processing
- Extracts text from uploaded PDFs
- Splits documents into manageable chunks

### Embedding Generation
- Converts text chunks into dense vector embeddings using Sentence Transformers

### Semantic Retrieval
- Uses FAISS to efficiently retrieve the most relevant information for a query

### Answer Generation
- FLAN-T5 generates accurate responses grounded in the retrieved document context

---

## 🎯 Learning Objectives

This project explores the core concepts behind Retrieval-Augmented Generation (RAG), semantic search, vector databases, and document-based question answering. It demonstrates how combining retrieval with language models improves response accuracy for domain-specific content.

---

## 🔮 Future Improvements

- Support multiple document uploads
- Chat history and conversational memory
- Citation highlighting for generated answers
- Support for additional document formats
- Integration with cloud-hosted LLMs
- User authentication and document management

---

## 👩‍💻 Author

Developed by **Sunaina** as an academic project demonstrating Retrieval-Augmented Generation (RAG), semantic search, vector databases, and LLM-powered document question answering.
