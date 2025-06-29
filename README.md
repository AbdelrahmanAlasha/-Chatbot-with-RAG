# 🔍 PDF Chatbot with RAG (Retrieval-Augmented Generation)

This project is a simple RAG (Retrieval-Augmented Generation) chatbot that can answer questions from uploaded PDF or TXT documents using semantic search and a local LLM.

## 🚀 Features

- Extracts text from PDF or TXT files
- Chunks text into meaningful pieces
- Embeds chunks using `SentenceTransformers`
- Indexes embeddings using `FAISS` with cosine similarity
- Answers questions using retrieved context + Falcon-7B-Instruct

## 🧠 Models Used

- Embedding Model: `multi-qa-MiniLM-L6-cos-v1`
- LLM: `tiiuae/falcon-7b-instruct` (via HuggingFace `transformers.pipeline`)

## 📦 Installation

Create a virtual environment or use Colab, then install the dependencies:

```bash
pip install -r requirements.txt
```

## 📝 Usage
Upload your PDF/TXT files.

Run the notebook app.ipynb step-by-step.

Ask questions interactively in the terminal or Colab cell.
