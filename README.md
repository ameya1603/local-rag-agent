# Local RAG AI Agent

A lightweight, fully local Retrieval-Augmented Generation (RAG) pipeline built in Python. This system processes local markdown documentation, generates semantic vector embeddings using Ollama, performs custom sliding-window chunking, calculates cosine similarity for context retrieval, and interfaces with a local LLM to answer questions privately and securely on macOS.

## Tech Stack

* **Language:** Python 3.x
* **Package Manager:** `uv` (for ultra-fast environment and dependency management)
* **Local LLM Engine:** [Ollama](https://ollama.com/)
  * **Chat Model:** `qwen3:4b-instruct`
  * **Embedding Model:** `nomic-embed-text`
* **Core Libraries:** `requests`, `numpy`, `pathlib`

---

## Project Structure

```text
RAG/
├── docs/               # Place your .md knowledge base files here
├── .venv/              # Virtual environment (managed by uv)
├── .gitignore          # Excludes environment and cache files
├── rag.py              # Main application script
└── README.md           # Project documentation



