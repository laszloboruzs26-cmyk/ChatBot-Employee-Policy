Basic Chatbot Using RAG Framework and LangChain

Project Overview
This project implements a basic but functional chatbot using the Retrieval-Augmented Generation (RAG) framework.
The chatbot answers user questions based on the content of a provided document rather than relying only on a language model’s general knowledge.
The system was built using LangChain, OpenAI embeddings, and a Chroma vector database to ensure responses are grounded in source material.

Task Description
Task:
Create a basic chatbot using the RAG framework and LangChain that can answer questions from a document.

Objective:
Load a document
Convert it into embeddings
Retrieve relevant content based on user queries
Generate accurate, document-based responses

How the System Works
Document Loading:
The source document (PDF) is loaded into the system.

Text Chunking:
The document is split into smaller text chunks to improve retrieval accuracy.

Embedding Generation:
Each text chunk is converted into a vector embedding using OpenAI embeddings.

Vector Storage:
Embeddings are stored in a Chroma vector database.

Retrieval:
When a user asks a question, the most relevant document chunks are retrieved using semantic similarity.

Response Generation:
The retrieved content is passed to a language model, which generates an answer grounded in the document.

Skills and Technologies Used
Technical Skills:
Retrieval-Augmented Generation (RAG)
Prompt engineering
Semantic search
Vector databases
Debugging and dependency management

Tools and Libraries:
Python
LangChain
OpenAI API
ChromaDB
PyPDF
Jupyter or Google Colab

What Was Delivered
A working RAG-based chatbot
Document ingestion and preprocessing pipeline
Vector database for semantic retrieval
Prompt-controlled responses grounded in source material
Secure API key handling without hard-coded secrets
Reproducible setup using open-source tools

API Key and Setup Notes
This project requires an OpenAI API key.
The API key is not included in this repository for security reasons.
Users must set it as an environment variable before running the project.

Learning Outcomes
Understanding and implementing RAG architecture
Practical use of LangChain for AI application development
Integration of LLMs with external knowledge sources
Secure handling of credentials
Building explainable and non-hallucinatory AI systems

Notes
This project was developed for academic purposes as part of a university assignment.
The focus is on clarity, correctness, and reproducibility rather than production-scale deployment.

Possible Future Improvements
Add conversation memory for multi-turn dialogue
Display source citations with each response
Build a simple web interface
Support multiple documents
