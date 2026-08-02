---
name: create-aws-cosell-opportunity
description: Create and track an AWS Partner Central co-sell opportunity through Tackle.
api: Tackle Co-Sell for AWS Partner Central
operations: [listSolutions, createOpportunity, getOpportunity, listOpportunityEvents]
provider: tackleio
generated: '2026-07-21'
method: generated
---

# Create and track an AWS Partner Central co-sell opportunity through Tackle.

## Steps

1. **Authenticate** and set `Authorization: Bearer <token>` (requires the `cosell:*` RBAC permissions).
2. **List solutions** (`listSolutions`): `GET https://aws.cosell.tackle.io/api/solutions` to find the registered co-sell solution to attach.
3. **Create the opportunity** (`createOpportunity`): `POST https://aws.cosell.tackle.io/api/opportunities`. The call is asynchronous — expect `202 Accepted` with the Tackle identifier. A duplicate `crmId` may return `409 Conflict` when one-opportunity-per-CRM-ID is enforced.
4. **Poll the outcome** (`getOpportunity`): `GET /api/opportunities/{opportunity_id}` until the cloud-side state settles.
5. **Audit history** (`listOpportunityEvents`): `GET /api/opportunities/{opportunity_id}/events` to follow AWS responses.

### Conventions
- Set the `tackle-operation-id` header to select sub-operations (updateDraftOpportunity, launchOpportunity, closeLostOpportunity, ...).
- `423 Locked` means a prior cloud operation is in flight — retry after a short delay.
