# Vector Database - (HNSW)

Vector databases are specialized databases designed to store and efficiently search high-dimensional vectors (embeddings). HNSW (Hierarchical Navigable Small World) is a graph-based indexing algorithm that enables fast approximate nearest neighbor search in vector spaces. It builds a multi-layer graph structure where each layer contains fewer nodes, allowing efficient navigation from coarse to fine-grained search. HNSW provides an excellent balance between search speed and accuracy, making it popular in production RAG systems for semantic search and retrieval.
