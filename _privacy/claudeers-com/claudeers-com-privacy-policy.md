---
api_specs:
- filename: claudeers-com-openapi-generated.yml
  format: yaml
  label: Claudeers API
  slug: claudeers-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claudeers-com/openapi/_ae-authored/claudeers-com-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your email address , your GitHub user ID and username , your display name , and your avatar URL
  - category: financial
    text: We store only the Stripe identifiers (customer, session, payment, and subscription IDs), the product purchased, the amount, currency, and status.
  - category: location
    text: your country (derived from a network header)
  - category: device
    text: a daily-salted, one-way hash of your IP address (never the raw IP)
  - category: behavioral
    text: the referring URL
  - category: communication
    text: We also store your email-notification preferences
  deletion:
    route: email to request deletion of account and associated personal data
    text: 'Account deletion: email [email protected] to request deletion of your account and associated personal data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the Service
    text: We use the information above to operate the Service (authenticate you, show your profile, run the directory)
  - purpose: payment processing
    text: process payments and deliver paid features via Stripe
  - purpose: communication
    text: communicate with you (transactional emails such as receipts and verification, plus digests and announcements if you opt in)
  - purpose: security and analytics
    text: measure and secure the Service (privacy-preserving analytics, abuse and fraud prevention, and rate-limiting
  residency:
  - region: United States and other countries
    text: The Service is operated from, and data may be processed in, the United States and other countries.
  retention:
  - period: null
    scope: account and content data
    text: We keep account and content data for as long as your account is active and as needed to provide the Service
  - period: null
    scope: hashed-IP analytics and operational logs
    text: Hashed-IP analytics records and operational logs are retained for a limited operational period and then aged out.
  rights:
  - right: opt out of digests and announcements
    text: 'Email: opt out of digests and announcements in your settings or via the unsubscribe link.'
  - right: account deletion
    text: 'Account deletion: email [email protected] to request deletion of your account and associated personal data.'
  role:
    text: Claudeers — a service operated by RAZLabs LLC , a Delaware limited liability company ("Claudeers", "we", "us")
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: We share data only with service providers that help us run the Service, each handling data under their own terms
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Claudeers
provenance_date: '2026-11-09'
provider_name: Claudeers
provider_slug: claudeers-com
slug: claudeers-com-privacy-policy
source_date: '2026-11-09'
source_filename: claudeers-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://claudeers.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Claudeers\naid: claudeers-com\nurl: https://claudeers.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Claudeers — a service operated by RAZLabs LLC , a Delaware limited liability company (\"Claudeers\", \"we\",\n    \"us\")\ndata_categories:\n- category: identifying\n  text: we store your email address , your GitHub user ID and username , your display name , and your avatar URL\n- category: financial\n  text: We store only the Stripe identifiers (customer, session, payment, and subscription IDs), the product purchased,\n    the amount, currency, and status.\n- category: location\n\
  \  text: your country (derived from a network header)\n- category: device\n  text: a daily-salted, one-way hash of your IP address (never the raw IP)\n- category: behavioral\n  text: the referring URL\n- category: communication\n  text: We also store your email-notification preferences\npurposes:\n- purpose: operate the Service\n  text: We use the information above to operate the Service (authenticate you, show your profile, run the directory)\n- purpose: payment processing\n  text: process payments and deliver paid features via Stripe\n- purpose: communication\n  text: communicate with you (transactional emails such as receipts and verification, plus digests and announcements\n    if you opt in)\n- purpose: security and analytics\n  text: measure and secure the Service (privacy-preserving analytics, abuse and fraud prevention, and rate-limiting\nretention:\n- scope: account and content data\n  period: null\n  text: We keep account and content data for as long as your account is active\
  \ and as needed to provide the Service\n- scope: hashed-IP analytics and operational logs\n  period: null\n  text: Hashed-IP analytics records and operational logs are retained for a limited operational period and then\n    aged out.\nresidency:\n- region: United States and other countries\n  text: The Service is operated from, and data may be processed in, the United States and other countries.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We share data only with service providers that help us run the Service, each handling data under their own\n    terms\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to request deletion of account and associated personal data\n  text: 'Account deletion: email [email protected] to request deletion of your account and associated personal data.'\nrights:\n- right: opt out of digests and announcements\n  text: 'Email: opt out of digests and announcements in your settings or via the unsubscribe link.'\n- right: account\
  \ deletion\n  text: 'Account deletion: email [email protected] to request deletion of your account and associated personal data.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/claudeers-com/privacy/claudeers-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Claudeers's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Registry
- Community
- Project
- Claude
---
