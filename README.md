A Retrieval-Augmented Generation (RAG) chatbot that allows users to interact with CSV data using natural language queries. Instead of manually writing queries or scanning spreadsheets, this system retrieves relevant rows and generates accurate, context-aware answers using Large Language Models (LLMs).


CSV Data → Preprocessing → Embedding → Vector Store → Retriever → LLM → Response

The system follows a standard RAG pipeline:
CSV Parsing – Load and clean structured data
Chunking – Convert rows into text chunks
Embedding – Transform text into vector representations
Retrieval – Find most relevant chunks using similarity search
Generation – LLM generates final answer using retrieved context
