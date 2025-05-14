# NestJS MCP Server

A demo project using NestJS with Model Context Protocol (MCP).

## Installation

```bash
# Install dependencies
npm install
```

## Configuration

The project has been configured with TypeScript to support imports with the `.ts` extension.

## Running the Application

### Stateful Server

```bash
npx ts-node-dev --respawn ./servers/statefull-server.ts
```

### Stateless Server

```bash
npx ts-node-dev --respawn ./servers/stateless-server.ts
```

## Project Structure

- `/resources`: Contains MCP resources such as prompts, tools, and resources
- `/servers`: Contains servers with different modes (stateful, stateless)

## Features

- Uses MCP (Model Context Protocol) with NestJS
- Supports both stateful and stateless modes
- Integrates sample prompts and tools