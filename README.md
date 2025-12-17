# Semantic Document Search (FAISS)

A semantic document search system that retrieves documents based on **meaning instead of keywords** using **sentence embeddings** and **FAISS**.

---

## 🚀 Features
- Supports **PDF, DOCX, and TXT** files  
- Meaning-based search using embeddings  
- Fast similarity search with **FAISS**  
- Returns relevant document snippets with similarity scores  

---

## 📁 Sample Documents
This repository includes sample files used for testing:
- `ai_intro.pdf`
- `data_science.docx`
- `db_basics.txt`

---

## 🛠 Tech Stack
- Python  
- FAISS  
- Sentence Transformers  
- NumPy  
- PyPDF2, python-docx  

---

## ⚙️ How It Works
- Load documents from a folder  
- Split text into chunks  
- Generate embeddings  
- Index embeddings using FAISS  
- Perform semantic search on user queries  

---

## ▶️ Usage

Install dependencies:
```bash
pip install sentence-transformers faiss-cpu PyPDF2 python-docx numpy
