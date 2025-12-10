# Semantic Graph Chunking (SGC)

Semantic Graph Chunking (SGC) is a structured semantic preprocessing technique designed to transform complex documents into clean, coherent, and semantically enriched chunks. It has the potential to significantly improve RAG pipelines by enhancing retrieval quality and reducing model hallucinations.

**SGC combines, in a single step:**

1- Ontology-based structuring (hierarchical and semantic meaning)
2- GraphRAG-inspired contextual relations
3- Semantic enrichment (high-relevance domain terms)
4- Zero-overlap logical chunking
5- Full hierarchical preservation

This integration forms a deterministic preprocessing flow that can substantially increase the precision and consistency of retrieval-augmented systems.

## Why SGC matters
SGC introduces a new paradigm of structured semantic preprocessing.
While traditional methods simply “cut text,” SGC interprets, organizes, enriches, and structures the document before chunking.

This produces chunks that are:

✔ semantically consistent
✔ noise-free
✔ aligned with the true thematic content
✔ enriched with domain-specific terminology
✔ suitable for deeper and more accurate contextual queries

For systems that depend on high-quality segmentation, SGC can become a meaningful differentiator.

## How it works

1- The user provides a structured document (laws, technical manuals, contracts, reports, etc.).
2- SGC sends the content to an LLM using a single central prompt that defines the entire processing logic.
3- The LLM analyzes hierarchy, semantics, and structure according to strict rules.
4- SGC returns a processed file containing:
*explicit hierarchy
*precise chunk markers
*semantic enrichment
*preservation of the original text

**Key Features**

✔ Zero-overlap logical chunking
✔ High semantic coherence
✔ Multi-provider LLM support
✔ Entire behavior controlled by one configurable prompt
✔ Output ready for any RAG pipeline
✔ Easily adaptable to any domain

## CLI (sgc-cli)
sgc process path/to/document.txt


Output file:
document_sgc.txt

**The user only needs to provide their own API key (OpenAI, Gemini, Claude, etc.).**

Model Configuration
The configuration file allows setting:

API key

provider

endpoint

model

custom prompt file

The design aims to remain simple while offering flexibility for advanced customization.

Why SGC tends to work well

It unifies techniques that are usually applied separately, generating a stronger semantic representation that may improve retrieval accuracy, reduce ambiguity, and increase consistency.

Instead of merely slicing text,
SGC transforms text into structured knowledge.

Installation (coming soon)
pip install sgc

Contributions

Pull requests, suggestions, and improvements are welcome.
