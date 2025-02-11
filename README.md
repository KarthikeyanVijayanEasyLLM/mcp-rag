# mcp-rag

RAG in [MCP](https://modelcontextprotocol.io/). This is a example MCP server for vanilla RAG.

## Concepts
[RAG Explained](https://www.youtube.com/watch?v=L8DXQJMJayE)

## Tools

The server implements one tool:
- retrieve: Retrieves the docs based on the query

## Quickstart - Claude Desktop

In Claude Desktop, go to `File` -> `Settings` -> `Developer` -> `Edit Config`

or

On MacOS: `~/Library/Application\ Support/Claude/claude_desktop_config.json`
On Windows: `%APPDATA%/Claude/claude_desktop_config.json`

In claude_desktop_config.json, add JSON given in config.json in this repo.

### Debugging

Since MCP servers run over stdio, debugging can be challenging. For the best debugging
experience, we strongly recommend using the [MCP Inspector](https://github.com/modelcontextprotocol/inspector).
