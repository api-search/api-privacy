---
api_specs:
- filename: lensmor-actions-api-openapi.yml
  format: yaml
  label: Lensmor Actions API
  slug: lensmor-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-actions-api-openapi.yml
- filename: lensmor-contacts-api-openapi.yml
  format: yaml
  label: Lensmor Contacts API
  slug: lensmor-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-contacts-api-openapi.yml
- filename: lensmor-credits-api-openapi.yml
  format: yaml
  label: Lensmor Credits API
  slug: lensmor-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-credits-api-openapi.yml
- filename: lensmor-events-api-openapi.yml
  format: yaml
  label: Lensmor Events API
  slug: lensmor-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-events-api-openapi.yml
- filename: lensmor-exhibitors-api-openapi.yml
  format: yaml
  label: Lensmor Exhibitors API
  slug: lensmor-exhibitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-exhibitors-api-openapi.yml
- filename: lensmor-personnel-api-openapi.yml
  format: yaml
  label: Lensmor Personnel API
  slug: lensmor-personnel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-personnel-api-openapi.yml
- filename: lensmor-profile-matching-api-openapi.yml
  format: yaml
  label: Lensmor Profile Matching API
  slug: lensmor-profile-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lensmor/openapi/lensmor-profile-matching-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email, authentication information, organization details, and team invitations.
  - category: professional
    text: Saved events, companies, professional profiles, filters, keywords, notes, and other settings or content submitted to the service.
  - category: financial
    text: Billing details handled by our payment provider, transaction metadata, and information submitted in support, demo, security-review, or privacy requests.
  - category: device
    text: We collect service and API activity such as timestamps, endpoints, status codes, browser or device information, IP address, referring pages, and product interactions
  - category: behavioral
    text: first-party product analytics data
  deletion:
    route: Request deletion by contacting the privacy email or through the Privacy Center; account deletion processed within 30 days
    text: If a user deletes their account or requests deletion, we will delete or anonymize their account profile and associated personal service records within 30 days after receiving the request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve service
    text: We use information to provide and improve Lensmor; authenticate users; process customer instructions; support exports and integrations
  - purpose: process payments
    text: process payments
  - purpose: security and fraud detection
    text: detect fraud, abuse, and security incidents; comply with law; and establish or defend legal claims.
  - purpose: advertising
    text: We do not use Plugin queries or server logs for advertising targeting.
  retention:
  - period: as long as the user's account remains active
    scope: account information
    text: We retain account information for as long as the user's account remains active.
  - period: within 30 days
    scope: deleted account data
    text: we will delete or anonymize their account profile and associated personal service records within 30 days after receiving the request
  - period: 7 days
    scope: routine database backups
    text: Routine database backups expire within 7 days; no manual database snapshots are maintained.
  - period: up to 6 months
    scope: operational and security logs
    text: Restricted operational and security logs may be retained for up to 6 months
  - period: up to 12 months
    scope: ChatGPT Plugin logs
    text: Plugin queries, interaction logs, server logs, IP addresses, timestamps, request metadata, and troubleshooting records are retained for up to 12 months
  - period: up to 2 hours
    scope: browser extension sign-in return state
    text: The temporary sign-in return state is kept for up to 2 hours.
  rights:
  - right: objection and restriction
    text: Depending on your location, you may also have rights to object to or restrict certain processing, request portability, withdraw consent, or lodge a complaint with a supervisory authority.
  role:
    text: Lensmor generally acts as a controller when it determines why and how publicly available or partner-provided professional and business information is collected and used to provide event intelligence.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell users' personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use recognized transfer mechanisms or other appropriate safeguards for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lensmor
provenance_date: '2026-11-09'
provider_name: Lensmor
provider_slug: lensmor
slug: lensmor-privacy-policy
source_date: '2026-11-09'
source_filename: lensmor-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lensmor.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lensmor\naid: lensmor\nurl: https://www.lensmor.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Lensmor generally acts as a controller when it determines why and how publicly available or partner-provided\n    professional and business information is collected and used to provide event intelligence.\ndata_categories:\n- category: identifying\n  text: Name, work email, authentication information, organization details, and team invitations.\n- category: professional\n  text: Saved events, companies, professional profiles, filters, keywords, notes, and other settings or content\n    submitted\
  \ to the service.\n- category: financial\n  text: Billing details handled by our payment provider, transaction metadata, and information submitted in support,\n    demo, security-review, or privacy requests.\n- category: device\n  text: We collect service and API activity such as timestamps, endpoints, status codes, browser or device information,\n    IP address, referring pages, and product interactions\n- category: behavioral\n  text: first-party product analytics data\npurposes:\n- purpose: provide and improve service\n  text: We use information to provide and improve Lensmor; authenticate users; process customer instructions; support\n    exports and integrations\n- purpose: process payments\n  text: process payments\n- purpose: security and fraud detection\n  text: detect fraud, abuse, and security incidents; comply with law; and establish or defend legal claims.\n- purpose: advertising\n  text: We do not use Plugin queries or server logs for advertising targeting.\nretention:\n-\
  \ scope: account information\n  period: as long as the user's account remains active\n  text: We retain account information for as long as the user's account remains active.\n- scope: deleted account data\n  period: within 30 days\n  text: we will delete or anonymize their account profile and associated personal service records within 30 days\n    after receiving the request\n- scope: routine database backups\n  period: 7 days\n  text: Routine database backups expire within 7 days; no manual database snapshots are maintained.\n- scope: operational and security logs\n  period: up to 6 months\n  text: Restricted operational and security logs may be retained for up to 6 months\n- scope: ChatGPT Plugin logs\n  period: up to 12 months\n  text: Plugin queries, interaction logs, server logs, IP addresses, timestamps, request metadata, and troubleshooting\n    records are retained for up to 12 months\n- scope: browser extension sign-in return state\n  period: up to 2 hours\n  text: The temporary\
  \ sign-in return state is kept for up to 2 hours.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required, we use recognized transfer mechanisms or other appropriate safeguards for cross-border transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by contacting the privacy email or through the Privacy Center; account deletion processed\n    within 30 days\n  text: If a user deletes their account or requests deletion, we will delete or anonymize their account profile\n    and associated personal service records within 30 days after receiving the request\nrights:\n- right: objection and restriction\n  text: Depending on your location, you may also have rights to object to or restrict certain processing, request\n    portability, withdraw consent, or lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell users' personal data.\n"
source_yaml_url: https://artifacts.apis.io/lensmor/privacy/lensmor-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Lensmor's own page on 2026-11-09.
synthetic: false
tags:
- Event Intelligence
- B2B
- Software-as-a-Service
- Lead Generation
- Trade Shows
---
