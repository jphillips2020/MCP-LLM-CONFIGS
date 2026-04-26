# MCP-LLM-CONFIGS

This repository contains Model Context Protocol (MCP) server configurations for various AI development environments.

## Configurations

### mcp_config.windsurf.json
MCP server configuration for Windsurf IDE.

**Servers:**
- **camoufox**: Headless browser automation server at `http://172.31.253.154:8000/mcp`
- **searxng**: Privacy-respecting metasearch engine at `http://192.168.1.101:8000/sse`

### mcp_config.antigravity.json
MCP server configuration for Antigravity.

**Servers:**
- **camoufox**: Headless browser automation server at `http://172.31.253.154:8000/mcp`

## Usage

Copy the appropriate configuration file to your IDE's MCP configuration directory and adjust the server URLs as needed for your environment.

## MCP Servers

- **camoufox**: Provides stealthy browser automation capabilities for web scraping and interaction
- **searxng**: Provides privacy-focused search functionality across multiple search engines

## Notes

- Server URLs are configured for a local network environment and may need adjustment for different setups
- The Windsurf configuration enables the `fetch_web_content` tool for searxng
- The Antigravity configuration uses `serverUrl` key for compatibility
