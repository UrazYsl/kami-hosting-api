# Kami Hosting — API
Express backend for the Kami Hosting site.

**Status:** http://PLACEHOLDER/api/status · **Web repo:** https://github.com/UrazYsl/kami-hosting-web

## Endpoints
- `GET /api/status` → health JSON
- `POST /api/order` → `{ plan, email, notes? }` → `201 { ok: true }`

## Quickstart (local)
```bash
npm i
npm run dev    # http://127.0.0.1:3000/api/status
