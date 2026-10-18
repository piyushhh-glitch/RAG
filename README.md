# RAG Learning

A learning repository to understand and practice **Retrieval-Augmented Generation (RAG)** using Python and popular AI libraries.

## Topics Covered

- RAG fundamentals and pipeline
- Document loading and chunking strategies
- Text embeddings using Sentence Transformers
- Vector databases with ChromaDB
- Semantic search and BM25 retrieval
- Hybrid search using Reciprocal Rank Fusion (RRF)
- Cross-Encoder reranking
- Context-grounded LLM responses using Groq
- Document metadata and citations

## Tech Stack

- Python
- LangChain
- Sentence Transformers
- ChromaDB
- BM25 (`rank_bm25`)
- Cross-Encoder
- Groq LLM

## RAG Pipeline

```text
Documents → Chunking → Embeddings → Vector Store
                                      ↓
User Query → Retrieval → Hybrid Search → Reranking
                                      ↓
                              Relevant Context
                                      ↓
                                LLM Response
```

## Purpose

The goal of this repository is to understand RAG concepts, implement retrieval techniques, and learn how different components work together to build LLM-powered applications.

