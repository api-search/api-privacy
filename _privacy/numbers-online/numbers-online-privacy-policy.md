---
api_specs:
- filename: numbers-online-account-api-openapi.yml
  format: yaml
  label: Numbers Online Account API
  slug: numbers-online-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-account-api-openapi.yml
- filename: numbers-online-community-reporting-api-openapi.yml
  format: yaml
  label: Numbers Online Community reporting API
  slug: numbers-online-community-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-community-reporting-api-openapi.yml
- filename: numbers-online-inbound-api-openapi.yml
  format: yaml
  label: Numbers Online Inbound API
  slug: numbers-online-inbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-inbound-api-openapi.yml
- filename: numbers-online-lookup-api-openapi.yml
  format: yaml
  label: Numbers Online Lookup API
  slug: numbers-online-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-lookup-api-openapi.yml
- filename: numbers-online-mcp-api-openapi.yml
  format: yaml
  label: Numbers Online MCP API
  slug: numbers-online-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-mcp-api-openapi.yml
- filename: numbers-online-msp-api-openapi.yml
  format: yaml
  label: Numbers Online MSP API
  slug: numbers-online-msp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-msp-api-openapi.yml
- filename: numbers-online-outbound-api-openapi.yml
  format: yaml
  label: Numbers Online Outbound API
  slug: numbers-online-outbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-outbound-api-openapi.yml
- filename: numbers-online-parsing-api-openapi.yml
  format: yaml
  label: Numbers Online Parsing API
  slug: numbers-online-parsing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-parsing-api-openapi.yml
- filename: numbers-online-pbx-api-openapi.yml
  format: yaml
  label: Numbers Online PBX API
  slug: numbers-online-pbx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-pbx-api-openapi.yml
- filename: numbers-online-receipts-api-openapi.yml
  format: yaml
  label: Numbers Online Receipts API
  slug: numbers-online-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-receipts-api-openapi.yml
- filename: numbers-online-reference-api-openapi.yml
  format: yaml
  label: Numbers Online Reference API
  slug: numbers-online-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-reference-api-openapi.yml
- filename: numbers-online-sbc-sip-api-openapi.yml
  format: yaml
  label: Numbers Online SBC / SIP API
  slug: numbers-online-sbc-sip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-sbc-sip-api-openapi.yml
- filename: numbers-online-system-api-openapi.yml
  format: yaml
  label: Numbers Online System API
  slug: numbers-online-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-system-api-openapi.yml
- filename: numbers-online-trust-api-openapi.yml
  format: yaml
  label: Numbers Online Trust API
  slug: numbers-online-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-trust-api-openapi.yml
