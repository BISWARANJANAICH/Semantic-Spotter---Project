# Semantic-Spotter---Project

Project Overview
Semantic Spotter is a Retrieval-Augmented Generation (RAG) system built using LangChain, HuggingFace embeddings, FAISS, and FLAN-T5 to perform semantic search over PDF documents.
________________________________________
Installation
pip install langchain
pip install langchain-community
pip install sentence-transformers
pip install faiss-cpu
pip install transformers
________________________________________
How to Run
1.	Open the notebook in Google Colab.
2.	Install dependencies.
3.	Upload PDF documents.
4.	Run all cells sequentially.
5.	Ask questions using the ask_question() function.
________________________________________
Project Workflow
•	Load PDFs
•	Split documents
•	Generate embeddings
•	Store in FAISS
•	Retrieve relevant chunks
•	Generate grounded answer
________________________________________
Example Query
What is covered under accidental insurance?
________________________________________
Requirements
•	Python 3.9+
•	8GB RAM recommended
•	Google Colab or local Jupyter environment

