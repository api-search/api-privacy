---
api_specs:
- filename: converra-ai-api-openapi-generated.yml
  format: yaml
  label: Converra API Reference API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-api-openapi-generated.yml
- filename: converra-ai-core-openapi-generated.yml
  format: yaml
  label: Converra core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-core-openapi-generated.yml
- filename: converra-ai-guide-openapi-generated.yml
  format: yaml
  label: Converra Guide API
  slug: guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/converra-ai/openapi/_ae-authored/converra-ai-guide-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address
  - category: contact
    text: Organization name, role, and contact details
  - category: financial
    text: Billing details such as company name, billing address, and tax IDs
  - category: device
    text: Device and browser information (type, version, user agent)
  - category: location
    text: IP address and approximate location inferred from IP
  - category: behavioral
    text: Usage metrics (e.g. token consumption, optimization runs, team members, feature usage)
  - category: communication
    text: Conversations, transcripts, simulation outputs, and evaluation data
  deletion:
    route: Upon termination of your account or upon your explicit written request
    text: 'Upon termination of your account or upon your explicit written request: We will delete or de-identify Customer Data from active systems within 30 days'
  dpa:
    available: true
    text: The current list is also maintained in our Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Authenticate users and secure multi-tenant access
  - purpose: Operate, secure, and monitor the platform
    text: Detect and prevent fraud, abuse, and security incidents
  - purpose: Improve the Service
    text: Analyze aggregated usage patterns (e.g., which features are used, how often)
  - purpose: Billing and account management
    text: Process subscriptions and usage-based fees
  - purpose: Communicate with you
    text: Send transactional emails (security alerts, account notices, billing updates)
  residency:
  - region: US
    text: MongoDB Atlas Primary database US
  - region: US/EU
    text: PostHog Product analytics US/EU
  retention:
  - period: 30 days
    scope: Customer Data upon termination or written request
    text: We will delete or de-identify Customer Data from active systems within 30 days
  - period: null
    scope: Backup copies
    text: Backup copies may persist for a limited time as part of normal backup and disaster recovery processes.
  rights:
  - right: Access
    text: 'Access: Request confirmation of whether we process personal data about you and receive a copy of that data.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete personal data.'
  - right: Deletion
    text: 'Deletion: Request deletion of personal data, subject to legal and contractual retention requirements.'
  - right: Portability
    text: 'Portability: Request a copy of your personal data in a structured, commonly used, machine-readable format.'
  - right: Objection
    text: 'Objection: Object to certain processing activities, particularly where based on legitimate interests or for direct marketing.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or Customer Data.
  subprocessors:
    text: We will provide at least 30 days' notice before adding new subprocessors that process Customer Data.
    url: null
  transfers:
  - mechanism: other
    text: we will implement appropriate safeguards (such as standard contractual clauses or equivalent mechanisms)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Converra
provenance_date: '2026-11-09'
provider_name: Converra
provider_slug: converra-ai
slug: converra-ai-privacy-policy
source_date: '2026-11-09'
source_filename: converra-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://converra.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Converra\naid: converra-ai\nurl: https://converra.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and email address\n- category: contact\n  text: Organization name, role, and contact details\n- category: financial\n  text: Billing details such as company name, billing address, and tax IDs\n- category: device\n  text: Device and browser information (type, version, user agent)\n- category: location\n  text: IP address and approximate location inferred from IP\n- category: behavioral\n  text: Usage metrics (e.g. token consumption,\
  \ optimization runs, team members, feature usage)\n- category: communication\n  text: Conversations, transcripts, simulation outputs, and evaluation data\npurposes:\n- purpose: Provide and maintain the Service\n  text: Authenticate users and secure multi-tenant access\n- purpose: Operate, secure, and monitor the platform\n  text: Detect and prevent fraud, abuse, and security incidents\n- purpose: Improve the Service\n  text: Analyze aggregated usage patterns (e.g., which features are used, how often)\n- purpose: Billing and account management\n  text: Process subscriptions and usage-based fees\n- purpose: Communicate with you\n  text: Send transactional emails (security alerts, account notices, billing updates)\nretention:\n- scope: Customer Data upon termination or written request\n  period: 30 days\n  text: We will delete or de-identify Customer Data from active systems within 30 days\n- scope: Backup copies\n  period: null\n  text: Backup copies may persist for a limited time as part\
  \ of normal backup and disaster recovery processes.\nresidency:\n- region: US\n  text: MongoDB Atlas Primary database US\n- region: US/EU\n  text: PostHog Product analytics US/EU\ntransfers:\n- mechanism: other\n  text: we will implement appropriate safeguards (such as standard contractual clauses or equivalent mechanisms)\nsubprocessors:\n  url: null\n  text: We will provide at least 30 days' notice before adding new subprocessors that process Customer Data.\ndpa:\n  available: true\n  url: null\n  text: The current list is also maintained in our Data Processing Agreement\ndeletion:\n  route: Upon termination of your account or upon your explicit written request\n  text: 'Upon termination of your account or upon your explicit written request: We will delete or de-identify Customer\n    Data from active systems within 30 days'\nrights:\n- right: Access\n  text: 'Access: Request confirmation of whether we process personal data about you and receive a copy of that data.'\n- right: Correction\n\
  \  text: 'Correction: Request correction of inaccurate or incomplete personal data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of personal data, subject to legal and contractual retention requirements.'\n- right: Portability\n  text: 'Portability: Request a copy of your personal data in a structured, commonly used, machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to certain processing activities, particularly where based on legitimate interests or\n    for direct marketing.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or Customer Data.\n"
source_yaml_url: https://artifacts.apis.io/converra-ai/privacy/converra-ai-privacy-policy.yml
stated_fields:
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
summary_line: 26 quoted statements, read from Converra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Optimization
- LLM Observability
- Simulation Testing
- Prompt Engineering
- MCP
---
