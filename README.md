# LexSpot

LexSpot is a company surfaced as a portfolio company of 500 Global and added to the API Evangelist network as a stub awaiting enrichment.

An enrichment pass on 2026-07-19 could not verify any public product, developer, or API surface for this company. It remains an **unverified lead**.

## Verification notes (2026-07-19)

- **Corrected website.** The profile previously recorded `https://bridge.legal`. That domain now redirects to `https://www.boundless.com/` (Boundless Immigration), an unrelated company whose site makes no reference to LexSpot or Bridge Legal. The pointer has been corrected to the company's own domain.
- **lexspot.com is registered but not serving.** Created 2011-10-16, Cloudflare registrar and DNS. The apex has no `A` record; `www.lexspot.com` resolves to Cloudflare but returns **HTTP 530 (error 1016, origin DNS failure)** — there is no reachable web origin.
- **Mail is live.** Google Workspace `MX` records and an `SPF` record (`_spf.google.com`, `spf.mtasv.net`, `mailgun.org`) are published, so the domain is still held and configured.
- **No developer surface found.** `/.well-known/security.txt`, `/.well-known/openid-configuration`, `/.well-known/oauth-authorization-server`, `/.well-known/api-catalog`, `/.well-known/ai-plugin.json`, and `/llms.txt` were all unreachable. No package on npm or PyPI, no `lexspot` GitHub organization, and no matching repositories in GitHub search.

## Artifacts

- `security/lexspot-domain-security.yml` — probed TLS/DNS posture (`type: DomainSecurity`).

No API, specification, or documentation artifacts have been generated: there is no published specification or documentation to ground them in, and nothing has been fabricated.

Backed by: 500 Global
