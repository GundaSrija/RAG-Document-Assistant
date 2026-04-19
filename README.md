# 🚀 RAG-based Document Assistant

## 📌 Overview
This project is a Retrieval-Augmented Generation (RAG) system that enables users to query documents and receive accurate, context-aware answers using Large Language Models (LLMs). It combines semantic search with generative AI to improve response relevance and reliability.

---

## ⚙️ Tech Stack
- Python  
- LangChain  
- FAISS (Vector Database)  
- OpenAI API (LLM)  
- FastAPI (deployment-ready architecture)  

---

## 🔄 RAG Pipeline
Document → Chunking → Embeddings → FAISS → Retrieval → LLM → Response  

---

## 🧠 Key Highlights
- Semantic search using FAISS  
- Context-aware response generation using LLMs  
- Efficient retrieval over large document datasets  
- Modular ETL pipeline for document processing  

---

## 📸 Example

**Question:** What is the summary of the document?  

**Answer:**  
This document explains the key concepts of machine learning, including supervised and unsupervised learning. It highlights the importance of data preprocessing and model evaluation.


<img width="635" height="236" alt="image" src="https://github.com/user-attachments/assets/0ac91d12-36df-4111-a818-b73b9ac3daad" />


---

## 🚀 Deployment
- Designed API-based architecture using FastAPI  
- Can be deployed on platforms like Render, AWS, or Hugging Face  

---

## ▶️ How to Run

```bash
git clone https://github.com/GundaSrija/RAG-Document-Assistant
cd RAG-Document-Assistant
pip install -r requirements.txt
python app.py
