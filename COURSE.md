# Course outline (teaser)

Full chapters, templates, and checklists ship with the **[Gumroad purchase](https://jjonesai.gumroad.com/l/yviahw)** ($99). This page is the public map only — no paid files here.

**Format:** 12 chapters · templates · printable checklists · glossary  
**Stack:** Ubuntu LTS VPS, Cloudflare DNS, Caddy, systemd or Docker Compose  
**Support:** support@jjones.ai

| Ch | Topic |
|---|---|
| 1 | VPS and domain fundamentals — registrar vs DNS vs hosting |
| 2 | VPS preparation — SSH, UFW, unattended upgrades, app user |
| 3 | App deployment patterns — systemd releases **or** Docker Compose |
| 4 | Caddy reverse proxy — 80/443 only, automatic HTTPS |
| 5 | DNS for migration — Proxied web, DNS-only mail |
| 6 | Migrating from paid hosting — inventory → cutover → monitor |
| 7 | Security and secrets |
| 8 | Backups and rollback |
| 9 | Verification commands |
| 10 | Troubleshooting (525/526/502, ACME, email after DNS) |
| 11 | Beginner quick start |
| 12 | Advanced hardening |

**Architecture taught:**

```
Internet → Cloudflare → Caddy (80/443) → app on Unix socket / private Docker network
```

App ports like 3000/5000/8000 stay off the public internet.

→ **[Get the full course on Gumroad](https://jjonesai.gumroad.com/l/yviahw)**
