# 📄 Resume RAG System

A Resume Retrieval-Augmented Generation (RAG) system built with **FastEmbed**, **ChromaDB**, and **Groq**. Upload resumes as PDFs, store embeddings, and query them with natural language to get AI-powered answers.

## 🚀 Features
- Upload multiple resumes in PDF format
- Extract and clean text using PyPDF2
- Store embeddings in ChromaDB
- Query resumes with semantic search
- AI-powered answers using Groq LLM
- Interactive UI with ipywidgets

## 🛠️ Tech Stack
- Python
- FastEmbed
- ChromaDB
- Groq API
- PyPDF2
- ipywidgets

## 📂 Usage
1. Upload resumes via the widget.
2. Store them in the database.
3. Ask questions like *"Who has the highest CGPA?"*.
4. Get contextual answers from the resumes.

## 📌 Example
```python
ask_groq("Who has experience in Data Science?")
