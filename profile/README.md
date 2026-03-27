<p align="center">
  <img src="https://raw.githubusercontent.com/delimit-ai/delimit-mcp-server/main/docs/demo.gif" alt="Delimit" width="700">
</p>

<h3 align="center">API governance for AI coding assistants</h3>
<p align="center">Switch models, not context.</p>

<p align="center">
  <a href="https://www.npmjs.com/package/delimit-cli"><img src="https://img.shields.io/npm/v/delimit-cli" alt="npm"></a>
  <a href="https://github.com/marketplace/actions/delimit-api-governance"><img src="https://img.shields.io/badge/GitHub%20Action-v1.7.0-blue" alt="Action"></a>
  <a href="https://delimit.ai"><img src="https://img.shields.io/badge/docs-delimit.ai-purple" alt="Docs"></a>
</p>

---

### How it works

1. **Add the Action** — one YAML file, zero config
2. **Push a PR** — Delimit diffs your OpenAPI spec against the base branch
3. **Get a report** — 27 change types detected, semver classified, migration guide posted

### Quick start

```bash
npx delimit-cli setup
```

### Repos

| Repo | What |
|------|------|
| [delimit-mcp-server](https://github.com/delimit-ai/delimit-mcp-server) | CLI + MCP server (116 tools) |
| [delimit-action](https://github.com/delimit-ai/delimit-action) | GitHub Action |
| [delimit-vscode](https://github.com/delimit-ai/delimit-vscode) | VS Code extension |
| [example-fastapi](https://github.com/delimit-ai/example-fastapi) | FastAPI example with live PR |
| [docs](https://github.com/delimit-ai/docs) | Documentation site |

### Live demos

- [Auto-fix loop (PR #11)](https://github.com/delimit-ai/delimit-mcp-server/pull/11) — Delimit flags, Claude fixes
- [FastAPI breaking changes (PR #1)](https://github.com/delimit-ai/example-fastapi/pull/1) — 3 breaking changes caught

<p align="center"><b>Keep Building.</b></p>
