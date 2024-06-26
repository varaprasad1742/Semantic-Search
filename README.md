# Semantic Search

Semantic search is a technique that aims to improve search accuracy by understanding the meaning and context of search queries and documents, rather than relying solely on keyword matching. 
It leverages natural language processing (NLP) and artificial intelligence (AI) to interpret the intent behind a user's query and retrieve more relevant results. 

#### Workflow:
* Connect to Qdrant vector database
* Read a csv file
* Create a collection in Qdrant
* Convert text into Embeddings using Sentence Transformer
* Uploading the embeddings to Qdrant
* Perform a query 
