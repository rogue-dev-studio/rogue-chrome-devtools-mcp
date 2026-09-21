# rogue-chrome-devtools-mcp

**Rogue Development** MCP package for agents.

Rogue Chrome DevTools MCP - inspect and debug pages from agents

- Market: https://rogue-dev-studio.github.io/rogue-market-agent/

## Requirements

- Node.js 18+ (`npx`)
- Google Chrome / Chromium available

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "chrome-devtools": {
      "command": "npx",
      "args": [
        "-y",
        "chrome-devtools-mcp@latest"
      ]
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
