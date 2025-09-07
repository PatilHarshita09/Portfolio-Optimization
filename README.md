# Portfolio-Optimization
This project is designed to perform portfolio optimization and predict future returns using historical stock data RAG and a language model.

APPROACH: 
Data Gathering – Download historical, news, and fundamental financial data for selected stocks.

Data Structuring – Convert raw data into Document objects for database use.

Vector Database Setup – Create a Chroma vector database using OpenAI embeddings for semantic search.

Retriever Function – Fetch the most relevant documents based on a user query.

LLM Analysis – Provide retrieved context to the LLM with a pre-defined prompt.

Answer Generation – LLM generates a concise, accurate, analyst-like response.

System – This end-to-end workflow is a Retrieval-Augmented Generation (RAG) pipeline.

REQUIREMENTS:
!pip install yfinance
!pip install pandas
!pip install langchain
!pip install langchain-chroma
!pip install langchain-openai
!pip install chromadb
!pip install openai
!pip install tiktoken
!pip install numpy
