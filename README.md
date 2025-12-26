# 🚀 **NVIDIA NIM RAG Demo (Streamlit)**

<div align="center">
🚀✨ A simple Retrieval-Augmented Generation (RAG) demo using NVIDIA NIM with Streamlit ✨🚀
  
Load PDFs • Embed with NVIDIA • Retrieve Context • Generate Answers — all in one interactive app

🤖 NVIDIA NIM • 🧠 LLaMA 3.3 (70B) • 🔍 RAG • 📚 FAISS • 🧩 LangChain • 🖥️ Streamlit
</div>

## 🌟 Overview
This project is a simple Retrieval-Augmented Generation (RAG) demo built to showcase how NVIDIA NIM can be used with modern LLM tooling to answer questions from private documents. The application allows users to: 

✔️ Load PDF documents from a local directory and Convert them into vector embeddings using NVIDIA-hosted models

✔️ Retrieve the most relevant document chunks and Generate accurate answers using a large language model

✔️ The entire pipeline is wrapped in an interactive Streamlit interface, making it easy to experiment with RAG concepts using NVIDIA’s AI ecosystem.

✔️ This project is intended for learning, demos, and experimentation, not production deployment.

## 🧩 Core Components

- 📄 Document Loader : Loads PDF files from a local directory using LangChain’s PDF loader.

- ✂️ Text Splitter : Breaks documents into smaller overlapping chunks for better context retrieval.

- 🧠 Embedding Model : Uses NVIDIA NIM embeddings to convert text chunks into vector representations.

- 📦 Vector Store : Stores embeddings in FAISS for fast and efficient similarity search.

- 🔍 Retriever : Fetches the most relevant document chunks based on the user’s query.

- 🤖 Large Language Model (LLM) : Uses a NVIDIA-hosted LLaMA 3.3 (70B Instruct) model to generate context-aware answers.

- 🖥️ User Interface : Streamlit-based UI that allows users to embed documents, ask questions, and view responses.

## 🚀 Getting Started

### ⚙️ Environment Setup

```bash
NVIDIA_API_KEY=your_nvidia_api_key_here
```

### 📦 Installation
```bash
git clone https://github.com/kirantushar10/NVIDIA-NIM-RAG-Demo.git
cd NVIDIA-NIM-RAG-Demo

python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows

pip install -r requirements.txt
```

### ▶️ Run the App
```bash
streamlit run finalapp.py
```

