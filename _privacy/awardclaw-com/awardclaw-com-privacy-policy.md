---
api_specs:
- filename: awardclaw-com-availability-api-openapi.yml
  format: yaml
  label: AwardClaw Availability API
  slug: awardclaw-com-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-availability-api-openapi.yml
- filename: awardclaw-com-briefing-api-openapi.yml
  format: yaml
  label: AwardClaw Briefing API
  slug: awardclaw-com-briefing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-briefing-api-openapi.yml
- filename: awardclaw-com-cards-api-openapi.yml
  format: yaml
  label: AwardClaw Cards API
  slug: awardclaw-com-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-cards-api-openapi.yml
- filename: awardclaw-com-drops-api-openapi.yml
  format: yaml
  label: AwardClaw Drops API
  slug: awardclaw-com-drops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-drops-api-openapi.yml
- filename: awardclaw-com-me-api-openapi.yml
  format: yaml
  label: AwardClaw Me API
  slug: awardclaw-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-me-api-openapi.yml
- filename: awardclaw-com-news-api-openapi.yml
  format: yaml
  label: AwardClaw News API
  slug: awardclaw-com-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-news-api-openapi.yml
- filename: awardclaw-com-watches-api-openapi.yml
  format: yaml
  label: AwardClaw Watches API
  slug: awardclaw-com-watches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-watches-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email address, and password (or OAuth credentials via Google)'
  - category: contact
    text: 'Mobile phone number: collected only if you choose to enable SMS alerts, together with the timestamp of your verification and opt-in'
  - category: financial
    text: 'Payment information: billing details processed through our third-party payment processor (we do not store full payment card numbers)'
  - category: device
    text: 'Device and browser information: IP address, browser type, operating system, and device identifiers'
  - category: behavioral
    text: 'Usage data: pages visited, features used, timestamps, referring URLs, and interaction patterns'
  - category: communication
    text: 'Communications: messages you send to us via contact forms or email'
  deletion:
    route: contact us at [email protected]
    text: To exercise any of these rights, contact us at [email protected] .
  dpa:
    available: null
    text: 'Service providers: third-party vendors who assist with hosting, analytics, payment processing, and email delivery, bound by data processing agreements'
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Account authentication
    text: Authenticate your identity and manage your account
  - purpose: Fraud and security
    text: Detect, prevent, and address fraud, abuse, and security issues
  - purpose: Payments and subscriptions
    text: Process payments and manage subscriptions
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your personal information for as long as your account is active or as needed to provide the Service.
  - period: up to 90 days
    scope: Data after account deletion
    text: After account deletion, we may retain certain data for up to 90 days for backup and fraud prevention purposes, after which it is permanently deleted.
  - period: indefinitely
    scope: Anonymized and aggregated data
    text: Anonymized and aggregated data may be retained indefinitely for analytics purposes.
  rights:
  - right: Access
    text: 'Access: request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction: request correction of inaccurate or incomplete data'
  - right: Deletion
    text: 'Deletion: request deletion of your personal data'
  - right: Portability
    text: 'Portability: receive your data in a structured, machine-readable format'
  - right: Objection
    text: 'Objection: object to processing based on legitimate interests'
  - right: Restriction
    text: 'Restriction: request restriction of processing in certain circumstances'
  - right: Withdraw consent
    text: 'Withdraw consent: withdraw consent at any time where processing is based on consent'
  role:
    text: C6 Labs LLC, formerly CarbonApps LLC ("Company," "we," "us," or "our") operates AwardClaw (the "Service").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information as defined by the CCPA/CPRA.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards such as Standard Contractual Clauses (SCCs) to ensure adequate protection of your personal information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AwardClaw
provenance_date: '2026-11-09'
provider_name: AwardClaw
provider_slug: awardclaw-com
slug: awardclaw-com-privacy-policy
source_date: '2026-11-09'
source_filename: awardclaw-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.awardclaw.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AwardClaw\naid: awardclaw-com\nurl: https://www.awardclaw.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: C6 Labs LLC, formerly CarbonApps LLC (\"Company,\" \"we,\" \"us,\" or \"our\") operates AwardClaw (the \"Service\").\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email address, and password (or OAuth credentials via Google)'\n- category: contact\n  text: 'Mobile phone number: collected only if you choose to enable SMS alerts, together with the timestamp of\n    your verification and opt-in'\n- category: financial\n  text: 'Payment information:\
  \ billing details processed through our third-party payment processor (we do not store\n    full payment card numbers)'\n- category: device\n  text: 'Device and browser information: IP address, browser type, operating system, and device identifiers'\n- category: behavioral\n  text: 'Usage data: pages visited, features used, timestamps, referring URLs, and interaction patterns'\n- category: communication\n  text: 'Communications: messages you send to us via contact forms or email'\npurposes:\n- purpose: Provide and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Account authentication\n  text: Authenticate your identity and manage your account\n- purpose: Fraud and security\n  text: Detect, prevent, and address fraud, abuse, and security issues\n- purpose: Payments and subscriptions\n  text: Process payments and manage subscriptions\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your personal information\
  \ for as long as your account is active or as needed to provide the Service.\n- scope: Data after account deletion\n  period: up to 90 days\n  text: After account deletion, we may retain certain data for up to 90 days for backup and fraud prevention purposes,\n    after which it is permanently deleted.\n- scope: Anonymized and aggregated data\n  period: indefinitely\n  text: Anonymized and aggregated data may be retained indefinitely for analytics purposes.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards such as Standard Contractual Clauses (SCCs) to ensure adequate protection\n    of your personal information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: 'Service providers: third-party vendors who assist with hosting, analytics, payment processing, and email\n    delivery, bound by data processing agreements'\ndeletion:\n  route: contact us at [email protected]\n  text: To exercise any of these rights, contact\
  \ us at [email protected] .\nrights:\n- right: Access\n  text: 'Access: request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction: request correction of inaccurate or incomplete data'\n- right: Deletion\n  text: 'Deletion: request deletion of your personal data'\n- right: Portability\n  text: 'Portability: receive your data in a structured, machine-readable format'\n- right: Objection\n  text: 'Objection: object to processing based on legitimate interests'\n- right: Restriction\n  text: 'Restriction: request restriction of processing in certain circumstances'\n- right: Withdraw consent\n  text: 'Withdraw consent: withdraw consent at any time where processing is based on consent'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information as defined by the CCPA/CPRA.\n"
source_yaml_url: https://artifacts.apis.io/awardclaw-com/privacy/awardclaw-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from AwardClaw's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Awards
- Airlines
- Flight Deals
- Automation
- Newsletters
---
