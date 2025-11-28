# LangChain Projects Portfolio

A comprehensive collection of practical projects demonstrating various applications of LangChain, LLMs, and vector databases. This repository showcases my journey learning and implementing Large Language Model (LLM) applications using the LangChain framework.

## 🚀 Overview

This portfolio contains four distinct projects, each exploring different aspects of LangChain and LLM integration:

1. **LangChain Crash Course** - Fundamentals and basic LLM operations
2. **RockyBot: News Research Tool** - Document retrieval and Q&A system
3. **Codebasics Q&A System** - E-learning FAQ assistant with vector search
4. **AtliQ Tees: SQL Database Interface** - Natural language to SQL query system

## 📚 Projects

### 1. LangChain Crash Course
**Location:** `1_langchain_crash_course/`

An introductory project covering LangChain fundamentals including:
- Basic LLM operations and chains
- Prompt templates and output parsers
- Streamlit application development
- **Restaurant Name Generator**: A Streamlit app that generates restaurant names and menu items based on cuisine type

**Technologies:** LangChain, OpenAI API, Streamlit

---

### 2. RockyBot: News Research Tool
**Location:** `2_news_research_tool_project/`

An intelligent news research assistant that allows users to:
- Load and process news articles from URLs
- Perform semantic search using FAISS vector store
- Ask questions and get answers with source citations
- Interactive Streamlit-based user interface

**Key Features:**
- URL-based article loading using UnstructuredURLLoader
- Text chunking and embedding generation
- FAISS vector database for efficient similarity search
- Retrieval-augmented generation (RAG) for accurate answers

**Technologies:** LangChain, OpenAI API, FAISS, Streamlit, Unstructured

---

### 3. Codebasics Q&A System
**Location:** `3_project_codebasics_q_and_a/`

A production-ready FAQ assistant for an e-learning platform that:
- Processes real-world FAQ datasets
- Uses Google PaLM LLM for question answering
- Implements semantic similarity search with FAISS
- Provides instant answers to student queries

**Key Features:**
- Vector-based knowledge retrieval
- Google PaLM integration
- FAISS index for fast similarity search
- Streamlit web interface

**Technologies:** LangChain, Google PaLM, FAISS, HuggingFace Embeddings, Streamlit

---

### 4. AtliQ Tees: SQL Database Interface
**Location:** `4_sqldb_tshirts/`

A natural language interface to MySQL database that:
- Converts natural language questions to SQL queries
- Executes queries on a T-shirt inventory database
- Uses few-shot learning for improved accuracy
- Provides business insights through conversational queries

**Key Features:**
- SQLDatabaseChain for query generation
- Few-shot learning with semantic similarity
- ChromaDB for example selection
- Handles complex queries involving joins, aggregations, and discounts

**Technologies:** LangChain, Google PaLM, MySQL, ChromaDB, HuggingFace Embeddings, Streamlit

## 🛠️ Technologies Used

- **LLM Frameworks:** LangChain, OpenAI, Google PaLM
- **Vector Databases:** FAISS, ChromaDB
- **Embeddings:** OpenAI Embeddings, HuggingFace Instructor Embeddings
- **Web Framework:** Streamlit
- **Database:** MySQL
- **Python Libraries:** pandas, numpy, pickle, unstructured

## 📦 Installation

### Prerequisites
- Python 3.8+
- pip
- MySQL (for Project 4)

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

4. **Set up API keys:**
   - For OpenAI projects: Create a `.env` file with `OPENAI_API_KEY=your_key_here`
   - For Google PaLM projects: Create a `.env` file with `GOOGLE_API_KEY=your_key_here`

5. **Run the application:**
```bash
streamlit run main.py
```

## 📁 Project Structure

```
langchain/
├── 1_langchain_crash_course/
│   ├── lanchain_crashcourse.ipynb
│   ├── RestaurantNameGenerator/
│   └── requirements.txt
├── 2_news_research_tool_project/
│   ├── main.py
│   ├── notebooks/
│   └── requirements.txt
├── 3_project_codebasics_q_and_a/
│   ├── main.py
│   ├── langchain_helper.py
│   └── requirements.txt
└── 4_sqldb_tshirts/
    ├── main.py
    ├── database/
    └── requirements.txt
```

## 🎯 Key Learnings

Through these projects, I've gained hands-on experience with:

- **LLM Integration:** Working with multiple LLM providers (OpenAI, Google PaLM)
- **Vector Databases:** Implementing FAISS and ChromaDB for semantic search
- **RAG Systems:** Building retrieval-augmented generation pipelines
- **Text Processing:** Document loading, chunking, and embedding generation
- **SQL Generation:** Converting natural language to SQL queries
- **Few-Shot Learning:** Improving LLM accuracy with example-based prompts
- **Web Applications:** Building interactive UIs with Streamlit

## 🔧 Features Demonstrated

- ✅ Document loading and text splitting
- ✅ Vector embeddings and similarity search
- ✅ Retrieval-augmented generation (RAG)
- ✅ Natural language to SQL conversion
- ✅ Few-shot learning with semantic similarity
- ✅ Streamlit web application development
- ✅ API integration (OpenAI, Google PaLM)
- ✅ Database connectivity and query execution

## 📝 Notes

- All projects include comprehensive Jupyter notebooks for learning and experimentation
- API keys should be stored securely in `.env` files (not committed to version control)
- Some projects include pre-built vector indices for demonstration purposes
- Database setup scripts are included for SQL-based projects

## 🤝 Contributing

This is a personal learning portfolio. Feel free to explore, fork, or use these projects as learning resources!

## 📄 License

This project is open source and available for educational purposes.

## 🔗 Resources

- [LangChain Documentation](https://python.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [Google PaLM](https://makersuite.google.com/)
- [Streamlit](https://streamlit.io/)
- [FAISS](https://github.com/facebookresearch/faiss)

---

**Built with ❤️ as a personal learning project**

*Exploring the possibilities of LLMs and LangChain, one project at a time.*
