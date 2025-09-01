# Decision Finder (Jupyter Notebook)
Jupyter notebook for exploring headnotes and catchwords of EPO board of appeal decisions

A lightweight **Jupyter notebook** for exploring the **Headnotes and Catchwords of EPO Board of Appeal Decisions** It performs semantic search and RAG-style answers using transformers—running **100% locally** on your machine for privacy and speed.

**Dataset (Zenodo):** [https://zenodo.org/records/14987955](https://zenodo.org/records/14987955)

## Features
- **Data:** 120 headnotes/catchwords in English (with duplicates)
- **Local-first & offline:** All processing (embeddings + LLM) runs locally on your device.
- **Focused corpus:** Optimized for **G-decision headnotes & catchwords (EN)** to answer domain-specific queries.
- **Semantic search + RAG answers:** Retrieve the most relevant snippets and generate concise answers with cited sources.
- **Notebook-native workflow:** Run cell-by-cell, tweak parameters, inspect intermediate results, and visualize embeddings.
- **Pluggable local models:** Works with **Ollama** (e.g., `nomic-embed-text`, `qwen2.5`) or **sentence-transformers**—swap without code churn.
- **Persistent vectors:** Uses Chroma for fast, on-disk indexing and quick restarts.

> **Disclaimer:** Transformer models can produce **incorrect or misleading statements** (“hallucinations”). Always verify outputs against the original decisions. This project does not provide legal advice.

