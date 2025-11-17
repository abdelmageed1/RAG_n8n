# 🚀 RAG Automation with n8n, Gemini & Pinecone

This repository contains a lightweight **RAG (Retrieval-Augmented Generation)** workflow built using **n8n**, integrating Google Drive, Gemini Embeddings, Gemini Chat Model, and Pinecone.

---

## 📌 Overview
This automation workflow:
- Detects new files uploaded to **Google Drive**
- Downloads and processes the document
- Generates **embeddings using Gemini**
- Stores vectors in **Pinecone**
- Uses **Gemini Chat Model** to answer questions based on the uploaded file (e.g., my CV)

---

## 🧩 Tech Stack
- **n8n** – Workflow automation  
- **Google Drive** – File trigger  
- **Gemini Embeddings** – Vector generation  
- **Gemini Chat Model** – Intelligent Q&A  
- **Pinecone** – Vector database  

---

## ⚙️ Workflow Summary
1. Google Drive file upload triggers the workflow  
2. n8n downloads and parses the file  
3. Gemini generates embeddings  
4. Embeddings are stored in Pinecone  
5. Gemini Chat Model retrieves relevant vectors and answers user questions  

---

## 🎯 Purpose
A simple, visual RAG pipeline demonstrating how to automate document understanding using n8n + Gemini + Pinecone.

---
