---
🧠 Assurio – Intelligent Clause Retriever & Decision System

**Assurio** is an AI-powered insurance assistant that enables users to upload PDF insurance documents, automatically indexes them using semantic embeddings, and allows natural language querying to retrieve relevant clauses and provide automated decisions.

---

## 🚀 Features

* **Drag & Drop PDF Upload** – Modern web interface for seamless document uploads.
* **Auto Indexing** – Extracts text, chunks content, and generates embeddings automatically.
* **Semantic Search** – Quickly retrieves clauses using FAISS vector search.
* **LLM Reasoning** – Integrates **Google Gemini** for automated decision-making and entity extraction.
* **Real-time Processing** – Displays background progress for uploads and queries.
* **File Management** – Manage uploaded documents: list, delete, or clean up files.
* **Health Monitoring** – Includes health and document status endpoints.

---

## 🛠️ Tech Stack

| Component               | Technology                    |
| ----------------------- | ----------------------------- |
| **Backend**             | FastAPI (Async)               |
| **Frontend**            | Tailwind CSS, HTML5           |
| **Embeddings**          | SentenceTransformers (MiniLM) |
| **Vector DB**           | FAISS (Local)                 |
| **LLM**                 | Google Gemini (via LangChain) |
| **Document Processing** | PyPDF2                        |
| **File Handling**       | aiofiles (Async)              |

---

## ⚡ Usage

1. **Start the backend:**

   ```bash
   python start_enhanced.py
   ```

2. **Open the enhanced web UI:**

   ```
   http://localhost:8000/frontend/enhanced.html
   ```

3. **Upload** PDF documents and **query** the system naturally.

---

## 📚 API Endpoints

| Method | Endpoint             | Description             |
| ------ | -------------------- | ----------------------- |
| `POST` | `/api/v1/upload_pdf` | Upload and index PDF    |
| `POST` | `/api/v1/query`      | Query indexed documents |
| `GET`  | `/api/v1/documents`  | Get document count      |
| `GET`  | `/api/v1/health`     | System health check     |

---

## 📄 License

**MIT License**

---

## 👤 Author

**Nikunj Jain**
📧 Email: [nikunjjainofficial@gmail.com](mailto:nikunjjainofficial@gmail.com)
🔗 LinkedIn: [https://www.linkedin.com/in/nikunjjain29/](https://www.linkedin.com/in/nikunjjain29/)

---
