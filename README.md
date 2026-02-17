An intelligent recommendation system that uses OpenAI Embeddings and Cosine Similarity to match customer queries to the most relevant banking products.

📖 Overview
Traditional keyword-based search often fails to capture user intent. This project demonstrates how to leverage Vector Embeddings to build a semantic search engine. In this scenario, a retail bank maps various products (Savings, Loans, Insurance) into a high-dimensional vector space, allowing it to "understand" the context of a customer's financial needs.

Key Features
Semantic Matching: Matches queries like "I need money to buy my first house" to a "Personal home loan" even if keywords don't overlap.
High-Dimensional Embeddings: Uses OpenAI's text-embedding-3-small model (1536 dimensions).
Visual Analysis: Includes a Cosine Similarity heatmap to visualize product relationships.
Efficient Batching: Implements batch processing for embedding generation.
🛠️ Tech Stack
Language: Python
AI Model: OpenAI text-embedding-3-small
Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib
🚀 Getting Started
Prerequisites
An OpenAI API Key
Google Colab or a local Python environment

