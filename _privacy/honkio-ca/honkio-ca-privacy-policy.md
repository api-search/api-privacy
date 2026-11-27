---
api_specs:
- filename: honkio-ca-accounts-api-openapi.yml
  format: yaml
  label: honkio-ca Accounts API
  slug: honkio-ca-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-accounts-api-openapi.yml
- filename: honkio-ca-auth-api-openapi.yml
  format: yaml
  label: honkio-ca Auth API
  slug: honkio-ca-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-auth-api-openapi.yml
- filename: honkio-ca-compliance-casl-api-openapi.yml
  format: yaml
  label: honkio-ca Compliance / CASL API
  slug: honkio-ca-compliance-casl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-compliance-casl-api-openapi.yml
- filename: honkio-ca-compliance-dncl-api-openapi.yml
  format: yaml
  label: honkio-ca Compliance / DNCL API
  slug: honkio-ca-compliance-dncl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-compliance-dncl-api-openapi.yml
- filename: honkio-ca-compliance-pipeda-api-openapi.yml
  format: yaml
  label: honkio-ca Compliance / PIPEDA API
  slug: honkio-ca-compliance-pipeda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-compliance-pipeda-api-openapi.yml
- filename: honkio-ca-contact-groups-api-openapi.yml
  format: yaml
  label: honkio-ca Contact Groups API
  slug: honkio-ca-contact-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-contact-groups-api-openapi.yml
- filename: honkio-ca-contacts-api-openapi.yml
  format: yaml
  label: honkio-ca Contacts API
  slug: honkio-ca-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-contacts-api-openapi.yml
- filename: honkio-ca-email-domains-api-openapi.yml
  format: yaml
  label: honkio-ca Email Domains API
  slug: honkio-ca-email-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-email-domains-api-openapi.yml
- filename: honkio-ca-email-suppressions-api-openapi.yml
  format: yaml
  label: honkio-ca Email Suppressions API
  slug: honkio-ca-email-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-email-suppressions-api-openapi.yml
- filename: honkio-ca-email-templates-api-openapi.yml
  format: yaml
  label: honkio-ca Email Templates API
  slug: honkio-ca-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-email-templates-api-openapi.yml
- filename: honkio-ca-emails-api-openapi.yml
  format: yaml
  label: honkio-ca Emails API
  slug: honkio-ca-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-emails-api-openapi.yml
- filename: honkio-ca-lists-api-openapi.yml
  format: yaml
  label: honkio-ca Lists API
  slug: honkio-ca-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-lists-api-openapi.yml
- filename: honkio-ca-messages-api-openapi.yml
  format: yaml
  label: honkio-ca Messages API
  slug: honkio-ca-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-messages-api-openapi.yml
- filename: honkio-ca-oauth-api-openapi.yml
  format: yaml
  label: honkio-ca OAuth API
  slug: honkio-ca-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-oauth-api-openapi.yml
- filename: honkio-ca-phone-numbers-api-openapi.yml
  format: yaml
  label: honkio-ca Phone Numbers API
  slug: honkio-ca-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-phone-numbers-api-openapi.yml
- filename: honkio-ca-pricing-api-openapi.yml
  format: yaml
  label: honkio-ca Pricing API
  slug: honkio-ca-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-pricing-api-openapi.yml
- filename: honkio-ca-verify-api-openapi.yml
  format: yaml
  label: honkio-ca Verify API
  slug: honkio-ca-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-verify-api-openapi.yml
