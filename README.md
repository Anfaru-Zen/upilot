# Upilot — AI Account Hub (Web Launcher)

Launcher statis untuk Google Flow, Dola, Migoo. Tanpa backend, tanpa password/token.

## Run lokal

Buka `index.html` langsung, atau:

```bash
npx serve .
```

## Deploy Cloudflare Workers Static Assets

```bash
npx wrangler deploy
```

Tanpa build step. `index.html` disajikan sebagai root URL.

## Data

`localStorage[aihub.accounts]` → `{id, provider, name, createdAt, lastOpenedAt}`.
