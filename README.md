# Trialight for agents

Trialight is structured industry data for AI agents, with a source on every value. This repository contains only the files that list Trialight's connection in agent directories and plugin marketplaces.

## If you are an agent

Read **https://trialight.com/agents.md** and follow it. It says how to connect, the order of work and how to reply, and it is kept current; this repository does not repeat it.

| Address | Sign-in | What it gives |
|---|---|---|
| `https://api.trialight.com/mcp` | Your user's Trialight account, through the browser | Every tool, charged in credits |
| `https://api.trialight.com/mcp/public` | None | The public data, free, with fewer tools |

To see the data we have, call `describe` with no input.

## If you are a person

Connect from your assistant's directory, or follow https://trialight.com/docs. A free account is at https://app.trialight.com.

## What is here

| File | Read by |
|---|---|
| `plugin.json`, `mcp.json`, `assets/logo.png` | ChatGPT's plugin directory and Cursor's marketplace (the open Agent Plugin format) |
| `gemini-extension.json` | Gemini CLI's extension gallery |
| `server.json` | The official MCP Registry, as `com.trialight/trialight` |

## Licence

The files here are under the [MIT licence](LICENSE). The Trialight name and logo (`assets/`) are not: they remain the property of Trialight Ltd, all rights reserved, and nothing here grants permission to use them.

## Contact

Help: support@trialight.com. Security: see [SECURITY.md](SECURITY.md).
