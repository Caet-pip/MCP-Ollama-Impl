# MCP-Ollama-Impl
Very basic and simple implementation of MCP (Model Context Protocol) with Ollama

### Install requirements
pip install -r requirements.txt

### Command to run the MCP Server (This contains the tool calling mechanism)
python server.py

### Command to run the MCP Client (This communicates with Ollama and MCP Server)
python client.py <path to server.py>

This Ollama integration is very simple and was inspired by https://github.com/anjor/ollama-mcp-client which is more in-depth.
