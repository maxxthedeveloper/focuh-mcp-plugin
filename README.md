# Focuh Agent Plugin

ADHD system of record for coding agents. Packages the hosted Focuh MCP server plus a planner skill for Cursor and other Agent Plugins clients.

## What you get
- Remote MCP at `https://www.focuh.com/api/mcp`
- Skills for Today / Loops / goals / calendar planning
- Official registry: `io.github.maxxthedeveloper/focuh`

## Install
1. Sign up at [focuh.com](https://www.focuh.com) (Free. Early beta. No subscription.)
2. Create a Bearer key in Settings → MCP
3. Install this plugin (Cursor Marketplace or local plugins folder), then set `FOCUH_API_KEY`

Docs: https://www.focuh.com/mcp

## Local test (Cursor)
Copy this folder to `~/.cursor/plugins/local/focuh`, set the API key, reload the window.
