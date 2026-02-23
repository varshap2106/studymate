# 📚 StudyPDF – AI Powered PDF Question Answering System

StudyPDF is an AI-powered web application that allows users to upload a PDF document and ask questions directly from its content.

Built during a hackathon, this project leverages Natural Language Processing (NLP) to extract meaningful answers from uploaded study material.

---

## 🚀 Features

- 📂 Upload any text-based PDF
- 🔎 Extract text automatically
- 🤖 Ask questions related to the PDF
- 📊 AI-generated answers with confidence score
- 📖 Text preview of extracted content
- ⚡ Fast processing using Hugging Face Transformers

---

## 🛠 Tech Stack

- **Python**
- **Streamlit** – Web interface
- **PyPDF2** – PDF text extraction
- **Hugging Face Transformers**
- **DistilBERT (SQuAD model)**

---

## 🧠 How It Works

1. User uploads a PDF file.
2. The application extracts text using PyPDF2.
3. The extracted text is passed to a pretrained Q&A model.
4. The model predicts the most relevant answer from the document.
5. The answer and confidence score are displayed to the user.

---

## ▶️ How to Run Locally

### 1️⃣ Install dependencies
pip install streamlit PyPDF2 transformers torch


---

## ⚠️ Limitations

- Works only with text-based PDFs (not scanned images).
- Large PDFs are truncated to avoid token overflow.
- Performance depends on model loading time.

---

## 🎯 Hackathon Project

This project was developed as a collaborative hackathon submission to demonstrate practical use of NLP in educational tools.

---

## 👩‍💻 Contributors
- Varshitha P Naik
- Vinutha T
