## Overview
A Retrieval Augmented Generation (RAG)-based question-answering system that extracts relevant context from PDF documents using LangChain for document processing, Sentence Transformers for generating vector embeddings, FAISS for vector search, and the FLAN-T5 LLM to generate grounded answers. The pipeline is implemented in Python using Hugging Face Transformers to enable accurate, context-aware responses.

Colab Notebook Link:
https://colab.research.google.com/drive/1voS5gLM3bqPE3JpWsMz8DkMapo8hAse3?usp=sharing



## Workflow
1. Load research paper PDF

2. Split text into chunks

3. Generate embeddings using sentence-transformers

4. Store embeddings in a FAISS vector database

5. Retrieve top relevant chunks for a query

6. Pass retrieved context to FLAN-T5

7. Generate an answer grounded only in the document context



## Tech Stack
•Python

•LangChain

•FAISS (vector store)

•Sentence-Transformers (all-MiniLM-L6-v2)

•FLAN-T5 (HuggingFace Transformers)



## Input
Any research paper PDF

Example paper used:
https://www.sciencedirect.com/science/article/pii/S0164121224003017
