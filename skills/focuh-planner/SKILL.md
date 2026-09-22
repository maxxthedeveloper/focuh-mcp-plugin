---
name: focuh-planner
description: Use this when planning Today, Loops, goals, or calendar around ADHD-friendly work in Focuh over MCP.
---

# Focuh planner

Focuh is the ADHD todo system of record for Mac and web. Over MCP you can read and write tasks, loops, goals, calendar, and focus stats.

## Rules
- Prefer bulk writes (`create_tasks`, `update_tasks`) over one-by-one chatter.
- Loops are undated standing intentions. Do not invent fake deadlines for them.
- Keep goal labels short; next actions live on tasks.
- Auth: Bearer key from Focuh Settings → MCP. Free. Early beta. No subscription.
- Product site: https://www.focuh.com — MCP docs: https://www.focuh.com/mcp

## Typical flow
1. `get_calendar` for the day.
2. `get_tasks` for Today.
3. Propose a short plan, then apply with `create_tasks` / `update_tasks`.
4. Park non-actionable items with loops tools when needed.
