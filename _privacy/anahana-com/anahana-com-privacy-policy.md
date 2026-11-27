---
api_specs:
- filename: anahana-com-discovery-api-openapi.yml
  format: yaml
  label: Anahana Discovery API
  slug: anahana-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anahana-com/openapi/anahana-com-discovery-api-openapi.yml
- filename: anahana-com-mcp-api-openapi.yml
  format: yaml
  label: Anahana MCP API
  slug: anahana-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anahana-com/openapi/anahana-com-mcp-api-openapi.yml
- filename: anahana-com-oauth-api-openapi.yml
  format: yaml
  label: Anahana OAuth API
  slug: anahana-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anahana-com/openapi/anahana-com-oauth-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address First name and last name Country / region (when relevant to localization)
  - category: identifying
    text: Birth date, birth time, and birth place (when you purchase a personalized astrology report — this information is required to compute your report)
  - category: device
    text: unique device identifiers
  - category: location
    text: With your permission, we may use and store information about your approximate location.
  - category: behavioral
    text: the pages of our Service that you visit, the time and date of your visit, time spent on those pages
  - category: financial
    text: Stripe (payment processing — we never see or store your card details)
  deletion:
    route: email
    text: To exercise any of these rights, contact us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and maintain the Service
    text: To provide and maintain our Service
  - purpose: analytics to improve the Service
    text: To gather analysis or valuable information to improve our Service
  - purpose: serve advertisements
    text: To serve advertisements and measure their effectiveness
  - purpose: marketing communications
    text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials, and other information that may be of interest to you.
  residency:
  - region: Canada
    text: Anahana Wellness Inc. is based in Canada, and your data is generally processed in Canada and in the United States by our Service Providers.
  retention:
  - period: 26 months
    scope: Usage / analytics data (Google Analytics)
    text: retained for up to 26 months in Google Analytics (default)
  - period: 13 months
    scope: Usage / analytics data (Microsoft Clarity)
    text: up to 13 months in Microsoft Clarity
  - period: 3 years
    scope: Customer support communications
    text: retained for up to 3 years to handle follow-up inquiries
  - period: 6-7 years
    scope: Transaction / payment records
    text: retained as required by Canadian tax and accounting law, typically 6-7 years
  rights:
  - right: access
    text: Right of access (Art. 15) — to request information about whether we hold Personal Data about you and to receive a copy.
  - right: erasure
    text: Right to erasure (“right to be forgotten”, Art. 17) — to request deletion of your Personal Data, subject to certain exceptions.
  - right: rectification
    text: Right to rectification (Art. 16) — to have inaccurate or incomplete data corrected.
  - right: portability
    text: Right to data portability (Art. 20)
  - right: object
    text: Right to object (Art. 21)
  - right: opt out of sale or sharing (California)
    text: Right to opt out of the sale or sharing of personal information.
  role:
    text: 'The data controller responsible for your personal data is: Anahana Wellness Inc.'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Anahana does not sell personal information for monetary consideration.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards, including the European Commission’s Standard Contractual Clauses (SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anahana
provenance_date: '2026-11-09'
provider_name: Anahana
provider_slug: anahana-com
slug: anahana-com-privacy-policy
source_date: '2026-11-09'
source_filename: anahana-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.anahana.com/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anahana\naid: anahana-com\nurl: https://www.anahana.com/en/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller responsible for your personal data is: Anahana Wellness Inc.'\ndata_categories:\n- category: contact\n  text: Email address First name and last name Country / region (when relevant to localization)\n- category: identifying\n  text: Birth date, birth time, and birth place (when you purchase a personalized astrology report — this information\n    is required to compute your report)\n- category: device\n  text: unique device identifiers\n- category: location\n\
  \  text: With your permission, we may use and store information about your approximate location.\n- category: behavioral\n  text: the pages of our Service that you visit, the time and date of your visit, time spent on those pages\n- category: financial\n  text: Stripe (payment processing — we never see or store your card details)\npurposes:\n- purpose: provide and maintain the Service\n  text: To provide and maintain our Service\n- purpose: analytics to improve the Service\n  text: To gather analysis or valuable information to improve our Service\n- purpose: serve advertisements\n  text: To serve advertisements and measure their effectiveness\n- purpose: marketing communications\n  text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials, and other\n    information that may be of interest to you.\nretention:\n- scope: Usage / analytics data (Google Analytics)\n  period: 26 months\n  text: retained for up to 26 months in Google Analytics (default)\n\
  - scope: Usage / analytics data (Microsoft Clarity)\n  period: 13 months\n  text: up to 13 months in Microsoft Clarity\n- scope: Customer support communications\n  period: 3 years\n  text: retained for up to 3 years to handle follow-up inquiries\n- scope: Transaction / payment records\n  period: 6-7 years\n  text: retained as required by Canadian tax and accounting law, typically 6-7 years\nresidency:\n- region: Canada\n  text: Anahana Wellness Inc. is based in Canada, and your data is generally processed in Canada and in the United\n    States by our Service Providers.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards, including the European Commission’s Standard Contractual Clauses (SCCs)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: To exercise any of these rights, contact us at [email protected] .\nrights:\n- right: access\n  text: Right of access (Art. 15) — to request information\
  \ about whether we hold Personal Data about you and to\n    receive a copy.\n- right: erasure\n  text: Right to erasure (“right to be forgotten”, Art. 17) — to request deletion of your Personal Data, subject\n    to certain exceptions.\n- right: rectification\n  text: Right to rectification (Art. 16) — to have inaccurate or incomplete data corrected.\n- right: portability\n  text: Right to data portability (Art. 20)\n- right: object\n  text: Right to object (Art. 21)\n- right: opt out of sale or sharing (California)\n  text: Right to opt out of the sale or sharing of personal information.\nsale_or_sharing:\n  stance: conditional\n  text: Anahana does not sell personal information for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/anahana-com/privacy/anahana-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Anahana's own page on 2026-11-09.
synthetic: false
tags:
- SpiritualWellness
- Personal Growth
- Astrology
- Meditation
- Yoga
---
