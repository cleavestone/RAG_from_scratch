# 📚 Retrieval-Augmented Generation (RAG) Learning Journey

This repository documents my hands-on learning path in **Retrieval-Augmented Generation (RAG)**.  
The goal is to build a strong foundation, explore different components step by step, and eventually design scalable RAG systems for real-world use cases.  

---

## ✅ Completed Notebooks (in order of learning)

### 🟢 Foundations
1. 🔵 [**Mathematical Foundations of RAG**](notebook/Mathematical_Foundations_of_RAG.ipynb)  
   - Core probability, similarity metrics, and vector space concepts.  
   - Provides the groundwork for embeddings and retrieval.  

---

2. 🔵 [**Text Chunking Strategies**](notebook/Text_Chunking_Strategies.ipynb)  
   - Why chunking is critical in RAG.  
   - Explored multiple methods: fixed-size, sentence-based, semantic, overlapping, and structure-aware chunking.  

---

3. 🔵 [**Document Loaders**](notebook/Document_Loaders.ipynb)  
   - Ingesting raw data into structured `Document` objects.  
   - Covered different file formats and loaders:  
     - **PDFs** → `PyPDFLoader`  
     - **Text files** → `TextLoader`  
     - **CSV files** → `CSVLoader`  
     - **Web pages** → `WebBaseLoader`  
   - Prepared documents for **chunking → embeddings → retrieval flow**.  

---

### 🔵 Embeddings
4. [**Embedding Models**](notebooks/Embedding_models.ipynb)  
   - Word, sentence, and document embeddings (including multilingual).  
   - Hands-on with `all-MiniLM-L6-v2` (SBERT).  
   - Implemented cosine similarity for comparison.  
   - Covered fine-tuning embeddings for domain-specific tasks.  

---

### 🟣 Vector Search
5. [**Approximate Nearest Neighbor (ANN) Algorithms**](notebooks/Approximate_Nearest_Neighbors_Algorithms.ipynb)  
   - Studied and implemented key ANN algorithms:  
     - **HNSW (Hierarchical Navigable Small World)** → Graph-based, high accuracy.  
     - **IVF (Inverted File Index)** → Quantization-based, efficient on large datasets.  
     - **LSH (Locality-Sensitive Hashing)** → Hashing-based, very fast but coarse.  
   - Compared trade-offs in **accuracy, speed, memory, and best use cases in RAG**.  

---

## 📌 Next Steps
- Dive deeper into **vector databases** (e.g., FAISS, Pinecone, Weaviate).  
- Explore **retriever + generator pipelines**.  
- Implement a **mini RAG project** using the learned components.  
