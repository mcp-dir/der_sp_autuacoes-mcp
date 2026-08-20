# Instalação detalhada

DER SP: Autuações é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_der_sp_autuacoes`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_der_sp_autuacoes` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_der_sp_autuacoes` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_der_sp_autuacoes` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.der_sp_autuacoes` (ou `servers.der_sp_autuacoes` no VS Code) do config do cliente e reinicie.
