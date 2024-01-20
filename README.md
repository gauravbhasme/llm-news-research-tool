
# News Research Analysis Tool 🔎

## Overview

This tool is a powerful solution designed for effortless information retrieval in the stock market and financial domain. With this tool, users can input article URLs, ask questions, and receive relevant insights, providing a streamlined approach to gathering valuable information.

## Features

Article URL Input: Users can input article URLs directly to fetch the corresponding article content.

Unstructured URL Loading: The tool utilizes LangChain's Unstructured URL Loader to process article content efficiently, extracting key information related to the stock market and finance.

Embedding Vector Construction: OpenAI's embeddings are employed to construct embedding vectors, capturing the essence of the article content. This allows for a comprehensive understanding of the information.

FAISS Integration: To enhance information retrieval, the tool leverages FAISS, a powerful similarity search library. This enables swift and effective retrieval of relevant information based on the constructed embedding vectors.

LLM Interaction (ChatGPT): Users can interact with Language Model (ChatGPT),  by inputting queries and receiving answers along with source URLs. This facilitates a conversational approach to extracting insights from the loaded articles.

Streamlit Interface: The entire tool is presented through a Streamlit web application, providing users with an intuitive and user-friendly platform to interact with the various features seamlessly.
