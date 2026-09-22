# Focuh Agent Plugin

ADHD system of record for coding agents. Packages the hosted Focuh MCP server plus a planner skill for Cursor and other Agent Plugins clients.

## What you get
- Remote MCP at `https://www.focuh.com/api/mcp`
- Skill for Today / Loops / goals / calendar planning
- Official registry: `io.github.maxxthedeveloper/focuh`

## Install (Cursor)
1. Sign up at [focuh.com](https://www.focuh.com). Free. Early beta. No subscription.
2. Create a Bearer key in Settings → MCP
3. Install this plugin from the Cursor Marketplace once listed, or copy the repo into `~/.cursor/plugins/local/focuh`
4. Set `FOCUH_API_KEY` in plugin configure
5. Optional MCP deeplink (replace the placeholder key after install):

`cursor://anysphere.cursor-deeplink/mcp/install?name=focuh&config=eyJ1cmwiOiAiaHR0cHM6Ly93d3cuZm9jdWguY29tL2FwaS9tY3AiLCAiaGVhZGVycyI6IHsiQXV0aG9yaXphdGlvbiI6ICJCZWFyZXIgWU9VUl9GT0NVSF9BUElfS0VZIn19`

Docs: https://www.focuh.com/mcp

## Local test
Copy this folder to `~/.cursor/plugins/local/focuh`, set the API key, reload the window.
