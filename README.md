## GraphRAG_Project

This project is a hands-on implementation of **GraphRAG**, inspired by the article [GraphRAG Explained: Enhancing RAG with Knowledge Graphs](https://medium.com/@zilliz_learn/graphrag-explained-enhancing-rag-with-knowledge-graphs-3312065f99e1). 

---

## Introduction to RAG and Its Challenges  

**Retrieval Augmented Generation (RAG)** is a framework that connects external data sources with large language models (LLMs) to improve their responses.  
By retrieving domain-specific or private information, RAG helps reduce *hallucinations* and ensures that LLMs produce more accurate outputs.  
This makes RAG a powerful approach for real-world GenAI applications such as **AI chatbots, recommendation systems, and knowledge assistants**.  

A typical RAG workflow might look like this when answering a historical question:  

1. **Identify the person** – Find out who defeated Allectus.  
2. **Research related details** – Search for information about this person’s family, such as his son.  
3. **Extract the answer** – Determine the son’s name.  

---

## What is GraphRAG and How Does It Work?  

GraphRAG builds on traditional RAG by incorporating **knowledge graphs**.  
Instead of relying only on vector similarity search, GraphRAG leverages structured relationships between entities.  
This allows it to retrieve information that is not just semantically similar, but also **contextually and relationally relevant**.  

<p align="center">
  <img width="1038" height="638" alt="image" src="https://github.com/user-attachments/assets/795199c3-fd1e-4292-875f-faeaec813cd7" />

</p>  

---

## Baseline RAG vs. GraphRAG in Output Quality  

The differences between Baseline RAG and GraphRAG can be seen in their outputs:  

- **Baseline RAG** often retrieves passages that are semantically close but not truly relevant.  
  For example, when asked a question about war, it may return unrelated text, leading to an incorrect conclusion.  
- **GraphRAG**, by contrast, produces a more accurate and focused answer.  
  It identifies the main themes and provides supporting evidence drawn directly from the dataset, ensuring the response is both relevant and well-grounded in the source material.  

<p align="center">
  <img width="1400" height="769" alt="image" src="https://github.com/user-attachments/assets/5982ab18-9f17-493a-aa5a-d88880949518" />

</p>


---

## References  

- [GraphRAG Explained: Enhancing RAG with Knowledge Graphs](https://medium.com/@zilliz_learn/graphrag-explained-enhancing-rag-with-knowledge-graphs-3312065f99e1)  
