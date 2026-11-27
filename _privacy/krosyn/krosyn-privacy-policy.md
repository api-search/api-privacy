---
api_specs:
- filename: krosyn-connectors-api-openapi.yml
  format: yaml
  label: Chmura Software Connectors API
  slug: krosyn-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/krosyn/openapi/krosyn-connectors-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name -- your first and last name
  - category: contact
    text: Email address -- used for account identification, login, and service communications
  - category: financial
    text: Stripe customer ID -- a reference identifier linking your account to your Stripe payment profile
  - category: device
    text: User agent string -- your browser and operating system information
  - category: location
    text: IP address -- recorded in your session record
  - category: behavioral
    text: Tutorial progress -- whether you have completed onboarding tutorials
  deletion:
    route: Account deletion via account settings or by contacting us
    text: Account deletion can be initiated through your account settings or by contacting us.
  dpa:
    available: true
    text: You can review and request our standard DPA on our Data Processing Agreement page .
    url: null
  purposes:
  - purpose: Account creation and management
    text: Account creation and management Name, email, password Contract performance (Art. 6(1)(b))
  - purpose: Connector execution and service operation
    text: Connector execution and service operation Connector config, endpoint tokens, payloads Contract performance (Art. 6(1)(b))
  - purpose: Service improvement and analytics
    text: Service improvement and analytics Pseudonymous usage data collected via Google Tag Manager and Google Analytics 4 (after consent) Consent (Art. 6(1)(a))
  - purpose: Security monitoring and fraud prevention
    text: Security monitoring and fraud prevention IP address, user agent, session data Legitimate interest (Art. 6(1)(f))
  residency:
  - region: Germany (EU)
    text: Infrastructure is hosted on Hetzner Online GmbH in Germany (EU)
  retention:
  - period: 30 days
    scope: Account data
    text: Retained while your account is active, and for up to 30 days after account deletion to allow for recovery
  - period: 120 minutes of inactivity
    scope: Session data
    text: Automatically purged after session expiry (120 minutes of inactivity)
  - period: 90 days
    scope: Connector event logs (Business plan)
    text: Connector event logs (Business plan) 90 days
  rights:
  - right: Access
    text: Right of Access (Art. 15) You have the right to request a copy of the personal data we hold about you
  - right: Erasure
    text: Right to Erasure (Art. 17) You have the right to request deletion of your personal data
  - right: Portability
    text: Right to Data Portability (Art. 20)
  - right: Object
    text: Right to Object (Art. 21) You have the right to object to processing based on legitimate interest.
  - right: Correction
    text: Right to Rectification (Art. 16) You have the right to request correction of inaccurate personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information, so no opt-out mechanism is needed.
  subprocessors:
    text: 'We use the following third-party services that may process personal data on our behalf: Sub-processor Purpose Data Accessed Location'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) -- as adopted by the European Commission, ensuring contractual obligations on the data importer to protect your data to EU standards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chmura Software
provenance_date: '2026-11-09'
provider_name: Chmura Software
provider_slug: krosyn
slug: krosyn-privacy-policy
source_date: '2026-11-09'
source_filename: krosyn-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://krosyn.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chmura Software\naid: krosyn\nurl: https://krosyn.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name -- your first and last name\n- category: contact\n  text: Email address -- used for account identification, login, and service communications\n- category: financial\n  text: Stripe customer ID -- a reference identifier linking your account to your Stripe payment profile\n- category: device\n  text: User agent string -- your browser and operating system information\n- category: location\n  text: IP address -- recorded in your\
  \ session record\n- category: behavioral\n  text: Tutorial progress -- whether you have completed onboarding tutorials\npurposes:\n- purpose: Account creation and management\n  text: Account creation and management Name, email, password Contract performance (Art. 6(1)(b))\n- purpose: Connector execution and service operation\n  text: Connector execution and service operation Connector config, endpoint tokens, payloads Contract performance\n    (Art. 6(1)(b))\n- purpose: Service improvement and analytics\n  text: Service improvement and analytics Pseudonymous usage data collected via Google Tag Manager and Google Analytics\n    4 (after consent) Consent (Art. 6(1)(a))\n- purpose: Security monitoring and fraud prevention\n  text: Security monitoring and fraud prevention IP address, user agent, session data Legitimate interest (Art.\n    6(1)(f))\nretention:\n- scope: Account data\n  period: 30 days\n  text: Retained while your account is active, and for up to 30 days after account deletion\
  \ to allow for recovery\n- scope: Session data\n  period: 120 minutes of inactivity\n  text: Automatically purged after session expiry (120 minutes of inactivity)\n- scope: Connector event logs (Business plan)\n  period: 90 days\n  text: Connector event logs (Business plan) 90 days\nresidency:\n- region: Germany (EU)\n  text: Infrastructure is hosted on Hetzner Online GmbH in Germany (EU)\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) -- as adopted by the European Commission, ensuring contractual obligations\n    on the data importer to protect your data to EU standards\nsubprocessors:\n  url: null\n  text: 'We use the following third-party services that may process personal data on our behalf: Sub-processor Purpose\n    Data Accessed Location'\ndpa:\n  available: true\n  url: null\n  text: You can review and request our standard DPA on our Data Processing Agreement page .\ndeletion:\n  route: Account deletion via account settings or by contacting us\n  text:\
  \ Account deletion can be initiated through your account settings or by contacting us.\nrights:\n- right: Access\n  text: Right of Access (Art. 15) You have the right to request a copy of the personal data we hold about you\n- right: Erasure\n  text: Right to Erasure (Art. 17) You have the right to request deletion of your personal data\n- right: Portability\n  text: Right to Data Portability (Art. 20)\n- right: Object\n  text: Right to Object (Art. 21) You have the right to object to processing based on legitimate interest.\n- right: Correction\n  text: Right to Rectification (Art. 16) You have the right to request correction of inaccurate personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information, so no opt-out mechanism is needed.\n"
source_yaml_url: https://artifacts.apis.io/krosyn/privacy/krosyn-privacy-policy.yml
stated_fields:
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
summary_line: 24 quoted statements, read from Chmura Software's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Developer Tools
- Security
---
