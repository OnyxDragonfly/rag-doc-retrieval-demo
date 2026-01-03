# rag-doc-retrieval-demo

## Overview
This project demonstrates a basic Retrieval-Augmented Generation (RAG) pipeline that allows a language model to answer questions using external documents.

## Why This Project
RAG pipelines are commonly used to reduce hallucinations and enable LLMs to work with private data or domain-specific data.

## PreRequisits:
- Updated Python & Ollama installed + running
- Install: pip install -r requirements.txt
- Run: python src/<script>.py
- Model: Replace "Phi4:Latest" with the model you are using.

## Current Status
- Repo Initialized
- Project Structure Created


## Day 2 Progress
- Implemented basic document embedding
- Added similarity-based retrieval
- Injected retrieved context into LLM prompts
- Successfully answered queries using grounded data
