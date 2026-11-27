---
api_specs:
- filename: docsmint-com-admin-api-openapi.yml
  format: yaml
  label: docsmint-com Admin API
  slug: docsmint-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-admin-api-openapi.yml
- filename: docsmint-com-attachments-api-openapi.yml
  format: yaml
  label: docsmint-com Attachments API
  slug: docsmint-com-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-attachments-api-openapi.yml
- filename: docsmint-com-auth-api-openapi.yml
  format: yaml
  label: docsmint-com Auth API
  slug: docsmint-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-auth-api-openapi.yml
- filename: docsmint-com-categories-api-openapi.yml
  format: yaml
  label: docsmint-com Categories API
  slug: docsmint-com-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-categories-api-openapi.yml
- filename: docsmint-com-csrf-token-api-openapi.yml
  format: yaml
  label: docsmint-com Csrf Token API
  slug: docsmint-com-csrf-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-csrf-token-api-openapi.yml
- filename: docsmint-com-documents-api-openapi.yml
  format: yaml
  label: docsmint-com Documents API
  slug: docsmint-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-documents-api-openapi.yml
- filename: docsmint-com-folders-api-openapi.yml
  format: yaml
  label: docsmint-com Folders API
  slug: docsmint-com-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-folders-api-openapi.yml
- filename: docsmint-com-graph-api-openapi.yml
  format: yaml
  label: docsmint-com Graph API
  slug: docsmint-com-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-graph-api-openapi.yml
- filename: docsmint-com-health-api-openapi.yml
  format: yaml
  label: docsmint-com Health API
  slug: docsmint-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-health-api-openapi.yml
- filename: docsmint-com-keys-api-openapi.yml
  format: yaml
  label: docsmint-com Keys API
  slug: docsmint-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-keys-api-openapi.yml
- filename: docsmint-com-plugins-api-openapi.yml
  format: yaml
  label: docsmint-com Plugins API
  slug: docsmint-com-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-plugins-api-openapi.yml
- filename: docsmint-com-search-api-openapi.yml
  format: yaml
  label: docsmint-com Search API
  slug: docsmint-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-search-api-openapi.yml
- filename: docsmint-com-share-api-openapi.yml
  format: yaml
  label: docsmint-com Share API
  slug: docsmint-com-share-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-share-api-openapi.yml
- filename: docsmint-com-tags-api-openapi.yml
  format: yaml
  label: docsmint-com Tags API
  slug: docsmint-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-tags-api-openapi.yml
- filename: docsmint-com-trash-api-openapi.yml
  format: yaml
  label: docsmint-com Trash API
  slug: docsmint-com-trash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-trash-api-openapi.yml
- filename: docsmint-com-webhooks-api-openapi.yml
  format: yaml
  label: docsmint-com Webhooks API
  slug: docsmint-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docsmint-com/openapi/docsmint-com-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: We receive account and identity data such as name, email, verification status, and session records
  - category: financial
    text: billing and subscription references from Stripe when enabled
  - category: communication
    text: support messages
  - category: device
    text: technical data such as IP address, request identifiers, browser information, security events, and service logs
  - category: behavioral
    text: first-party campaign attribution; consent and preference records
  deletion:
    route: Email docs@webs.cool from the account address and describe the request.
    text: Email docs@webs.cool from the account address and describe the request.
  dpa:
    available: true
    text: Article 28 DPA terms for business customers.
    url: https://docsmint.com/dpa
  purposes:
  - purpose: provide accounts, documents, search, sharing, imports, support, and AI features
    text: We process data to provide accounts, documents, search, sharing, imports, support, and requested AI features
  - purpose: secure and troubleshoot the Service
    text: secure and troubleshoot the Service; prevent abuse; administer subscriptions
  - purpose: improve reliability
    text: and improve reliability
  residency:
  - region: Germany
    text: The current hosted SaaS runs on Contabo infrastructure in Germany.
  retention:
  - period: 30 days
    scope: Account data and documents
    text: while the account is active, then deletion from live systems targeted within 30 days after a valid deletion request, subject to legal holds and service dependencies
  - period: 30 days
    scope: PostgreSQL backups
    text: 'PostgreSQL backups: no more than 30 days where a backup scheduler is configured.'
  - period: 12 months
    scope: Security and access logs
    text: 'Security and access logs: up to 12 months unless needed longer for an active investigation or legal claim.'
  - period: 30 days
    scope: AI result payloads
    text: 'AI result payloads: policy target of 30 days; AI run metadata: policy target of 90 days.'
  - period: 10 years
    scope: Billing and tax records
    text: 'Billing and tax records: up to 10 years where required by Portuguese law.'
  - period: 24 months
    scope: Support correspondence
    text: 'Support correspondence: up to 24 months after resolution.'
  rights:
  - right: access
    text: you may request access, correction, deletion, restriction, portability, or objection
  - right: withdraw consent
    text: withdraw consent
  - right: complain to supervisory authority
    text: You may complain to Portugal's supervisory authority, the Comissão Nacional de Proteção de Dados (CNPD), at https://www.cnpd.pt/
  role:
    text: Vladislav Galibov, Cabanas de Tavira, Portugal, is the data controller for account administration, billing, security, support, and operation of the hosted DocsMint service.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not currently sell personal information, share it for cross-context behavioural advertising, or use it for targeted advertising.
  subprocessors:
    text: The current code-default model families are disclosed in the Subprocessors & DPA tab
    url: https://docsmint.com/subprocessors
  transfers:
  - mechanism: SCC
    text: Where required, we use an adequacy decision, the European Commission's Standard Contractual Clauses, supplementary measures, or an EU-only provider configuration.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: docsmint-com
