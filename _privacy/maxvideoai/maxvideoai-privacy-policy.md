---
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account & identity: name, email, password hash, country/region, language.'
  - category: financial
    text: 'Payments: processed by Stripe; we store Stripe identifiers and minimal payment metadata, never full card numbers.'
  - category: device
    text: 'Usage & telemetry: device information, IP, user-agent, approximate location, feature flags, error diagnostics, logs.'
  - category: behavioral
    text: 'Content: prompts, inputs, generated outputs, and file uploads needed to provide the Service.'
  - category: communication
    text: 'Consents & preferences: legal document versions accepted, cookie choices, marketing opt-in, preferred currency.'
  - category: contact
    source: https://maxvideoai.com/legal/subprocessors
    text: Email addresses, message contents and delivery metadata.
  - category: financial
    source: https://maxvideoai.com/legal/subprocessors
    text: Billing details, payment identifiers and transactions.
  - category: device
    source: https://maxvideoai.com/legal/subprocessors
    text: Application content, technical logs, IP addresses and performance metrics.
  - category: behavioral
    source: https://maxvideoai.com/legal/subprocessors
    text: Visits, usage/purchase events and browser/session identifiers
  deletion:
    route: Email privacy [at] maxvideoai.com to exercise rights, including erasure.
    text: To exercise rights, email privacy [at] maxvideoai.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: account management, wallet, video jobs, support — legal basis: contract.'
  - purpose: Payments and fraud prevention
    text: 'Payments & fraud prevention: processing payments, fraud monitoring — legal bases: contract, legitimate interests, legal obligation.'
  - purpose: Analytics and product improvement
    text: 'Analytics & product improvement: measuring usage to improve features — legal bases: consent for non-essential cookies; otherwise legitimate interests with safeguards.'
  - purpose: Marketing emails
    text: 'Marketing emails: sending product updates when you opt in — legal basis: consent (revocable anytime).'
  - purpose: Legal compliance and security
    text: 'Legal compliance & security: record keeping, audit trails, incident response — legal bases: legal obligation and legitimate interests.'
  - purpose: Payments and fraud prevention
    source: https://maxvideoai.com/legal/subprocessors
    text: Payments and fraud prevention
  - purpose: Audience measurement and attribution
    source: https://maxvideoai.com/legal/subprocessors
    text: Audience measurement and attribution
  - purpose: Hosting, delivery and performance
    source: https://maxvideoai.com/legal/subprocessors
    text: Hosting, delivery and performance
  residency:
  - region: outside the EEA
    source: https://maxvideoai.com/legal/subprocessors
    text: Processing may take place outside the EEA, including in the United States for our AWS S3 storage.
  retention:
  - period: null
    scope: Account and workspace data
    text: 'Account and workspace: account data, projects, conversations and media are kept to provide your workspace, history and downloads. You may request erasure.'
  - period: 90 days
    scope: Internal assistant review access
    text: Detailed review access expires 90 days after the exchange.
  - period: 10 years
    scope: Accounting records
    text: 'Accounting records: invoices and supporting accounting documents must be retained for 10 years from the end of the relevant financial year.'
  - period: null
    scope: Technical logs and backups
    text: 'Technical logs and backups: retention depends on the service concerned and the needs of security, recovery and legal obligations.'
  rights:
  - right: access
    text: you may request access, rectification, erasure, restriction, objection, and data portability.
  - right: withdraw consent
    text: You may also withdraw consent at any time.
  - right: complaint to authority
    text: You can lodge a complaint with your local data protection authority; in France, contact the CNIL.
  role:
    text: 'Controller: MaxVideoAI (Adrien Millot, EI).'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Hosting, storage, authentication, payments and emails use the services listed in our provider register.
    url: null
  transfers:
  - mechanism: SCC
    text: When personal data leaves the EEA/UK, we rely on appropriate safeguards such as Standard Contractual Clauses and implement supplementary measures where required.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MaxVideoAI
