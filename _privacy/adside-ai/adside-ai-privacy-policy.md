---
api_specs:
- filename: adside-ai-openapi.yaml
  format: yaml
  label: Multi-Source Ads API
  slug: multi-source-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adside-ai/openapi/adside-ai-openapi.yaml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address; Company name, job title, and website (if provided)
  - category: financial
    text: Billing and payment information (processed by our third-party payment processor; we do not store full card numbers).
  - category: behavioral
    text: Pages visited, features used, and actions taken within the platform; Referring URLs and session duration
  - category: device
    text: IP address, browser type and version, operating system; Pages visited, features used, and actions taken within the platform; Referring URLs and session duration; Device type and screen resolution.
  - category: communication
    text: If you contact us via email, chat, or a support form, we retain the content of those communications and your contact details.
  deletion:
    route: Contact privacy@adside.ai or delete account
    text: To exercise any of the rights above, please contact us at privacy@adside.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing, operating, and maintaining the Service
    text: Providing, operating, and maintaining the Service Contractual necessity
  - purpose: Executing campaign actions on connected ad platforms
    text: Executing campaign actions on connected ad platforms on your behalf Contractual necessity / your instructions
  - purpose: Generating AI-powered campaign strategies and recommendations
    text: Generating AI-powered campaign strategies, creatives, and recommendations personalized to your account
  - purpose: Analytics and improving the Service
    text: Analytics and improving the Service Legitimate interest
  - purpose: Fraud prevention and security
    text: Fraud prevention and security Legitimate interest / legal obligation
  residency:
  - region: United States
    text: Adside is based in the United States. If you are in the EU, UK, or Switzerland, your data will be transferred to and processed in the United States.
  retention:
  - period: as long as your account is active or as needed to provide the Service
    scope: Account data
    text: We retain your account data for as long as your account is active or as needed to provide the Service.
  - period: within 90 days
    scope: Deleted account data
    text: If you delete your account, we will delete or anonymize your personal data within 90 days, unless we are required to retain it longer to comply with legal obligations, resolve disputes, or enforce our agreements.
  - period: indefinitely
    scope: Aggregated anonymized analytics
    text: Aggregated, anonymized analytics data that cannot be used to identify you may be retained indefinitely.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction: Request that we correct inaccurate or incomplete data'
  - right: Deletion
    text: 'Deletion: Request that we delete your personal data, subject to certain legal exceptions'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format'
  - right: Objection / Restriction
    text: 'Objection / Restriction: Object to or request that we restrict certain processing'
  - right: Withdraw Consent
    text: 'Withdraw Consent: Where processing is based on consent, withdraw that consent at any time without affecting the lawfulness of prior processing.'
  role:
    text: Adside acts as a data processor on your behalf with respect to the advertising platform data you instruct us to access.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on appropriate safeguards for such transfers, including Standard Contractual Clauses (SCCs) approved by the European Commission, and the UK International Data Transfer Agreement (IDTA) where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Adside
provenance_date: '2026-11-09'
provider_name: Adside
provider_slug: adside-ai
slug: adside-ai-privacy-policy
source_date: '2026-11-09'
source_filename: adside-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.adside.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Adside\naid: adside-ai\nurl: https://www.adside.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Adside acts as a data processor on your behalf with respect to the advertising platform data you instruct\n    us to access.\ndata_categories:\n- category: identifying\n  text: Name and email address; Company name, job title, and website (if provided)\n- category: financial\n  text: Billing and payment information (processed by our third-party payment processor; we do not store full card\n    numbers).\n- category: behavioral\n  text: Pages visited, features used, and actions taken within the\
  \ platform; Referring URLs and session duration\n- category: device\n  text: IP address, browser type and version, operating system; Pages visited, features used, and actions taken\n    within the platform; Referring URLs and session duration; Device type and screen resolution.\n- category: communication\n  text: If you contact us via email, chat, or a support form, we retain the content of those communications and\n    your contact details.\npurposes:\n- purpose: Providing, operating, and maintaining the Service\n  text: Providing, operating, and maintaining the Service Contractual necessity\n- purpose: Executing campaign actions on connected ad platforms\n  text: Executing campaign actions on connected ad platforms on your behalf Contractual necessity / your instructions\n- purpose: Generating AI-powered campaign strategies and recommendations\n  text: Generating AI-powered campaign strategies, creatives, and recommendations personalized to your account\n- purpose: Analytics and improving\
  \ the Service\n  text: Analytics and improving the Service Legitimate interest\n- purpose: Fraud prevention and security\n  text: Fraud prevention and security Legitimate interest / legal obligation\nretention:\n- scope: Account data\n  period: as long as your account is active or as needed to provide the Service\n  text: We retain your account data for as long as your account is active or as needed to provide the Service.\n- scope: Deleted account data\n  period: within 90 days\n  text: If you delete your account, we will delete or anonymize your personal data within 90 days, unless we are\n    required to retain it longer to comply with legal obligations, resolve disputes, or enforce our agreements.\n- scope: Aggregated anonymized analytics\n  period: indefinitely\n  text: Aggregated, anonymized analytics data that cannot be used to identify you may be retained indefinitely.\nresidency:\n- region: United States\n  text: Adside is based in the United States. If you are in the EU, UK,\
  \ or Switzerland, your data will be transferred\n    to and processed in the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on appropriate safeguards for such transfers, including Standard Contractual Clauses (SCCs) approved\n    by the European Commission, and the UK International Data Transfer Agreement (IDTA) where applicable.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@adside.ai or delete account\n  text: To exercise any of the rights above, please contact us at privacy@adside.ai .\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction: Request that we correct inaccurate or incomplete data'\n- right: Deletion\n  text: 'Deletion: Request that we delete your personal data, subject to certain legal exceptions'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable\
  \ format'\n- right: Objection / Restriction\n  text: 'Objection / Restriction: Object to or request that we restrict certain processing'\n- right: Withdraw Consent\n  text: 'Withdraw Consent: Where processing is based on consent, withdraw that consent at any time without affecting\n    the lawfulness of prior processing.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/adside-ai/privacy/adside-ai-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Adside's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Marketing
- Software-as-a-Service
- Automation
---
