# Naive-RAG-Agent

Implementation of a naive RAG pipeline: TF-IDF/BM25 retrieval, chunking strategies, quantization, and evaluation.

## Contents

| # | Section | What it covers |
|---|---------|----------------|
| 1 | Naive RAG | TF-IDF retrieval, BM25 scoring, BERT embeddings |
| 2 | Tokenization & Chunking | Fixed-size, overlap, newline, recursive, Markdown, LaTeX, HTML, propositions |
| 3 | Quantization | Binary and int8 embeddings, Matryoshka truncation |
| 4 | Evaluation | Precision, recall, PR curve |
| 5 | A RAG Pipeline | TMDB movies → MiniLM → ChromaDB → Mistral-7B recommendations |
| 6 | Reranking | MonoBERT cross-encoder reranking, integration into the RAG pipeline |

## Usage

Open `Naive_RAG_Agent.ipynb` in Google Colab or Jupyter and run the cells in order.
