# Ai-legal-assistant
Intro
The AI Legal Assistant is an intelligent system designed to answer legal questions using uploaded documents such as PDFs and case files.
 It uses RAG (Retrieval-Augmented Generation) to ensure every response is grounded in real legal text, minimizing errors and hallucinations. 
The system integrates LangChain for document chunking and retrieval workflows, and IBM WatsonX for accurate, context-aware answer generation. 
It helps students, users, and legal professionals quickly locate relevant IPC sections, laws, and judgments without manually searching lengthy documents.
Problem Background & Motivation
Problem Background
Legal documents such as IPC sections, judgments, and case laws are extremely long, complex, and difficult to search manually.
Students, lawyers, and common users struggle to locate relevant legal information quickly.
Traditional keyword search often gives incomplete or misleading results.

Motivation
There is a growing need for a fast, intelligent, document-based legal support system.
With advancements in AI, especially RAG (Retrieval-Augmented Generation), it is now possible to answer legal queries accurately and with citations.
Our motivation is to make legal knowledge accessible, reliable, and easy to search for everyone.
Novelty of Idea 
What Makes Our Idea Unique?
Uses Retrieval-Augmented Generation (RAG) to ensure every answer is grounded in real legal documents, not guessed by AI.
Integrates LangChain + Vector Databases + WatsonX to retrieve the most relevant legal text before generating an answer.
Provides evidence-backed legal responses with citations from uploaded PDFs.
Unlike normal chatbots, our system does not hallucinate — it only answers from uploaded documents.
Has potential to scale across multiple laws, acts, languages, and domains such as contracts, cybercrime, property law, etc.

Why It Is Innovative
Brings together modern LLM reasoning + document retrieval → high accuracy legal responses.
Converts complex legal documents into searchable, AI-understandable chunks.
Reduces a 5–10 minute manual search to less than 5 seconds.
TOOLS & TECHNOLOGIES
IBM WATSONX.AI → LLM FOR FINALANSWER GENERATION
IBM WATSON NLU → PREPROCESSING & METADATA EXTRACTION LANGCHAIN → CHUNKING, EMBEDDINGS, RETRIEVAL, RAG PIPELINE
VECTOR DATABASE (E.G., PINECONE / FAISS) → STORES EMBEDDINGS FOR SIMILARITY SEARCH PDF/TEXT EXTRACTORS → PDFPLUMBER / PYPDF2
STREAMLIT → WEB UI FRONTEND 
PYTHON- CORE IMPLEMENTATION
