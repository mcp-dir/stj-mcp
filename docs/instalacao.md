# Instalação detalhada

Jurisprudência STJ é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_stj`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_stj` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_stj` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_stj` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.stj` (ou `servers.stj` no VS Code) do config do cliente e reinicie.
