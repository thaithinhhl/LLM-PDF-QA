RAG Application for Lesson Document Q&A
Overview
This project uses Retrieval-Augmented Generation (RAG) to answer questions based on lesson documents. The system integrates a vector database, retriever, and large language models (LLMs) to provide accurate answers.

Pipeline
The project pipeline is illustrated in the image below:


Input Document: Upload lesson documents.
Vector Database: Stores vector representations of the documents.
Retriever: Finds relevant sections from the vector database based on the question.
Prompt: Combines the retrieved information and the question.
LLMs: Uses the Vicuna LLM to generate answers.
Output Answer: Provides the final answer to the user.
Input and Output
Input: Questions and lesson documents.
Output: Generated answers based on the documents.
