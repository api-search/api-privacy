---
api_specs:
- filename: inoreader-accounts-api-openapi.yml
  format: yaml
  label: Inoreader Accounts API
  slug: inoreader-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inoreader/openapi/inoreader-accounts-api-openapi.yml
- filename: inoreader-oauth2-api-openapi.yml
  format: yaml
  label: Inoreader Oauth2 API
  slug: inoreader-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inoreader/openapi/inoreader-oauth2-api-openapi.yml
- filename: inoreader-reader-api-openapi.yml
  format: yaml
  label: Inoreader Reader API
  slug: inoreader-reader-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inoreader/openapi/inoreader-reader-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email, password (stored hashed), name, profile picture, language and time zone, sign-in provider ID if you use Google, Apple or SSO
  - category: financial
    text: Name, billing address, VAT number, plan and transaction history. Card data is handled by our payment provider; we only receive the card type, last 4 digits and expiry date
  - category: device
    text: IP address, device and browser data, login history, reCAPTCHA signals
  - category: behavioral
    text: Pages visited, time on site, referrer, device data, collected through cookies
  - category: communication
    text: Messages you send us, contact form data, related account details
  deletion:
    route: Delete your account
    text: Deleted as soon as you delete your account; backups are overwritten within 30 days
  dpa:
    available: null
    text: They act on our instructions and under data processing agreements.
    url: null
  purposes:
  - purpose: Creating and running your account
    text: Creating and running your account
  - purpose: Inoreader Intelligence AI features
    text: When you use AI features, the article text and your prompt are sent to our AI provider only to generate the result you asked for.
  - purpose: Security and fraud prevention
    text: Legitimate interest in protecting the Service and our users – Art. 6(1)(f)
  - purpose: Marketing emails and newsletters
    text: Your consent – Art. 6(1)(a), or for existing customers, legitimate interest in promoting similar services
  residency:
  - region: EU (Bulgaria)
    text: Equinix (SO1 data centre, Sofia) Server hosting and data storage (colocation of our own servers) EU (Bulgaria)
  retention:
  - period: 30 days
    scope: Account and content data
    text: Deleted as soon as you delete your account; backups are overwritten within 30 days
  - period: 10 years
    scope: Invoices and accounting records
    text: 10 years, as required by the Bulgarian Accountancy Act
  - period: 90 days
    scope: Security and server logs
    text: Security and server logs 90 days
  - period: 3 years
    scope: Marketing consent and preferences
    text: Until you withdraw consent or unsubscribe, plus proof of consent for 3 years
  rights:
  - right: access
    text: access your data and get a copy of it
  - right: rectify
    text: rectify inaccurate data
  - right: erase
    text: erase your data (“right to be forgotten”), including by deleting your account
  - right: restrict processing
    text: restrict processing in certain cases
  - right: portability
    text: data portability – export your subscriptions (OPML) and content in a machine-readable format
  - right: object
    text: object at any time to processing based on legitimate interest, and to direct marketing
  - right: withdraw consent
    text: withdraw consent at any time, without affecting earlier processing
  role:
    text: The controller of your personal data is Innologica Ltd, a company registered in Bulgaria, UIC 202279697, registered address 35 Boris Stefanov Str., 1700 Sofia, Bulgaria.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Cloudflare, Inc. Content delivery, security, bot protection EU / USA
    url: null
  transfers:
  - mechanism: DPF
    text: we rely on the EU-US Data Privacy Framework (for certified providers)
  - mechanism: adequacy
    text: on an adequacy decision of the European Commission
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses together with additional safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Inoreader
provenance_date: '2026-11-09'
provider_name: Inoreader
provider_slug: inoreader
slug: inoreader-privacy-policy
source_date: '2026-11-09'
source_filename: inoreader-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.inoreader.com/privacy_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Inoreader\naid: inoreader\nurl: https://www.inoreader.com/privacy_policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is Innologica Ltd, a company registered in Bulgaria, UIC 202279697,\n    registered address 35 Boris Stefanov Str., 1700 Sofia, Bulgaria.\ndata_categories:\n- category: identifying\n  text: Email, password (stored hashed), name, profile picture, language and time zone, sign-in provider ID if you\n    use Google, Apple or SSO\n- category: financial\n  text: Name, billing address, VAT number, plan and transaction history. Card data is handled\
  \ by our payment provider;\n    we only receive the card type, last 4 digits and expiry date\n- category: device\n  text: IP address, device and browser data, login history, reCAPTCHA signals\n- category: behavioral\n  text: Pages visited, time on site, referrer, device data, collected through cookies\n- category: communication\n  text: Messages you send us, contact form data, related account details\npurposes:\n- purpose: Creating and running your account\n  text: Creating and running your account\n- purpose: Inoreader Intelligence AI features\n  text: When you use AI features, the article text and your prompt are sent to our AI provider only to generate\n    the result you asked for.\n- purpose: Security and fraud prevention\n  text: Legitimate interest in protecting the Service and our users – Art. 6(1)(f)\n- purpose: Marketing emails and newsletters\n  text: Your consent – Art. 6(1)(a), or for existing customers, legitimate interest in promoting similar services\nretention:\n- scope:\
  \ Account and content data\n  period: 30 days\n  text: Deleted as soon as you delete your account; backups are overwritten within 30 days\n- scope: Invoices and accounting records\n  period: 10 years\n  text: 10 years, as required by the Bulgarian Accountancy Act\n- scope: Security and server logs\n  period: 90 days\n  text: Security and server logs 90 days\n- scope: Marketing consent and preferences\n  period: 3 years\n  text: Until you withdraw consent or unsubscribe, plus proof of consent for 3 years\nresidency:\n- region: EU (Bulgaria)\n  text: Equinix (SO1 data centre, Sofia) Server hosting and data storage (colocation of our own servers) EU (Bulgaria)\ntransfers:\n- mechanism: DPF\n  text: we rely on the EU-US Data Privacy Framework (for certified providers)\n- mechanism: adequacy\n  text: on an adequacy decision of the European Commission\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses together with additional safeguards\nsubprocessors:\n  url:\
  \ null\n  text: Cloudflare, Inc. Content delivery, security, bot protection EU / USA\ndpa:\n  available: null\n  url: null\n  text: They act on our instructions and under data processing agreements.\ndeletion:\n  route: Delete your account\n  text: Deleted as soon as you delete your account; backups are overwritten within 30 days\nrights:\n- right: access\n  text: access your data and get a copy of it\n- right: rectify\n  text: rectify inaccurate data\n- right: erase\n  text: erase your data (“right to be forgotten”), including by deleting your account\n- right: restrict processing\n  text: restrict processing in certain cases\n- right: portability\n  text: data portability – export your subscriptions (OPML) and content in a machine-readable format\n- right: object\n  text: object at any time to processing based on legitimate interest, and to direct marketing\n- right: withdraw consent\n  text: withdraw consent at any time, without affecting earlier processing\nsale_or_sharing:\n  stance:\
  \ prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/inoreader/privacy/inoreader-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Inoreader's own page on 2026-11-09.
synthetic: false
tags:
- Company
- RSS
- Content Aggregation
- Productivity
---
