# RAG_BASED_Q-A_SYSTEM

## Overview
An interactive system that allows users to query uploaded PDF documents using Google Generative AI's Gemini model and ChromaDB. The project enables users to extract meaningful answers from uploaded documents in a user-friendly and non-technical manner.

## Table Of Contents
- Introduction
- Features
- Technologies Used
- Installation
- Usage
- Code Overview
- Limitation
- Future Enhancements

## Introduction
This project demonstrates a solution for document querying using advanced AI techniques. Users can upload a PDF file, extract its content, store embeddings in a database, and query the database using natural language. The system provides comprehensive answers in a friendly and conversational tone.

## Features
- Extract Text From PDF
- Store and manage document embeddings using ChromaDB.
- Query the stored documents with natural language.
- Leverage Google Generative AI's Gemini model for embedding and answering queries.
- User-friendly conversational tone for non-technical audiences.

## Technologies Used
- **Python**: Core programming language.
- **Google Generative AI**: For embedding and generating answers.
- **ChromaDB**: Database for storing and querying embeddings.
- **PyPDF2**: PDF parsing and text extraction.
- **Jupyter Widgets**: Interactive file upload interface.

## Installation 
### 1. Clone this repository:
    ```bash
    git clone https://github.com/krimerwool/RAG_BASED_Q-A_SYSTEM
    cd RAG_BASED_Q-A_SYSTEM
### 2. Install Dependencies:\
    ```bash
    pip install -r requirements.txt
### 3. Set up the environment variable for the Google API Key:
    ```bash
    export GOOGLE_API_KEY="YOUR_API_KEY"
## Usage
  - Open the notebook and execute the code cells sequentially.
  - Use the upload widget to upload a PDF file.
  - The content of the PDF will be extracted and stored in ChromaDB.
  - Query the database using natural language to retrieve specific information.
  - View responses formatted in a conversational and user-friendly manner.




