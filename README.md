# 🤖 gemini_qa_chatbot

A **Conversational Q&A Chatbot** that lets users ask questions from a collection of PDF documents using **LangChain**, **FAISS**, and **Google Gemini Pro (Free API)**. This chatbot performs document ingestion, embedding, and intelligent retrieval to give precise answers to user queries.

---

## 📘 Project Overview

This end-to-end tutorial helps you build a **Conversational AI Assistant** capable of:

- Ingesting documents (PDFs)
- Splitting large text into chunks
- Generating semantic vector embeddings using **Google Generative AI**
- Storing embeddings in **FAISS** (vector database)
- Using **LangChain + LLaMA 3 via Groq** for context-based responses
- Answering user questions based only on the documents

---

## 🚀 Features

- 📂 Upload and parse multiple PDFs
- 📊 Chunking and vector embedding using **Google Gemini**
- 🧠 Conversational Q&A using **LangChain Retrieval Chain**
- 💡 Responses generated using **LLaMA-3 via Groq API**
- ⚙️ Efficient context-aware document search

---

## 🧱 Tech Stack

- Python 3.9+
- Streamlit
- LangChain
- FAISS (Facebook AI Similarity Search)
- Google Gemini Pro Embeddings (`models/embedding-001`)
- LLaMA 3 via Groq (`Llama3-8b-8192`)
- dotenv

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/debkumar8/smart_chat_assistant
cd gemini_qa_chatbot
