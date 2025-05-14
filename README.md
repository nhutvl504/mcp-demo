# MCP Demo

This project is a comprehensive example of using the Model Context Protocol (MCP) with various technologies. It includes three subprojects: fast-mcp-client, lastmile-mcp, and nest-mcp.

## Project Structure

### fast-mcp-client
- Simple MCP client built with Python
- Uses the `fastmcp` library to connect to MCP servers

### lastmile-mcp
- Advanced MCP client using the `mcp-agent` library
- Integrates with OpenAI and other tools
- Supports logging and flexible configuration

### nest-mcp
- MCP server built with NestJS (TypeScript)
- Supports both stateful and stateless modes
- Includes examples of prompts, tools, and resources

## Getting Started

### Installing and Running the Server (nest-mcp)

```bash
cd nest-mcp
npm install

# Run stateless server
npx ts-node-dev --respawn ./servers/stateless-server.ts

# Or run stateful server
npx ts-node-dev --respawn ./servers/statefull-server.ts
```

### Running fast-mcp-client

```bash
cd fast-mcp-client

# Create virtual environment
uv venv .env

# Activate virtual environment
source .env/bin/activate  # On macOS/Linux
# env\Scripts\activate  # On Windows

# Install dependencies
uv pip install -r requirements.txt

# Run client
uv run client.py
```

### Running lastmile-mcp

```bash
cd lastmile-mcp

# Create virtual environment
uv venv .env

# Activate virtual environment
source .env/bin/activate  # On macOS/Linux
# env\Scripts\activate  # On Windows

# Install dependencies
uv pip install -r requirements.txt

# Run client
uv run main.py
```

## Features

- Illustrates the implementation of Model Context Protocol (MCP)
- Examples of client-server connections using MCP
- Support for HTTP transport methods with streaming capabilities
- Integration with AI and natural language tools

## System Requirements

- Python 3.10+
- Node.js 18+ (for nest-mcp)
- uv tool (for Python environment management)
- npm (for Node.js package management)
