# Custom Retriever using LlamaIndex and Gemini

## Overview
This project demonstrates how to build a **Custom Retriever** using **LlamaIndex** and **Google Gemini**. It combines **vector-based retrieval** and **keyword-based retrieval** to enhance query responses.

## Features
- Loads and processes documents using `SimpleDirectoryReader`
- Uses **Gemini Embeddings** for vector-based retrieval
- Implements a **Custom Retriever** that combines:
  - **Vector search** (Semantic similarity)
  - **Keyword search** (Lexical match)
- Integrates with **LlamaIndex** to enable efficient querying
- Uses `RetrieverQueryEngine` for structured retrieval

## Installation
To run this project, install the required dependencies:

```bash
pip install llama-index google-generativeai
