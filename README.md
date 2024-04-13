# Retrieval-Augmented-Generation-with-Open-Source-LLM-and-LangChain
Retrieval Augmented Generation with Huggingface model Zephyr-7b and ChromaDB 

## Steps:

- Load Model and Tokenizer: Load a quantized conversational model and initialize its tokenizer.
- Mount Google Drive: Mount Google Drive to access documents.
- Process Text from PDFs: Extract text from PDF documents, remove links, references, stopwords, and blank lines, then save the processed text as text files.
- Generate Embeddings and Vectorization: Use Sentence Transformers for text embeddings, then vectorize using Chroma.
- Build Chatbot Pipeline: Construct a conversational retrieval chain with memory (RAG) using LangChain, integrating the model, retriever, and memory.
- Create UI with Gradio: Develop a user interface using Gradio for users to interact with the chatbot.

