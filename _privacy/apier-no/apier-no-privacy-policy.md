---
api_specs:
- filename: apier-no-account-api-openapi.yml
  format: yaml
  label: Apier.no Account API
  slug: apier-no-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-account-api-openapi.yml
- filename: apier-no-actions-api-openapi.yml
  format: yaml
  label: Apier.no Actions API
  slug: apier-no-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-actions-api-openapi.yml
- filename: apier-no-admin-api-openapi.yml
  format: yaml
  label: Apier.no Admin API
  slug: apier-no-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-admin-api-openapi.yml
- filename: apier-no-altinn-api-openapi.yml
  format: yaml
  label: Apier.no Altinn API
  slug: apier-no-altinn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-altinn-api-openapi.yml
- filename: apier-no-auth-gateway-api-openapi.yml
  format: yaml
  label: Apier.no Auth Gateway API
  slug: apier-no-auth-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-auth-gateway-api-openapi.yml
- filename: apier-no-brreg-api-openapi.yml
  format: yaml
  label: Apier.no Brreg API
  slug: apier-no-brreg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-brreg-api-openapi.yml
- filename: apier-no-changes-api-openapi.yml
  format: yaml
  label: Apier.no Changes API
  slug: apier-no-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-changes-api-openapi.yml
- filename: apier-no-company-api-openapi.yml
  format: yaml
  label: Apier.no Company API
  slug: apier-no-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-company-api-openapi.yml
- filename: apier-no-discovery-api-openapi.yml
  format: yaml
  label: Apier.no Discovery API
  slug: apier-no-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-discovery-api-openapi.yml
- filename: apier-no-fullmakt-api-openapi.yml
  format: yaml
  label: Apier.no Fullmakt API
  slug: apier-no-fullmakt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-fullmakt-api-openapi.yml
- filename: apier-no-infrastructure-api-openapi.yml
  format: yaml
  label: Apier.no Infrastructure API
  slug: apier-no-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-infrastructure-api-openapi.yml
- filename: apier-no-knowledge-api-openapi.yml
  format: yaml
  label: Apier.no Knowledge API
  slug: apier-no-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-knowledge-api-openapi.yml
- filename: apier-no-privacy-api-openapi.yml
  format: yaml
  label: Apier.no Privacy API
  slug: apier-no-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-privacy-api-openapi.yml
- filename: apier-no-public-api-openapi.yml
  format: yaml
  label: Apier.no Public API
  slug: apier-no-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-public-api-openapi.yml
- filename: apier-no-sandbox-api-openapi.yml
  format: yaml
  label: Apier.no Sandbox API
  slug: apier-no-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-sandbox-api-openapi.yml
- filename: apier-no-subscriptions-api-openapi.yml
  format: yaml
  label: Apier.no Subscriptions API
  slug: apier-no-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apier-no/openapi/apier-no-subscriptions-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: your email address, used for sign-in via magic link.'
  - category: identifying
    text: 'Role holders from Brønnøysundregistrene: the names of people registered with roles in Norwegian businesses'
  - category: device
    text: 'Usage and technical data: IP address, timestamps, request metadata and logs generated when you use the service.'
  - category: behavioral
    text: 'Audit and traceability data: Apier keeps an append-only audit log of actions in the service, for example lookups, account changes and top-ups.'
  - category: professional
    text: Business details you provide, for example an organisation number and contact details linked to your account.
  deletion:
    route: Self-service API
    text: You can delete your account and its associated account data yourself via the self-service API (DELETE /api/v1/account) while signed in.
  dpa:
    available: true
    text: To provide the service we use certain subprocessors that process personal data on our behalf; with those we have a data processing agreement in place.
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service you have requested — creating and managing your account, authenticating sign-in and answering your requests.
  - purpose: Audit log
    text: To maintain a traceable, append-only audit log so that actions can be documented and verified.
  - purpose: Security and operations
    text: For security, operations, troubleshooting and abuse prevention.
  - purpose: Answer who may bind a business
    text: To answer who may bind a Norwegian business, with the names of its registered role holders.
  residency:
  - region: EU (Stockholm, eu-north-1)
    text: Personal data is stored in the EU (eu-north-1, Stockholm).
  retention:
  - period: null
    scope: Account data
    text: We keep account data for as long as you have an active account, and delete or anonymise it within a reasonable time after the account is closed, unless we are legally required to keep it longer.
  - period: 12 months
    scope: Change log
    text: The change log is anonymised after 12 months.
  - period: 24 months
    scope: MCP tool query log
    text: The MCP tool query log is deleted after 24 months, and the API request logs after 30 days.
  - period: 30 days
    scope: API request logs
    text: The MCP tool query log is deleted after 24 months, and the API request logs after 30 days.
  rights:
  - right: Access, rectification, erasure
    text: Under the GDPR you have the right to access, rectify and erase personal data about you
  - right: Restriction and objection
    text: and to request restriction of or object to processing
  - right: Portability
    text: as well as the right to data portability (Articles 15 to 22)
  - right: Complain to authority
    text: You also have the right to lodge a complaint with the Norwegian Data Protection Authority (Datatilsynet, www.datatilsynet.no)
  role:
    text: Grov Digital is the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Supabase — primary database and storage (stored in the EU, eu-north-1 Stockholm). Vercel — build and hosting of the application (server functions run in Stockholm).
    url: null
  transfers:
  - mechanism: SCC
    text: Where personal data is transferred outside the EU/EEA, this is done on the basis of the EU Standard Contractual Clauses or the EU–US Data Privacy Framework
  - mechanism: DPF
    text: Where personal data is transferred outside the EU/EEA, this is done on the basis of the EU Standard Contractual Clauses or the EU–US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apier.no
