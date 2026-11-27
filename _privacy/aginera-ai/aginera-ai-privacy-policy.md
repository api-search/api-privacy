---
api_specs:
- filename: aginera-ai-billing-api-openapi.yml
  format: yaml
  label: Aginera Billing API
  slug: aginera-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-billing-api-openapi.yml
- filename: aginera-ai-cad-api-openapi.yml
  format: yaml
  label: Aginera CAD API
  slug: aginera-ai-cad-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-cad-api-openapi.yml
- filename: aginera-ai-clients-api-openapi.yml
  format: yaml
  label: Aginera Clients API
  slug: aginera-ai-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-clients-api-openapi.yml
- filename: aginera-ai-documents-api-openapi.yml
  format: yaml
  label: Aginera Documents API
  slug: aginera-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-documents-api-openapi.yml
- filename: aginera-ai-exports-api-openapi.yml
  format: yaml
  label: Aginera Exports API
  slug: aginera-ai-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-exports-api-openapi.yml
- filename: aginera-ai-projects-api-openapi.yml
  format: yaml
  label: Aginera Projects API
  slug: aginera-ai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-projects-api-openapi.yml
- filename: aginera-ai-reference-api-openapi.yml
  format: yaml
  label: Aginera Reference API
  slug: aginera-ai-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-reference-api-openapi.yml
- filename: aginera-ai-takeoffs-api-openapi.yml
  format: yaml
  label: Aginera Takeoffs API
  slug: aginera-ai-takeoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-takeoffs-api-openapi.yml
- filename: aginera-ai-usage-api-openapi.yml
  format: yaml
  label: Aginera Usage API
  slug: aginera-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aginera-ai/openapi/aginera-ai-usage-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email, phone (optional), company name, role/title (optional), login credentials (stored in hashed form where applicable).'
  - category: financial
    text: 'Billing data: billing contact details, billing address (optional), tax/VAT fields (if provided), payment status and transaction metadata.'
  - category: other
    text: 'Customer Content: project data and files you upload or submit (e.g., PDFs, drawings, CAD files, specs, takeoffs, BOMs, prompts/instructions, notes).'
  - category: communication
    text: 'Support communications: messages, tickets, emails, meeting notes, and attachments you send.'
  - category: behavioral
    text: 'Usage data: pages/screens viewed, features used, actions taken, timestamps.'
  - category: device
    text: 'Device/network data: IP address, browser type, device identifiers, OS, approximate location inferred from IP.'
  deletion:
    route: Customer may request deletion via organization or support email
    text: request deletion/export consistent with your agreement
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Provide and operate the Services (including processing Customer Content to generate outputs).
  - purpose: Model development and training
    text: Develop, train, evaluate, and improve machine-learning models and extraction rules
  - purpose: Licensing de-identified datasets
    text: which we may license to third parties including AI developers
  - purpose: Analytics
    text: Understand usage trends and measure site/app performance (analytics).
  residency:
  - region: various (including United States)
    text: Your information may be processed in countries other than where you reside (including the United States) depending on where our providers operate.
  retention:
  - period: retained while your account is active
    scope: Account data
    text: 'Account data: retained while your account is active; limited retention after closure.'
  - period: per your workspace settings/contract
    scope: Customer Content
    text: 'Customer Content: retained per your workspace settings/contract; may be deleted upon request/termination, subject to backup retention and legal/security requirements.'
  - period: for a limited period
    scope: Logs/security records
    text: 'Logs/security records: retained for a limited period for security, abuse prevention, and reliability.'
  rights:
  - right: access, correct, delete, restrict, object, portability, withdraw consent
    text: access, correct, delete, or restrict processing of your personal data, object to processing, request portability, and withdraw consent where processing is based on consent.
  - right: opt out of de-identified dataset licensing
    text: opt the workspace out of de-identified dataset creation and licensing by emailing support@aginera.ai from an administrator address
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: Appendix A — Subprocessors (Service Providers)
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use appropriate safeguards for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aginera
provenance_date: '2026-11-09'
provider_name: Aginera
provider_slug: aginera-ai
slug: aginera-ai-privacy-policy
source_date: '2026-11-09'
source_filename: aginera-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aginera.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aginera\naid: aginera-ai\nurl: https://aginera.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email, phone (optional), company name, role/title (optional), login credentials (stored\n    in hashed form where applicable).'\n- category: financial\n  text: 'Billing data: billing contact details, billing address (optional), tax/VAT fields (if provided), payment\n    status and transaction metadata.'\n- category: other\n  text: 'Customer Content: project data and files you upload or submit (e.g., PDFs, drawings,\
  \ CAD files, specs,\n    takeoffs, BOMs, prompts/instructions, notes).'\n- category: communication\n  text: 'Support communications: messages, tickets, emails, meeting notes, and attachments you send.'\n- category: behavioral\n  text: 'Usage data: pages/screens viewed, features used, actions taken, timestamps.'\n- category: device\n  text: 'Device/network data: IP address, browser type, device identifiers, OS, approximate location inferred from\n    IP.'\npurposes:\n- purpose: Provide and operate the Services\n  text: Provide and operate the Services (including processing Customer Content to generate outputs).\n- purpose: Model development and training\n  text: Develop, train, evaluate, and improve machine-learning models and extraction rules\n- purpose: Licensing de-identified datasets\n  text: which we may license to third parties including AI developers\n- purpose: Analytics\n  text: Understand usage trends and measure site/app performance (analytics).\nretention:\n- scope: Account\
  \ data\n  period: retained while your account is active\n  text: 'Account data: retained while your account is active; limited retention after closure.'\n- scope: Customer Content\n  period: per your workspace settings/contract\n  text: 'Customer Content: retained per your workspace settings/contract; may be deleted upon request/termination,\n    subject to backup retention and legal/security requirements.'\n- scope: Logs/security records\n  period: for a limited period\n  text: 'Logs/security records: retained for a limited period for security, abuse prevention, and reliability.'\nresidency:\n- region: various (including United States)\n  text: Your information may be processed in countries other than where you reside (including the United States)\n    depending on where our providers operate.\ntransfers:\n- mechanism: other\n  text: Where required, we use appropriate safeguards for cross-border transfers.\nsubprocessors:\n  url: null\n  text: Appendix A — Subprocessors (Service Providers)\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Customer may request deletion via organization or support email\n  text: request deletion/export consistent with your agreement\nrights:\n- right: access, correct, delete, restrict, object, portability, withdraw consent\n  text: access, correct, delete, or restrict processing of your personal data, object to processing, request portability,\n    and withdraw consent where processing is based on consent.\n- right: opt out of de-identified dataset licensing\n  text: opt the workspace out of de-identified dataset creation and licensing by emailing support@aginera.ai from\n    an administrator address\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/aginera-ai/privacy/aginera-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Aginera's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Construction
- Estimating
- MEP
- Software
---
