# Sithafal-task1
# Chat With PDF - Streamlit Application

## Overview

"Chat With PDF" is a Streamlit-based application that allows users to upload PDF files, extract the text, tables, and images from them, and interact with the extracted content using an AI language model. The app performs Optical Character Recognition (OCR) on images in PDFs and stores the extracted content as vector embeddings for fast query-based interactions.

Users can ask questions about the uploaded documents, and the system will retrieve relevant text from the document and generate answers using a language model.

## Features

- **PDF Text Extraction**: Extracts raw text from uploaded PDFs.
- **Table Data Extraction**: Identifies and extracts tables from PDFs.
- **OCR on Images**: Uses Tesseract OCR to extract text from images (e.g., graphs, charts).
- **Text Chunking & Embedding**: Splits large text into smaller chunks and creates embeddings for efficient retrieval.
- **Question Answering**: Allows users to query the content of the uploaded PDFs and get answers based on the extracted text.
- **FAISS Vector Store**: Stores embeddings in a FAISS vector index for fast retrieval.


![Task1](https://i.postimg.cc/zGB9JgFw/task1.jpg)

# Chat with Website Using RAG Pipeline

This project implements a Retrieval-Augmented Generation (RAG) pipeline for interacting with websites. It allows users to query and chat with the content of websites by scraping data, embedding the text, and generating responses using a language model (GPT-2). This system enables users to ask questions about the content of multiple websites, retrieving relevant information and generating accurate answers.

## Features

- **Web Scraping**: Extracts and processes content from provided URLs (websites) using `requests` and `BeautifulSoup`.
- **Data Chunking & Embedding**: Segments the content into meaningful chunks and generates vector embeddings for efficient retrieval using the `SentenceTransformer` model.
- **Similarity Search**: Uses FAISS for fast similarity-based search to find the most relevant chunks of data from the embeddings.
- **Chat with GPT-2**: Generates detailed responses to user queries based on the retrieved content using the GPT-2 model from Hugging Face.

## Requirements

To use this project, ensure you have Python 3.7+ and the following dependencies installed:

- `requests`: For sending HTTP requests to websites.
- `beautifulsoup4`: For parsing HTML and extracting text.
- `sentence-transformers`: For generating sentence embeddings.
- `faiss-cpu`: For efficient similarity search using FAISS.
- `transformers`: For generating responses with GPT-2.
- `huggingface-hub`: For interacting with Hugging Face models.

![Task2](https://i.postimg.cc/PfCyrQg5/task2.jpg)

