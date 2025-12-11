# **Semantic Graph Chunking (SGC)**

**Semantic Graph Chunking (SGC)** is a structured semantic preprocessing technique designed to transform complex documents into clean, coherent, and semantically enriched chunks. It has the potential to significantly improve RAG pipelines by enhancing retrieval quality and reducing model hallucinations.

SGC combines, in a single step:

- **Ontology-based structuring** (hierarchical and semantic meaning)  
- **GraphRAG-inspired contextual relations**  
- **Semantic enrichment** (high-relevance domain terms)  
- **Zero-overlap logical chunking**  
- **Full hierarchical preservation**  

This integration forms a deterministic preprocessing flow that can substantially increase the precision and consistency of retrieval-augmented systems.

---

## **Why SGC matters**

SGC introduces a **new paradigm of structured semantic preprocessing**.  
While traditional methods simply “cut text,” SGC **interprets, organizes, enriches, and structures** the document before chunking.

This produces chunks that are:

- semantically consistent  
- noise-free  
- aligned with the true thematic content  
- enriched with domain-specific terminology  
- suitable for deeper and more accurate contextual queries  

For systems that depend on high-quality segmentation, SGC can become a meaningful differentiator.

---

## **How it works**

1. The user provides a structured document (laws, technical manuals, contracts, reports, etc.).  
2. SGC sends the content to an LLM using a **single central prompt** that defines the entire processing logic.  
3. The LLM analyzes hierarchy, semantics, and structure according to strict rules.  
4. SGC returns a processed file containing:  
   - explicit hierarchy  
   - precise chunk markers  
   - semantic enrichment  
   - preservation of the original text  

---

## **Key Features**

- ✔ Zero-overlap logical chunking  
- ✔ High semantic coherence  
- ✔ Multi-provider LLM support  
- ✔ Entire behavior controlled by one configurable prompt  
- ✔ Output ready for any RAG pipeline  
- ✔ Easily adaptable to any domain  

---

## **CLI (sgc-cli)**

```bash
sgc process path/to/document.txt
