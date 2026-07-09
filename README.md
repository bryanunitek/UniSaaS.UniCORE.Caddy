# UniSaaS.UniCORE.Caddy

**UniCORE fork of upstream `caddyserver/caddy`.** Part of the UniCORE upstream-merge building-block fleet.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
Fork family created: **2026-07-07 UTC.** Standard layer added: **2026-07-09 22:33 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.Caddy` is the **Caddy** family member.

**Family purpose:** Fast, extensible, cross-platform HTTP/1-2-3 web server with automatic HTTPS. UniCORE.GVB reverse-proxy / TLS-termination substrate.

## Branch model

- `main` — tracks upstream `caddyserver/caddy` (receives the periodic upstream-merge; nothing deploys from `main`).
- `unicore` — the deploy branch: `main` + UniCORE additions (Badge/attribution, config, integration). **Deploy ONLY from `unicore`.**

See [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) for the merge sequence and [`STARTING-POINT.md`](STARTING-POINT.md) for the upstream anchor. Upstream's own README is preserved verbatim as [`README.upstream.md`](README.upstream.md).

## Licence

Code additions match upstream's licence; UniCORE documentation additions are CC BY 4.0. See [`LICENSE.md`](LICENSE.md); upstream licence preserved as `LICENSE.upstream` where applicable.
