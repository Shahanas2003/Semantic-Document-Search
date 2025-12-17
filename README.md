Semantic Document Search using FAISS
Overview

This project implements a Semantic Document Search system that retrieves documents based on meaning rather than exact keyword matching.
It uses sentence embeddings and FAISS to perform fast and accurate similarity search over unstructured documents.

Features

Supports PDF, DOCX, and TXT files

Converts documents into semantic embeddings

Uses FAISS for efficient similarity search

Retrieves the most relevant document snippets

Displays similarity score and source file

Technologies Used

Python

FAISS (Facebook AI Similarity Search)

Sentence Transformers

NumPy

PyPDF2

python-docx

How It Works

Documents are loaded from a folder

Text is extracted and split into chunks

Each chunk is converted into an embedding

Embeddings are indexed using FAISS

User query is embedded and searched

Most relevant document snippets are returned

Installation

Install the required libraries:

pip install sentence-transformers faiss-cpu PyPDF2 python-docx numpy

Usage

Place your documents in a folder

Run the Jupyter Notebook

Enter a search query

View the most relevant results with similarity scores

Example:

semantic_search_best("applications of artificial intelligence")

Output

Source document name

Similarity score

Relevant text snippet

Future Improvements

Add overlapping chunks

Save and load FAISS index

Build a web interface

Integrate with large language models

Author

Shahanas
