---
api_specs:
- filename: millimetric-identity-api-openapi.yml
  format: yaml
  label: Millimetric Identity API
  slug: millimetric-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-identity-api-openapi.yml
- filename: millimetric-ingest-api-openapi.yml
  format: yaml
  label: Millimetric Ingest API
  slug: millimetric-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-ingest-api-openapi.yml
- filename: millimetric-read-api-openapi.yml
  format: yaml
  label: Millimetric Read API
  slug: millimetric-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-read-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: email, name, hashed password (or OAuth identifier), team/role.'
  - category: financial
    text: 'Billing data: company name, billing address, last 4 digits of payment card, tax IDs.'
  - category: communication
    text: 'Support data: any content you send us in emails, chat, or bug reports.'
  - category: device
    text: 'Coarse user-agent data: browser family, OS family, device type.'
  - category: location
    text: 'Coarse geographic data: country, region, city (derived from IP at ingestion time).'
  - category: behavioral
    text: Page URL (without query parameters that look like PII), referrer URL, document title.
  deletion:
    route: email privacy@millimetric.ai
    text: To exercise any of these rights, email privacy@millimetric.ai .
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: provide the Service
    text: 'Contract (Art. 6(1)(b)): to provide the Service you signed up for.'
  - purpose: security, abuse prevention, debugging and product improvement
    text: 'Legitimate interests (Art. 6(1)(f)): to secure the Service, prevent abuse, debug issues, and improve our product.'
  - purpose: legal compliance
    text: 'Legal obligation (Art. 6(1)(c)): to comply with tax, accounting and audit requirements.'
  residency:
  - region: EU
    text: Long-term event storage is in an EU region by default; US-region storage is available on request.
  retention:
  - period: lifetime of the account, deleted within 30 days of account closure
    scope: Account data
    text: 'Account data: kept for the lifetime of the account, deleted within 30 days of account closure.'
  - period: 7–10 years
    scope: Billing data
    text: 'Billing data: kept for the period required by tax law (typically 7–10 years).'
  - period: 30, 90, or 365 days
    scope: Event data
    text: 'Event data: kept for the retention window of your plan (30, 90, or 365 days).'
  - period: 30 days
    scope: Server logs
    text: 'Server logs: 30 days.'
  rights:
  - right: access
    text: Access the personal data we hold about you.
  - right: correct
    text: Correct inaccurate personal data.
  - right: delete
    text: Delete your personal data ("right to erasure").
  - right: restrict or object
    text: Restrict or object to certain processing.
  - right: portability
    text: Receive your data in a portable format.
  - right: withdraw consent
    text: Withdraw consent where consent was the legal basis.
  role:
    text: For analytics data we collect about Visitors on our customers' sites and apps, Millimetric acts as a data processor (or "service provider" under CCPA) on behalf of the customer.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information.
  subprocessors:
    text: The current list lives at millimetric.ai/legal/subprocessors and we will notify customers of changes at least 30 days in advance.
    url: https://millimetric.ai/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: Transfers from the EU or UK to the US are protected by the Standard Contractual Clauses (and UK Addendum)
  - mechanism: DPF
    text: and the EU-US Data Privacy Framework where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Millimetric
provenance_date: '2026-11-10'
provider_name: Millimetric
provider_slug: millimetric
slug: millimetric-privacy-policy
source_date: '2026-11-10'
source_filename: millimetric-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.millimetric.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Millimetric\naid: millimetric\nurl: https://www.millimetric.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For analytics data we collect about Visitors on our customers' sites and apps, Millimetric acts as a data\n    processor (or \"service provider\" under CCPA) on behalf of the customer.\ndata_categories:\n- category: contact\n  text: 'Account data: email, name, hashed password (or OAuth identifier), team/role.'\n- category: financial\n  text: 'Billing data: company name, billing address, last 4 digits of payment card, tax IDs.'\n- category: communication\n  text: 'Support data:\
  \ any content you send us in emails, chat, or bug reports.'\n- category: device\n  text: 'Coarse user-agent data: browser family, OS family, device type.'\n- category: location\n  text: 'Coarse geographic data: country, region, city (derived from IP at ingestion time).'\n- category: behavioral\n  text: Page URL (without query parameters that look like PII), referrer URL, document title.\npurposes:\n- purpose: provide the Service\n  text: 'Contract (Art. 6(1)(b)): to provide the Service you signed up for.'\n- purpose: security, abuse prevention, debugging and product improvement\n  text: 'Legitimate interests (Art. 6(1)(f)): to secure the Service, prevent abuse, debug issues, and improve our\n    product.'\n- purpose: legal compliance\n  text: 'Legal obligation (Art. 6(1)(c)): to comply with tax, accounting and audit requirements.'\nretention:\n- scope: Account data\n  period: lifetime of the account, deleted within 30 days of account closure\n  text: 'Account data: kept for the lifetime\
  \ of the account, deleted within 30 days of account closure.'\n- scope: Billing data\n  period: 7–10 years\n  text: 'Billing data: kept for the period required by tax law (typically 7–10 years).'\n- scope: Event data\n  period: 30, 90, or 365 days\n  text: 'Event data: kept for the retention window of your plan (30, 90, or 365 days).'\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs: 30 days.'\nresidency:\n- region: EU\n  text: Long-term event storage is in an EU region by default; US-region storage is available on request.\ntransfers:\n- mechanism: SCC\n  text: Transfers from the EU or UK to the US are protected by the Standard Contractual Clauses (and UK Addendum)\n- mechanism: DPF\n  text: and the EU-US Data Privacy Framework where applicable.\nsubprocessors:\n  url: https://millimetric.ai/legal/subprocessors\n  text: The current list lives at millimetric.ai/legal/subprocessors and we will notify customers of changes at\n    least 30 days in advance.\ndpa:\n  available:\
  \ true\n  url: null\n  text: Data Processing Agreement\ndeletion:\n  route: email privacy@millimetric.ai\n  text: To exercise any of these rights, email privacy@millimetric.ai .\nrights:\n- right: access\n  text: Access the personal data we hold about you.\n- right: correct\n  text: Correct inaccurate personal data.\n- right: delete\n  text: Delete your personal data (\"right to erasure\").\n- right: restrict or object\n  text: Restrict or object to certain processing.\n- right: portability\n  text: Receive your data in a portable format.\n- right: withdraw consent\n  text: Withdraw consent where consent was the legal basis.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information.\n"
source_yaml_url: https://artifacts.apis.io/millimetric/privacy/millimetric-privacy-policy.yml
stated_fields:
- role
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
summary_line: 27 quoted statements, read from Millimetric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Web Analytics
- Product Analytics
- Attribution
- Privacy
- MCP
- AI Agents
- Event
- Developer Tools
---
