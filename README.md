# faro-web

Source for **faro.khassinx.com** — the public web property for **Faro**, a private, end-to-end encrypted bridge between a trusted adult and a child living apart.

## What lives here

- `index.html` — landing page (EN)
- `legal/` — Privacy Policy, Terms of Use, Legal index
- `security/` — Security & Responsible Disclosure (with responsible disclosure invitation)
- `support/` — User support + FAQ + data access/deletion
- `es/` — native localized mirror (Spanish)
- `_layouts/` — Jekyll base + prose layouts
- `assets/css/` — Layer 3 primitives (shared) + Layer 2 Faro brand tokens
- `assets/favicons/` — lighthouse monogram favicons (warm rust accent)
- `.well-known/security.txt` — RFC 9116 machine-readable security policy

## Stack

Static site (Jekyll), served over HTTPS at `faro.khassinx.com`.

## Localization

EN default (no prefix), ES under `/es/`. Each locale is **natively written**, not machine-translated. EN is co-primary; ES is neutral pan-Hispanic. Per-page `lang:` front-matter + hreflang tags signal locale to crawlers.

## Contact

- General: [hello@khassinx.com](mailto:hello@khassinx.com)
- Security: [security@khassinx.com](mailto:security@khassinx.com)
