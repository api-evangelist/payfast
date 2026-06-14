# PayFast

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
