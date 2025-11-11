# Embedding  

This directory will hold scripts to create vector embeddings from cleaned content. The aim is to convert text into numerical vectors using embedding models and store them in Pinecone for semantic search.  

Recommended tasks:  
- Use a language model to generate embeddings (e.g. OpenAI or Hugging Face models).  
- Upsert embeddings into a Pinecone index along with metadata such as content source, date, and relevance scores.  
- Implement functions to perform similarity searches over the embeddings.  
- Weight embeddings or metadata by user interactions (likes/comments/shares) to prioritize more relevant content during retrieval. 
