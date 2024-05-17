# Tutorial for Unstructured.io library usage

All the code comes from examples of DeepLearning.AI's [course](https://www.deeplearning.ai/short-courses/preprocessing-unstructured-data-for-llm-applications/) on Unstructured.

Includes
- Normalizing elements of several documents (PPTX, PDF, MD)
- Processing Embedded Tables
- Chunking text by section
- Using ChromaDB to store chunks in a collection
- Using Metadata to filter


On the contrary to the Unstructured API used in the course, I set up local Docker image running as an API.
Also, apart from using OpenAI-based models, I used local Embeddings and LLM via Ollama.

- [Ollama](https://github.com/ollama/ollama)
- [Unstructured API in Docker](https://github.com/Unstructured-IO/unstructured#eight_pointed_black_star-quick-start)
- [Nomic Embeddings](https://ollama.com/library/nomic-embed-text)
- [Llama3](https://ollama.com/library/llama3)
