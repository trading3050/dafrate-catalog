# dafrate-catalog

Öffentlicher Produkt-Katalog von **DaFrate** — automatisch generiert (nächtlich) aus den 2Performant-Feeds.
Enthält nur **öffentliche** Produktdaten + Affiliate-Links (keine Keys). Nicht von Hand bearbeiten (wird überschrieben).

- `catalog.json.gz` — gzip-komprimierter Katalog (`{ lastRefresh, total, produse[] }`)
- `catalog-meta.json` — Counts + `lastRefresh` (Staleness-Check des Clients)
