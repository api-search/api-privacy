---
api_specs:
- filename: sitefire-book-demo-api-openapi.yml
  format: yaml
  label: Sitefire Book Demo API
  slug: sitefire-book-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitefire/openapi/sitefire-book-demo-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: contact
    text: Email addresses for website analysis
  - category: identifying
    text: We use your account identifier, email address, and workspace role to authorize the call.
  - category: device
    text: Device information (screen resolution, device type)
  - category: location
    text: IP address and general location information
  - category: behavioral
    text: Pages visited and time spent on pages
  - category: communication
    text: Feedback and support requests
  deletion:
    route: Contact privacy@sitefire.ai to request deletion or exercise rights
    text: To exercise any of these rights, please contact us at privacy@sitefire.ai
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: 'Service provision: To provide and maintain our website and services'
  - purpose: Analytics
    text: 'Analytics: To understand how users interact with our website and improve user experience'
  - purpose: Security
    text: 'Security: To protect against fraud and ensure the security of our services'
  - purpose: Communication
    text: 'Communication: To respond to your inquiries and provide support'
  - purpose: Legal compliance
    text: 'Legal compliance: To comply with applicable laws and regulations'
  residency:
  - region: Germany (Frankfurt)
    text: Supabase is hosted in Frankfurt, Germany.
  - region: EU
    text: Your personal data is primarily processed within the European Economic Area (EEA).
  retention:
  - period: 12 months
    scope: Session recordings
    text: 'Session recordings: Retained for up to 12 months'
  - period: 24 months
    scope: Analytics data
    text: 'Analytics data: Retained for up to 24 months'
  - period: 30 days
    scope: Server logs
    text: 'Server logs: Retained for up to 30 days'
  - period: 30 days
    scope: AI workflow traces
    text: 'AI workflow traces: Content deleted after 30 days'
  - period: null
    scope: User-provided data
    text: 'User-provided data: Retained until you request deletion'
  rights:
  - right: Access
    text: 'Right of Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Right to Rectification: Request correction of inaccurate data'
  - right: Erasure
    text: 'Right to Erasure: Request deletion of your personal data'
  - right: Restrict processing
    text: 'Right to Restrict Processing: Request limitation of data processing'
  - right: Portability
    text: 'Right to Data Portability: Request your data in a structured format'
  - right: Object
    text: 'Right to Object: Object to processing of your personal data'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: Withdraw consent for data processing'
  role:
    text: Sitefire is the data controller responsible for the processing of your personal data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The companies that process workspace data on behalf of our customers are listed in our sub-processor list .
    url: null
  transfers:
  - mechanism: SCC
    text: Google processes this data in the United States under the EU-US Data Privacy Framework and standard contractual clauses.
  - mechanism: other
    text: 'When data is transferred outside the EEA, we ensure appropriate safeguards are in place, such as: Adequacy decisions by the European Commission'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sitefire
provenance_date: '2026-11-10'
provider_name: Sitefire
provider_slug: sitefire
slug: sitefire-privacy-policy
source_date: '2026-11-10'
source_filename: sitefire-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sitefire.ai/data-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sitefire\naid: sitefire\nurl: https://sitefire.ai/data-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Sitefire is the data controller responsible for the processing of your personal data.\ndata_categories:\n- category: contact\n  text: Email addresses for website analysis\n- category: identifying\n  text: We use your account identifier, email address, and workspace role to authorize the call.\n- category: device\n  text: Device information (screen resolution, device type)\n- category: location\n  text: IP address and general location information\n- category: behavioral\n  text: Pages\
  \ visited and time spent on pages\n- category: communication\n  text: Feedback and support requests\npurposes:\n- purpose: Service provision\n  text: 'Service provision: To provide and maintain our website and services'\n- purpose: Analytics\n  text: 'Analytics: To understand how users interact with our website and improve user experience'\n- purpose: Security\n  text: 'Security: To protect against fraud and ensure the security of our services'\n- purpose: Communication\n  text: 'Communication: To respond to your inquiries and provide support'\n- purpose: Legal compliance\n  text: 'Legal compliance: To comply with applicable laws and regulations'\nretention:\n- scope: Session recordings\n  period: 12 months\n  text: 'Session recordings: Retained for up to 12 months'\n- scope: Analytics data\n  period: 24 months\n  text: 'Analytics data: Retained for up to 24 months'\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs: Retained for up to 30 days'\n- scope: AI workflow traces\n\
  \  period: 30 days\n  text: 'AI workflow traces: Content deleted after 30 days'\n- scope: User-provided data\n  period: null\n  text: 'User-provided data: Retained until you request deletion'\nresidency:\n- region: Germany (Frankfurt)\n  text: Supabase is hosted in Frankfurt, Germany.\n- region: EU\n  text: Your personal data is primarily processed within the European Economic Area (EEA).\ntransfers:\n- mechanism: SCC\n  text: Google processes this data in the United States under the EU-US Data Privacy Framework and standard contractual\n    clauses.\n- mechanism: other\n  text: 'When data is transferred outside the EEA, we ensure appropriate safeguards are in place, such as: Adequacy\n    decisions by the European Commission'\nsubprocessors:\n  url: null\n  text: The companies that process workspace data on behalf of our customers are listed in our sub-processor list\n    .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@sitefire.ai to request\
  \ deletion or exercise rights\n  text: To exercise any of these rights, please contact us at privacy@sitefire.ai\nrights:\n- right: Access\n  text: 'Right of Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Right to Rectification: Request correction of inaccurate data'\n- right: Erasure\n  text: 'Right to Erasure: Request deletion of your personal data'\n- right: Restrict processing\n  text: 'Right to Restrict Processing: Request limitation of data processing'\n- right: Portability\n  text: 'Right to Data Portability: Request your data in a structured format'\n- right: Object\n  text: 'Right to Object: Object to processing of your personal data'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent: Withdraw consent for data processing'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sitefire/privacy/sitefire-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Sitefire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Generative Engine Optimization
- AI Visibility
- Marketing
- SEO
- Analytics
- Artificial Intelligence
- Content Generation
- MCP
- Agents
---
