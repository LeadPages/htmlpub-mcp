# HTMLPub — MCP Server

**Publish the web page your AI just built — live, on your own domain.**

HTMLPub is a hosted publishing platform. Its MCP server lets Claude, ChatGPT, Cursor, and other AI assistants **create and publish web pages, sites, and blogs directly to hosting** — pass it HTML and it's live. Unlike temporary paste-HTML tools, HTMLPub pages are **permanent, on your own custom domain, with built-in forms to capture leads**.

- 🌐 **Server URL:** `https://mcp.htmlpub.com/mcp`
- 🔑 **Auth:** OAuth — sign in with your HTMLPub account (no API key)
- 🚚 **Transport:** Streamable HTTP (remote)
- 💻 **Clients:** Claude.ai · Claude Desktop · Claude Code · Cursor · ChatGPT (paid)

## What it does

Connect once and your AI can:

| Tool | What it does |
|---|---|
| `create_page` | Publish HTML as a live page (optional custom slug) |
| `update_page` | Replace a page's full HTML |
| `edit_page` | Make targeted text edits to a page |
| `get_page` / `list_pages` | Read your pages |
| `delete_page` | Remove a page |
| `create_site` / `list_sites` | Group related pages into a site |
| `upload_asset` | Add images, CSS, JS, or fonts |

## Connect in 30 seconds

**Claude.ai / Claude Desktop:** Settings → Connectors → add a custom connector → enter `https://mcp.htmlpub.com/mcp` → sign in with your HTMLPub account.

**Cursor:** add the remote MCP server URL `https://mcp.htmlpub.com/mcp` in your MCP settings.

Full setup guide: <https://htmlpub.com/docs/mcp>

## Why HTMLPub

Most AI tools write you a page, then leave you stuck on the hard part: getting it online. HTMLPub is the publish step — permanent hosting, your own custom domain from $10/mo, and lead-capture forms, not a link that expires.

- **Website:** <https://htmlpub.com>
- **Docs:** <https://htmlpub.com/docs/mcp>
- **Pricing:** Free (design + preview) · Starter $10 (custom domain) · Pro $29 · Business $49
