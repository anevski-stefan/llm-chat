# Local LLM Chatbot

A locally-running AI chatbot built with Chainlit and CTransformers. Chat with AI models directly in your browser, with all processing happening on your machine.

## Features

- 🤖 Local LLM inference using CTransformers
- 💬 Clean chat interface with Chainlit
- 🔄 Conversational memory
- 🔀 Switch between models (Orca Mini and Llama2)
- ⚡ Streaming responses
- 🔗 Optional LangChain integration

## Quick Start

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the chatbot:
```bash
chainlit run chat.py
```

3. Open your browser at `http://localhost:8000`

## Models

The app supports two models out of the box:
- **Orca Mini 3B**: Default model, smaller and faster
- **Llama 2**: Optional larger model with potentially better responses

Models will be downloaded automatically on first use from Hugging Face.

## Development

This project includes a complete VS Code devcontainer configuration for easy development. Key tools:
- Black formatter
- Flake8 linter
- MyPy type checking

## Dependencies

Key packages:
- `ctransformers`: Local LLM inference
- `chainlit`: Chat interface
- `langchain` (optional): For advanced chains and memory

See `requirements.txt` for full list.
```

