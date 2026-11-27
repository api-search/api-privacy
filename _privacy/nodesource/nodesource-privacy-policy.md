---
api_specs:
- filename: nodesource-openapi-generated.yml
  format: yaml
  label: NodeSource API
  slug: nodesource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nodesource/openapi/_ae-authored/nodesource-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, business email, role, billing address
  - category: device
    text: CPU usage, heap snapshots, stack traces (may include file paths & function names)
  - category: device
    text: IP address, browser type, referring URL, pages visited
  - category: other
    text: Prompts you send to N Solid Copilot / N Sentinel and generated suggestions
  - category: other
    text: Crash dumps, log files, screenshots
  deletion:
    route: Submit requests via privacy@nodesource.com or our online form.
    text: Submit requests via privacy@nodesource.com or our online form.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract performance, billing, support
    text: Contract performance, billing, support
  - purpose: Service delivery, security alerts, performance optimization
    text: Service delivery, security alerts, performance optimization
  - purpose: Site analytics, fraud prevention
    text: Site analytics, fraud prevention
  - purpose: Troubleshoot issues
    text: Troubleshoot issues
  retention:
  - period: Life of contract + 7 yrs
    scope: Account data
    text: Life of contract + 7 yrs (tax & audit)
  - period: 13 months
    scope: Product telemetry
    text: Configurable by customer (default = 13 months)
  - period: 13 months
    scope: Website logs and analytics
    text: Website logs & analytics 13 months Aggregated thereafter
  - period: 30 days
    scope: Support artifacts
    text: Deleted 30 days after ticket closure
  - period: null
    scope: N | Sentinel data
    text: Data used by N | Sentinel is processed in memory and is never stored or retained by NodeSource or its AI service providers.
  rights:
  - right: EEA/UK/Switzerland rights
    text: Access • Rectification • Erasure • Restriction • Portability • Objection • Lodge a complaint with a supervisory authority
  - right: US state rights
    text: Access • Deletion • Correction • Portability • Opt-out of “sale” or “sharing” of personal data • Limit use of sensitive data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A live list of sub-processors appears at nodesource.com/legal/sub-processors
    url: nodesource.com/legal/sub-processors
  transfers:
  - mechanism: DPF
    text: NodeSource participates in the EU-U.S. Data Privacy Framework (DPF) , the UK Extension to the DPF , and the Swiss-U.S. DPF for transfers of personal data from the EEA, UK, and Switzerland to the United States.
  - mechanism: SCC
    text: Where the DPF is unavailable, we rely on the European Commission’s 2021 Standard Contractual Clauses (SCCs) or other approved safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NodeSource
provenance_date: '2026-11-10'
provider_name: NodeSource
provider_slug: nodesource
slug: nodesource-privacy-policy
source_date: '2026-11-10'
source_filename: nodesource-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.nodesource.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NodeSource\naid: nodesource\nurl: https://www.nodesource.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, business email, role, billing address\n- category: device\n  text: CPU usage, heap snapshots, stack traces (may include file paths & function names)\n- category: device\n  text: IP address, browser type, referring URL, pages visited\n- category: other\n  text: Prompts you send to N Solid Copilot / N Sentinel and generated suggestions\n- category: other\n  text: Crash dumps, log files, screenshots\npurposes:\n\
  - purpose: Contract performance, billing, support\n  text: Contract performance, billing, support\n- purpose: Service delivery, security alerts, performance optimization\n  text: Service delivery, security alerts, performance optimization\n- purpose: Site analytics, fraud prevention\n  text: Site analytics, fraud prevention\n- purpose: Troubleshoot issues\n  text: Troubleshoot issues\nretention:\n- scope: Account data\n  period: Life of contract + 7 yrs\n  text: Life of contract + 7 yrs (tax & audit)\n- scope: Product telemetry\n  period: 13 months\n  text: Configurable by customer (default = 13 months)\n- scope: Website logs and analytics\n  period: 13 months\n  text: Website logs & analytics 13 months Aggregated thereafter\n- scope: Support artifacts\n  period: 30 days\n  text: Deleted 30 days after ticket closure\n- scope: N | Sentinel data\n  period: null\n  text: Data used by N | Sentinel is processed in memory and is never stored or retained by NodeSource or its AI\n    service providers.\n\
  residency: []\ntransfers:\n- mechanism: DPF\n  text: NodeSource participates in the EU-U.S. Data Privacy Framework (DPF) , the UK Extension to the DPF , and\n    the Swiss-U.S. DPF for transfers of personal data from the EEA, UK, and Switzerland to the United States.\n- mechanism: SCC\n  text: Where the DPF is unavailable, we rely on the European Commission’s 2021 Standard Contractual Clauses (SCCs)\n    or other approved safeguards.\nsubprocessors:\n  url: nodesource.com/legal/sub-processors\n  text: A live list of sub-processors appears at nodesource.com/legal/sub-processors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Submit requests via privacy@nodesource.com or our online form.\n  text: Submit requests via privacy@nodesource.com or our online form.\nrights:\n- right: EEA/UK/Switzerland rights\n  text: Access • Rectification • Erasure • Restriction • Portability • Objection • Lodge a complaint with a supervisory\n    authority\n- right: US state rights\n\
  \  text: Access • Deletion • Correction • Portability • Opt-out of “sale” or “sharing” of personal data • Limit use\n    of sensitive data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nodesource/privacy/nodesource-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 20 quoted statements, read from NodeSource's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Node.js
- Enterprise
- Monitoring
- Security
- Performance
---
