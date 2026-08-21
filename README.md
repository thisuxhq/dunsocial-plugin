# DunSocial

Schedule and publish social posts with OAuth, drafts, media, workspaces, and brand memory.

This repo is a thin Agent Plugin for DunSocial's hosted MCP. It is not the product source, not the knowledge base, and not the CLI skill repo.

## Hosted MCP

| | |
| --- | --- |
| URL | `https://api.dunsocial.com/api/mcp` |
| Transport | Streamable HTTP |
| Auth | OAuth in the client |
| Registry name | `com.dunsocial/dunsocial` |

Hosted only. No API key, no token paste, and no `Authorization` header in `mcp.json`. Confirm with the user before publishing a post.

## Install the plugin

Cursor and other Agent Plugin clients can install this repository. Cursor reads `.cursor-plugin/plugin.json`. Portable clients read root `plugin.json` and `mcp.json`.

After install, approve the OAuth prompt in your browser. Sign in, choose a workspace, and grant the scopes you want. Wait until that approval finishes. The agent should not type passwords or paste tokens.

Submit this public repo at [cursor.com/marketplace/publish](https://cursor.com/marketplace/publish) when you want it listed on the Cursor Marketplace.

## Add the MCP URL yourself

In any OAuth-capable MCP client, add a Streamable HTTP server named DunSocial:

```text
https://api.dunsocial.com/api/mcp
```

The client opens DunSocial for OAuth. Approve access there, then return to the client.

## Links

- Product and MCP setup: [dunsocial.com/mcp](https://www.dunsocial.com/mcp)
- Knowledge base (do not copy it here): [thisuxhq/dunsocial](https://github.com/thisuxhq/dunsocial)
- CLI skills (separate project): [thisuxhq/dunsocial-skills](https://github.com/thisuxhq/dunsocial-skills)

## License

MIT. Copyright THISUX Private Limited 2026.

Security reports: [support@dunsocial.com](mailto:support@dunsocial.com)
