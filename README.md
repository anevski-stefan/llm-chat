# Local LLM Chatbot

A locally-running AI chatbot built with Chainlit and CTransformers. This chatbot provides a clean web interface for interacting with local LLM models, with all processing happening on your machine.

## Features

- 🤖 Local LLM inference using CTransformers
- 💬 Clean chat interface powered by Chainlit
- 🔄 Conversation history tracking
- 🎯 Focused responses with custom system prompt
- ⚡ Real-time streaming responses
- 🚀 Easy to deploy and use

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

## Implementation Details

The chatbot is implemented with the following key components:

- **Model**: Uses the Orca Mini 3B model (quantized version) from Hugging Face
- **Interface**: Chainlit for the web UI and chat functionality
- **Memory**: Maintains conversation history for context-aware responses
- **Streaming**: Real-time token streaming for responsive user experience

The system prompt instructs the AI to provide helpful, concise answers to user queries.

## Project Structure

```
.
├── chat.py           # Main chatbot implementation
├── requirements.txt  # Python dependencies
├── chainlit.md      # Chainlit configuration
└── assets/          # Project assets
```

## Development Environment

The project includes comprehensive development environment setup:

- VS Code devcontainer configuration
- Code quality tools:
  - Black formatter
  - Flake8 linter
  - MyPy type checking
- Git configuration and ignore rules

## Dependencies

Key packages:
- `ctransformers`: For local LLM inference
- `chainlit`: Web interface and chat functionality
- Additional development dependencies in `requirements.txt`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

