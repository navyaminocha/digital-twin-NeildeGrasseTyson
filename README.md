# digital-twin-NeildeGrasseTyson

## Overview

The Neil deGrasse Tyson Digital Twin is a Retrieval-Augmented Generation (RAG) based conversational AI system designed to emulate the knowledge, communication style, and personality of astrophysicist Neil deGrasse Tyson.

## Features

### Retrieval-Augmented Generation (RAG)

- Loads Neil deGrasse Tyson's writings and essays
- Splits documents into semantic chunks
- Generates embeddings using HuggingFace sentence transformers
- Stores embeddings in ChromaDB vector database
- Retrieves relevant knowledge based on user queries

### Conversational Memory

- Stores conversation history
- Remembers user preferences
- Maintains conversational continuity

## Technology Stack

- Streamlit
- Gemini API
- ChromaDB
- LangChain
- HuggingFace Embeddings
- ElevenLabs
