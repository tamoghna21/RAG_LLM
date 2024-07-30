# Retrieval-Augmented Generation(RAG) framework to generate answers from local knowledge base using Open source LLM (zephyr-7b-beta/ Mistral-7B-Instruct-v0.2)
Blog Post [here](https://medium.com/@tamoghna.bec/building-a-smart-chatbot-with-your-private-documents-pdf-using-langchain-faiss-and-open-source-4b93c40ef303).

## Naive RAG
* Vector Store: [FAISS](https://faiss.ai/index.html)
* Local Knowledge Base: Federal Open Market Committee (FOMC) [meeting documents](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) for the years 2020-2023
* LLM : [HuggingFaceH4/zephyr-7b-beta](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta) & [Mistral-7B-Instruct-v0.2](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2)
* Local documents in pdf

  ### NoteBooks:
  * [1a](https://github.com/tamoghna21/RAG_LLM/blob/main/1a_RAG_QA_pdf.ipynb): Creating a Vector Store database (FAISS) from pdf documents (local knowledge base)
  * [1b](https://github.com/tamoghna21/RAG_LLM/blob/main/1b_RAG_QA_pdf_full.ipynb): RAG implementation using transformers pipeline
  * [1c](https://github.com/tamoghna21/RAG_LLM/blob/main/1c_RAG_QA_pdf_full_with_langchain.ipynb): RAG implementetion using langchain llm chain with ReRanker
  * [1d](https://github.com/tamoghna21/RAG_LLM/blob/main/1d_Conversational_RAG_with_pdf.ipynb) : Conversational RAG implementation

## Graph RAG

  ### Notebooks
  * [2a](https://github.com/tamoghna21/RAG_LLM/blob/main/2a_GraphRAG_Neo4j.ipynb) : Graph RAG implemention using Neo4j Graph and Open source LLM(Mistral-7B-Instruct-v0.2)

Colab Notebooks.

