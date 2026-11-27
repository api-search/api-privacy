---
api_specs:
- filename: cautellus-com-openapi-generated.yml
  format: yaml
  label: Cautellus API
  slug: cautellus-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cautellus-com/openapi/_ae-authored/cautellus-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (b) First name and last name (c) Cookies and Usage Data.
  - category: device
    text: unique device identifiers, and other diagnostic data
  - category: contact
    text: Your IP address , used only for short-term rate limiting and free-tier tracking
  - category: behavioral
    text: the pages of our Service that you visit, the time and date of your visit, the time spent on those pages
  - category: financial
    text: Payment information is processed and stored by our payment processor, Stripe. We do not store your full credit card number.
  deletion:
    route: email support@cautellus.com with the subject line "Data Deletion Request"
    text: You may request deletion of your personal data at any time by emailing us at support@cautellus.com with the subject line "Data Deletion Request."
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and maintain the Service
    text: (a) to provide and maintain our Service;
  - purpose: rate limiting and abuse prevention
    text: we temporarily process your IP address for rate limiting and abuse prevention purposes only.
  - purpose: marketing communications
    text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials, and other information that may be of interest to you.
  - purpose: service improvement
    text: (e) to gather analysis or valuable information so that we can improve our Service;
  residency:
  - region: United States
    text: we transfer the data, including Personal Data, to the United States and process it there.
  retention:
  - period: 30 days
    scope: account data
    text: If you delete your account or request deletion, we will remove your personal data within 30 days, except where we are required to retain it for legal or regulatory purposes.
  - period: null
    scope: uploaded messages and images
    text: Messages submitted for scam analysis and images uploaded to the AI Image Detector are processed in real-time and immediately discarded.
  - period: 90 days
    scope: newsletter subscription data
    text: Upon unsubscription, we retain the email address for 90 days to process the request and prevent accidental re-subscription.
  - period: null
    scope: scan history and usage logs
    text: We retain scan-event metadata for usage measurement and service operations.
  rights:
  - right: Access
    text: Access — Request a copy of the personal data we hold about you
  - right: Rectification
    text: Rectification — Request correction of inaccurate or incomplete personal data
  - right: Erasure
    text: Erasure — Request deletion of your personal data ("right to be forgotten")
  - right: Restrict Processing
    text: Restrict Processing — Request that we limit how we use your data
  - right: Data Portability
    text: Data Portability — Request your data in a structured, commonly used format
  - right: Object
    text: Object — Object to processing based on legitimate interests or for direct marketing
  - right: Withdraw Consent
    text: Withdraw Consent — Withdraw consent at any time where processing is based on consent
  role:
    text: For the purpose of this Privacy Policy, we are a Data Controller of your data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: our third-party processors (Supabase, Stripe, Google, Anthropic) maintain appropriate safeguards including Standard Contractual Clauses (SCCs) approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cautellus
provenance_date: '2026-11-09'
provider_name: Cautellus
provider_slug: cautellus-com
slug: cautellus-com-privacy-policy
source_date: '2026-11-09'
source_filename: cautellus-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cautellus.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cautellus\naid: cautellus-com\nurl: https://cautellus.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the purpose of this Privacy Policy, we are a Data Controller of your data.\ndata_categories:\n- category: identifying\n  text: Email address (b) First name and last name (c) Cookies and Usage Data.\n- category: device\n  text: unique device identifiers, and other diagnostic data\n- category: contact\n  text: Your IP address , used only for short-term rate limiting and free-tier tracking\n- category: behavioral\n  text: the pages of our Service that you visit, the time and date\
  \ of your visit, the time spent on those pages\n- category: financial\n  text: Payment information is processed and stored by our payment processor, Stripe. We do not store your full\n    credit card number.\npurposes:\n- purpose: provide and maintain the Service\n  text: (a) to provide and maintain our Service;\n- purpose: rate limiting and abuse prevention\n  text: we temporarily process your IP address for rate limiting and abuse prevention purposes only.\n- purpose: marketing communications\n  text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials, and other\n    information that may be of interest to you.\n- purpose: service improvement\n  text: (e) to gather analysis or valuable information so that we can improve our Service;\nretention:\n- scope: account data\n  period: 30 days\n  text: If you delete your account or request deletion, we will remove your personal data within 30 days, except\n    where we are required to retain it for\
  \ legal or regulatory purposes.\n- scope: uploaded messages and images\n  period: null\n  text: Messages submitted for scam analysis and images uploaded to the AI Image Detector are processed in real-time\n    and immediately discarded.\n- scope: newsletter subscription data\n  period: 90 days\n  text: Upon unsubscription, we retain the email address for 90 days to process the request and prevent accidental\n    re-subscription.\n- scope: scan history and usage logs\n  period: null\n  text: We retain scan-event metadata for usage measurement and service operations.\nresidency:\n- region: United States\n  text: we transfer the data, including Personal Data, to the United States and process it there.\ntransfers:\n- mechanism: SCC\n  text: our third-party processors (Supabase, Stripe, Google, Anthropic) maintain appropriate safeguards including\n    Standard Contractual Clauses (SCCs) approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: email support@cautellus.com with the subject line \"Data Deletion Request\"\n  text: You may request deletion of your personal data at any time by emailing us at support@cautellus.com with\n    the subject line \"Data Deletion Request.\"\nrights:\n- right: Access\n  text: Access — Request a copy of the personal data we hold about you\n- right: Rectification\n  text: Rectification — Request correction of inaccurate or incomplete personal data\n- right: Erasure\n  text: Erasure — Request deletion of your personal data (\"right to be forgotten\")\n- right: Restrict Processing\n  text: Restrict Processing — Request that we limit how we use your data\n- right: Data Portability\n  text: Data Portability — Request your data in a structured, commonly used format\n- right: Object\n  text: Object — Object to processing based on legitimate interests or for direct marketing\n- right: Withdraw Consent\n  text: Withdraw Consent — Withdraw consent at any\
  \ time where processing is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/cautellus-com/privacy/cautellus-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Cautellus's own page on 2026-11-09.
synthetic: false
tags:
- Scam Detection
- Artificial Intelligence
- Cybersecurity
- Consumer Protection
- Chrome Extension
- Company
---
