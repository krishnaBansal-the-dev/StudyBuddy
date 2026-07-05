# 📚 StudyBuddy

<div align="center">

### An AI-powered Study Assistant built using Retrieval-Augmented Generation (RAG)

Retrieve relevant information from your documents and generate accurate, context-aware answers using Large Language Models.

**🚧 Frontend currently under development**

</div>

---

## 📖 About

**StudyBuddy** is a Retrieval-Augmented Generation (RAG) based AI study assistant designed to answer questions from your study materials.

Instead of relying solely on an LLM's internal knowledge, StudyBuddy first retrieves the most relevant information from uploaded documents and then uses that context to generate accurate, grounded responses.

The current version implements the complete RAG backend pipeline. A Streamlit-based frontend is under development.

---

## ✨ Features

- 📄 PDF document loading
- ✂️ Intelligent text chunking
- 🧠 Semantic embedding generation
- 🗂️ ChromaDB vector database integration
- 🔍 Semantic similarity search
- 🤖 Context-aware answer generation using Groq LLM
- 📝 Prompt engineering to reduce hallucinations
- 🧹 Automatic ChromaDB cleanup after execution

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Framework | LangChain |
| Vector Database | ChromaDB |
| Embedding Model | Sentence Transformers |
| LLM | Groq |
| Document Processing | PyMuPDF, PyPDF |
| Utilities | NumPy, Scikit-learn, python-dotenv |

---

# 📂 Project Structure

```text
StudyBuddy/
│
├── data/
│   └── # PDF documents
│
├── notebook/
│   └── RAG.ipynb
│
├── .env
├── .gitignore
├── .python-version
├── pyproject.toml
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/StudyBuddy.git

cd StudyBuddy
```

---

### 2. Create a virtual environment

```bash
python -m venv .venv
```

---

### 3. Activate the environment

**Linux / macOS**

```bash
source .venv/bin/activate
```

**Windows**

```bash
.venv\Scripts\activate
```

---

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file in the project root.

Example:

```env
GROQ_API_KEY=your_groq_api_key
```

---

# ▶️ Running the Project

1. Place your PDF documents inside the `data/` directory.

2. Open the notebook

```text
notebook/RAG.ipynb
```

3. Run all cells sequentially.

---

# 🔄 RAG Pipeline

```
PDF Documents
      │
      ▼
Document Loader
      │
      ▼
Text Splitter
      │
      ▼
Sentence Transformer
      │
      ▼
Embeddings
      │
      ▼
ChromaDB
      │
      ▼
Retriever
      │
      ▼
Prompt Template
      │
      ▼
Groq LLM
      │
      ▼
Generated Answer
```

---

# 📌 Current Status

## ✅ Completed

- PDF Loading
- Text Chunking
- Embedding Generation
- ChromaDB Integration
- Semantic Retrieval
- Prompt Engineering
- Context-Aware Answer Generation
- Automatic Database Cleanup

---

## 🚧 Under Development

- Streamlit Frontend
- AI Chat Interface
- Multi-file Upload
- Conversation History
- Source Citations
- Deployment

---

# 🚀 Future Improvements

- Support for DOCX, TXT and PPTX
- Hybrid Search (Keyword + Semantic)
- Multi-document Question Answering
- Streaming Responses
- Conversation Memory
- Docker Support
- Cloud Deployment

---

# 📦 Requirements

Install all required packages using

```bash
pip install -r requirements.txt
```

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve StudyBuddy:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Krishna Bansal**

Second Year B.Tech CSE Student

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a Star!

**StudyBuddy — Learn Smarter with AI**

</div>