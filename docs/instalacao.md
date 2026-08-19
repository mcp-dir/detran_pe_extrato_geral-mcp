# Instalação detalhada

DETRAN PE: Extrato Geral (Nada consta) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_detran_pe_extrato_geral`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_detran_pe_extrato_geral` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_detran_pe_extrato_geral` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_detran_pe_extrato_geral` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.detran_pe_extrato_geral` (ou `servers.detran_pe_extrato_geral` no VS Code) do config do cliente e reinicie.
