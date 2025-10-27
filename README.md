# Metadata-Driven Hybrid Search for Enhanced TAU Online Tutor

**Orpaz Ashkenazy, Guy Weintraub, Yaar Koren**

Workshop On Applying Large Language Models to Education
Tel-Aviv University, February 2025

## Abstract

This paper presents an enhancement to TAU Online Tutor (OT), an AI-powered educational assistant designed to support the university students, by integrating metadatabased querying into a Retrieval-Augmented Generation (RAG) framework. 
Our approach enhances both retrieval and answer generation through metadata-driven capabilities by introducing an additional LLM step, along with architectural functions and logic, to parse and analyze user queries, refining downstream retrieval and generationprocesses. 
The query parsing mechanism, referred to as self-querying, employs a LLM to extract metadata directly from user queries, enabling metadata-based filtering in the vector database. 
Further analysis of the parsed query enabled the incorporation of adaptive strategies, optimizing both retrieval parameters and the answer generation process. 
We evaluated the effectiveness of our work on a benchmark dataset comprising both standard queries and metadata-specific queries.
Overall, our findings contribute to the advancement of OT by providing a scalable framework for intelligent, adaptive, metadata-based content retrieval and question answering.
