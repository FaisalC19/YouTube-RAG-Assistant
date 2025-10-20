# YouTube-RAG-Assistant
A production-ready Retrieval Augmented Generation (RAG) system that enables intelligent Q&A and summarization of educational YouTube videos. Built with modern AI engineering practices and designed for scalability.

## 🚀 Features

- **Intelligent Video Processing**: Automated YouTube transcript extraction with error handling
- **Semantic Search**: FAISS vector database with OpenAI embeddings
- **Timestamp Citations**: Answers include specific video timestamps for verification
- **Production Architecture**: Modular, well-tested, and containerized
- **Advanced RAG**: Semantic chunking, hybrid search, and query optimization

| Component | Technology | Purpose |
|-----------|------------|---------|
| **LLM** | OpenAI GPT-4-turbo | Reasoning & text generation |
| **Embeddings** | text-embedding-3-small | Vector representations |
| **Vector Store** | FAISS | Efficient similarity search |
| **Framework** | LangChain | RAG pipeline orchestration |
| **UI** | Gradio | User-friendly interface |
| **Processing** | YouTube Transcript API | Video content extraction |