provenance_date: '2026-11-09'
provider_name: Apier.no
provider_slug: apier-no
slug: apier-no-privacy-policy
source_date: '2026-11-09'
source_filename: apier-no-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.apier.no/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apier.no\naid: apier-no\nurl: https://www.apier.no/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Grov Digital is the data controller for the personal data described here.\ndata_categories:\n- category: contact\n  text: 'Account data: your email address, used for sign-in via magic link.'\n- category: identifying\n  text: 'Role holders from Brønnøysundregistrene: the names of people registered with roles in Norwegian businesses'\n- category: device\n  text: 'Usage and technical data: IP address, timestamps, request metadata and logs generated when you use the\n    service.'\n- category:\
  \ behavioral\n  text: 'Audit and traceability data: Apier keeps an append-only audit log of actions in the service, for example\n    lookups, account changes and top-ups.'\n- category: professional\n  text: Business details you provide, for example an organisation number and contact details linked to your account.\npurposes:\n- purpose: Provide the service\n  text: To provide the service you have requested — creating and managing your account, authenticating sign-in and\n    answering your requests.\n- purpose: Audit log\n  text: To maintain a traceable, append-only audit log so that actions can be documented and verified.\n- purpose: Security and operations\n  text: For security, operations, troubleshooting and abuse prevention.\n- purpose: Answer who may bind a business\n  text: To answer who may bind a Norwegian business, with the names of its registered role holders.\nretention:\n- scope: Account data\n  period: null\n  text: We keep account data for as long as you have an active account,\
  \ and delete or anonymise it within a reasonable\n    time after the account is closed, unless we are legally required to keep it longer.\n- scope: Change log\n  period: 12 months\n  text: The change log is anonymised after 12 months.\n- scope: MCP tool query log\n  period: 24 months\n  text: The MCP tool query log is deleted after 24 months, and the API request logs after 30 days.\n- scope: API request logs\n  period: 30 days\n  text: The MCP tool query log is deleted after 24 months, and the API request logs after 30 days.\nresidency:\n- region: EU (Stockholm, eu-north-1)\n  text: Personal data is stored in the EU (eu-north-1, Stockholm).\ntransfers:\n- mechanism: SCC\n  text: Where personal data is transferred outside the EU/EEA, this is done on the basis of the EU Standard Contractual\n    Clauses or the EU–US Data Privacy Framework\n- mechanism: DPF\n  text: Where personal data is transferred outside the EU/EEA, this is done on the basis of the EU Standard Contractual\n    Clauses\
  \ or the EU–US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: Supabase — primary database and storage (stored in the EU, eu-north-1 Stockholm). Vercel — build and hosting\n    of the application (server functions run in Stockholm).\ndpa:\n  available: true\n  url: null\n  text: To provide the service we use certain subprocessors that process personal data on our behalf; with those\n    we have a data processing agreement in place.\ndeletion:\n  route: Self-service API\n  text: You can delete your account and its associated account data yourself via the self-service API (DELETE /api/v1/account)\n    while signed in.\nrights:\n- right: Access, rectification, erasure\n  text: Under the GDPR you have the right to access, rectify and erase personal data about you\n- right: Restriction and objection\n  text: and to request restriction of or object to processing\n- right: Portability\n  text: as well as the right to data portability (Articles 15 to 22)\n- right: Complain to authority\n\
  \  text: You also have the right to lodge a complaint with the Norwegian Data Protection Authority (Datatilsynet,\n    www.datatilsynet.no)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apier-no/privacy/apier-no-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 24 quoted statements, read from Apier.no's own page on 2026-11-09.
synthetic: false
tags:
- Norwegian
- Company Data
- MCP
- Verification
---
