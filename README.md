# LinkAPM Speed-to-Lead Intake Demo

Single-page interactive demo of a custom speed-to-lead intake system, built by [lilAgents](https://lilagents.com) for a LinkAPM proposal.

## What it shows

Three views, toggled via the tab strip at the top:

1. **`01 · INTAKE`** — What a prospect (board member, condo treasurer, owner) fills out on linkapm.com.
2. **`02 · RESPONSE`** — Instant confirmation page with calendar booking + email preview.
3. **`03 · BRIEF`** — AI-generated pre-call brief delivered to the regional director's inbox ~4 minutes after submission. Includes prospect/community context, talking points, objection handling, and a suggested close.

The persona (Margaret Hollis, Stoneridge Commons COA) is fictional, designed to illustrate LinkAPM's sweet spot: self-managed community boards with high-dollar capital projects.

## Stack

- Single file, no build step
- Vanilla HTML + [Tailwind CSS](https://tailwindcss.com/) via CDN
- Google Fonts: Manrope, Fraunces, JetBrains Mono

Works in any modern browser, including mobile.

## Local preview

```bash
open index.html
# or
python3 -m http.server 8000
```

## Deploy

Static hosting — drop into any host that serves HTML. Currently deployed via Vercel.

---

Built by [lilAgents](https://lilagents.com) — human-first, AI-driven agency.