- filename: honkio-ca-webhooks-api-openapi.yml
  format: yaml
  label: honkio-ca Webhooks API
  slug: honkio-ca-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/honkio-ca/openapi/honkio-ca-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email address, billing information, and API credentials when you create an account.
  - category: communication
    text: 'Message data: Phone numbers (sender and recipient), message content, delivery timestamps, and status information when you send SMS messages through our API.'
  - category: financial
    text: Billing information is handled directly by Stripe.
  - category: location
    text: an approximate place derived from the IP address (country, region and city)
  - category: device
    text: a device identifier from a cookie set on the sign-in page
  - category: other
    text: 'Usage data: API call logs, rate limit events, and billing ledger entries for operational and compliance purposes.'
  deletion:
    route: DELETE /v1/compliance/erasure API endpoint or email privacy@honkio.ca
    text: Request deletion of personal information via DELETE /v1/compliance/erasure API endpoint or by emailing privacy@honkio.ca
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: SMS gateway service
    text: Providing and operating the SMS gateway service
  - purpose: Billing
    text: Processing billing and managing account credits
  - purpose: Fraud and abuse prevention
    text: Detecting and preventing fraud and abuse
  - purpose: Push notification delivery
    text: Delivering push notifications to our customers’ apps through Apple and Google
  - purpose: HonkIO Auth sign-in
    text: Providing HonkIO Auth hosted sign-in on our customers’ behalf
  residency:
  - region: Canada
    text: All personal information HonkIO holds is stored in Canada.
  retention:
  - period: 90 days
    scope: Message content
    text: Message content is retained for 90 days by default.
  - period: 3 years
    scope: Message metadata
    text: Message metadata (sender, recipient, timestamps, status) is retained for 3 years for billing and compliance purposes.
  - period: 90 days
    scope: HonkIO Auth sign-in history IP addresses and risk scores
    text: the IP addresses, networks, approximate places and risk scores in sign-in history are kept for 90 days
  - period: life of the account plus 12 months
    scope: Account data
    text: Account data is retained for the life of the account plus 12 months after account closure.
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correction
    text: Correct inaccurate personal information
  - right: Withdraw consent
    text: Withdraw consent to processing (subject to legal and contractual restrictions)
  - right: Erasure
    text: Request deletion of personal information via DELETE /v1/compliance/erasure API endpoint or by emailing privacy@honkio.ca
  - right: Portability
    text: 'Data portability: Receive a copy of your data in machine-readable format'
  - right: Complaint
    text: Lodge a complaint with the Office of the Privacy Commissioner of Canada (OPC) at priv.gc.ca
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: 'We share limited data with the following Canadian-compliant processors:'
    url: null
  transfers:
  - mechanism: other
    text: they store it on their systems, outside Canada, until it is delivered or expires.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: honkio-ca
provenance_date: '2026-11-09'
provider_name: honkio-ca
provider_slug: honkio-ca
slug: honkio-ca-privacy-policy
source_date: '2026-11-09'
source_filename: honkio-ca-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://honkio.ca/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: honkio-ca\naid: honkio-ca\nurl: https://honkio.ca/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, email address, billing information, and API credentials when you create an account.\n- category: communication\n  text: 'Message data: Phone numbers (sender and recipient), message content, delivery timestamps, and status information\n    when you send SMS messages through our API.'\n- category: financial\n  text: Billing information is handled directly by Stripe.\n- category: location\n  text: an approximate place derived from\
  \ the IP address (country, region and city)\n- category: device\n  text: a device identifier from a cookie set on the sign-in page\n- category: other\n  text: 'Usage data: API call logs, rate limit events, and billing ledger entries for operational and compliance\n    purposes.'\npurposes:\n- purpose: SMS gateway service\n  text: Providing and operating the SMS gateway service\n- purpose: Billing\n  text: Processing billing and managing account credits\n- purpose: Fraud and abuse prevention\n  text: Detecting and preventing fraud and abuse\n- purpose: Push notification delivery\n  text: Delivering push notifications to our customers’ apps through Apple and Google\n- purpose: HonkIO Auth sign-in\n  text: Providing HonkIO Auth hosted sign-in on our customers’ behalf\nretention:\n- scope: Message content\n  period: 90 days\n  text: Message content is retained for 90 days by default.\n- scope: Message metadata\n  period: 3 years\n  text: Message metadata (sender, recipient, timestamps, status)\
  \ is retained for 3 years for billing and compliance\n    purposes.\n- scope: HonkIO Auth sign-in history IP addresses and risk scores\n  period: 90 days\n  text: the IP addresses, networks, approximate places and risk scores in sign-in history are kept for 90 days\n- scope: Account data\n  period: life of the account plus 12 months\n  text: Account data is retained for the life of the account plus 12 months after account closure.\nresidency:\n- region: Canada\n  text: All personal information HonkIO holds is stored in Canada.\ntransfers:\n- mechanism: other\n  text: they store it on their systems, outside Canada, until it is delivered or expires.\nsubprocessors:\n  url: null\n  text: 'We share limited data with the following Canadian-compliant processors:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DELETE /v1/compliance/erasure API endpoint or email privacy@honkio.ca\n  text: Request deletion of personal information via DELETE /v1/compliance/erasure API endpoint\
  \ or by emailing privacy@honkio.ca\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correction\n  text: Correct inaccurate personal information\n- right: Withdraw consent\n  text: Withdraw consent to processing (subject to legal and contractual restrictions)\n- right: Erasure\n  text: Request deletion of personal information via DELETE /v1/compliance/erasure API endpoint or by emailing privacy@honkio.ca\n- right: Portability\n  text: 'Data portability: Receive a copy of your data in machine-readable format'\n- right: Complaint\n  text: Lodge a complaint with the Office of the Privacy Commissioner of Canada (OPC) at priv.gc.ca\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/honkio-ca/privacy/honkio-ca-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from honkio-ca's own page on 2026-11-09.
synthetic: false
tags:
- SMS
- Email
- Canada
- CASL
- PIPEDA
- Company
---
