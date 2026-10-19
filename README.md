# TaskLinkr MCP Servers — Public Descriptors

Public descriptor repo for the TaskLinkr MCP server family, published under the
`co.tasklinkr` namespace on the official MCP Registry
(https://registry.modelcontextprotocol.io).

This repo contains **what** these servers are — names, descriptions, and
categories. Implementation, data sources, and infrastructure stay private.

## Servers

| Name | Registry | What it does |
|------|----------|--------------|
| `co.tasklinkr/directory` | [listing](https://registry.modelcontextprotocol.io) | Discovery for the agent ecosystem: findable businesses, tools, knowledge, agent spaces, skills. |
| `co.tasklinkr/corpus` | [listing](https://registry.modelcontextprotocol.io) | Maintained behavior records for the tools and platforms AI agents use, distilled from live docs. |
| `co.tasklinkr/skills` | [listing](https://registry.modelcontextprotocol.io) | Executable skill packages for agents: vetted competence, ready to run, not just documents. |

## Layout

- `servers/directory.md` — directory server descriptor
- `servers/corpus.md` — corpus server descriptor
- `servers/skills.md` — skills server descriptor

## Categories

- **Discovery** — `co.tasklinkr/directory`
- **Knowledge** — `co.tasklinkr/corpus`
- **Capabilities** — `co.tasklinkr/skills`

## License

Descriptors are public. Server implementations are proprietary.
