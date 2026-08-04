# PayFast

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

South African payment gateway with REST APIs for online payment processing, subscription billing, QR code payments, and instant EFT bank transfer integration. Trusted by 80,000+ South African businesses and certified PCI-DSS Level 1.

**Developer Portal:** https://developers.payfast.co.za/documentation  
**Website:** https://payfast.io  
**Status:** https://status.payfast.io  
**Pricing:** https://payfast.io/fees  
**GitHub:** https://github.com/Payfast  

## APIs

- **Payments API** — Initiate transactions via 18+ payment methods including credit card, Instant EFT, QR code, Apple Pay, Google Pay, and more.
- **Subscriptions API** — Manage recurring billing subscriptions (fetch, pause, unpause, cancel, update, adhoc charges).
- **Tokenization API** — Store and charge payment tokens for flexible recurring card payments.
- **Transaction History API** — Query merchant transaction records by date range, daily, weekly, or monthly.
- **Credit Card Transactions API** — Fetch individual credit card transaction details by ID.
- **Refunds API** — Create and track customer refunds programmatically.

## Authentication

All API requests require four HTTP headers: `merchant-id`, `version` (v1), `timestamp` (ISO 8601), and `signature` (MD5 hash of sorted parameters + passphrase). A sandbox environment is available at `sandbox.payfast.co.za` with test credentials.

## Pricing

No monthly fees. Transaction fees only:
- Credit/Cheque Card: 3.2% + R2.00
- Instant EFT / Capitec Pay: 2.0% (min R2.00)
- Refunds: R2.00 excl. VAT each
- Payout: R8.70 excl. VAT per disbursement

Volume pricing available for merchants averaging R50,000+/month.
