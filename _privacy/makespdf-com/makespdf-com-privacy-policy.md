---
api_specs:
- filename: makespdf-com-artifacts-api-openapi.yml
  format: yaml
  label: makespdf-com Artifacts API
  slug: makespdf-com-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-artifacts-api-openapi.yml
- filename: makespdf-com-public-api-openapi.yml
  format: yaml
  label: makespdf-com Public API
  slug: makespdf-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-public-api-openapi.yml
- filename: makespdf-com-render-api-openapi.yml
  format: yaml
  label: makespdf-com Render API
  slug: makespdf-com-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-render-api-openapi.yml
- filename: makespdf-com-validate-api-openapi.yml
  format: yaml
  label: makespdf-com Validate API
  slug: makespdf-com-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-validate-api-openapi.yml
- filename: makespdf-com-x402-api-openapi.yml
  format: yaml
  label: makespdf-com X402 API
  slug: makespdf-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/makespdf-com/openapi/makespdf-com-x402-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register, we store your email address, a hashed password (we never see or store your plaintext password), and optionally your name.
  - category: financial
    text: We receive and store a Stripe customer identifier, subscription status, plan tier, the last four digits and brand of your saved payment method (for auto top-up display), and invoice history references.
  - category: behavioral
    text: 'we record: API key usage (key prefix only — full keys are hashed), endpoint, timestamp, response status, payload size, and number of pages rendered.'
  - category: device
    text: standard web-server metadata (IP address, user agent) for security and abuse prevention
  - category: communication
    text: we store the message you wrote so we can act on it, along with the account it came from if you were signed in
  - category: location
    text: your country
  deletion:
    route: Delete your account from your account settings; or email jason@makespdf.com
    text: You can delete your account from your account settings. For other requests, contact us at jason@makespdf.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: account data, billing data, and content you submit are processed to provide the Service you have signed up for.
  - purpose: Security and abuse prevention
    text: 'Legitimate interests: operational logs, security monitoring, and abuse prevention, balanced against your privacy.'
  - purpose: Product analytics
    text: PostHog Inc. — product analytics (anonymous page views and UI events) so we can understand which features are used and where people get stuck.
  - purpose: Improve the product
    text: Feedback text is used to improve the product
  residency:
  - region: EU (PostHog analytics)
    text: Data is processed in the EU region.
  - region: Global (Cloudflare)
    text: Data is processed in Cloudflare's global network.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: 'Account data: retained for as long as your account is active.'
  - period: within 30 days
    scope: Account data backups
    text: account data and associated content are removed from our primary systems promptly and from backups within 30 days.
  - period: minutes
    scope: Content you submit
    text: A short-lived cache of rendered PDFs may exist (typically measured in minutes) to allow retry of failed downloads
  - period: null
    scope: Feedback
    text: 'Feedback you send: stored until we delete it — feedback is not on an automatic expiry schedule.'
  - period: up to 13 months
    scope: Usage and billing records
    text: 'Usage and billing records: retained for up to 13 months for billing, dispute resolution, and security'
  - period: up to 90 days
    scope: Security logs
    text: 'Security logs: retained for up to 90 days unless needed longer to investigate an incident.'
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your account and associated data ("right to be forgotten")
  - right: Export
    text: Export your data in a portable format
  - right: Object or restrict
    text: Object to or restrict certain processing
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: Complain
    text: Lodge a complaint with your local data-protection authority
  role:
    text: The data controller for personal data processed via the Service is Eight Degrees Off Center, a business registered in Queensland, Australia.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it with advertisers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses
  - mechanism: adequacy
    text: where applicable, adequacy decisions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: makespdf-com
provenance_date: '2026-11-10'
provider_name: makespdf-com
provider_slug: makespdf-com
slug: makespdf-com-privacy-policy
source_date: '2026-11-10'
source_filename: makespdf-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://makespdf.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: makespdf-com\naid: makespdf-com\nurl: https://makespdf.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for personal data processed via the Service is Eight Degrees Off Center, a business\n    registered in Queensland, Australia.\ndata_categories:\n- category: identifying\n  text: When you register, we store your email address, a hashed password (we never see or store your plaintext\n    password), and optionally your name.\n- category: financial\n  text: We receive and store a Stripe customer identifier, subscription status, plan tier, the last four digits\n\
  \    and brand of your saved payment method (for auto top-up display), and invoice history references.\n- category: behavioral\n  text: 'we record: API key usage (key prefix only — full keys are hashed), endpoint, timestamp, response status,\n    payload size, and number of pages rendered.'\n- category: device\n  text: standard web-server metadata (IP address, user agent) for security and abuse prevention\n- category: communication\n  text: we store the message you wrote so we can act on it, along with the account it came from if you were signed\n    in\n- category: location\n  text: your country\npurposes:\n- purpose: Provide the Service\n  text: account data, billing data, and content you submit are processed to provide the Service you have signed\n    up for.\n- purpose: Security and abuse prevention\n  text: 'Legitimate interests: operational logs, security monitoring, and abuse prevention, balanced against your\n    privacy.'\n- purpose: Product analytics\n  text: PostHog Inc. — product\
  \ analytics (anonymous page views and UI events) so we can understand which features\n    are used and where people get stuck.\n- purpose: Improve the product\n  text: Feedback text is used to improve the product\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: 'Account data: retained for as long as your account is active.'\n- scope: Account data backups\n  period: within 30 days\n  text: account data and associated content are removed from our primary systems promptly and from backups within\n    30 days.\n- scope: Content you submit\n  period: minutes\n  text: A short-lived cache of rendered PDFs may exist (typically measured in minutes) to allow retry of failed\n    downloads\n- scope: Feedback\n  period: null\n  text: 'Feedback you send: stored until we delete it — feedback is not on an automatic expiry schedule.'\n- scope: Usage and billing records\n  period: up to 13 months\n  text: 'Usage and billing records: retained for up to 13 months for\
  \ billing, dispute resolution, and security'\n- scope: Security logs\n  period: up to 90 days\n  text: 'Security logs: retained for up to 90 days unless needed longer to investigate an incident.'\nresidency:\n- region: EU (PostHog analytics)\n  text: Data is processed in the EU region.\n- region: Global (Cloudflare)\n  text: Data is processed in Cloudflare's global network.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses\n- mechanism: adequacy\n  text: where applicable, adequacy decisions\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account from your account settings; or email jason@makespdf.com\n  text: You can delete your account from your account settings. For other requests, contact us at jason@makespdf.com\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your account and\
  \ associated data (\"right to be forgotten\")\n- right: Export\n  text: Export your data in a portable format\n- right: Object or restrict\n  text: Object to or restrict certain processing\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent\n- right: Complain\n  text: Lodge a complaint with your local data-protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/makespdf-com/privacy/makespdf-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from makespdf-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Conversion
- Developers
---
