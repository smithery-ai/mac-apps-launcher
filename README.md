# Mac Apps Launcher MCP Server
[![smithery badge](https://smithery.ai/badge/@joshuarileydev/mac-apps-launcher-mcp-server)](https://smithery.ai/server/@joshuarileydev/mac-apps-launcher-mcp-server)

A Model Context Protocol (MCP) server for launching and managing macOS applications.

## Features

- List all applications installed in the `/Applications` folder
- Launch applications by name
- Open files with specific applications

## Installation

### Installing via Smithery

To install Mac Apps Launcher for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@joshuarileydev/mac-apps-launcher-mcp-server):

```bash
npx -y @smithery/cli install @joshuarileydev/mac-apps-launcher-mcp-server --client claude
```

### Installing Manually
Add the following to your Claude Config JSON file
```
{
  "mcpServers": {
    "simulator": {
      "command": "npx",
      "args": [
        "y",
        "@joshuarileydev/mac-apps-launcher-mcp-server"
      ]
    }
  }
}
```