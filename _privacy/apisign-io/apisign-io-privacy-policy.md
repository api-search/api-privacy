---
api_specs:
- filename: apisign-io-api-keys-api-openapi.yml
  format: yaml
  label: APISign API Keys API
  slug: apisign-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-api-keys-api-openapi.yml
- filename: apisign-io-contracts-api-openapi.yml
  format: yaml
  label: APISign Contracts API
  slug: apisign-io-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-contracts-api-openapi.yml
- filename: apisign-io-health-api-openapi.yml
  format: yaml
  label: APISign Health API
  slug: apisign-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-health-api-openapi.yml
- filename: apisign-io-organization-api-openapi.yml
  format: yaml
  label: APISign Organization API
  slug: apisign-io-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-organization-api-openapi.yml
- filename: apisign-io-templates-api-openapi.yml
  format: yaml
  label: APISign Templates API
  slug: apisign-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-templates-api-openapi.yml
- filename: apisign-io-webhooks-api-openapi.yml
  format: yaml
  label: APISign Webhooks API
  slug: apisign-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apisign-io/openapi/apisign-io-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address
  - category: financial
    text: Payment information (processed securely by Stripe)
  - category: device
    text: Browser and device information for audit purposes
  - category: location
    text: IP addresses of signers at time of signature
  - category: behavioral
    text: API usage data (endpoints accessed, request timestamps)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve service
    text: Provide, maintain, and improve our Service
  - purpose: Transactional emails
    text: Send transactional emails (contract notifications, receipts)
  - purpose: Fraud and technical issues
    text: Detect, prevent, and address technical issues and fraud
  - purpose: Audit trails
    text: Maintain audit trails for legal validity of signatures
  retention:
  - period: while your account is active
    scope: Account data
    text: 'Account data: Retained while your account is active'
  - period: the duration of your account plus 7 years
    scope: Documents and signatures
    text: 'Documents and signatures: Retained for the duration of your account plus 7 years for legal compliance'
  - period: 7 years
    scope: Audit logs
    text: 'Audit logs: Retained for 7 years to ensure legal validity of signatures'
  - period: up to 2 years
    scope: Usage logs
    text: 'Usage logs: Retained for up to 2 years'
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Correction
    text: 'Correction: Request correction of inaccurate data'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data'
  - right: Portability
    text: 'Portability: Request transfer of your data'
  - right: Objection
    text: 'Objection: Object to certain processing activities'
  - right: Restriction
    text: 'Restriction: Request restriction of processing'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for such transfers, including standard contractual clauses approved by relevant authorities.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: APISign
provenance_date: '2026-11-09'
provider_name: APISign
provider_slug: apisign-io
slug: apisign-io-privacy-policy
source_date: '2026-11-09'
source_filename: apisign-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apisign.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: APISign\naid: apisign-io\nurl: https://apisign.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and email address\n- category: financial\n  text: Payment information (processed securely by Stripe)\n- category: device\n  text: Browser and device information for audit purposes\n- category: location\n  text: IP addresses of signers at time of signature\n- category: behavioral\n  text: API usage data (endpoints accessed, request timestamps)\npurposes:\n- purpose: Provide and improve service\n  text: Provide, maintain, and improve\
  \ our Service\n- purpose: Transactional emails\n  text: Send transactional emails (contract notifications, receipts)\n- purpose: Fraud and technical issues\n  text: Detect, prevent, and address technical issues and fraud\n- purpose: Audit trails\n  text: Maintain audit trails for legal validity of signatures\nretention:\n- scope: Account data\n  period: while your account is active\n  text: 'Account data: Retained while your account is active'\n- scope: Documents and signatures\n  period: the duration of your account plus 7 years\n  text: 'Documents and signatures: Retained for the duration of your account plus 7 years for legal compliance'\n- scope: Audit logs\n  period: 7 years\n  text: 'Audit logs: Retained for 7 years to ensure legal validity of signatures'\n- scope: Usage logs\n  period: up to 2 years\n  text: 'Usage logs: Retained for up to 2 years'\nresidency: []\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place for such transfers, including\
  \ standard contractual clauses\n    approved by relevant authorities.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate data'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data'\n- right: Portability\n  text: 'Portability: Request transfer of your data'\n- right: Objection\n  text: 'Objection: Object to certain processing activities'\n- right: Restriction\n  text: 'Restriction: Request restriction of processing'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/apisign-io/privacy/apisign-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from APISign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Artificial Intelligence
- MCP
- Contracts
- Developer Platform
---
