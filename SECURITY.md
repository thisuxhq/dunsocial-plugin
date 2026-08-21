# Security

Report security issues to [support@dunsocial.com](mailto:support@dunsocial.com). Do not file them as public GitHub issues.

This repository is a thin plugin wrapper. It points clients at the hosted DunSocial MCP:

```text
https://api.dunsocial.com/api/mcp
```

It does not ship credentials, API keys, or a local server. Authentication is OAuth in the client. Approve access in the browser. Do not put tokens or `Authorization` headers in `mcp.json`. The agent should not type passwords.
