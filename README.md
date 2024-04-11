# Retrieval Augmented Generation (RAG) with Open Source LLM and LangChain for PDF Search

This project introduces an innovative approach to searching PDF documents using the power of LangChain, ChromaDB, and an Open Source LLM. The system aims to enable efficient retrieval, summarization, and response generation for user queries without relying on external services.

# Features:

LangChain: LangChain facilitates language generation and understanding, enhancing the search tool's capabilities.
ChromaDB: ChromaDB acts as a vector store and database, enabling efficient storage and retrieval of vector representations of PDF documents.
Open Source LLM: Utilizing an Open Source Language Model (LLM) enables question-answering capabilities, allowing the system to process user queries and extract relevant information from PDF documents.
Unique Aspects:

# No External Services: 
The system operates entirely on the CPU, eliminating the need for external services like the OpenAI API. This ensures greater control, privacy, and accessibility for PDF search needs.
Tasks:

# Data Pre-processing and Cleaning: 
Clean PDF files by removing figures, tables, and in-text citations.
Vector Database Creation: Index cleaned text files using an open-source vector database, preprocess text, and create vector representations of each file.
Query Formulation and Retrieval: Use LangChain to integrate the vector database and LLM to retrieve the top 5 most similar research findings for each query.
Summarization and Response Generation: Summarize retrieved findings using another LLM and generate final responses for each query.
Application Process Integration using LangChain: Demonstrate proficiency in using LangChain to integrate various processes and application process integration in the code.

