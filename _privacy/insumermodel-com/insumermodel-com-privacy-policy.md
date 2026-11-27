---
api_specs:
- filename: insumermodel-com-agent-commerce-protocols-api-openapi.yml
  format: yaml
  label: insumermodel-com Agent Commerce Protocols API
  slug: insumermodel-com-agent-commerce-protocols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-agent-commerce-protocols-api-openapi.yml
- filename: insumermodel-com-agent-onboarding-api-openapi.yml
  format: yaml
  label: insumermodel-com Agent Onboarding API
  slug: insumermodel-com-agent-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-agent-onboarding-api-openapi.yml
- filename: insumermodel-com-discounts-codes-api-openapi.yml
  format: yaml
  label: insumermodel-com Discounts & Codes API
  slug: insumermodel-com-discounts-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-discounts-codes-api-openapi.yml
- filename: insumermodel-com-discovery-api-openapi.yml
  format: yaml
  label: insumermodel-com Discovery API
  slug: insumermodel-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-discovery-api-openapi.yml
- filename: insumermodel-com-keys-billing-api-openapi.yml
  format: yaml
  label: insumermodel-com Keys & Billing API
  slug: insumermodel-com-keys-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-keys-billing-api-openapi.yml
- filename: insumermodel-com-merchant-setup-api-openapi.yml
  format: yaml
  label: insumermodel-com Merchant Setup API
  slug: insumermodel-com-merchant-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-merchant-setup-api-openapi.yml
- filename: insumermodel-com-platform-api-openapi.yml
  format: yaml
  label: insumermodel-com Platform API
  slug: insumermodel-com-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-platform-api-openapi.yml
- filename: insumermodel-com-point-of-sale-api-openapi.yml
  format: yaml
  label: insumermodel-com Point of Sale API
  slug: insumermodel-com-point-of-sale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-point-of-sale-api-openapi.yml
- filename: insumermodel-com-trust-fact-profiles-api-openapi.yml
  format: yaml
  label: insumermodel-com Trust Fact Profiles API
  slug: insumermodel-com-trust-fact-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-trust-fact-profiles-api-openapi.yml
- filename: insumermodel-com-wallet-auth-api-openapi.yml
  format: yaml
  label: insumermodel-com Wallet Auth API
  slug: insumermodel-com-wallet-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insumermodel-com/openapi/insumermodel-com-wallet-auth-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: If you contact us, we may collect your name, email address, and message content.
  - category: identifying
    text: When you connect a cryptocurrency wallet, we read your public wallet address to verify token holdings.
  - category: behavioral
    text: We may collect information about how you interact with the Platform, including scan logs, timestamps, and discount applications.
  - category: device
    text: Browser type, operating system, and device identifiers.
  - category: financial
    text: For crypto credit purchases (USDC), we store the transaction hash, sender wallet address, chain, and amount, for payment verification and fraud prevention.
  deletion:
    route: Email support@insumermodel.com with your request
    text: 'Deletion: Request deletion of your information, subject to legal retention requirements.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Evaluate wallet conditions
    text: Evaluate wallet conditions and return signed results to API callers
  - purpose: Verify token ownership
    text: Verify token ownership for discount eligibility
  - purpose: Prevent fraud and security
    text: Prevent fraud and ensure platform security
  retention:
  - period: 30 days
    scope: Standard platform request logs
    text: Standard platform request logs, which do not include request contents, are retained for 30 days and then deleted.
  - period: 24 hours
    scope: Rate limit records
    text: Rate limit records are purged after 24 hours.
  - period: 12 months
    scope: Partner pass tap records
    text: tap records are deleted 12 months after the tap
  rights:
  - right: Access
    text: 'Access: Request a copy of the information we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate information.'
  - right: Deletion
    text: 'Deletion: Request deletion of your information, subject to legal retention requirements.'
  - right: Disconnect wallet
    text: 'Disconnect: You can disconnect your wallet at any time, which stops us from reading your token holdings.'
  role:
    text: which is the controller of the personal information described in this Privacy Policy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to and processed in countries other than your own.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: insumermodel-com
provenance_date: '2026-11-09'
provider_name: insumermodel-com
provider_slug: insumermodel-com
slug: insumermodel-com-privacy-policy
source_date: '2026-11-09'
source_filename: insumermodel-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://insumermodel.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: insumermodel-com\naid: insumermodel-com\nurl: https://insumermodel.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: which is the controller of the personal information described in this Privacy Policy\ndata_categories:\n- category: contact\n  text: If you contact us, we may collect your name, email address, and message content.\n- category: identifying\n  text: When you connect a cryptocurrency wallet, we read your public wallet address to verify token holdings.\n- category: behavioral\n  text: We may collect information about how you interact with the Platform, including\
  \ scan logs, timestamps, and\n    discount applications.\n- category: device\n  text: Browser type, operating system, and device identifiers.\n- category: financial\n  text: For crypto credit purchases (USDC), we store the transaction hash, sender wallet address, chain, and amount,\n    for payment verification and fraud prevention.\npurposes:\n- purpose: Evaluate wallet conditions\n  text: Evaluate wallet conditions and return signed results to API callers\n- purpose: Verify token ownership\n  text: Verify token ownership for discount eligibility\n- purpose: Prevent fraud and security\n  text: Prevent fraud and ensure platform security\nretention:\n- scope: Standard platform request logs\n  period: 30 days\n  text: Standard platform request logs, which do not include request contents, are retained for 30 days and then\n    deleted.\n- scope: Rate limit records\n  period: 24 hours\n  text: Rate limit records are purged after 24 hours.\n- scope: Partner pass tap records\n  period: 12 months\n\
  \  text: tap records are deleted 12 months after the tap\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to and processed in countries other than your own.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@insumermodel.com with your request\n  text: 'Deletion: Request deletion of your information, subject to legal retention requirements.'\nrights:\n- right: Access\n  text: 'Access: Request a copy of the information we hold about you.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate information.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your information, subject to legal retention requirements.'\n- right: Disconnect wallet\n  text: 'Disconnect: You can disconnect your wallet at any time, which stops us from reading your token holdings.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/insumermodel-com/privacy/insumermodel-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from insumermodel-com's own page on 2026-11-09.
synthetic: false
tags:
- Wallet Auth
- Blockchain
- AI Agents
- Condition-Based Access
- Cryptocurrency
- Developer Tools
---
