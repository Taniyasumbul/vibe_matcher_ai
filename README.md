#  Vibe Matcher — AI-based Fashion Recommender
**By Taniya Sumbul**

###  Project Overview
This notebook implements a *mini recommendation system* that takes a "vibe" query (like *"boho"*, *"urban chic"*, *"cozy"*) and matches top-3 fashion products based on semantic similarity.

###  Tech Stack
- Python, Pandas, scikit-learn  
- SentenceTransformer (`all-MiniLM-L6-v2`)  
- Cosine Similarity for ranking  

###  Steps
1. Create product DataFrame (5–10 mock fashion items)  
2. Generate embeddings for each item  
3. Compute cosine similarity with query  
4. Display top-3 matches + similarity scores  
5. Evaluate latency and “good” match rate  

###  Reflection
- Could use Pinecone / FAISS for scalable retrieval  
- Add personalization via user interaction data  
- Extend to multimodal (image + text) embeddings  

###  Example Query
