# Intelligent Banking Product Recommendation System

An intelligent recommendation system that uses **OpenAI Embeddings** and **Cosine Similarity** to match customer queries with the most relevant banking products.

---

## 📖 Overview

Traditional keyword-based search often fails to capture true user intent. This project demonstrates how **vector embeddings** can be used to build a semantic search engine that understands context rather than relying on exact keyword matches.

In this scenario, a retail bank maps its products (Savings, Loans, Insurance, etc.) into a high-dimensional vector space. Customer queries are embedded into the same space, allowing the system to recommend products that best align with the customer’s financial needs.

---

## ✨ Key Features

- **Semantic Matching**  
  Matches queries like *“I need money to buy my first house”* to a **Personal Home Loan**, even when keywords do not overlap.

- **High-Dimensional Embeddings**  
  Uses the `text-embedding-3-small` model (1536 dimensions) for accurate semantic representation.

- **Cosine Similarity Scoring**  
  Identifies the most relevant products by measuring vector similarity between queries and products.

- **Visual Analysis**  
  Includes a cosine similarity heatmap to visualize relationships between banking products.

- **Efficient Batching**  
  Implements batch processing to optimize embedding generation and API usage.

---

## 🛠️ Tech Stack

- **Language:** Python  
- **AI Model:** OpenAI `text-embedding-3-small`  
- **Libraries:**  
  - NumPy  
  - Pandas  
  - Scikit-learn  
  - Matplotlib  

---

## 🚀 Getting Started

### Prerequisites

- An OpenAI API key
- Google Colab **or** a local Python environment (Python 3.8+ recommended)

---

## 📂 Project Structure (Example)

```text
.
├── data/
│   └── banking_products.csv
├── embeddings/
│   └── product_embeddings.npy
├── notebooks/
│   └── semantic_search_demo.ipynb
├── src/
│   ├── embedding_generator.py
│   ├── similarity_engine.py
│   └── visualization.py
├── README.md
└── requirements.txt
