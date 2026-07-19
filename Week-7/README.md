# 🧠 Retrieval-Augmented Generation (RAG) for Document Question Answering

This repository contains my **Week 7 Machine Learning Foundation assignment** completed as part of the **Celebal Technologies Internship Program**.

---

## 📌 Project Overview

This project implements an end-to-end **Retrieval-Augmented Generation (RAG)** pipeline for document-based question answering. The system processes a PDF document, extracts and preprocesses text, generates semantic embeddings, stores them in a FAISS vector database, retrieves the most relevant document chunks based on a user query, and generates context-aware answers using a Large Language Model (LLM).

The project demonstrates the practical application of semantic search, vector databases, and Retrieval-Augmented Generation for AI-powered document question answering.

---

## 🎯 Objectives

- Understand the concept of Retrieval-Augmented Generation (RAG)
- Load and preprocess a PDF document
- Split the document into meaningful overlapping text chunks
- Generate semantic embeddings using Sentence Transformers
- Store embeddings in a FAISS vector database
- Perform semantic similarity search
- Retrieve relevant document chunks
- Generate context-aware answers using a Large Language Model
- Validate retrieval performance using sample questions

---

## 🛠️ Tools and Libraries Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- PyPDF
- Sentence Transformers
- FAISS
- Hugging Face Transformers

---

## 📂 Repository Structure

```text
Week-7/
│
├── ML_Foundation_Week_7_RAG_Document_Question_Answering.ipynb
├── Week7_Project.pdf
└── README.md
```

---

## 📄 Dataset

This project uses the **Week7_Project.pdf** document as the knowledge source for the Retrieval-Augmented Generation pipeline.

The PDF is processed through:

- Text Extraction
- Text Preprocessing
- Intelligent Chunking
- Embedding Generation
- Semantic Retrieval

No additional datasets are required.

---

## 🔄 Workflow Followed

1. Install required libraries
2. Import necessary modules
3. Load the PDF document
4. Extract text from the document
5. Clean and preprocess the extracted text
6. Generate document statistics
7. Split the document into overlapping text chunks
8. Generate semantic embeddings using Sentence Transformers
9. Store embeddings in a FAISS vector database
10. Convert user questions into embeddings
11. Retrieve the most relevant document chunks
12. Generate answers using a Large Language Model
13. Validate the RAG pipeline using sample questions
14. Analyze the results and summarize findings

---

## 🏗️ RAG Pipeline

```text
PDF Document
      │
      ▼
Text Extraction
      │
      ▼
Text Preprocessing
      │
      ▼
Text Chunking
      │
      ▼
Sentence Transformer Embeddings
      │
      ▼
FAISS Vector Database
      │
      ▼
User Question
      │
      ▼
Semantic Retrieval
      │
      ▼
Retrieved Context
      │
      ▼
Large Language Model
      │
      ▼
Generated Answer
```

---

## 📈 Results

- Successfully implemented an end-to-end Retrieval-Augmented Generation pipeline.
- Generated semantic embeddings for document chunks.
- Built a FAISS vector database for efficient similarity search.
- Retrieved contextually relevant document chunks for user queries.
- Generated context-aware answers using a Large Language Model.
- Validated the system using multiple sample questions.

---

## 📚 Key Learning Outcomes

This project helped strengthen my understanding of:

- Retrieval-Augmented Generation (RAG)
- Document Processing
- Text Preprocessing
- Intelligent Text Chunking
- Sentence Embeddings
- Semantic Search
- FAISS Vector Database
- Large Language Models (LLMs)
- Document Question Answering
- Information Retrieval
- Natural Language Processing (NLP)

---

## 🚀 Future Improvements

- Implement hybrid search combining keyword and semantic retrieval.
- Experiment with larger embedding models.
- Add document re-ranking for improved retrieval quality.
- Support multiple PDF documents.
- Develop an interactive web application using Streamlit or Gradio.

---

## 👨‍💻 Author

**Devratan**

- 🎓 PGDM (Business Analytics & Marketing)
- 🏫 Lloyd Business School
- 💼 Data Scientist – Celebal Technologies

---

## 📝 Note

This repository has been created for **academic submission and learning purposes** as part of the **Machine Learning Foundation Program at Celebal Technologies**.

The project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system using semantic search, vector databases, and Large Language Models for document-based question answering.
