# LangChain Chatbot

This project is a simple demo for a chatbot application using LangChain.  
You can refer [LangGraph-deploy](https://github.com/chinhang0104/LangGraph-deploy) for deployment. 

## Notebooks

### LangChain Notebook
Use Groq as the LLM to build the chatbot.  
Integrate a web search feature using Tavily as the web search engine.

### RAG Notebook
Use Chroma as the vector store for RAG.  
Includes a demo for setting document permission restrictions for different users.

### LangGraph Notebook
This notebook builds upon the LangChain notebook by using LangGraph. 
LangGraph is graph-based, stateful orchestration model, which is designed to handle complex, dynamic, multi-agent workflows efficiently.

## Environment
Run the following command to install the required packages:
```bash
pip install langchain-community langchain-chroma langchain-text-splitters langchain-huggingface langchain-groq langgraph langsmith
