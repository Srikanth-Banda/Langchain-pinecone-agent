
# LangChain with Google Generative AI and Pinecone

## Overview

This project demonstrates the integration of **LangChain**, **Google Generative AI (Gemini)**, and **Pinecone** for building advanced pipelines involving AI language models and vector databases. The notebook provided in this project walks through how to use these technologies to perform text generation, store embeddings, and perform similarity searches using vectors.

The project can be used to showcase skills in handling large language models, performing semantic searches, and building complex AI-powered workflows. 

## Problem Solved

The goal of this project is to solve the problem of managing large language models and their embeddings efficiently. Specifically, it focuses on:

1. **Text Generation**: Generating content, such as explaining AI concepts (e.g., autoencoders) via prompts.
2. **Embedding Search**: Storing documents as embeddings and performing similarity searches over those embeddings.

## Key Components

- **LangChain**: Used to structure and manage conversations, text embeddings, and to create chains for processing queries.
- **Google Generative AI (Gemini)**: Used for text generation, including answering complex queries and generating creative content.
- **Pinecone**: Acts as the vector database for storing embeddings and running similarity searches.

## Sections

1. **Environment Setup**: Loading environment variables and setting API keys for Google and Pinecone.
2. **Google Generative AI Query**: Running a basic query using the `gemini-1.0-pro` model to generate content.
3. **Chat Interaction with GPT-3.5-turbo**: Implementing a conversational AI using the GPT-3.5 model.
4. **Prompt Template**: Customizing prompts for explaining AI concepts.
5. **LLMChain**: Running a LangChain process that generates explanations based on specific input.
6. **Sequential Chains**: Chaining multiple LangChain processes together.
7. **Text Splitting**: Splitting larger content into manageable text chunks for processing.
8. **Embeddings with Pinecone**: Storing text embeddings in Pinecone and running queries to perform similarity searches.
9. **Running Python Commands**: Using LangChain to run Python code execution within the chain.

## Installation

### 1. Setting up the environment and running Google Generative AI queries

```bash
python3 -m venv langchain-pine-env
source langchain-pine-env/bin/activate
```

## How to Use

1. Clone the repository containing this project.
    ```bash
    git clone git@github.com:Srikanth-Banda/langchain-pinecone-agent.git
    cd langchain-pinecone-agent
    ```
2. Setting up the environment:
    ```bash
    python3 -m venv langchain-pine-env
    source langchain-pine-env/bin/activate
    ```
3. Create a `.env` file in the root of the project and add your **API Keys**:
    ```bash
    GOOGLE_API_KEY=your_google_api_key
    PINECONE_ENV=your_pinecone_env
    PINECONE_API_KEY=your_pinecone_api_key
    ```
2. Install the required dependencies using `pip`:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook (`LangChain_Gemini_Pinecone_Project.ipynb`):
    ```bash
    jupyter notebook LangChain_Gemini_Pinecone_Project.ipynb
    ```
4. Follow the instructions within the notebook to run queries, generate text, and perform similarity searches.

## Dependencies

Ensure that you have the following Python libraries installed:

- `langchain`
- `google.generativeai`
- `pinecone-client`
- `dotenv`
- `openai`

## Conclusion

This project demonstrates how to leverage LangChain with Google Generative AI and Pinecone for efficient text generation, embedding storage, and similarity searches. It's an excellent showcase of AI skills for managing complex workflows and interacting with advanced models.
