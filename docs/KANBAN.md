# Klaus_backup — Sanpablo (Dev) Kanban

## NOW (Critical / unblock)
- [ ] Confirm indexing policy for dev (recommended: **noindex** for sanpablo).
- [ ] Verify WordPress health: plugin conflicts/warnings (notably SSL warning from `woo-product-custom-size-guide` + session warnings from `phonepe-payment-solutions`).
- [ ] Decide repo scope: **themes only** vs **themes + plugins** vs **custom-only**.

## NEXT (High impact)
- [ ] SEO baseline audit (titles/meta, H1, canonicals, sitemap, robots, schema).
- [ ] Home page copy refresh aligned to brand (youthful + Indian cultural vibe).
- [ ] Performance baseline (Core Web Vitals quick pass; reduce bloat where possible).

## LATER (Hardening / scale)
- [ ] Set up repeatable deploy workflow (dev → prod) with rollback.
- [ ] Nightly backups (DB + wp-content excluding uploads caches) + retention policy.
- [ ] Monitoring: uptime, SSL expiry, error log watch.

## DONE
- [x] Located sanpablo install path on Hostinger.
- [x] Took DB + wp-content backup on server.
- [x] Created GitHub repo and pushed initial snapshot (excluding uploads/secrets/logs).
