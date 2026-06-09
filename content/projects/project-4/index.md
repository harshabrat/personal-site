+++
title = "ResearchGPT"
date = 2025-04-29

[taxonomies]
categories = ["artificial-intelligence"]
+++

ResearchGPT is a Retrieval-Augmented Generation system for querying and summarizing scientific research papers using natural language questions.

<!-- more -->

The project focuses on making dense academic papers easier to explore. It loads research documents, splits them into smaller semantic chunks, generates embeddings, and stores the vectors in FAISS for fast similarity search.

When a user asks a question, the system retrieves the most relevant paper sections and passes them into a LangChain workflow connected to the Gemini API. The response is generated from the retrieved context so answers stay closer to the source material and avoid unsupported claims.

Key work included:

- Built document chunking and embedding generation with Sentence Transformers.
- Implemented semantic search with FAISS to retrieve high-relevance context.
- Integrated Gemini API through LangChain for grounded question answering.
- Designed responses around source-backed summaries to improve relevance and reduce hallucinations.

Tech stack:

Python, LangChain, FAISS, Sentence Transformers, Gemini API
