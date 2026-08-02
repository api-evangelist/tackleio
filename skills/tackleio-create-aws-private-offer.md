---
name: create-aws-private-offer
description: Assemble and publish an AWS Marketplace private offer via Tackle Offers.
api: Tackle Offers for AWS Marketplace
operations: [listProducts, getProductPricing, listAllowedCurrencies, createPrivateOffer, marketplaceCreatePrivateOffer, getPrivateOffer]
provider: tackleio
generated: '2026-07-21'
method: generated
---

# Assemble and publish an AWS Marketplace private offer via Tackle Offers.

## Steps

1. **Authenticate** and set `Authorization: Bearer <token>` (requires `offers:*` RBAC permissions).
2. **Pick a product** (`listProducts`): `GET https://aws.offers.tackle.io/api/products`. Use `encrypted_productid` (not `productid`) for pricing lookups.
3. **Fetch pricing** (`getProductPricing`): `GET /products/{productId}/pricing` and **allowed currencies** (`listAllowedCurrencies`): `GET /allowed-currencies`.
4. **Create the offer** (`createPrivateOffer`): `POST /private-offers`. Set `dry_run:true` to validate without persisting (returns `200`), or `create_in_marketplace:true` to publish in the same call.
5. **Push a draft to AWS Marketplace** (`marketplaceCreatePrivateOffer`): `POST /private-offers/{id}/marketplace-create` (asynchronous).
6. **Confirm** (`getPrivateOffer`): `GET /private-offers/{id}` and watch `status` / `activities`, or subscribe to Private Offer webhooks.

### Conventions
- Errors are custom JSON (`Error`), not RFC 9457.
- Marketplace pushes are asynchronous; do not assume completion from the initial response.
