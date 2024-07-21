# RAG Pipeline Implementation

## Project Overview
This project demonstrates how to build a Retrieval-Augmented Generation (RAG) pipeline from scratch. The goal is to create a local implementation that processes and embeds documents, retrieves relevant information, and generates augmented responses using a language model.

## Features

1. Document Processing and Embedding:
- Import and preprocess a PDF document.
- Perform exploratory data analysis (EDA) on the text data.
- Split text into sentences and further process them for embedding.

2. Embedding and Retrieval:
- Embed the processed text using a suitable embedding model.
- Implement a simple retrieval mechanism to find relevant text chunks based on a query.

3. Generation:
- Use the retrieved text chunks to augment the input query.
- Generate responses using a language model.

4. Interactive Query Handling:
- Formulate and format queries.
- Retrieve relevant resources and generate context-aware responses.
