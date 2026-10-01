# AbleTime OpenAI plugin

This repository is the **hook-free OpenAI plugin package**. The repository root is the plugin root (`plugin.json`, `mcp.json`, skills, assets).

## Upload to OpenAI Platform

1. On GitHub, use **Code → Download ZIP**.
2. In [OpenAI Platform](https://platform.openai.com/) → New Plugin, upload that ZIP.

Upload creates a **draft** only. It does **not** submit the plugin for review or publish it.

## Codex marketplace

For Codex marketplace installation **with watch hooks**, use [`AbleTime/codex-plugin`](https://github.com/AbleTime/codex-plugin) instead.

## MCP endpoint

Single streamable-http server:

`https://track.abletime.com/api/public/v2/mcp/plugins`
