# Upilot — AI Account Hub (Web Launcher)

Launcher statis untuk Google Flow, Dola, Migoo. Tanpa backend, tanpa password/token.

## Run lokal

Buka `index.html` langsung, atau:

```bash
npx serve .
```

## Deploy Cloudflare Pages

Connect repo `upilot` → Build command kosong, Output `/`.

## Data

`localStorage[aihub.accounts]` → `{id, provider, name, createdAt, lastOpenedAt}`.
