---
api_specs:
- filename: createprints-ai-account-api-openapi.yml
  format: yaml
  label: Create Prints Account API
  slug: createprints-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-account-api-openapi.yml
- filename: createprints-ai-artwork-api-openapi.yml
  format: yaml
  label: Create Prints Artwork API
  slug: createprints-ai-artwork-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-artwork-api-openapi.yml
- filename: createprints-ai-checkout-api-openapi.yml
  format: yaml
  label: Create Prints Checkout API
  slug: createprints-ai-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-checkout-api-openapi.yml
- filename: createprints-ai-orders-api-openapi.yml
  format: yaml
  label: Create Prints Orders API
  slug: createprints-ai-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-orders-api-openapi.yml
- filename: createprints-ai-product-discovery-api-openapi.yml
  format: yaml
  label: Create Prints Product discovery API
  slug: createprints-ai-product-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-product-discovery-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: email address, account ID, authentication-provider identifiers, and account settings.'
  - category: contact
    text: 'Order and delivery information: customer and recipient names, email address, delivery address, telephone number where supplied'
  - category: financial
    text: We receive transaction status, payment references, and limited billing information, but we do not store full payment-card numbers.
  - category: location
    text: 'Room analysis information: when you ask us to suggest artwork for a room, we analyse any room photograph you provide in order to measure its colour palette.'
  - category: device
    text: 'Service and device data: IP address, user-agent, referring URL, timestamps, API or MCP tool calls, response and error codes, authentication events, device information, and security logs.'
  - category: communication
    text: 'Communications and partner information: support messages'
  deletion:
    route: Email to privacy contact
    text: To exercise one, email [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract performance
    text: 'Contract: to create and manage accounts, generate artwork, publish website generations as described above, suggest and score artwork for a room you describe or photograph, process orders, take payment, manufacture and deliver products'
  - purpose: Legal obligation
    text: 'Legal obligation: to keep accounting and transaction records, respond to lawful requests, protect consumer rights'
  - purpose: Legitimate interests
    text: 'Legitimate interests: to secure and troubleshoot the Service, prevent fraud and abuse, enforce our Terms, answer support requests, understand service performance, and improve reliability.'
  - purpose: Consent-based marketing and tracking
    text: 'Consent: where we specifically ask for consent, such as for optional electronic marketing or non-essential tracking.'
  - purpose: Matching artwork to a room
    text: 'We do build and train our own models for one specific purpose: matching artwork to a room.'
  residency:
  - region: Outside the United Kingdom
    text: Some providers and production facilities process information outside the United Kingdom, including in the United States and other service regions.
  retention:
  - period: null
    scope: Account information
    text: account information is kept while the account is active and afterwards only for as long as needed to close the account, resolve disputes, and meet legal obligations
  - period: up to six years
    scope: Order, payment, tax and partner-payout records
    text: which will normally be up to six years after the relevant transaction or the end of the relevant accounting period
  - period: null
    scope: Room analysis information
    text: When you delete your account we anonymise this information rather than erase it
  - period: null
    scope: Security logs, support records, unsuccessful partner applications
    text: security logs, support records, and unsuccessful partner applications are kept only for as long as reasonably needed for their purpose
  rights:
  - right: Access
    text: access and receive a copy of your personal information
  - right: Correction
    text: correct inaccurate or incomplete information
  - right: Deletion or restriction
    text: request deletion or restriction of processing
  - right: Portability
    text: receive certain information in a portable format
  - right: Objection
    text: object to processing based on legitimate interests
  - right: Withdraw consent
    text: withdraw consent without affecting earlier lawful processing
  role:
    text: Viable Digital Limited is the controller of this information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioural advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we use an applicable adequacy regulation or contractual safeguard such as the UK International Data Transfer Agreement or UK Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Create Prints
provenance_date: '2026-11-09'
provider_name: Create Prints
provider_slug: createprints-ai
slug: createprints-ai-privacy-policy
source_date: '2026-11-09'
source_filename: createprints-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.createprints.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Create Prints\naid: createprints-ai\nurl: https://www.createprints.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Viable Digital Limited is the controller of this information.\ndata_categories:\n- category: identifying\n  text: 'Account information: email address, account ID, authentication-provider identifiers, and account settings.'\n- category: contact\n  text: 'Order and delivery information: customer and recipient names, email address, delivery address, telephone\n    number where supplied'\n- category: financial\n  text: We receive transaction status, payment references,\
  \ and limited billing information, but we do not store\n    full payment-card numbers.\n- category: location\n  text: 'Room analysis information: when you ask us to suggest artwork for a room, we analyse any room photograph\n    you provide in order to measure its colour palette.'\n- category: device\n  text: 'Service and device data: IP address, user-agent, referring URL, timestamps, API or MCP tool calls, response\n    and error codes, authentication events, device information, and security logs.'\n- category: communication\n  text: 'Communications and partner information: support messages'\npurposes:\n- purpose: Contract performance\n  text: 'Contract: to create and manage accounts, generate artwork, publish website generations as described above,\n    suggest and score artwork for a room you describe or photograph, process orders, take payment, manufacture and\n    deliver products'\n- purpose: Legal obligation\n  text: 'Legal obligation: to keep accounting and transaction records,\
  \ respond to lawful requests, protect consumer\n    rights'\n- purpose: Legitimate interests\n  text: 'Legitimate interests: to secure and troubleshoot the Service, prevent fraud and abuse, enforce our Terms,\n    answer support requests, understand service performance, and improve reliability.'\n- purpose: Consent-based marketing and tracking\n  text: 'Consent: where we specifically ask for consent, such as for optional electronic marketing or non-essential\n    tracking.'\n- purpose: Matching artwork to a room\n  text: 'We do build and train our own models for one specific purpose: matching artwork to a room.'\nretention:\n- scope: Account information\n  period: null\n  text: account information is kept while the account is active and afterwards only for as long as needed to close\n    the account, resolve disputes, and meet legal obligations\n- scope: Order, payment, tax and partner-payout records\n  period: up to six years\n  text: which will normally be up to six years after the relevant\
  \ transaction or the end of the relevant accounting\n    period\n- scope: Room analysis information\n  period: null\n  text: When you delete your account we anonymise this information rather than erase it\n- scope: Security logs, support records, unsuccessful partner applications\n  period: null\n  text: security logs, support records, and unsuccessful partner applications are kept only for as long as reasonably\n    needed for their purpose\nresidency:\n- region: Outside the United Kingdom\n  text: Some providers and production facilities process information outside the United Kingdom, including in the\n    United States and other service regions.\ntransfers:\n- mechanism: other\n  text: we use an applicable adequacy regulation or contractual safeguard such as the UK International Data Transfer\n    Agreement or UK Addendum\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to privacy contact\n  text: To exercise one,\
  \ email [email protected] .\nrights:\n- right: Access\n  text: access and receive a copy of your personal information\n- right: Correction\n  text: correct inaccurate or incomplete information\n- right: Deletion or restriction\n  text: request deletion or restriction of processing\n- right: Portability\n  text: receive certain information in a portable format\n- right: Objection\n  text: object to processing based on legitimate interests\n- right: Withdraw consent\n  text: withdraw consent without affecting earlier lawful processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/createprints-ai/privacy/createprints-ai-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Create Prints's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Art
- Generative AI
- Art Prints
- Print on Demand
- E-Commerce
- Interior Design
- MCP
---
