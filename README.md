# Ask questions on a external knowledge base with LLM

This project loads a pdf file, split it into chunks, convert them into embeddings and save locally.

Instead of vector database like pinecone, saving locally is sufficient for a smaller pdf (<1000 pages).

The relevant chunks will be pulled up and inserted into the prompt when querying llm, producing more relevant and accurate answers.