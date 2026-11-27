---
api_specs:
- filename: fasten-health-bridge-api-openapi.yml
  format: yaml
  label: Fasten Health Bridge API
  slug: fasten-health-bridge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fasten-health/openapi/fasten-health-bridge-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: an individual’s name, address, email address, phone number, or social security number
  - category: contact
    text: email address, phone number
  - category: health
    text: diagnostic, treatment, and billing information
  - category: device
    text: IP address, device type, operating system, unique device identifiers, browser information, crash data
  - category: behavioral
    text: which features you use and how you use them
  - category: financial
    text: financial information related to payment for healthcare services
  deletion:
    route: Email request to [email protected]
    text: Upon your request, Fasten Health will permanently delete 100% of your personal information, including all associated data stored on our systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To respond promptly to your requests, provide efficient customer support, and deliver the services you have signed up for.
  - purpose: Communication
    text: To contact you via email, phone, or postal mail about updates, security alerts, and product offerings related to Fasten Connect.
  - purpose: Research and development
    text: To better understand your needs and interests, leading to enhanced features and new product development.
  - purpose: Legal compliance and protection
    text: To comply with legal obligations, prevent fraud, protect our digital and physical assets, and defend our legal rights or manage disputes where necessary.
  retention:
  - period: 24 hours
    scope: Health information shared through Fasten Connect
    text: This data is automatically deleted within 24 hours after successful transmission.
  rights:
  - right: Access
    text: Access to a copy of your Personal Information or Protected Health Information stored on our systems
  - right: Deletion
    text: Deletion of your data from our systems
  - right: Revoke consent
    text: Revocation of your consent for Fasten Health to maintain, use, or disclose your data, to the extent applicable to your relationship with us
  - right: Download in machine-readable format
    text: Download your individually identifiable information in a machine-readable format.
  - right: Opt out of disclosure
    text: You have the right to opt out of having your Personal Information disclosed.
  role:
    text: Fasten Health, Inc. (“Fasten Health,” “we,” “us,” or “our”) collects, uses, shares, and protects your personal information when you use Fasten Connect.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your personal information, ever.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fasten Health
provenance_date: '2026-11-09'
provider_name: Fasten Health
provider_slug: fasten-health
slug: fasten-health-privacy-policy
source_date: '2026-11-09'
source_filename: fasten-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policy.fastenhealth.com/connect/privacy_policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fasten Health\naid: fasten-health\nurl: https://policy.fastenhealth.com/connect/privacy_policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Fasten Health, Inc. (“Fasten Health,” “we,” “us,” or “our”) collects, uses, shares, and protects your personal\n    information when you use Fasten Connect.\ndata_categories:\n- category: identifying\n  text: an individual’s name, address, email address, phone number, or social security number\n- category: contact\n  text: email address, phone number\n- category: health\n  text: diagnostic, treatment, and billing information\n- category: device\n\
  \  text: IP address, device type, operating system, unique device identifiers, browser information, crash data\n- category: behavioral\n  text: which features you use and how you use them\n- category: financial\n  text: financial information related to payment for healthcare services\npurposes:\n- purpose: Service delivery\n  text: To respond promptly to your requests, provide efficient customer support, and deliver the services you have\n    signed up for.\n- purpose: Communication\n  text: To contact you via email, phone, or postal mail about updates, security alerts, and product offerings related\n    to Fasten Connect.\n- purpose: Research and development\n  text: To better understand your needs and interests, leading to enhanced features and new product development.\n- purpose: Legal compliance and protection\n  text: To comply with legal obligations, prevent fraud, protect our digital and physical assets, and defend our\n    legal rights or manage disputes where necessary.\nretention:\n\
  - scope: Health information shared through Fasten Connect\n  period: 24 hours\n  text: This data is automatically deleted within 24 hours after successful transmission.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to [email protected]\n  text: Upon your request, Fasten Health will permanently delete 100% of your personal information, including all\n    associated data stored on our systems.\nrights:\n- right: Access\n  text: Access to a copy of your Personal Information or Protected Health Information stored on our systems\n- right: Deletion\n  text: Deletion of your data from our systems\n- right: Revoke consent\n  text: Revocation of your consent for Fasten Health to maintain, use, or disclose your data, to the extent applicable\n    to your relationship with us\n- right: Download in machine-readable format\n  text: Download your individually identifiable information in\
  \ a machine-readable format.\n- right: Opt out of disclosure\n  text: You have the right to opt out of having your Personal Information disclosed.\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your personal information, ever.\n"
source_yaml_url: https://artifacts.apis.io/fasten-health/privacy/fasten-health-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Fasten Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Personal Health Record
- Electronic Medical Record
- Health Data Interoperability
- TEFCA
- EHI Export
- Patient Consent
- Self-Hosted
- Open Source
- HL7
- Healthcare Connectivity
- A2A
---
