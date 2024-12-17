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


