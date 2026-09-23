# RAG Chatbot

A **Retrieval-Augmented Generation (RAG) chatbot** that combines document retrieval with a Large Language Model to provide context-aware answers based on information stored in a knowledge base.

## Workflow

1. **Document Loading** – Loads the source information from a knowledge base.
2. **Text Normalization** – Cleans and prepares the text for further processing.
3. **Tokenization** – Processes the text using NLP techniques.
4. **Chunking** – Splits the document into smaller overlapping chunks for efficient retrieval.
5. **Embeddings** – Converts text chunks into numerical vector representations.
6. **Vector Database** – Stores the embeddings using FAISS for efficient similarity search.
7. **Similarity Search** – Retrieves the most relevant information based on the user's query.
8. **Response Generation** – Combines the user's question with the retrieved context and sends it to Google Gemini to generate a relevant response.

## Technologies Used

* Python
* LangChain
* Hugging Face Embeddings
* FAISS
* spaCy
* TextBlob
* Google Gemini
* Regular Expressions

## Purpose

This project demonstrates how a **RAG-powered chatbot** can understand user queries, retrieve relevant information from a knowledge base, and generate context-based responses using a Large Language Model.

The project focuses on understanding the complete flow of a RAG chatbot, from **document processing and retrieval to AI-powered response generation**.

## Files

* `RAG_architecture.ipynb` — RAG chatbot development and experiments
* `data.txt` — Knowledge base used by the chatbot

## Future Improvements

* Improve document preprocessing
* Experiment with different embedding models
* Compare different chunking strategies
* Add conversation history and conversational memory
* Improve retrieval accuracy
* Add source references to chatbot responses
* Build an interactive user interface for the chatbot
