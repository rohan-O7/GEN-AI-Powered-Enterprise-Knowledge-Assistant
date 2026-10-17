## Self-RAG-Based Document Intelligence System

An intelligent document question-answering system built using **Python, LangGraph, LangChain, FAISS, and the OpenAI API**. The system retrieves relevant information from PDF documents and generates context-aware answers using a Self-RAG-inspired workflow.

### Key Features
- **Document Retrieval:** Uses OpenAI embeddings and FAISS vector search to retrieve relevant document chunks.
- **Relevance Grading:** Evaluates retrieved documents to determine whether they contain information relevant to the user's query.
- **Hallucination Detection:** Checks whether generated answers are supported by the retrieved context.
- **Answer Quality Assessment:** Evaluates whether the generated response adequately addresses the user's question.
- **Adaptive Retrieval:** Rewrites queries and retries retrieval when the generated answer is insufficient, with a bounded retry mechanism.
- **Graph-Based Orchestration:** Uses LangGraph to manage conditional routing, evaluation, and answer refinement.

### Tech Stack
Python • LangGraph • LangChain • FAISS • OpenAI API • PyPDF

### Objective
To improve the reliability of document-based question answering by combining semantic retrieval with iterative relevance checking, answer verification, and query refinement.
