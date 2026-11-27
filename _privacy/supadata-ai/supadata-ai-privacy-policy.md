---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, password (hashed), organisation, sign-in provider profile, two-factor secrets
  - category: financial
    text: Billing name and address, VAT ID, invoices, payment method (held by Stripe)
  - category: device
    text: IP address, browser and device data, pages visited
  - category: behavioral
    text: Analytics events and identifiers from consent-based tools (section 3)
  - category: communication
    text: Support messages and feedback
  - category: location
    text: 'Playground: URL you enter, result, IP address, bot-protection signals'
  deletion:
    route: dashboard
    text: You can delete your account yourself in the dashboard.
  dpa:
    available: true
    text: we act as their processor under our Data Processing Agreement
    url: null
  purposes:
  - purpose: Running the website securely, preventing abuse
    text: Running the website securely, preventing abuse
  - purpose: Creating and securing your account, communicating with you
    text: Creating and securing your account, communicating with you
  - purpose: Providing the API, billing, security
    text: Providing the API, billing, security
  - purpose: Charging, invoicing, tax compliance
    text: Charging, invoicing, tax compliance
  - purpose: Understanding usage, testing page variants
    text: Understanding usage, testing page variants
  residency:
  - region: United States
    text: Data is processed in the United States.
  retention:
  - period: 30 days
    scope: Server logs
    text: Server logs 30 days
  - period: 10 years (German tax law)
    scope: Billing records
    text: 10 years (German tax law)
  - period: Until you delete your account
    scope: Account data
    text: Until you delete your account
  - period: 2 years after last contact
    scope: Support messages
    text: 2 years after last contact
  - period: For the duration of your customer relationship
    scope: API keys and usage data
    text: For the duration of your customer relationship
  - period: 1 hour (single jobs) or 24 hours (batch jobs)
    scope: API job results
    text: Job results can be retrieved for 1 hour (single jobs) or 24 hours (batch jobs) and are then deleted.
  rights:
  - right: access, rectify, erase, restrict, object, portability, withdraw consent
    text: You have the right to access, rectify and erase your personal data, to restrict or object to its processing, to receive it in a portable format, and to withdraw consent at any time.
  role:
    text: We are the controller for this processing.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: They are listed with purpose and location at supadata.ai/legal/sub-processors
    url: https://supadata.ai/legal/sub-processors
  transfers:
  - mechanism: DPF
    text: we rely on the EU-US Data Privacy Framework where the provider is certified
  - mechanism: SCC
    text: otherwise on the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: supadata-ai
provenance_date: '2026-11-10'
provider_name: supadata-ai
provider_slug: supadata-ai
slug: supadata-ai-privacy-policy
source_date: '2026-11-10'
source_filename: supadata-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://supadata.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: supadata-ai\naid: supadata-ai\nurl: https://supadata.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for this processing.\ndata_categories:\n- category: identifying\n  text: Name, email, password (hashed), organisation, sign-in provider profile, two-factor secrets\n- category: financial\n  text: Billing name and address, VAT ID, invoices, payment method (held by Stripe)\n- category: device\n  text: IP address, browser and device data, pages visited\n- category: behavioral\n  text: Analytics events and identifiers from consent-based tools (section 3)\n- category:\
  \ communication\n  text: Support messages and feedback\n- category: location\n  text: 'Playground: URL you enter, result, IP address, bot-protection signals'\npurposes:\n- purpose: Running the website securely, preventing abuse\n  text: Running the website securely, preventing abuse\n- purpose: Creating and securing your account, communicating with you\n  text: Creating and securing your account, communicating with you\n- purpose: Providing the API, billing, security\n  text: Providing the API, billing, security\n- purpose: Charging, invoicing, tax compliance\n  text: Charging, invoicing, tax compliance\n- purpose: Understanding usage, testing page variants\n  text: Understanding usage, testing page variants\nretention:\n- scope: Server logs\n  period: 30 days\n  text: Server logs 30 days\n- scope: Billing records\n  period: 10 years (German tax law)\n  text: 10 years (German tax law)\n- scope: Account data\n  period: Until you delete your account\n  text: Until you delete your account\n\
  - scope: Support messages\n  period: 2 years after last contact\n  text: 2 years after last contact\n- scope: API keys and usage data\n  period: For the duration of your customer relationship\n  text: For the duration of your customer relationship\n- scope: API job results\n  period: 1 hour (single jobs) or 24 hours (batch jobs)\n  text: Job results can be retrieved for 1 hour (single jobs) or 24 hours (batch jobs) and are then deleted.\nresidency:\n- region: United States\n  text: Data is processed in the United States.\ntransfers:\n- mechanism: DPF\n  text: we rely on the EU-US Data Privacy Framework where the provider is certified\n- mechanism: SCC\n  text: otherwise on the EU Standard Contractual Clauses\nsubprocessors:\n  url: https://supadata.ai/legal/sub-processors\n  text: They are listed with purpose and location at supadata.ai/legal/sub-processors\ndpa:\n  available: true\n  url: null\n  text: we act as their processor under our Data Processing Agreement\ndeletion:\n  route:\
  \ dashboard\n  text: You can delete your account yourself in the dashboard.\nrights:\n- right: access, rectify, erase, restrict, object, portability, withdraw consent\n  text: You have the right to access, rectify and erase your personal data, to restrict or object to its processing,\n    to receive it in a portable format, and to withdraw consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/supadata-ai/privacy/supadata-ai-privacy-policy.yml
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
summary_line: 26 quoted statements, read from supadata-ai's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Transcript
- YouTube
- TikTok
- Instagram
- Facebook
- X
- Artificial Intelligence
- Data
---
