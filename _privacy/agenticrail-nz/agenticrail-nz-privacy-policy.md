---
api_specs:
- filename: agenticrail-nz-enforcement-api-openapi.yml
  format: yaml
  label: AgenticRail Enforcement API
  slug: agenticrail-nz-enforcement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticrail-nz/openapi/agenticrail-nz-enforcement-api-openapi.yml
- filename: agenticrail-nz-evidence-api-openapi.yml
  format: yaml
  label: AgenticRail Evidence API
  slug: agenticrail-nz-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticrail-nz/openapi/agenticrail-nz-evidence-api-openapi.yml
- filename: agenticrail-nz-operational-api-openapi.yml
  format: yaml
  label: AgenticRail Operational API
  slug: agenticrail-nz-operational-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticrail-nz/openapi/agenticrail-nz-operational-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Account information (email address, optional name)
  - category: behavioral
    text: System outcomes (ALLOW / HALT / DENY)
  - category: device
    text: Request headers (standard HTTP)
  - category: other
    text: Sequence identifiers (IDs you provide or we generate)
  deletion:
    route: email request to hello@agenticrail.nz
    text: To exercise your rights, contact hello@agenticrail.nz
  dpa:
    available: true
    text: A Data Processing Agreement (DPA) incorporating Standard Contractual Clauses is available at agenticrail.nz/dpa
    url: agenticrail.nz/dpa
  purposes:
  - purpose: enforce sequence and policy rules
    text: enforce sequence and policy rules
  - purpose: prevent replay attacks
    text: prevent replay attacks (nonce validation)
  - purpose: debug errors and improve performance
    text: debug errors and improve performance
  - purpose: measure usage for billing
    text: measure usage for billing
  residency:
  - region: New Zealand
    text: AgenticRail is operated from New Zealand
  - region: multiple countries
    text: uses Cloudflare's global network, which may process data in multiple countries
  retention:
  - period: null
    scope: Enforcement receipts
    text: There is no tiered or automated deletion schedule
  - period: 90 days
    scope: Server and operational logs
    text: retained for 90 days, then automatically deleted
  - period: null
    scope: Account information
    text: retained while the account is active, plus a reasonable period for legal or security purposes
  rights:
  - right: access
    text: access your personal data
  - right: correct
    text: correct inaccurate data
  - right: deletion
    text: request deletion
  - right: restrict or object
    text: restrict or object to processing
  - right: portability
    text: data portability
  role:
    text: In respect of data a Client sends through the gate, AgenticRail is a processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share user data for marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: New Zealand has been recognised by the European Commission as providing an adequate level of data protection
  - mechanism: SCC
    text: For EU users, we rely on Cloudflare's compliance mechanisms, including Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgenticRail
provenance_date: '2026-11-09'
provider_name: AgenticRail
provider_slug: agenticrail-nz
slug: agenticrail-nz-privacy-policy
source_date: '2026-11-09'
source_filename: agenticrail-nz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenticrail.nz/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgenticRail\naid: agenticrail-nz\nurl: https://agenticrail.nz/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In respect of data a Client sends through the gate, AgenticRail is a processor\ndata_categories:\n- category: contact\n  text: Account information (email address, optional name)\n- category: behavioral\n  text: System outcomes (ALLOW / HALT / DENY)\n- category: device\n  text: Request headers (standard HTTP)\n- category: other\n  text: Sequence identifiers (IDs you provide or we generate)\npurposes:\n- purpose: enforce sequence and policy rules\n  text: enforce sequence and policy\
  \ rules\n- purpose: prevent replay attacks\n  text: prevent replay attacks (nonce validation)\n- purpose: debug errors and improve performance\n  text: debug errors and improve performance\n- purpose: measure usage for billing\n  text: measure usage for billing\nretention:\n- scope: Enforcement receipts\n  period: null\n  text: There is no tiered or automated deletion schedule\n- scope: Server and operational logs\n  period: 90 days\n  text: retained for 90 days, then automatically deleted\n- scope: Account information\n  period: null\n  text: retained while the account is active, plus a reasonable period for legal or security purposes\nresidency:\n- region: New Zealand\n  text: AgenticRail is operated from New Zealand\n- region: multiple countries\n  text: uses Cloudflare's global network, which may process data in multiple countries\ntransfers:\n- mechanism: adequacy\n  text: New Zealand has been recognised by the European Commission as providing an adequate level of data protection\n\
  - mechanism: SCC\n  text: For EU users, we rely on Cloudflare's compliance mechanisms, including Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: agenticrail.nz/dpa\n  text: A Data Processing Agreement (DPA) incorporating Standard Contractual Clauses is available at agenticrail.nz/dpa\ndeletion:\n  route: email request to hello@agenticrail.nz\n  text: To exercise your rights, contact hello@agenticrail.nz\nrights:\n- right: access\n  text: access your personal data\n- right: correct\n  text: correct inaccurate data\n- right: deletion\n  text: request deletion\n- right: restrict or object\n  text: restrict or object to processing\n- right: portability\n  text: data portability\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share user data for marketing.\n"
source_yaml_url: https://artifacts.apis.io/agenticrail-nz/privacy/agenticrail-nz-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from AgenticRail's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Sequence Enforcement
- Cryptographic Receipts
- Compliance
---
