﻿# Project_RAG

This project was developed as part of an optional class in Big Data and AI. The aim of the project was to implement a language model and understand the workings of a RAG (Retrieval-Augmented Generation) model.

The code is capable of sourcing PDFs directly from Google Drive, extracting and processing their text, and then storing this information in a vector database using ChromaDB. Additionally, it integrates the Gemma 7b model from Google via a Hugging Face Endpoint, forming a RAG model chain that can respond to user questions.

With the provided Gradio interface, users can directly interact with the implemented RAG model. They can input questions related to the content of the PDFs, and in return, the RAG model generates responses based on the available knowledge. This functionality enables users to query the model and receive informative answers tailored to their inquiries.
