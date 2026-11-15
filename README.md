# MailSlurp plugin for Claude

Connects Claude to [MailSlurp](https://www.mailslurp.com): test inboxes and phone numbers, email rendering previews on real clients and devices, inbox placement tests and sender warmup.

## Install in Claude Code

```
/plugin install mailslurp --marketplace mailslurp/mailslurp-claude-plugin
```

The plugin adds the MailSlurp MCP server (`https://api.mailslurp.com/mcp`) and skills for email rendering, inbox placement, sending connections and warmup. You sign in to MailSlurp and choose the workspace when the server first connects. Then ask: "Check my MailSlurp connection and explain the actions available for this workspace."

Available tools depend on the permissions you approve when you connect. Rendering, placement and other usage follow your MailSlurp plan.

## Other clients

Add `https://api.mailslurp.com/mcp` as a remote MCP server. Setup guides for Claude, ChatGPT, Codex, Cursor and others are at [mailslurp.com/docs/mcp](https://www.mailslurp.com/docs/mcp/).

[Documentation](https://www.mailslurp.com/docs/agents/) | [Privacy and terms](https://legal.mailslurp.com/) | [Support](https://www.mailslurp.com/contact/)

## Licence

MIT. See [LICENSE](LICENSE).
