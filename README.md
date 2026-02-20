# FAISS Vector Database Semantic Search

## Overview
This project implements semantic search using text embeddings and the FAISS vector database. Documents are transformed into numerical vectors and searched based on semantic similarity.

## Method
- Convert text documents into embeddings  
- Store embeddings in a FAISS index  
- Embed a query sentence  
- Retrieve the Top-K most similar documents using cosine similarity  

## Tools Used
- Python  
- OpenAI Embeddings API  
- FAISS  
- NumPy  

## Outcome
The system returns the most semantically relevant documents along with similarity scores.

## Concepts Covered
- Text embeddings  
- Vector indexing  
- Similarity search with FAISS
