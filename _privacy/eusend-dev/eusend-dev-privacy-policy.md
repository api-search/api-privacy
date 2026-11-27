---
api_specs:
- filename: eusend-dev-api-keys-api-openapi.yml
  format: yaml
  label: eusend-dev API keys API
  slug: eusend-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-api-keys-api-openapi.yml
- filename: eusend-dev-audiences-api-openapi.yml
  format: yaml
  label: eusend-dev Audiences API
  slug: eusend-dev-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-audiences-api-openapi.yml
- filename: eusend-dev-broadcasts-api-openapi.yml
  format: yaml
  label: eusend-dev Broadcasts API
  slug: eusend-dev-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-broadcasts-api-openapi.yml
- filename: eusend-dev-contact-properties-api-openapi.yml
  format: yaml
  label: eusend-dev Contact properties API
  slug: eusend-dev-contact-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-contact-properties-api-openapi.yml
- filename: eusend-dev-contacts-api-openapi.yml
  format: yaml
  label: eusend-dev Contacts API
  slug: eusend-dev-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-contacts-api-openapi.yml
- filename: eusend-dev-domains-api-openapi.yml
  format: yaml
  label: eusend-dev Domains API
  slug: eusend-dev-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-domains-api-openapi.yml
- filename: eusend-dev-emails-api-openapi.yml
  format: yaml
  label: eusend-dev Emails API
  slug: eusend-dev-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-emails-api-openapi.yml
- filename: eusend-dev-suppressions-api-openapi.yml
  format: yaml
  label: eusend-dev Suppressions API
  slug: eusend-dev-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-suppressions-api-openapi.yml
- filename: eusend-dev-system-api-openapi.yml
  format: yaml
  label: eusend-dev System API
  slug: eusend-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-system-api-openapi.yml
- filename: eusend-dev-templates-api-openapi.yml
  format: yaml
  label: eusend-dev Templates API
  slug: eusend-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-templates-api-openapi.yml
- filename: eusend-dev-topics-api-openapi.yml
  format: yaml
  label: eusend-dev Topics API
  slug: eusend-dev-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-topics-api-openapi.yml
- filename: eusend-dev-webhooks-api-openapi.yml
  format: yaml
  label: eusend-dev Webhooks API
  slug: eusend-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eusend-dev/openapi/eusend-dev-webhooks-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: when you sign up we collect your name, email address, and a hashed password
  - category: communication
    text: we process the recipient addresses, message content, and delivery metadata (timestamps, bounce codes, open and click events) on your behalf
  - category: financial
    text: We store only a Polar customer and subscription ID; we never see or store your card number.
  - category: device
    text: We record the page visited, the referring site, the country, and rough device type.
  - category: location
    text: the country
  deletion:
    route: delete content in account or close account; email privacy@eusend.dev to request deletion
    text: Request deletion of your account and associated data
  dpa:
    available: true
    text: Because you decide whether to email these recipients and whether to measure them, you are the controller for that choice — see our Data Processing Addendum .
    url: https://eusend.dev/legal/dpa
  purposes:
  - purpose: operate and improve the email delivery service
    text: To operate and improve the email delivery service
  - purpose: authenticate account and secure API keys
    text: To authenticate your account and secure your API keys
  - purpose: process billing and send receipts
    text: To process billing and send receipts
  - purpose: detect and prevent abuse
    text: To detect and prevent abuse, spam, and fraudulent use
  - purpose: respond to support requests
    text: To respond to support requests
  residency:
  - region: European Union
    text: All customer data is stored within the European Union
  retention:
  - period: 30 days
    scope: sent-email logs and delivery events
    text: Sent-email logs and delivery events (opens, clicks, bounces) are retained for 30 days on the Free tier and on monthly volumes up to 100,000
  - period: 30 days
    scope: attachments
    text: 'Attachments are deleted sooner: they are held for 30 days at every volume and then removed from the storage they are held in'
  - period: up to 90 days
    scope: operational API request logs
    text: These operational logs are retained for up to 90 days.
  - period: within 30 days of account closure
    scope: account data
    text: Account data is retained while your account is active and deleted within 30 days of account closure
  - period: three days
    scope: encrypted backups
    text: We also keep encrypted backups for disaster recovery on a rolling window, currently three days
  rights:
  - right: access
    text: Access the data we hold about you
  - right: correct
    text: Correct inaccurate data
  - right: deletion
    text: Request deletion of your account and associated data
  - right: export
    text: Export your data in a machine-readable format
  - right: human review of holds
    text: Have a person review any hold our automated screening places on your account
  role:
    text: the data controller for the personal data described in this policy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it for advertising.
  subprocessors:
    text: The canonical, always-current list — with each one’s role, location, and transfer safeguard — lives on our Sub-processors page.
    url: https://eusend.dev/legal/subprocessors
  transfers:
  - mechanism: DPF
    text: Cloudflare is certified under the EU–U.S. Data Privacy Framework, with Standard Contractual Clauses as a fallback.
  - mechanism: SCC
    text: Because Sentry is a US company, it is covered by the EU–U.S. Data Privacy Framework, with Standard Contractual Clauses as a fallback.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: eusend-dev
