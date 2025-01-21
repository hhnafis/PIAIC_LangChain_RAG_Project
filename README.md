# PIAIC_LangChain_RAG_Project

This project implements a Retrieval Augmented Generation (RAG) system using Google Gemini, LangChain, and Pinecone. It ingests documents (PDFs in this case), chunks and embeds them using Gemini embeddings, and stores them in a Pinecone vector database.

When a user asks a question, the system retrieves relevant context from the database and feeds it to the Gemini LLM along with the question to generate a comprehensive and accurate answer. Finally, the project deploys the RAG system as an API using FastAPI for easy access.
