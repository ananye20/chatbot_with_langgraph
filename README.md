# Chatbot with Lang Graph
This project showcases a conversational AI chatbot built with LangGraph, LangChain, and Groq LLMs. It demonstrates how to design, build, and run a chatbot using a state graph approach to manage conversation flow.

## Features
- **LangGraph State Management** – Implements chatbot logic with `StateGraph` for structured conversation handling.  
- **Groq LLM Integration** – Uses `ChatGroq` with the `Gemma2-9b-It` model for fast and efficient responses.  
- **LangChain Orchestration** – Leverages LangChain for managing prompts, models, and execution flows.  
- **Customizable Workflow** – Easily extend conversation states and chatbot behavior.

## Tech Stack
- **LangGraph**
- **LangChain**
- **Groq LLMs** (`ChatGroq`)
- **Python (Colab / Jupyter Notebook)**

## Set up your API Key

import os
os.environ["GROQ_API_KEY"] = "your_api_key"
os.environ["LANGCHAIN_API_KEY"] = "your_api_key"

## Example Usage

- Define chatbot states using LangGraph.
- Pass user messages into the chatbot function.
- Get model-generated responses using Groq’s LLMs.

## License

This project is licensed under the MIT License.
