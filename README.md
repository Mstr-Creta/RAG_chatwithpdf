The **RAG (Retrieval Augmented Generation) App** is a Python-based tool that enables users to interact with their PDF documents using generative AI. By combining retrieval-based systems and generative models, this app allows you to query, chat, and gain insights directly from your documents. 

This project demonstrates advanced concepts like running RAG apps locally (using Ollama), updating vector databases dynamically, utilizing RAG workflows with PDFs (or other files), and testing the quality of AI-generated responses.

---

## Features

1. **Query PDFs**:
   - Ask natural language questions directly from your PDF files.
   - Receive accurate, context-aware responses.

2. **Dynamic Vector Database**:
   - Automatically update the database when new documents are added.
   - Ensures your queries always access the latest information.

3. **Local Deployment**:
   - Run the app locally with tools like **Ollama**, ensuring data privacy.
   - No reliance on external cloud services.

4. **File Compatibility**:
   - Primarily supports PDFs, with extensibility for other file types (e.g., DOCX, TXT).

5. **Quality Testing**:
   - Integrated tools to assess and improve the relevance of AI-generated answers.

---

## Tech Stack

- **Python**: Core programming language for development.
- **LangChain**: For building RAG workflows.
- **Vector Databases**: Options like Pinecone, FAISS, or Weaviate for efficient document retrieval.
- **PyPDF2**: To extract text from PDFs.
- **OpenAI API**: For generating context-aware, natural language responses.
- **Streamlit/Gradio**: For creating an intuitive user interface (optional).
- **Ollama**: For local model deployment.

---
