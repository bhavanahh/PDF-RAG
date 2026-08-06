# 📚 PDF Question Answering Assistant using RAG

## Author

Bhavana B  
MUID: bhavanab-1@mulearn

## Project Overview

This project is a PDF QuesDIRtion Answering Application built using Retrieval-Augmented Generation (RAG).

The application allows users to upload a PDF document and ask questions based on its content. The system retrieves relevant information from the document and uses Google Gemini AI to generate accurate, context-based answers.

The application can understand document context and provide meaningful responses from the uploaded PDF.

---

## Technologies Used

### Programming Language
- Python

### Frontend
- Streamlit

### RAG Framework
- LangChain

### PDF Processing
- PyPDFLoader

### Text Processing
- Recursive Character Text Splitter

### Embedding Model
- Sentence Transformers (`all-MiniLM-L6-v2`)

### Vector Database
- ChromaDB

### Large Language Model
- Google Gemini API

### Environment Management
- python-dotenv

---

## How It Works

1. User uploads a PDF document.
2. The PDF content is extracted using PyPDFLoader.
3. The text is divided into smaller chunks.
4. Each chunk is converted into embeddings.
5. Embeddings are stored in ChromaDB.
6. User questions are matched with relevant document chunks.
7. Gemini AI generates answers using the retrieved context.

---

## Installation

### Create Virtual Environment

```bash
python -m venv .venv

## Future Improvements

- Support multiple PDF uploads
- Add PDF preview
- Add source page references
- Improve retrieval accuracy
- Deploy as a web application

---