Semantic Document Search (FAISS)

A semantic document search system that retrieves documents based on meaning instead of keywords using sentence embeddings and FAISS.

🚀 Features

Supports PDF, DOCX, and TXT files

Meaning-based search using embeddings

Fast similarity search with FAISS

Returns relevant document snippets with similarity scores

🛠 Tech Stack

Python

FAISS

Sentence Transformers

NumPy

PyPDF2, python-docx

⚙️ How It Works

Load documents from a folder

Split text into chunks

Generate embeddings

Index embeddings using FAISS

Perform semantic search on user queries

▶️ Usage

Install dependencies:

pip install sentence-transformers faiss-cpu PyPDF2 python-docx numpy


Run the notebook and search:

semantic_search_best("applications of artificial intelligence")

📌 Output

Source document

Similarity score

Relevant text snippet

📈 Future Improvements

Index persistence

Overlapping chunks

Web UI

LLM integration (RAG)

👤 Author

shahanas
