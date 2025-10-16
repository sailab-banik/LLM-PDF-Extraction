# 🧠 Open Source Text Extraction from PDFs using RAG Pipeline

This project is an **open-source Retrieval-Augmented Generation (RAG)** application designed to **extract and query text data from PDF documents** using local LLMs and embeddings.

It’s built as part of my **LLM learning journey** — a hands-on exploration into how **embeddings, vector databases, and language models** can work together to make unstructured documents queryable through natural language.

---

## 🚀 Features

- 📄 Upload PDF files and process them locally  
- 🔍 Extract and embed PDF text using **EmbeddingGemma**  
- 🧠 Query the document using **Llama 3.1 (8B)** via **Ollama**  
- ⚙️ Built with **LangChain** for the RAG pipeline  
- 💬 Interactive chat-based UI with **Gradio**  
- 🔐 Runs fully offline — no external API calls  

---

## 🧩 Tech Stack

| Component | Tool / Model |
|------------|---------------|
| **LLM** | Llama 3.1 (8B) via Ollama |
| **Embeddings** | EmbeddingGemma |
| **Framework** | LangChain |
| **Vector Store** | Chroma |
| **Frontend** | Gradio |
| **Language** | Python 3.10+ |

---

## 💡 Use Cases

1. **Sample Invoice (3 pages)**  
   Extracted key details like invoice number, customer info, itemized data, and totals.  

2. **Sample Insurance Policy (30 pages)**  
   Implemented a QA-style chatbot capable of answering contextual questions about coverage, terms, and exclusions.  

---

### Outputs

<img width="1891" height="1078" alt="invoice-extract" src="https://github.com/user-attachments/assets/ebd36b9c-ee34-40c1-ab50-1772647ba45c" />


<img width="1897" height="1078" alt="insurance-qa" src="https://github.com/user-attachments/assets/8e3e0860-6bf6-4fc7-86a4-f0daf54df7ef" />