- filename: numbers-online-webhooks-api-openapi.yml
  format: yaml
  label: Numbers Online Webhooks API
  slug: numbers-online-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/numbers-online/openapi/numbers-online-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: The phone number you search and the IP address of your request
  - category: identifying
    text: company legal name, registration, address and tax identifiers
  - category: financial
    text: we receive only metadata such as a transaction reference, amount, and status
  - category: device
    text: Technical information such as browser type, device and operating-system details, timestamps, and security logs.
  - category: communication
    text: an optional email for an API account, kept solely to send subscription-renewal reminders
  - category: behavioral
    text: Derived signals (such as account age, corroboration with other accounts, and payment-method fingerprint)
  deletion:
    route: Sign in with the number at numbers.online/dashboard/privacy, or write to the privacy address
    text: You can access, correct, delete or object to processing of your data at any time by signing in with your number at numbers.online/dashboard/privacy
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing reverse lookups and risk scores
    text: Providing reverse lookups and risk scores (legitimate interests).
  - purpose: Securing the directory and preventing abuse
    text: Securing the directory and preventing abuse (legitimate interests).
  - purpose: Paid verification and B2B services
    text: Paid verification and B2B services (contract).
  - purpose: Meeting legal obligations
    text: Meeting our obligations (legal obligation).
  residency:
  - region: Singapore
    text: We operate from Singapore, and our sub-processors may be located in other countries
  retention:
  - period: null
    scope: Lookup logs and IP data
    text: Kept for a short period for rate-limiting, security, and abuse prevention, then deleted or aggregated.
  - period: 12 months
    scope: Requests made on the privacy page
    text: Kept for 12 months after we answer them.
  - period: a few days
    scope: Hashed call-attempt metadata
    text: It is held briefly (a few days), kept server-side, and is never shown to either party.
  - period: 30 days
    scope: Scheduled job logs
    text: The logs of our scheduled jobs are deleted after 30 days.
  - period: null
    scope: B2B scrubbing lists
    text: Processed transiently to return a result and not retained beyond what is needed to deliver the service.
  rights:
  - right: access
    text: to access the personal data we hold about you, to correct it, to delete or erase it
  - right: object/restrict
    text: to restrict or object to certain processing (including processing based on our legitimate interests)
  - right: portability
    text: to receive a portable copy of data you provided
  - right: withdraw consent
    text: to withdraw any consent you have given
  role:
    text: we act as a processor (an intermediary)
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share your lookup history with data brokers.
  subprocessors:
    text: Sub-processors who help us run the Service under contract and on our instructions, for example cloud hosting providers, our payment processor, and messaging providers that send OTP and verification codes.
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (and the UK Addendum where relevant), or equivalent measures
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Numbers Online
provenance_date: '2026-11-10'
provider_name: Numbers Online
provider_slug: numbers-online
slug: numbers-online-privacy-policy
source_date: '2026-11-10'
source_filename: numbers-online-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://numbers.online/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Numbers Online\naid: numbers-online\nurl: https://numbers.online/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a processor (an intermediary)\ndata_categories:\n- category: contact\n  text: The phone number you search and the IP address of your request\n- category: identifying\n  text: company legal name, registration, address and tax identifiers\n- category: financial\n  text: we receive only metadata such as a transaction reference, amount, and status\n- category: device\n  text: Technical information such as browser type, device and operating-system details, timestamps, and\
  \ security\n    logs.\n- category: communication\n  text: an optional email for an API account, kept solely to send subscription-renewal reminders\n- category: behavioral\n  text: Derived signals (such as account age, corroboration with other accounts, and payment-method fingerprint)\npurposes:\n- purpose: Providing reverse lookups and risk scores\n  text: Providing reverse lookups and risk scores (legitimate interests).\n- purpose: Securing the directory and preventing abuse\n  text: Securing the directory and preventing abuse (legitimate interests).\n- purpose: Paid verification and B2B services\n  text: Paid verification and B2B services (contract).\n- purpose: Meeting legal obligations\n  text: Meeting our obligations (legal obligation).\nretention:\n- scope: Lookup logs and IP data\n  period: null\n  text: Kept for a short period for rate-limiting, security, and abuse prevention, then deleted or aggregated.\n- scope: Requests made on the privacy page\n  period: 12 months\n  text:\
  \ Kept for 12 months after we answer them.\n- scope: Hashed call-attempt metadata\n  period: a few days\n  text: It is held briefly (a few days), kept server-side, and is never shown to either party.\n- scope: Scheduled job logs\n  period: 30 days\n  text: The logs of our scheduled jobs are deleted after 30 days.\n- scope: B2B scrubbing lists\n  period: null\n  text: Processed transiently to return a result and not retained beyond what is needed to deliver the service.\nresidency:\n- region: Singapore\n  text: We operate from Singapore, and our sub-processors may be located in other countries\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses (and the UK Addendum where relevant), or equivalent\n    measures\nsubprocessors:\n  url: null\n  text: Sub-processors who help us run the Service under contract and on our instructions, for example cloud hosting\n    providers, our payment processor, and messaging providers that send OTP and verification\
  \ codes.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Sign in with the number at numbers.online/dashboard/privacy, or write to the privacy address\n  text: You can access, correct, delete or object to processing of your data at any time by signing in with your\n    number at numbers.online/dashboard/privacy\nrights:\n- right: access\n  text: to access the personal data we hold about you, to correct it, to delete or erase it\n- right: object/restrict\n  text: to restrict or object to certain processing (including processing based on our legitimate interests)\n- right: portability\n  text: to receive a portable copy of data you provided\n- right: withdraw consent\n  text: to withdraw any consent you have given\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share your lookup history with data brokers.\n"
source_yaml_url: https://artifacts.apis.io/numbers-online/privacy/numbers-online-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Numbers Online's own page on 2026-11-10.
synthetic: false
tags:
- Phone Intelligence
- Caller ID
- CNAM
- Reverse Phone Lookup
- Spam Detection
- Do Not Call
- Telephony
- STIR/SHAKEN
- MCP
- Agent-Native
- Compliance
- Company
- A2A
---
