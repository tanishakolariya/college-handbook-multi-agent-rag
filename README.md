#  College Handbook RAG Assistant

An AI-powered question-answering system that combines **Retrieval-Augmented Generation (RAG)**, semantic search, and AI agents to retrieve and answer questions using college handbook information.

##  Overview

College handbooks contain important information about academic policies, attendance requirements, and student guidelines. Finding specific information in lengthy documents can be time-consuming.

This project explores how **RAG and tool-using AI agents** can make college information easier to retrieve through natural-language queries.

##  Key Features

- **PDF Text Extraction:** Extracts text from the college handbook.
- **Text Chunking:** Divides extracted text into smaller chunks for retrieval.
- **Text Embeddings:** Converts text into numerical vector representations.
- **Semantic Search:** Uses cosine similarity to identify relevant document chunks.
- **RAG Pipeline:** Supplies retrieved document context to a language model.
- **AI Agent Integration:** Combines document retrieval with additional tools.
- **Context-Grounded Answers:** Uses retrieved information to support responses to handbook-related questions.

##  Technology Stack

- Python
- Jupyter Notebook
- Retrieval-Augmented Generation (RAG)
- Text Embeddings
- Scikit-learn
- Cosine Similarity
- Smolagents
- Large Language Models (LLMs)

##  How It Works

1. Extract text from the college handbook PDF.
2. Clean the extracted text and divide it into chunks.
3. Generate embeddings for the document chunks.
4. Convert the user's question into an embedding.
5. Retrieve relevant chunks using cosine similarity.
6. Pass the retrieved context to the language model.
7. Use an AI agent and its configured tools to process supported queries and generate responses.

##  Project Structure

```text
college-handbook-multi-agent-rag/
├── smolagent.ipynb
├── README.md
└── LICENSE
```

## Future Improvements

- Evaluate retrieval quality using a test dataset.
- Experiment with different chunk sizes and retrieval strategies.
- Include source references in generated answers.
- Improve handling of questions with insufficient supporting context.
- Build a user-friendly interface.

##  Author

**Tanisha Kolariya**  
B.Sc. Data Science | Aspiring AI Engineer
