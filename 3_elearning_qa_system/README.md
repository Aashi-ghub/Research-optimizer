# E-Learning Q&A System

A production-ready question and answer system built with Google PaLM LLM and LangChain for e-learning platforms. This system provides an intelligent FAQ assistant that can handle student queries with instant, accurate responses.

![](qa_system.png)

## Project Highlights

- Processes large-scale FAQ datasets for e-learning platforms
- Reduces workload on human support staff
- Provides instant answers to student questions
- Scalable vector-based knowledge retrieval system

## Technologies

- **LangChain + Google PaLM:** LLM-based question answering
- **Streamlit:** Interactive web interface
- **HuggingFace Instructor Embeddings:** Text embeddings
- **FAISS:** Vector database for semantic search

## Installation

1. Clone this repository to your local machine:
```bash
git clone https://github.com/Aashi-ghub/Research-optimizer.git
```

2. Navigate to the project directory:
```bash
cd 3_elearning_qa_system
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Acquire an API key through [makersuite.google.com](https://makersuite.google.com) and put it in a `.env` file:
```bash
GOOGLE_API_KEY="your_api_key_here"
```

## Usage

1. Run the Streamlit app:
```bash
streamlit run main.py
```

2. The web app will open in your browser.

3. To create a knowledge base of FAQs:
   - Click on "Create Knowledgebase" button
   - Wait for the knowledge base to be created (this may take some time)
   - Once created, you will see a directory called `faiss_index` in your current folder

4. Ask questions:
   - Type your question in the Question box and hit Enter
   - Receive instant, accurate answers based on the FAQ knowledge base

## Sample Questions

- Do you provide internship opportunities and EMI payment options?
- What programming languages are covered in your courses?
- Should I learn Power BI or Tableau?
- Can I use Power BI on a Mac computer?
- How can I enable Power Pivot?

## Project Structure

- `main.py`: The main Streamlit application script
- `langchain_helper.py`: Contains all LangChain implementation code
- `faqs.csv`: FAQ dataset file
- `requirements.txt`: Required Python packages
- `.env`: Configuration file for storing your Google API key (create this file)
