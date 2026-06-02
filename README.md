# digital-twin-NeildeGrasseTyson

Overview

The Neil deGrasse Tyson Digital Twin is a Retrieval-Augmented Generation (RAG) based conversational AI system designed to emulate the knowledge, communication style, and personality of astrophysicist Neil deGrasse Tyson.

The system combines document retrieval, conversational memory, timeline awareness, and voice interaction to create an engaging and context-aware digital twin capable of answering scientific questions while maintaining Neil's characteristic explanatory style.

Features
Retrieval-Augmented Generation (RAG)
Loads Neil deGrasse Tyson's writings and essays.
Splits documents into semantic chunks.
Generates embeddings using HuggingFace sentence transformers.
Stores embeddings in ChromaDB vector database.
Retrieves relevant knowledge based on user queries.
Conversational Memory
Stores conversation history in JSON format.
Remembers user preferences and facts.
Recalls previous interactions.
Maintains conversational continuity.
Memory Dashboard
Displays total stored memories.
Shows recent conversations.
Extracts and displays learned user facts.
Allows exploration of previous interactions.
Timeline Awareness
Maintains awareness of the current date.
Includes key milestones from Neil deGrasse Tyson's career.
References scientific events within proper historical context.
Produces temporally grounded responses.
Voice Interaction
Voice input support using speech recognition.
Voice output using ElevenLabs Text-to-Speech.
Enables natural spoken conversations with the digital twin.
Persona Simulation
Replicates Neil deGrasse Tyson's communication style.
Uses analogies and storytelling techniques.
Provides educational and conversational responses.
Maintains consistent personality throughout interactions.
System Architecture

User
↓
Streamlit Interface
↓
Prompt Builder

├── Memory System (memory.json)
├── Timeline Context
├── RAG Retrieval
│ └── ChromaDB
│ └── HuggingFace Embeddings
│ └── Neil Documents
↓
Gemini API
↓
Generated Response
↓
ElevenLabs Text-to-Speech
↓
User

Technology Stack
Frontend
Streamlit
Large Language Model
Google Gemini
Vector Database
ChromaDB
Embedding Model
all-MiniLM-L6-v2
Retrieval Framework
LangChain
Voice Output
ElevenLabs
Data Processing
Python
Memory Storage
JSON
