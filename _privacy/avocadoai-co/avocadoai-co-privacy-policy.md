---
api_specs:
- filename: avocadoai-co-openapi.json
  format: json
  label: Avocado AI API
  slug: avocado-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avocadoai-co/openapi/avocadoai-co-openapi.json
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email, password (handled by our authentication provider), profile image, organization name, role.'
  - category: financial
    text: 'Billing data: billing name, address, country, VAT/Tax ID, payment method details.'
  - category: biometric
    text: it may include biometric identifiers as defined under GDPR Article 9.
  - category: location
    text: basic request information the assistant attaches (such as language or approximate region)
  - category: device
    text: 'Usage data: features used, generations performed, credits consumed, error logs, session timestamps, device and browser information, IP address, referrer.'
  - category: behavioral
    text: analytics cookies (where consent is given), and security cookies.
  - category: communication
    text: 'Communications: messages sent to support, survey responses, replies to our emails.'
  deletion:
    route: Account settings or email to privacy@avocadoai.co
    text: You can delete your account from your account settings, or by emailing privacy@avocadoai.co.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: Provide the Service (account, generation, storage, collaboration) Contract
  - purpose: Process payments and subscriptions
    text: Process payments and manage subscriptions, add-ons, top-ups, and partner billing Contract
  - purpose: Improve the Service and prevent abuse and fraud
    text: Improve the Service, debug, prevent abuse and fraud Legitimate interests
  - purpose: Marketing emails
    text: Send marketing emails (only with your consent or where permitted) Consent / Legitimate interests
  residency:
  - region: Estonia
    text: We are based in Estonia and many of our sub-processors are located outside the European Economic Area, primarily in the United States.
  retention:
  - period: plus up to 90 days after deletion
    scope: Account data
    text: Account data For the lifetime of your account, plus up to 90 days after deletion
  - period: 7 years after the transaction
    scope: Billing records
    text: Billing records 7 years after the transaction (legal and tax requirement)
  - period: Up to 24 months
    scope: Usage and analytics logs
    text: Usage and analytics logs Up to 24 months
  - period: Up to 3 years after the last interaction
    scope: Support communications
    text: Support communications Up to 3 years after the last interaction
  rights:
  - right: Access
    text: Access your personal data
  - right: Rectify
    text: Rectify inaccurate data
  - right: Erase
    text: Erase your data ("right to be forgotten")
  - right: Restrict processing
    text: Restrict processing
  - right: Data portability
    text: Data portability
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Withdraw consent
    text: Withdraw consent at any time
  - right: Opt out of sale or sharing (CCPA)
    text: Opt out of the sale or sharing of personal information (we do not sell personal information)
  role:
    text: We are the data controller for the personal data we process.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: 6. Sub-processors We use the following sub-processors to deliver the Service.
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission;
  - mechanism: adequacy
    text: Adequacy decisions, where available;
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Avocado AI
provenance_date: '2026-11-09'
provider_name: Avocado AI
provider_slug: avocadoai-co
slug: avocadoai-co-privacy-policy
source_date: '2026-11-09'
source_filename: avocadoai-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.avocadoai.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Avocado AI\naid: avocadoai-co\nurl: https://www.avocadoai.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data we process.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email, password (handled by our authentication provider), profile image, organization\n    name, role.'\n- category: financial\n  text: 'Billing data: billing name, address, country, VAT/Tax ID, payment method details.'\n- category: biometric\n  text: it may include biometric identifiers as defined under GDPR Article 9.\n- category: location\n\
  \  text: basic request information the assistant attaches (such as language or approximate region)\n- category: device\n  text: 'Usage data: features used, generations performed, credits consumed, error logs, session timestamps, device\n    and browser information, IP address, referrer.'\n- category: behavioral\n  text: analytics cookies (where consent is given), and security cookies.\n- category: communication\n  text: 'Communications: messages sent to support, survey responses, replies to our emails.'\npurposes:\n- purpose: Provide the Service\n  text: Provide the Service (account, generation, storage, collaboration) Contract\n- purpose: Process payments and subscriptions\n  text: Process payments and manage subscriptions, add-ons, top-ups, and partner billing Contract\n- purpose: Improve the Service and prevent abuse and fraud\n  text: Improve the Service, debug, prevent abuse and fraud Legitimate interests\n- purpose: Marketing emails\n  text: Send marketing emails (only with your\
  \ consent or where permitted) Consent / Legitimate interests\nretention:\n- scope: Account data\n  period: plus up to 90 days after deletion\n  text: Account data For the lifetime of your account, plus up to 90 days after deletion\n- scope: Billing records\n  period: 7 years after the transaction\n  text: Billing records 7 years after the transaction (legal and tax requirement)\n- scope: Usage and analytics logs\n  period: Up to 24 months\n  text: Usage and analytics logs Up to 24 months\n- scope: Support communications\n  period: Up to 3 years after the last interaction\n  text: Support communications Up to 3 years after the last interaction\nresidency:\n- region: Estonia\n  text: We are based in Estonia and many of our sub-processors are located outside the European Economic Area, primarily\n    in the United States.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission;\n- mechanism: adequacy\n  text: Adequacy decisions, where\
  \ available;\nsubprocessors:\n  url: null\n  text: 6. Sub-processors We use the following sub-processors to deliver the Service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or email to privacy@avocadoai.co\n  text: You can delete your account from your account settings, or by emailing privacy@avocadoai.co.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Erase\n  text: Erase your data (\"right to be forgotten\")\n- right: Restrict processing\n  text: Restrict processing\n- right: Data portability\n  text: Data portability\n- right: Object\n  text: Object to processing based on legitimate interests\n- right: Withdraw consent\n  text: Withdraw consent at any time\n- right: Opt out of sale or sharing (CCPA)\n  text: Opt out of the sale or sharing of personal information (we do not sell personal information)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal\
  \ data.\n"
source_yaml_url: https://artifacts.apis.io/avocadoai-co/privacy/avocadoai-co-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Avocado AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Creative
- E-Commerce
- Image Generation
- Video Generation
---