provenance_date: '2026-11-10'
provider_name: MaxVideoAI
provider_slug: maxvideoai
slug: maxvideoai-privacy-policy
source_date: '2026-11-10'
source_filename: maxvideoai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://maxvideoai.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MaxVideoAI\naid: maxvideoai\nurl: https://maxvideoai.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://maxvideoai.com/legal/privacy\n  - https://maxvideoai.com/legal/subprocessors\nrole:\n  value: controller\n  text: 'Controller: MaxVideoAI (Adrien Millot, EI).'\ndata_categories:\n- category: identifying\n  text: 'Account & identity: name, email, password hash, country/region, language.'\n- category: financial\n  text: 'Payments: processed by Stripe; we store Stripe identifiers and minimal payment metadata, never full card\n    numbers.'\n- category: device\n  text: 'Usage & telemetry:\
  \ device information, IP, user-agent, approximate location, feature flags, error diagnostics,\n    logs.'\n- category: behavioral\n  text: 'Content: prompts, inputs, generated outputs, and file uploads needed to provide the Service.'\n- category: communication\n  text: 'Consents & preferences: legal document versions accepted, cookie choices, marketing opt-in, preferred currency.'\n- category: contact\n  text: Email addresses, message contents and delivery metadata.\n  source: https://maxvideoai.com/legal/subprocessors\n- category: financial\n  text: Billing details, payment identifiers and transactions.\n  source: https://maxvideoai.com/legal/subprocessors\n- category: device\n  text: Application content, technical logs, IP addresses and performance metrics.\n  source: https://maxvideoai.com/legal/subprocessors\n- category: behavioral\n  text: Visits, usage/purchase events and browser/session identifiers\n  source: https://maxvideoai.com/legal/subprocessors\npurposes:\n- purpose: Provide\
  \ the Service\n  text: 'Provide the Service: account management, wallet, video jobs, support — legal basis: contract.'\n- purpose: Payments and fraud prevention\n  text: 'Payments & fraud prevention: processing payments, fraud monitoring — legal bases: contract, legitimate\n    interests, legal obligation.'\n- purpose: Analytics and product improvement\n  text: 'Analytics & product improvement: measuring usage to improve features — legal bases: consent for non-essential\n    cookies; otherwise legitimate interests with safeguards.'\n- purpose: Marketing emails\n  text: 'Marketing emails: sending product updates when you opt in — legal basis: consent (revocable anytime).'\n- purpose: Legal compliance and security\n  text: 'Legal compliance & security: record keeping, audit trails, incident response — legal bases: legal obligation\n    and legitimate interests.'\n- purpose: Payments and fraud prevention\n  text: Payments and fraud prevention\n  source: https://maxvideoai.com/legal/subprocessors\n\
  - purpose: Audience measurement and attribution\n  text: Audience measurement and attribution\n  source: https://maxvideoai.com/legal/subprocessors\n- purpose: Hosting, delivery and performance\n  text: Hosting, delivery and performance\n  source: https://maxvideoai.com/legal/subprocessors\nretention:\n- scope: Account and workspace data\n  period: null\n  text: 'Account and workspace: account data, projects, conversations and media are kept to provide your workspace,\n    history and downloads. You may request erasure.'\n- scope: Internal assistant review access\n  period: 90 days\n  text: Detailed review access expires 90 days after the exchange.\n- scope: Accounting records\n  period: 10 years\n  text: 'Accounting records: invoices and supporting accounting documents must be retained for 10 years from the\n    end of the relevant financial year.'\n- scope: Technical logs and backups\n  period: null\n  text: 'Technical logs and backups: retention depends on the service concerned and\
  \ the needs of security, recovery\n    and legal obligations.'\nresidency:\n- region: outside the EEA\n  text: Processing may take place outside the EEA, including in the United States for our AWS S3 storage.\n  source: https://maxvideoai.com/legal/subprocessors\ntransfers:\n- mechanism: SCC\n  text: When personal data leaves the EEA/UK, we rely on appropriate safeguards such as Standard Contractual Clauses\n    and implement supplementary measures where required.\nsubprocessors:\n  url: null\n  text: Hosting, storage, authentication, payments and emails use the services listed in our provider register.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy [at] maxvideoai.com to exercise rights, including erasure.\n  text: To exercise rights, email privacy [at] maxvideoai.com .\nrights:\n- right: access\n  text: you may request access, rectification, erasure, restriction, objection, and data portability.\n- right: withdraw consent\n  text: You may also\
  \ withdraw consent at any time.\n- right: complaint to authority\n  text: You can lodge a complaint with your local data protection authority; in France, contact the CNIL.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maxvideoai/privacy/maxvideoai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 29 quoted statements, read from MaxVideoAI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- Image Generation
- MCP
- Agent-Native
- Image-to-Video
- Creative Production
- Pay-as-you-go
---
