# Campus-Knowledge-Base-RAG
A Retrieval-Augmented Generation (RAG) chatbot built with LangChain, Ollama, and CHROMA to answer questions from a custom university knowledge base. Features a simple Gradio interface for interactive Q&amp;A.
A prototype **Retrieval-Augmented Generation (RAG) chatbot** that answers questions about a university knowledge base.  
Built using **LangChain**, **Ollama**, **ChromaDB**, and **Gradio**.

---

## Features

- Load and split university documents into semantic chunks
- Store embeddings in **ChromaDB** for fast retrieval
- Chat with a **local LLM** (LLaMA 3.2) using LangChain
- Interactive web UI using **Gradio**

---

## Tech Stack

- [LangChain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)
- [ChromaDB](https://www.trychroma.com/)
- [Gradio](https://gradio.app/)
- Python 3.10+

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/campus-knowledge-base-rag.git
cd campus-knowledge-base-rag
pip install -r requirements.txt


```

## Usage

1. Start your Ollama server with the model:

```bash
ollama run llama3.2:3b
```
