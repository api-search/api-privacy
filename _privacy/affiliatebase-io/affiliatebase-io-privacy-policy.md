---
api_specs:
- filename: affiliatebase-io-affiliate-coupons-api-openapi.yml
  format: yaml
  label: AffiliateBase Affiliate Coupons API
  slug: affiliatebase-io-affiliate-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-affiliate-coupons-api-openapi.yml
- filename: affiliatebase-io-affiliates-api-openapi.yml
  format: yaml
  label: AffiliateBase Affiliates API
  slug: affiliatebase-io-affiliates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-affiliates-api-openapi.yml
- filename: affiliatebase-io-api-keys-api-openapi.yml
  format: yaml
  label: AffiliateBase API Keys API
  slug: affiliatebase-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-api-keys-api-openapi.yml
- filename: affiliatebase-io-campaigns-api-openapi.yml
  format: yaml
  label: AffiliateBase Campaigns API
  slug: affiliatebase-io-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-campaigns-api-openapi.yml
- filename: affiliatebase-io-commissions-api-openapi.yml
  format: yaml
  label: AffiliateBase Commissions API
  slug: affiliatebase-io-commissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-commissions-api-openapi.yml
- filename: affiliatebase-io-invitations-api-openapi.yml
  format: yaml
  label: AffiliateBase Invitations API
  slug: affiliatebase-io-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-invitations-api-openapi.yml
- filename: affiliatebase-io-links-api-openapi.yml
  format: yaml
  label: AffiliateBase Links API
  slug: affiliatebase-io-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-links-api-openapi.yml
- filename: affiliatebase-io-payout-exports-api-openapi.yml
  format: yaml
  label: AffiliateBase Payout Exports API
  slug: affiliatebase-io-payout-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-payout-exports-api-openapi.yml
- filename: affiliatebase-io-payout-runs-api-openapi.yml
  format: yaml
  label: AffiliateBase Payout Runs API
  slug: affiliatebase-io-payout-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-payout-runs-api-openapi.yml
- filename: affiliatebase-io-payouts-api-openapi.yml
  format: yaml
  label: AffiliateBase Payouts API
  slug: affiliatebase-io-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-payouts-api-openapi.yml
- filename: affiliatebase-io-referrals-api-openapi.yml
  format: yaml
  label: AffiliateBase Referrals API
  slug: affiliatebase-io-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affiliatebase-io/openapi/affiliatebase-io-referrals-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: financial
    text: Payment information (PayPal email, Wise email, or payout references)
  - category: device
    text: Browser type, operating system, device type (desktop/mobile/tablet)
  - category: location
    text: IP address
  - category: behavioral
    text: Referring URL, page URL, page title
  - category: communication
    text: Recipient names and email addresses, email content, delivery and bounce status, and the content of replies you send us
  deletion:
    route: Owners can delete an account from Settings while it has no affiliate program, billing, or Stripe event records; otherwise contact us
    text: Owners can delete an account from Settings while it has no affiliate program, billing, or Stripe event records
  dpa:
    available: true
    text: standard contractual clauses, which are included in our data processing addendum, available on request at support@affiliatebase.io
    url: null
  purposes:
  - purpose: Provide the Service
    text: Track referrals, calculate commissions, and manage payout records
  - purpose: Fraud prevention
    text: Detect suspicious patterns, self-referrals, and invalid clicks
  - purpose: Communication
    text: Send transactional emails (commission notifications, payout confirmations, invitation emails)
  - purpose: Improvement
    text: Analyze usage patterns to improve our service
  - purpose: Legal compliance
    text: Meet regulatory requirements and enforce our terms
  residency:
  - region: United States
    text: We are based in the United States and process your information there.
  retention:
  - period: 180 days
    scope: Visit logs
    text: Each tracked visit (with IP address, browser details, and pages) is deleted after 180 days.
  - period: up to 7 years
    scope: Sales, commission and payout records
    text: When an account with these records is deleted, we keep what we need for tax and legal compliance for up to 7 years
  - period: 30 days
    scope: Backups
    text: Deleted data can remain in our private database backups for up to 30 days
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Correction
    text: 'Correction: Update or correct inaccurate information'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data'
  - right: Portability
    text: 'Portability: Receive your data in a portable format'
  - right: Objection
    text: 'Objection: Object to certain processing activities'
  - right: Withdrawal
    text: 'Withdrawal: Withdraw consent where processing is based on consent'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: A current list of our service providers is available on request at support@affiliatebase.io .
    url: null
  transfers:
  - mechanism: SCC
    text: Where the law requires a transfer mechanism for data from the EU, UK or Switzerland, we rely on standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AffiliateBase
provenance_date: '2026-11-09'
provider_name: AffiliateBase
provider_slug: affiliatebase-io
slug: affiliatebase-io-privacy-policy
source_date: '2026-11-09'
source_filename: affiliatebase-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.affiliatebase.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AffiliateBase\naid: affiliatebase-io\nurl: https://www.affiliatebase.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: Payment information (PayPal email, Wise email, or payout references)\n- category: device\n  text: Browser type, operating system, device type (desktop/mobile/tablet)\n- category: location\n  text: IP address\n- category: behavioral\n  text: Referring URL, page URL, page title\n- category: communication\n  text: Recipient names and email addresses, email content, delivery and bounce status, and the content of replies\n\
  \    you send us\npurposes:\n- purpose: Provide the Service\n  text: Track referrals, calculate commissions, and manage payout records\n- purpose: Fraud prevention\n  text: Detect suspicious patterns, self-referrals, and invalid clicks\n- purpose: Communication\n  text: Send transactional emails (commission notifications, payout confirmations, invitation emails)\n- purpose: Improvement\n  text: Analyze usage patterns to improve our service\n- purpose: Legal compliance\n  text: Meet regulatory requirements and enforce our terms\nretention:\n- scope: Visit logs\n  period: 180 days\n  text: Each tracked visit (with IP address, browser details, and pages) is deleted after 180 days.\n- scope: Sales, commission and payout records\n  period: up to 7 years\n  text: When an account with these records is deleted, we keep what we need for tax and legal compliance for up\n    to 7 years\n- scope: Backups\n  period: 30 days\n  text: Deleted data can remain in our private database backups for up to\
  \ 30 days\nresidency:\n- region: United States\n  text: We are based in the United States and process your information there.\ntransfers:\n- mechanism: SCC\n  text: Where the law requires a transfer mechanism for data from the EU, UK or Switzerland, we rely on standard\n    contractual clauses\nsubprocessors:\n  url: null\n  text: A current list of our service providers is available on request at support@affiliatebase.io .\ndpa:\n  available: true\n  url: null\n  text: standard contractual clauses, which are included in our data processing addendum, available on request at\n    support@affiliatebase.io\ndeletion:\n  route: Owners can delete an account from Settings while it has no affiliate program, billing, or Stripe event\n    records; otherwise contact us\n  text: Owners can delete an account from Settings while it has no affiliate program, billing, or Stripe event records\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Correction\n  text:\
  \ 'Correction: Update or correct inaccurate information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data'\n- right: Portability\n  text: 'Portability: Receive your data in a portable format'\n- right: Objection\n  text: 'Objection: Object to certain processing activities'\n- right: Withdrawal\n  text: 'Withdrawal: Withdraw consent where processing is based on consent'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/affiliatebase-io/privacy/affiliatebase-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from AffiliateBase's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Affiliate Marketing
- Stripe
- Payments
- Marketing Automation
---
