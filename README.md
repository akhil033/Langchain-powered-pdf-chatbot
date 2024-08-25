# Langchain-powered-pdf-chatbot

This is a conversational chatbot powered by Langchain, OpenAI and Hugging Face models. It is designed to provide a seamless chat interface for querying information from PDF documents. The chatbot utilizes the capabilities of language models and embeddings to perform conversational retrieval, enabling users to ask questions and receive relevant answers from the PDF content.

## Purpose

The purpose of this project is to create a chatbot that can interact with users and provide answers from a provided PDF document. The chatbot uses natural language processing and machine learning techniques to understand user queries and retrieve relevant information from the PDFs. By incorporating OpenAI and Hugging Face models, the chatbot leverages powerful language models and embeddings to enhance its conversational abilities and improve the accuracy of responses.

## Features

- Conversational Retrieval: The chatbot uses conversational retrieval techniques to provide relevant and context-aware responses to user queries.
- Language Models: The project incorporates OpenAI and Hugging Face models for natural language understanding and generation, enabling the chatbot to engage in meaningful conversations.
- PDF Text Extraction: The PDF documents are processed to extract the text content, which is used for indexing and retrieval.
- Text Chunking: The extracted text is split into smaller chunks to improve the efficiency of retrieval and provide more precise answers.
  
## Technologies Used

1. Langchain
2. ChromaDB as vector store
3. OpenAI embeddings
4. OpenAI chat model (gpt-3.5-turbo)
5. Gradio 

## Steps performed

1. Build a chatbot interface using Gradio
2. Extract texts from pdfs and create embeddings
3. Store embeddings in the Chroma vector database
4. Send query to the backend (Langchain chain)
5. Perform a semantic search over texts to find relevant sources of data
6. Send data to LLM (ChatGPT) and receive answers on the chatbot

