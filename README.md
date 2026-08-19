# DETRAN PE: Extrato Geral (Nada consta)

### DETRAN PE: Extrato Geral (Nada consta) para Claude, ChatGPT e agentes de IA

DETRAN PE: Extrato Geral (Nada consta), consulta em fonte oficial. Hospedado pela plataforma, sem credenciais da plataforma, pague por consulta com crédito pré-pago.

- 📊 **1 ferramenta**
- 🔒 **Somente leitura**
- 💬 **Funciona com qualquer cliente MCP**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Login via magic-link (sem senha)**

[English version](README.en.md) · [Documentação completa](docs/) · [Skill pra agentes](skills/)

---

## Instalar em 1 clique

### Claude (Web e Desktop)

A Anthropic unificou a instalação de MCPs em `claude.ai/customize/connectors`. **O mesmo link serve pra Claude Web e Claude Desktop** (basta estar logado):

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (se o deeplink não abrir): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → cole **Nome** `DETRAN PE: Extrato Geral (Nada consta)` e **URL** `https://api.mcp.ai/p_detran_pe_extrato_geral`.

### Cursor

[➕ Instalar DETRAN PE: Extrato Geral (Nada consta) no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=detran_pe_extrato_geral&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9kZXRyYW5fcGVfZXh0cmF0b19nZXJhbCJ9)

### VS Code (Copilot Chat)

[➕ Instalar DETRAN PE: Extrato Geral (Nada consta) no VS Code](vscode:mcp/install?name=detran_pe_extrato_geral&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_detran_pe_extrato_geral%22%7D)

### ChatGPT, Manus, OpenClaw e mais 40+ clientes

Funciona em qualquer cliente MCP que suporte **MCP over HTTP**. A URL do servidor é sempre:

```
https://api.mcp.ai/p_detran_pe_extrato_geral
```

Detalhes por cliente: [INSTALL.md](INSTALL.md).

---

## Exemplos de uso

```
Consultar DETRAN PE: Extrato Geral (Nada consta)
```

---

## 1 ferramenta disponível

| Tool | Descrição |
|---|---|
| `detran_pe_extrato_geral_consultar` | DETRAN PE: Extrato Geral (Nada consta), consulta em fonte oficial. |

Detalhe de cada tool: [docs/ferramentas.md](docs/ferramentas.md)

---

## Preços

Pré-pago (carteira de créditos), paga por uso. Veja [docs/precos.md](docs/precos.md).

---

## Privacidade & LGPD

- **Somente leitura**, nenhuma ferramenta altera dados na origem.
- **Sub-processadores**: o LLM host que você escolher (Claude, ChatGPT, Cursor, agente próprio). Lista completa em [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Os dados retornados pelas tools são enviados ao **LLM host que você escolher**, sub-processador fora do nosso controle. Recomendamos planos com opt-out de treinamento.

---

## Perguntas frequentes

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills — tudo MIT.

**Posso usar com agente próprio (não Claude/Cursor)?**
Sim — qualquer cliente que suporte MCP over HTTP. URL: `https://api.mcp.ai/p_detran_pe_extrato_geral`.


---

## Suporte

- 📧 [detran_pe_extrato_geral@mcp.ai](mailto:detran_pe_extrato_geral@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/detran_pe_extrato_geral-mcp/issues)
- 📄 [docs/](docs/)

---

## Licença

MIT — veja [LICENSE](LICENSE). O servidor MCP em `api.mcp.ai/p_detran_pe_extrato_geral` é proprietário (hosted); este repositório (manifestos, docs, skills) é MIT.
