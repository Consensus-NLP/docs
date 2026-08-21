<a href="https://consensus.app"><img src="logo/light.svg" alt="Consensus" width="80" /></a>

# Consensus Documentation

[![Docs](https://img.shields.io/badge/docs-docs.consensus.app-068EF1)](https://docs.consensus.app)
[![MCP guide](https://img.shields.io/badge/guide-MCP-3BCDAA)](https://docs.consensus.app/docs/mcp)
[![API reference](https://img.shields.io/badge/reference-API-068EF1)](https://docs.consensus.app/reference/v1_search)
[![Follow on X](https://img.shields.io/badge/follow-%40ConsensusNLP-000000?logo=x&logoColor=white)](https://x.com/ConsensusNLP)

Source for [docs.consensus.app](https://docs.consensus.app) — developer documentation for [Consensus](https://consensus.app), the AI search engine for research over 220M+ peer-reviewed papers. Built with [Mintlify](https://mintlify.com).

## What's inside

- **[MCP guide](https://docs.consensus.app/docs/mcp)** — connect Claude, ChatGPT, Cursor, and any MCP client to Consensus search (`consensus-mcp.mdx`)
- **[API reference](https://docs.consensus.app/reference/v1_search)** — the `/v1/search` REST endpoint, generated from `openapi.json`

## Develop locally

```bash
npm i -g mint   # Mintlify CLI
mint dev        # preview at http://localhost:3000
```

Edit the `.mdx` pages or `docs.json` and the preview hot-reloads. Changes merged to `main` deploy to production automatically.

## Related

- [consensus-mcp](https://github.com/Consensus-NLP/consensus-mcp) — the Consensus MCP server
- [consensus-api](https://github.com/Consensus-NLP/consensus-api) — the Consensus REST API

---

Made by [Consensus](https://consensus.app), the AI search engine for research. Follow us on [X](https://x.com/ConsensusNLP) and [LinkedIn](https://www.linkedin.com/company/consensus-nlp).
