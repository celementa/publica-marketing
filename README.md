# publica Marketing Services — marketing.publica.kg

Same structure as publica.kg (repo `celementa/publica-site`):

- **Meta data (titles, descriptions, noindex):** `_data/seo.yml`
- **Site settings (domain, GTM):** `_config.yml` — same GTM container as publica.kg
- **Schema (JSON-LD):** `_includes/schema-organization.html`
- **Styles:** `site.css` is a copy of publica.kg's (keep in sync); marketing-only components live in `mkt.css`
- **Menu, footer, CTA:** `site.js`

## Contact form
Same Web3Forms access key as publica.kg. Each submission includes the site and page the form was sent from,
the visitor's first landing site/page across publica.kg and all *.publica.kg subdomains, the external referrer
and UTM tags (shared `pub_src` cookie, set in `site.js`).