provenance_date: '2026-11-09'
provider_name: docsmint-com
provider_slug: docsmint-com
slug: docsmint-com-privacy-policy
source_date: '2026-11-09'
source_filename: docsmint-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docsmint.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: docsmint-com\naid: docsmint-com\nurl: https://docsmint.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Vladislav Galibov, Cabanas de Tavira, Portugal, is the data controller for account administration, billing,\n    security, support, and operation of the hosted DocsMint service.\ndata_categories:\n- category: identifying\n  text: We receive account and identity data such as name, email, verification status, and session records\n- category: financial\n  text: billing and subscription references from Stripe when enabled\n- category: communication\n  text: support messages\n- category:\
  \ device\n  text: technical data such as IP address, request identifiers, browser information, security events, and service\n    logs\n- category: behavioral\n  text: first-party campaign attribution; consent and preference records\npurposes:\n- purpose: provide accounts, documents, search, sharing, imports, support, and AI features\n  text: We process data to provide accounts, documents, search, sharing, imports, support, and requested AI features\n- purpose: secure and troubleshoot the Service\n  text: secure and troubleshoot the Service; prevent abuse; administer subscriptions\n- purpose: improve reliability\n  text: and improve reliability\nretention:\n- scope: Account data and documents\n  period: 30 days\n  text: while the account is active, then deletion from live systems targeted within 30 days after a valid deletion\n    request, subject to legal holds and service dependencies\n- scope: PostgreSQL backups\n  period: 30 days\n  text: 'PostgreSQL backups: no more than 30 days where\
  \ a backup scheduler is configured.'\n- scope: Security and access logs\n  period: 12 months\n  text: 'Security and access logs: up to 12 months unless needed longer for an active investigation or legal claim.'\n- scope: AI result payloads\n  period: 30 days\n  text: 'AI result payloads: policy target of 30 days; AI run metadata: policy target of 90 days.'\n- scope: Billing and tax records\n  period: 10 years\n  text: 'Billing and tax records: up to 10 years where required by Portuguese law.'\n- scope: Support correspondence\n  period: 24 months\n  text: 'Support correspondence: up to 24 months after resolution.'\nresidency:\n- region: Germany\n  text: The current hosted SaaS runs on Contabo infrastructure in Germany.\ntransfers:\n- mechanism: SCC\n  text: Where required, we use an adequacy decision, the European Commission's Standard Contractual Clauses, supplementary\n    measures, or an EU-only provider configuration.\nsubprocessors:\n  url: https://docsmint.com/subprocessors\n  text:\
  \ The current code-default model families are disclosed in the Subprocessors & DPA tab\ndpa:\n  available: true\n  url: https://docsmint.com/dpa\n  text: Article 28 DPA terms for business customers.\ndeletion:\n  route: Email docs@webs.cool from the account address and describe the request.\n  text: Email docs@webs.cool from the account address and describe the request.\nrights:\n- right: access\n  text: you may request access, correction, deletion, restriction, portability, or objection\n- right: withdraw consent\n  text: withdraw consent\n- right: complain to supervisory authority\n  text: You may complain to Portugal's supervisory authority, the Comissão Nacional de Proteção de Dados (CNPD),\n    at https://www.cnpd.pt/\nsale_or_sharing:\n  stance: prohibited\n  text: We do not currently sell personal information, share it for cross-context behavioural advertising, or use\n    it for targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/docsmint-com/privacy/docsmint-com-privacy-policy.yml
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
- sale_or_sharing
summary_line: 24 quoted statements, read from docsmint-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Document Management
- Knowledge Base
- Software-as-a-Service
- Collaboration
---
