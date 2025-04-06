# 🔍 Retrieval-Augmented Generation (RAG) for PDF Document Querying

This project demonstrates a Retrieval-Augmented Generation (RAG) pipeline using LangChain and LLMs to query and summarize unstructured content from PDFs. Built during a hands-on workshop at the University at Buffalo.

## 🧠 What It Does

- Loads a technical PDF document (e.g., Transformer research paper)
- Splits and embeds the text using text embedding models
- Stores embeddings in a vector database (e.g., FAISS)
- On user query, performs semantic search to retrieve top relevant chunks
- Uses a Large Language Model (OpenAI or HuggingFace) to generate context-aware, grounded answers from retrieved content

## 🛠️ Tech Stack
- Python (Jupyter Notebook)
- LangChain
- OpenAI API / HuggingFace
- FAISS (or similar vector store)
- PDF loader utilities

## 📂 Files

- `QueryPDF_RAG.ipynb` – Complete notebook implementing the RAG workflow
- `attention.pdf` – Source document used for querying (Transformer paper)
- `RAG_Workshop.pptx` – Presentation from the UB workshop explaining RAG
- `README.md` – Project documentation

## ✅ Outcome & Learnings

- Learned how to build a complete RAG pipeline using LangChain
- Applied real-world NLP workflows with semantic search and LLMs
- Understood how to ground generative AI outputs using vector-based retrieval
- Demonstrated the use of APIs, embeddings, and unstructured data workflows
- Built a functional prototype for document-based Q&A that can scale to business use cases
