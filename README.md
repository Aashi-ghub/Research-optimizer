# LangChain Applications Portfolio

A collection of production-ready applications built with LangChain, demonstrating practical implementations of Large Language Models (LLMs) for real-world use cases.

## 🚀 Overview

This repository contains three enterprise-grade applications showcasing different LLM integration patterns:

1. **RockyBot: News Research Tool** - Intelligent document retrieval and Q&A system
2. **E-Learning Q&A Assistant** - FAQ system with semantic search capabilities  
3. **AtliQ Tees: Business Intelligence Interface** - Natural language to SQL query system

## 📚 Projects

### 1. RockyBot: News Research Tool
**Location:** `2_news_research_tool_project/`

An intelligent news research assistant that enables users to:
- Load and process news articles from multiple URLs
- Perform semantic search using FAISS vector store
- Ask questions and receive accurate answers with source citations
- Interactive web-based user interface

**Key Features:**
- URL-based article loading using UnstructuredURLLoader
- Advanced text chunking and embedding generation
- FAISS vector database for efficient similarity search
- Retrieval-augmented generation (RAG) for contextually accurate answers
- Source attribution for all responses

**Technologies:** LangChain, OpenAI API, FAISS, Streamlit, Unstructured

---

### 2. E-Learning Q&A Assistant
**Location:** `3_elearning_qa_system/`

A production-ready FAQ assistant system that:
- Processes large-scale FAQ datasets
- Leverages Google PaLM LLM for intelligent question answering
- Implements semantic similarity search with FAISS
- Provides instant, accurate responses to user queries

**Key Features:**
- Vector-based knowledge retrieval system
- Google PaLM integration for advanced language understanding
- FAISS index for fast and scalable similarity search
- Streamlit web interface for seamless user experience
- Handles complex multi-part questions

**Technologies:** LangChain, Google PaLM, FAISS, HuggingFace Embeddings, Streamlit

---

### 3. AtliQ Tees: Business Intelligence Interface
**Location:** `4_sqldb_tshirts/`

A natural language interface to MySQL database that:
- Converts natural language questions to optimized SQL queries
- Executes queries on inventory and sales databases
- Uses few-shot learning for improved query accuracy
- Provides business insights through conversational interactions

**Key Features:**
- SQLDatabaseChain for intelligent query generation
- Few-shot learning with semantic similarity matching
- ChromaDB for efficient example selection
- Handles complex queries involving joins, aggregations, and business logic
- Real-time inventory and sales analytics

**Technologies:** LangChain, Google PaLM, MySQL, ChromaDB, HuggingFace Embeddings, Streamlit

## 🛠️ Technology Stack

- **LLM Frameworks:** LangChain, OpenAI, Google PaLM
- **Vector Databases:** FAISS, ChromaDB
- **Embeddings:** OpenAI Embeddings, HuggingFace Instructor Embeddings
- **Web Framework:** Streamlit
- **Database:** MySQL
- **Python Libraries:** pandas, numpy, unstructured, sqlalchemy

## 📦 Installation

### Prerequisites
- Python 3.8+
- pip
- MySQL (for AtliQ Tees project)

### Setup

1. **Clone the repository:**
```bash
git clone https://github.com/Aashi-ghub/Research-optimizer.git
cd Research-optimizer
```

2. **Navigate to a specific project:**
```bash
cd <project_directory>
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Configure API keys:**
   - For OpenAI projects: Create a `.env` file with `OPENAI_API_KEY=your_key_here`
   - For Google PaLM projects: Create a `.env` file with `GOOGLE_API_KEY=your_key_here`

5. **Run the application:**
```bash
streamlit run main.py
```

## 📁 Project Structure

```
Research-optimizer/
├── 2_news_research_tool_project/
│   ├── main.py
│   ├── notebooks/
│   └── requirements.txt
├── 3_elearning_qa_system/
│   ├── main.py
│   ├── langchain_helper.py
│   └── requirements.txt
└── 4_sqldb_tshirts/
    ├── main.py
    ├── database/
    └── requirements.txt
```

## 🔧 Core Capabilities

- ✅ Advanced document loading and text processing
- ✅ Vector embeddings and semantic similarity search
- ✅ Retrieval-augmented generation (RAG) pipelines
- ✅ Natural language to SQL query conversion
- ✅ Few-shot learning with semantic example selection
- ✅ Interactive web application interfaces
- ✅ Multi-LLM provider integration
- ✅ Database connectivity and query optimization

## 🎯 Use Cases

- **Content Research:** Extract insights from large document collections
- **Customer Support:** Automated FAQ systems for instant responses
- **Business Analytics:** Natural language interfaces for database queries
- **Knowledge Management:** Semantic search across organizational knowledge bases

## 📝 Configuration

- API keys should be stored securely in `.env` files (not committed to version control)
- Pre-built vector indices are included for demonstration purposes
- Database setup scripts are provided for SQL-based projects
- Each project includes comprehensive documentation in respective README files

## 🔗 Resources

- [LangChain Documentation](https://python.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [Google PaLM](https://makersuite.google.com/)
- [Streamlit](https://streamlit.io/)
- [FAISS](https://github.com/facebookresearch/faiss)

---

**Professional LLM Applications | Built with LangChain**

*Transforming how we interact with data and information through intelligent language models.*
