# How to Use

Install this MCP server by adding the following JSON code to your MCP config file

```json
{
  "mcpServers": [
    {
      "name": "Chess",
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/gtrifoni-ciandt/chesscom-mcp.git",
        "chess"
      ]
    }
  ]
}
```
