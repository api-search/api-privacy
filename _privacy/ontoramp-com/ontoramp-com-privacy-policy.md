---
api_specs:
- filename: ontoramp-com-commerce-api-openapi.yml
  format: yaml
  label: ontoramp-com Commerce API
  slug: ontoramp-com-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-commerce-api-openapi.yml
- filename: ontoramp-com-decision-intelligence-api-openapi.yml
  format: yaml
  label: ontoramp-com Decision Intelligence API
  slug: ontoramp-com-decision-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-decision-intelligence-api-openapi.yml
- filename: ontoramp-com-governance-evaluator-api-openapi.yml
  format: yaml
  label: ontoramp-com Governance Evaluator API
  slug: ontoramp-com-governance-evaluator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-governance-evaluator-api-openapi.yml
- filename: ontoramp-com-knowledge-graph-api-openapi.yml
  format: yaml
  label: ontoramp-com Knowledge Graph API
  slug: ontoramp-com-knowledge-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-knowledge-graph-api-openapi.yml
- filename: ontoramp-com-projection-engine-api-openapi.yml
  format: yaml
  label: ontoramp-com Projection Engine API
  slug: ontoramp-com-projection-engine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ontoramp-com/openapi/ontoramp-com-projection-engine-api-openapi.yml
claim_count: 35
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information Name, email, password (hashed), organization name, role
  - category: financial
    text: Billing information Payment method (held by Stripe), billing address, tax ID, invoice history
  - category: communication
    text: Communication content Emails to m@ontoramp.com , in-product messages
  - category: behavioral
    text: Usage telemetry API call counts, latency, error rates, feature usage
  - category: device
    text: Device + browser IP address, user-agent, browser type, device type, language
  - category: location
    text: Approximate location (city-level, derived from IP), connection metadata
  - category: other
    text: Service inputs Prompts, governance subjects, decision contexts, organizational artifacts you submit to the Service
  deletion:
    route: Email m@ontoramp.com to request deletion; deleted on request within 30 days
    text: Retained while needed to provide the Service; deleted on request (§7) within 30 days.
  dpa:
    available: true
    text: Data Processing Addendum
    url: https://ontoramp.com/legal/dpa
  purposes:
  - purpose: Deliver the Service
    text: to deliver the Service to you (process inputs, return verdicts, store account state)
  - purpose: Billing
    text: to bill you (process payments, calculate tax, issue invoices)
  - purpose: Communication
    text: to communicate with you (account notifications, billing notices, transactional emails, support replies)
  - purpose: Security
    text: to secure the Service (detect abuse, investigate incidents, prevent fraud)
  - purpose: Legal compliance
    text: to comply with legal obligations (respond to lawful requests, meet tax reporting requirements)
  - purpose: Improve the Service
    text: to operate and improve the Service (described in §3.2 with strict limits)
  residency:
  - region: United States
    text: OntoRamp's primary infrastructure is in the United States.
  retention:
  - period: 90 days
    scope: Account information
    text: deleted within 90 days of account closure
  - period: 30 days
    scope: Verdicts, scores, recommendations (free tier)
    text: 'Target window once automated deletion is live: 30 days after generation.'
  - period: 1 year
    scope: Service inputs (paid tier)
    text: 'Target window once automated deletion is live: 1 year .'
  - period: 12 months
    scope: Usage telemetry
    text: 12 months in identifiable form; longer in aggregated, identifier-stripped form per §3.3
  - period: 7 years
    scope: Billing records
    text: As required by tax law (typically 7 years in the United States; varies by jurisdiction)
  - period: 12 months
    scope: Audit log entries
    text: Audit log entries 12 months 12 months (longer plans available on request for regulated customers)
  - period: 24 months
    scope: Support communications
    text: Support communications 24 months from last reply 24 months from last reply
  rights:
  - right: Access
    text: ask us what personal data we hold about you
  - right: Correction
    text: ask us to correct inaccurate data
  - right: Deletion
    text: ask us to delete your data (subject to retention limits in §6 and any legal-hold obligations)
  - right: Withdraw consent
    text: withdraw consent for optional processing (cookies, marketing)
  - right: Portability (EU/UK)
    text: data portability (Art 20) — receive your data in a structured, commonly used format
  - right: Objection (EU/UK)
    text: objection (Art 21) — object to processing based on legitimate interests
  - right: California know/access/delete/correct/opt-out
    text: know what personal information we collect, the sources, the purposes, and the categories of third parties with whom we share it
  role:
    text: 'If you are an end user of a customer''s product: the customer is the controller of your personal data. Their privacy policy governs that relationship; this Policy describes our role as their processor.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information for monetary or other valuable consideration. We do not share personal information for cross-context behavioral advertising.
  subprocessors:
    text: Sub-processors — outside services that touch your data
    url: https://ontoramp.com/legal/sub-processors
  transfers:
  - mechanism: SCC
    text: the EU Standard Contractual Clauses (2021 SCCs, Module 2 controller-processor and Module 3 processor-processor as applicable)
  - mechanism: other
    text: the UK Addendum to the EU SCCs
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ontoramp-com
provenance_date: '2026-11-10'
provider_name: ontoramp-com
provider_slug: ontoramp-com
slug: ontoramp-com-privacy-policy
source_date: '2026-11-10'
source_filename: ontoramp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ontoramp.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ontoramp-com\naid: ontoramp-com\nurl: https://ontoramp.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'If you are an end user of a customer''s product: the customer is the controller of your personal data.\n    Their privacy policy governs that relationship; this Policy describes our role as their processor.'\ndata_categories:\n- category: identifying\n  text: Account information Name, email, password (hashed), organization name, role\n- category: financial\n  text: Billing information Payment method (held by Stripe), billing address, tax ID, invoice history\n- category: communication\n\
  \  text: Communication content Emails to m@ontoramp.com , in-product messages\n- category: behavioral\n  text: Usage telemetry API call counts, latency, error rates, feature usage\n- category: device\n  text: Device + browser IP address, user-agent, browser type, device type, language\n- category: location\n  text: Approximate location (city-level, derived from IP), connection metadata\n- category: other\n  text: Service inputs Prompts, governance subjects, decision contexts, organizational artifacts you submit to the\n    Service\npurposes:\n- purpose: Deliver the Service\n  text: to deliver the Service to you (process inputs, return verdicts, store account state)\n- purpose: Billing\n  text: to bill you (process payments, calculate tax, issue invoices)\n- purpose: Communication\n  text: to communicate with you (account notifications, billing notices, transactional emails, support replies)\n- purpose: Security\n  text: to secure the Service (detect abuse, investigate incidents, prevent\
  \ fraud)\n- purpose: Legal compliance\n  text: to comply with legal obligations (respond to lawful requests, meet tax reporting requirements)\n- purpose: Improve the Service\n  text: to operate and improve the Service (described in §3.2 with strict limits)\nretention:\n- scope: Account information\n  period: 90 days\n  text: deleted within 90 days of account closure\n- scope: Verdicts, scores, recommendations (free tier)\n  period: 30 days\n  text: 'Target window once automated deletion is live: 30 days after generation.'\n- scope: Service inputs (paid tier)\n  period: 1 year\n  text: 'Target window once automated deletion is live: 1 year .'\n- scope: Usage telemetry\n  period: 12 months\n  text: 12 months in identifiable form; longer in aggregated, identifier-stripped form per §3.3\n- scope: Billing records\n  period: 7 years\n  text: As required by tax law (typically 7 years in the United States; varies by jurisdiction)\n- scope: Audit log entries\n  period: 12 months\n  text: Audit\
  \ log entries 12 months 12 months (longer plans available on request for regulated customers)\n- scope: Support communications\n  period: 24 months\n  text: Support communications 24 months from last reply 24 months from last reply\nresidency:\n- region: United States\n  text: OntoRamp's primary infrastructure is in the United States.\ntransfers:\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses (2021 SCCs, Module 2 controller-processor and Module 3 processor-processor\n    as applicable)\n- mechanism: other\n  text: the UK Addendum to the EU SCCs\nsubprocessors:\n  url: https://ontoramp.com/legal/sub-processors\n  text: Sub-processors — outside services that touch your data\ndpa:\n  available: true\n  url: https://ontoramp.com/legal/dpa\n  text: Data Processing Addendum\ndeletion:\n  route: Email m@ontoramp.com to request deletion; deleted on request within 30 days\n  text: Retained while needed to provide the Service; deleted on request (§7) within 30 days.\nrights:\n- right:\
  \ Access\n  text: ask us what personal data we hold about you\n- right: Correction\n  text: ask us to correct inaccurate data\n- right: Deletion\n  text: ask us to delete your data (subject to retention limits in §6 and any legal-hold obligations)\n- right: Withdraw consent\n  text: withdraw consent for optional processing (cookies, marketing)\n- right: Portability (EU/UK)\n  text: data portability (Art 20) — receive your data in a structured, commonly used format\n- right: Objection (EU/UK)\n  text: objection (Art 21) — object to processing based on legitimate interests\n- right: California know/access/delete/correct/opt-out\n  text: know what personal information we collect, the sources, the purposes, and the categories of third parties\n    with whom we share it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information for monetary or other valuable consideration. We do not share personal\n    information for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/ontoramp-com/privacy/ontoramp-com-privacy-policy.yml
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
summary_line: 35 quoted statements, read from ontoramp-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- AI Agents
- Compliance
- Certification
---