provenance_date: '2026-11-09'
provider_name: eusend-dev
provider_slug: eusend-dev
slug: eusend-dev-privacy-policy
source_date: '2026-11-09'
source_filename: eusend-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eusend.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: eusend-dev\naid: eusend-dev\nurl: https://eusend.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the data controller for the personal data described in this policy\ndata_categories:\n- category: identifying\n  text: when you sign up we collect your name, email address, and a hashed password\n- category: communication\n  text: we process the recipient addresses, message content, and delivery metadata (timestamps, bounce codes, open\n    and click events) on your behalf\n- category: financial\n  text: We store only a Polar customer and subscription ID; we never see or store\
  \ your card number.\n- category: device\n  text: We record the page visited, the referring site, the country, and rough device type.\n- category: location\n  text: the country\npurposes:\n- purpose: operate and improve the email delivery service\n  text: To operate and improve the email delivery service\n- purpose: authenticate account and secure API keys\n  text: To authenticate your account and secure your API keys\n- purpose: process billing and send receipts\n  text: To process billing and send receipts\n- purpose: detect and prevent abuse\n  text: To detect and prevent abuse, spam, and fraudulent use\n- purpose: respond to support requests\n  text: To respond to support requests\nretention:\n- scope: sent-email logs and delivery events\n  period: 30 days\n  text: Sent-email logs and delivery events (opens, clicks, bounces) are retained for 30 days on the Free tier and\n    on monthly volumes up to 100,000\n- scope: attachments\n  period: 30 days\n  text: 'Attachments are deleted sooner:\
  \ they are held for 30 days at every volume and then removed from the storage\n    they are held in'\n- scope: operational API request logs\n  period: up to 90 days\n  text: These operational logs are retained for up to 90 days.\n- scope: account data\n  period: within 30 days of account closure\n  text: Account data is retained while your account is active and deleted within 30 days of account closure\n- scope: encrypted backups\n  period: three days\n  text: We also keep encrypted backups for disaster recovery on a rolling window, currently three days\nresidency:\n- region: European Union\n  text: All customer data is stored within the European Union\ntransfers:\n- mechanism: DPF\n  text: Cloudflare is certified under the EU–U.S. Data Privacy Framework, with Standard Contractual Clauses as a\n    fallback.\n- mechanism: SCC\n  text: Because Sentry is a US company, it is covered by the EU–U.S. Data Privacy Framework, with Standard Contractual\n    Clauses as a fallback.\nsubprocessors:\n\
  \  url: https://eusend.dev/legal/subprocessors\n  text: The canonical, always-current list — with each one’s role, location, and transfer safeguard — lives on our\n    Sub-processors page.\ndpa:\n  available: true\n  url: https://eusend.dev/legal/dpa\n  text: Because you decide whether to email these recipients and whether to measure them, you are the controller\n    for that choice — see our Data Processing Addendum .\ndeletion:\n  route: delete content in account or close account; email privacy@eusend.dev to request deletion\n  text: Request deletion of your account and associated data\nrights:\n- right: access\n  text: Access the data we hold about you\n- right: correct\n  text: Correct inaccurate data\n- right: deletion\n  text: Request deletion of your account and associated data\n- right: export\n  text: Export your data in a machine-readable format\n- right: human review of holds\n  text: Have a person review any hold our automated screening places on your account\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell your data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/eusend-dev/privacy/eusend-dev-privacy-policy.yml
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
summary_line: 28 quoted statements, read from eusend-dev's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Transactional
- Marketing
- EU
- GDPR
---
