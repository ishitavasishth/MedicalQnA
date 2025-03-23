# Medical Chatbot

# 🧠 Medical Q&A Chatbot 

This project demonstrates how to build a medical domain Q&A chatbot **without using APIs or large transformer models**. Instead, it leverages:

- 🔍 **TF-IDF Vectorization** for local document understanding
- 🧱 **FAISS** for fast similarity search
- 🔗 **LangChain** for chaining components together
- 🌐 **Gradio** for a simple web interface

---

## 🚀 How It Works

1. **PDF Loader**: Loads and splits a medical research paper into smaller chunks.
2. **Embedding & Indexing**: Converts text into embeddings using `TfidfVectorizer` and indexes them with FAISS.
3. **Retrieval**: Given a user query, the most relevant chunk is retrieved using similarity search.
4. **Gradio UI**: Provides an interactive frontend where users can ask questions based on the uploaded PDF.

---

## 🛠️ Libraries Used

- `LangChain`
- `FAISS`
- `Gradio`
- `scikit-learn`
- `PyPDFLoader` (LangChain Community)
- `pypdf`

---

## 📦 How to Run (Google Colab)

1. Upload a PDF (preferably medical/research-based).
2. Run all cells top-to-bottom.
3. Use the **Gradio UI** to interact with the bot.

---

## 📎 Sample Questions to Ask

- "What is prompt-based learning?"
- "What are the two sea changes in NLP?"
- "List the applications of prompt engineering."

---

---

