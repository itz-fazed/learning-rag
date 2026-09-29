# Learning RAG

A hands-on repository for learning how to implement **Retrieval-Augmented Generation (RAG)** in AI systems.

## What this project is about

The goal is to build and understand a RAG pipeline end to end: ingest documents, retrieve relevant context, and generate grounded answers instead of relying on the model alone.

## Domain: nutrition

For this learning project, the knowledge base focuses on **nutrition**. Source materials in `docs/` provide factual grounding so the system can answer nutrition-related questions and help guide someone toward healthier everyday choices.

Current knowledge sources:

- USDA FoodData Central dataset
- Dietary Guidelines for Americans

## Repository layout

```
docs/           Knowledge base files used for retrieval
ingestion.py    Entry point for loading and preparing source material
```

## Status

Early stage — focused on learning RAG concepts and wiring up ingestion against a nutrition knowledge base.
