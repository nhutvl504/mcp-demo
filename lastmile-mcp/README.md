# Fast MCP Client

This is a client for the Model Context Protocol (MCP).

## Installation

```bash
# Create a virtual environment
uv venv .env

# Activate the virtual environment
# On Windows
# env\Scripts\activate
# On macOS/Linux
source .env/bin/activate

# Install dependencies
uv pip install -r requirements.txt
```

## Usage

To run the client, use the command:

```bash
uv run main.py
```

## Features

- Connect to the MCP server
- Process requests from the server
- Send responses back to the server
