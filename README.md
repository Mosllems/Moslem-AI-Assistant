# 🤖 Telegram AI Assistant

An AI-powered Telegram assistant built with **n8n**, **RAG (Retrieval-Augmented Generation)**, and **Supabase Vector Store**. The assistant answers questions about you by retrieving relevant information from your personal knowledge base and supports both text and voice conversations.

## ✨ Features

- 🤖 AI-powered Telegram assistant
- 🧠 Retrieval-Augmented Generation (RAG)
- 📄 Upload your personal PDF as a knowledge base
- ✂️ Automatic document chunking
- 🗂️ Stores embeddings in **Supabase Vector Store**
- 💬 Supports text conversations
- 🎤 Supports voice messages
- 🌍 Replies in the same language as the user's message
- ⚡ Built with **n8n** workflows
- 🔎 Retrieves only the most relevant information from your knowledge base before generating responses
- 🚫 Does **not** support photos, videos, GIFs, or Telegram video messages

---

## 🚀 How It Works

### 1. Create Your Knowledge Base

First, provide a PDF containing your personal information (resume, portfolio, biography, FAQs, etc.).

The assistant will:

- Extract the document content
- Split it into chunks
- Generate embeddings
- Store them in **Supabase Vector Store**

---

### 2. Ask Questions

Users can interact with the assistant by sending:

- 💬 Text messages
- 🎤 Voice messages

For each query, the assistant:

1. Converts voice to text (if needed)
2. Retrieves the most relevant chunks using **RAG**
3. Sends the retrieved context to the LLM
4. Generates an accurate and personalized response

---

## 🛠 Tech Stack

- n8n
- Telegram Bot API
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Supabase Vector Store
- PDF Processing
- Embeddings

---


## 🤖 Telegram Bot

Try it here:

**@mosllems_assistant_bot**


---
