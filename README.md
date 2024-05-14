# Conversational AI with RAG Application Model

This project implements a conversational AI model using open-source embeddings from Hugging Face and the Groq Mixtral model using Casandra Based Vector Store. The goal is to create a retrieval-augmented generation (RAG) application capable of answering questions based on provided context.

## Overview

The project utilizes a combination of data loaders, text preprocessing techniques, embeddings, and a vector store to enable conversational AI capabilities. It leverages state-of-the-art natural language processing (NLP) technologies to process text documents and generate context-based responses.

## Key Components

- **Data Loaders**: Fetches and loads text documents from specified web URLs.
- **Text Preprocessing**: Splits and processes text into manageable chunks for analysis.
- **Embeddings**: Utilizes Hugging Face Bge embeddings for text representation.
- **Vector Store**: Implements a Cassandra-based vector store to manage text embeddings.
- **ChatGroq Model**: Incorporates the Groq Mixtral model for conversational AI.

## Setup and Usage

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hamzahey/Rag-Application-with-Open-source-embeddings-and-Groq-Mixtral-Model-with-Casandra-based-Vector-Store.git

2. Install Dependencies:
```bash 
    pip install -r requirements.txt

3. Setup Enviroment Variables:
```bash
    GROQ_API_KEY=your_groq_api_key
    ASTRA_DB_TOKEN=your_astra_db_token
    ASTRA_DB_ID=your_astra_db_id

4. Run Application:
```bash
    python main.py

## Note
This project serves as a demonstration of a retrieval-augmented generation (RAG) application using advanced NLP techniques and open-source libraries. Feel free to explore and extend the functionality based on your use case.

