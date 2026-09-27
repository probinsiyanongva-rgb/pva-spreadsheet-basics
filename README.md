# PVA Spreadsheet Basics v1.0

Cloudflare Workers Static Assets deployment package for PVA Academy.

## Structure

- `public/index.html` — learner-facing course
- `public/PVA_Spreadsheet_Basics_Practice.xlsx` — practice workbook
- `wrangler.jsonc` — Cloudflare Workers Static Assets configuration

The public asset directory is intentionally limited to the learner-facing files. Do not deploy the Git repository root as the static asset directory.

## Cloudflare deployment

Use:

```text
Build command: (blank)
Deploy command: npx wrangler deploy
Preview command: npx wrangler preview
```

The committed `wrangler.jsonc` points Cloudflare to `./public`.
