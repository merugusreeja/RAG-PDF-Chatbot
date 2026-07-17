# 📄 RAG PDF Chatbot

An AI-powered Retrieval-Augmented Generation (RAG) chatbot that allows users to upload a PDF document, index its contents, and ask questions based only on the uploaded document. The application uses Google's Gemini API, ChromaDB, Sentence Transformers, and Gradio.

## 🚀 Features

- 📂 Upload PDF documents
- 📑 Extract text from PDFs
- ✂️ Automatically split text into chunks
- 🧠 Generate embeddings using Sentence Transformers
- 🗄️ Store embeddings in ChromaDB
- 🔍 Retrieve relevant document sections
- 🤖 Answer questions using Gemini 2.5 Flash
- 🌐 Interactive Gradio web interface

## 🛠️ Technologies Used

- Python
- Google Gemini API
- ChromaDB
- Sentence Transformers
- PyPDF
- Gradio

## 📂 Project Structure

```
RAG-PDF-Chatbot/
│── app.py
│── RAG_PDF_Chatbot.ipynb
│── requirements.txt
│── README.md
└── .gitignore
```

## 📦 Installation

```bash
pip install -r requirements.txt
```

## ▶️ Run

```bash
python app.py
```

## 📌 Workflow

1. Upload a PDF document.
2. Extract text from the PDF.
3. Split the text into chunks.
4. Generate embeddings.
5. Store embeddings in ChromaDB.
6. Ask questions.
7. Retrieve relevant chunks.
8. Gemini generates an answer using the retrieved context.

## 🎯 Use Cases

- Document Question Answering
- Research Assistance
- Study Materials
- Company Documentation Search
- Knowledge Base Chatbot

## 👩‍💻 Author

Merugu Sreeja

## 📄 License

This project is for educational purposes.
