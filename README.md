# Kosmix

Kosmix Corporation was a Mountain View, California topic-discovery and search company operating from roughly 2005 to 2011. Instead of returning a ranked list of links, Kosmix automatically assembled a topic "home page for the web" for any subject, aggregating and categorizing content across health, science, food, sports, politics, travel and finance. It also shipped the RightHealth, MeeHive and Tweetbeat properties, the last of which filtered and organized real-time Twitter activity by topic.

**Status: defunct.** Kosmix was acquired by Walmart in 2011 and became the nucleus of @WalmartLabs.

Backed by: lightspeed-venture-partners

## Enrichment verdict: no live surface

The API Evangelist enrichment pipeline ran against this repo on 2026-07-19 and found nothing to enrich. No artifacts were generated, because none can be sourced without fabrication:

- `kosmix.com` has no A/AAAA record; HTTPS is unreachable.
- The domain's DNS is administered by Walmart — SOA RNAME `domainadmin.walmartlabs.com`, `_dmarc.kosmix.com` CNAMEs to `_dmarc-r.walmart.com`, SPF is `v=spf1 -all` (no mail), and CAA restricts issuance to `globalsign.com`.
- Registered via MarkMonitor with registry expiry 2027-05-26 — held defensively, not operated.
- `http://kosmix.com/about` returned a 301 to `http://www.walmartlabs.com/` (Internet Archive, 2012-09-11).
- The archived homepage (Internet Archive, 2010-12-31) self-describes as "Kosmix: The web organized for you" and carries a "2007-2010 Kosmix™ Corporation" copyright.

Note that `kosmix.ai` is an unrelated growth-equity firm (Kosmix Partners) and is **not** this company. `kosmix.io`, `kosmix.dev`, `kosmix.co` and `getkosmix.com` do not resolve or do not serve.

Future re-runs should skip this repo unless the identity is reassigned to a different, live company.
