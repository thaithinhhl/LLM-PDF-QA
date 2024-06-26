# RAG Application for Lesson Document Q&A

## Overview

This project uses Retrieval-Augmented Generation (RAG) to answer questions based on lesson documents. The system integrates a vector database, retriever, and large language models (LLMs) to provide accurate answers.

## Pipeline

The project pipeline is illustrated in the image below:
![image](https://github.com/thaithinhhl/LLM-PDF-QA/assets/149486062/e3cac1a0-4d25-4a39-af7d-7d35dd1c0126)

1. **Input Document**: Upload lesson documents.
2. **Vector Database**: Stores vector representations of the documents.
3. **Retriever**: Finds relevant sections from the vector database based on the question.
4. **Prompt**: Combines the retrieved information and the question.
5. **LLMs**: Uses the Vicuna LLM to generate answers.
6. **Output Answer**: Provides the final answer to the user.

## Input and Output

- **Input**: Questions and lesson documents.
- **Output**: Generated answers based on the documents.


