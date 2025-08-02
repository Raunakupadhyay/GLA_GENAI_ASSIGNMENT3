# GLA_GENAI_ASSIGNMENT3
# 🤖 Practical RAG Pipeline

This repository contains a complete, minimal Retrieval-Augmented Generation (RAG) pipeline built from scratch using **Hugging Face Transformers**, **FAISS**, and **PyMuPDF**, without relying on LangChain.

---

## 🔍 Features

- 📄 Load and process PDF documents
- ✂️ Split documents into manageable chunks
- 🔐 Convert chunks to embeddings using `sentence-transformers/all-MiniLM-L6-v2`
- 💾 Store and retrieve embeddings using FAISS
- 🤖 Answer questions using `google/flan-t5-base` from Hugging Face
- 🔁 Compare raw LLM response vs RAG-enhanced answers
- 🧪 Works fully offline with open-source models (no OpenAI key required)

---
