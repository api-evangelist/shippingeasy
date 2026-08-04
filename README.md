# ShippingEasy (shippingeasy)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ShippingEasy is an Austin, Texas shipping software platform for online merchants, providing multi-carrier label printing with discounted USPS, UPS, FedEx, and DHL rates, automated order import and workflow rules, inventory and product management, branded tracking, customer email marketing, and reporting. ShippingEasy was acquired by Stamps.com in 2016 and is part of the Auctane portfolio of shipping brands, which also includes ShipStation, ShipEngine, ShipWorks, MetaPack, Packlink, and Endicia. The company exposes a public Customer API focused on sending orders into ShippingEasy from custom marketplaces or storefronts not already covered by the built-in integration catalog; for fuller multi-carrier label, rate, and tracking APIs, ShippingEasy directs developers to sister brand ShipEngine.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shippingeasy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shippingeasy/refs/heads/main/apis.yml)

## Tags

- Shipping
- Logistics
- Multi-Carrier
- Labels
- Order Management
- Ecommerce
- Auctane
- Stamps.com

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### ShippingEasy Customer API

The ShippingEasy Customer API is an HMAC-SHA256 signed REST API that lets a merchant push orders into their own ShippingEasy account from a custom marketplace, storefront, or backoffice system that is not already covered by ShippingEasy's built-in integration catalog (Shopify, Amazon, eBay, WooCommerce, BigCommerce, Magento, Etsy, Walmart, Squarespace, etc.). Operations cover listing API-enabled stores, creating an order, looking up orders by ID, external order number, or store, updating order status, and cancelling an order. Credentials (API key, API secret, and per-store API key) are generated inside the ShippingEasy UI at Settings > Account Settings > API Credentials.

- **Human URL:** [https://shippingeasy.readme.io/reference/getting-started](https://shippingeasy.readme.io/reference/getting-started)
- **Base URL:** `https://app.shippingeasy.com/api`

#### Tags

- Orders
- Stores
- Order Management
- Shipping
- Ecommerce

#### Properties

- [Documentation](https://shippingeasy.readme.io/reference/getting-started)
- [API Reference](https://shippingeasy.readme.io/reference/getting-started)
- [Authentication](https://shippingeasy.readme.io/reference/authentication-signing-requests)
- [Rate Limits](https://shippingeasy.readme.io/reference/rate-limits-and-throttling)
- [OpenAPI](openapi/shippingeasy-customer-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shippingeasy-customer-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shippingeasy-customer-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](https://github.com/ShippingEasy/shippingeasy-api-examples) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Signup](https://app.shippingeasy.com/settings/api_credentials)
- [Support](api-questions@shippingeasy.com)

## Common Properties

- [Website](https://shippingeasy.com)
- [Pricing](https://shippingeasy.com/pricing/)
- [Features](https://shippingeasy.com/features/)
- [Integrations](https://shippingeasy.com/integrationpartners/)
- [Shipping A P I](https://shippingeasy.com/shipping-api/)
- [Documentation](https://shippingeasy.readme.io/reference/getting-started)
- [Signup](https://app.shippingeasy.com/customer/new)
- [Login](https://app.shippingeasy.com/login)
- [A P I Credentials](https://app.shippingeasy.com/settings/api_credentials)
- [Support](https://support.shippingeasy.com)
- [Blog](https://shippingeasy.com/blog/)
- [Careers](https://shippingeasy.com/careers/)
- [Parent](https://auctane.com)
- [Sister Brand](https://www.shipengine.com/)
- [GitHub Organization](https://github.com/ShippingEasy)
- [Twitter](https://twitter.com/ShippingEasy)
- [LinkedIn](https://www.linkedin.com/company/shippingeasy)
- [Facebook](https://www.facebook.com/ShippingEasy)
- [YouTube](https://www.youtube.com/user/ShippingEasy)
- [Terms of Service](https://shippingeasy.com/terms-of-service/)
- [Privacy Policy](https://shippingeasy.com/privacy-policy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
