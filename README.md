# Coffee Barista AI Agent

Coffee Barista AI Agent is an AI-powered assistant designed to answer coffee-related queries and provide intelligent recommendations using Generative AI and Retrieval Augmented Generation (RAG).

The project combines Google Agent Development Kit (ADK), Streamlit, and vector-based search to build a conversational AI system that retrieves relevant information from a knowledge base and generates accurate responses.

## Project Overview

The goal of this project is to develop an intelligent coffee assistant that can understand user queries, search through coffee-related information, and provide useful responses through a simple interactive interface.

The system uses a RAG architecture where relevant information is retrieved from stored documents and provided to the AI model to improve response accuracy and reliability.

## Features

- Conversational AI assistant for coffee-related queries
- Retrieval Augmented Generation (RAG) based response generation
- Document-based knowledge retrieval
- Semantic search using vector embeddings
- Streamlit-based interactive user interface
- Google ADK agent integration
- Scalable architecture for future cloud deployment

## System Architecture

User->Streamlit Interface->Google ADK AI Agent->RAG Pipeline->Vector Database->Coffee Knowledge Documents

## Technologies Used

Programming Language:
- Python

AI :
- Gen AI
- LLMs
- RAG
- Vector Embeddings

Frameworks and Tools:
- Google ADK
- Streamlit
- Vector Database

## Installation and Setup

### To clone the repository
git clone https://github.com/sanathsarker10/Coffee-Barista-AI-Agent

### To navigate to the project directory
cd Coffee-Barista-AI-Agent

### To install required dependencies
pip install -r requirements.txt

### To run the application
streamlit run app/main.py

## Working

1. We users enter the query through the Streamlit interface
2. The AI agent processes the request
3. The RAG pipeline searches the vector database for relevant information
4. Retrieved knowledge is provided to the language model
5. The system generates a context-aware response

## Deployment

The application can be deployed using cloud platforms such as Google Cloud Run or Streamlit Cloud.

## Live Link

https://coffee-barista-704462473519.asia-south1.run.app/