---
name: score-buyer-domains
description: Score a batch of domains for cloud-marketplace buyer-signal propensity and search the scored results.
api: Tackle Prospect API
operations: [scoreDomains, searchScoredDomains]
provider: tackleio
generated: '2026-07-21'
method: generated
---

# Score a batch of domains for cloud-marketplace buyer-signal propensity and search the scored results.

## Steps

1. **Authenticate.** `POST https://api.tackle.io/v1/authenticate` with `client_id`, `client_secret`, `grant_type=client_credentials`. Use the returned `access_token` as `Authorization: Bearer <token>` (valid ~90 min).
2. **Score domains** (`scoreDomains`): `POST https://prospect.tackle.io/api/scores` with a batch of domains. Each result includes a `ScoreResult` and `ScoreBin` indicating buyer-signal propensity per `CloudMarketplace`.
3. **Search scored domains** (`searchScoredDomains`): `POST https://prospect.tackle.io/api/scores/search`. Paginate with `page_number` and `records_per_page`; for large result sets, pass `metadata.search_after` from one response as the next request's `search_after`.

### Conventions
- Errors are custom JSON (`MessageError` / `SearchError`), not RFC 9457.
- 401 means the token is missing/expired; re-authenticate.
