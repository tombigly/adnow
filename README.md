# AdNow Marketing — Landing site

Marketing site for **AdNow Marketing**, an MCP server that generates AI video ads and auto-publishes them to Instagram, TikTok, X, Facebook, and YouTube — directly from Claude Code.

Live at **[adnowmarketing.com](https://adnowmarketing.com)**.

## Stack

Single static `index.html`. No build step, no JS framework, no external assets. Inline SVG creatives, system fonts, CSS gradients only. Loads in under 50 ms cold.

## Deploying

Pushed to `main` → served by GitHub Pages → mapped to `adnowmarketing.com` via the `CNAME` file.

## Local preview

```bash
open index.html
```

That's it.

## Related

- **Ad Studio MCP** — the actual product code (Gemini Nano Banana → Replicate Kling → Cloudflare R2 → Pipedream).
