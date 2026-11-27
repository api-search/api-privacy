---
api_specs:
- filename: policycheck-tools-chatgpt-api-openapi.yml
  format: yaml
  label: PolicyCheck Chatgpt API
  slug: policycheck-tools-chatgpt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/policycheck-tools/openapi/policycheck-tools-chatgpt-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: other
    text: Shopify store domain, store policies (terms, privacy, refund, shipping)
  - category: behavioral
    text: Which policies are analyzed, frequency of queries (anonymized)
  - category: other
    text: API request logs for debugging and performance monitoring
  deletion:
    route: Email privacy@policycheck.tools
    text: Contact us at privacy@policycheck.tools to exercise these rights.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Plain-English policy summaries
    text: Analyze store policies to provide plain-English summaries
  - purpose: Improve AI analysis
    text: Improve our AI analysis algorithms
  - purpose: Usage analytics to merchants
    text: Provide usage analytics to merchants
  - purpose: Troubleshooting
    text: Troubleshoot technical issues
  retention:
  - period: null
    scope: Active merchants
    text: Data retained while app is installed
  - period: 30 days
    scope: Uninstalled merchants
    text: Data deleted within 30 days of uninstallation
  - period: 12 months
    scope: Analytics
    text: Anonymized usage data retained for 12 months
  rights:
  - right: Access a copy of data
    text: Request a copy of your data
  - right: Deletion
    text: Request deletion of your data
  - right: Opt-out of analytics tracking
    text: Opt-out of analytics tracking
  - right: Data portability
    text: Request data portability
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 'We do not sell or share your data with third parties, except:'
  subprocessors:
    text: 'Service Providers: OpenAI API for AI analysis (text only, no PII)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PolicyCheck
provenance_date: '2026-11-10'
provider_name: PolicyCheck
provider_slug: policycheck-tools
slug: policycheck-tools-privacy-policy
source_date: '2026-11-10'
source_filename: policycheck-tools-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policycheck.tools/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PolicyCheck\naid: policycheck-tools\nurl: https://policycheck.tools/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: Shopify store domain, store policies (terms, privacy, refund, shipping)\n- category: behavioral\n  text: Which policies are analyzed, frequency of queries (anonymized)\n- category: other\n  text: API request logs for debugging and performance monitoring\npurposes:\n- purpose: Plain-English policy summaries\n  text: Analyze store policies to provide plain-English summaries\n- purpose: Improve AI analysis\n  text: Improve our\
  \ AI analysis algorithms\n- purpose: Usage analytics to merchants\n  text: Provide usage analytics to merchants\n- purpose: Troubleshooting\n  text: Troubleshoot technical issues\nretention:\n- scope: Active merchants\n  period: null\n  text: Data retained while app is installed\n- scope: Uninstalled merchants\n  period: 30 days\n  text: Data deleted within 30 days of uninstallation\n- scope: Analytics\n  period: 12 months\n  text: Anonymized usage data retained for 12 months\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service Providers: OpenAI API for AI analysis (text only, no PII)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@policycheck.tools\n  text: Contact us at privacy@policycheck.tools to exercise these rights.\nrights:\n- right: Access a copy of data\n  text: Request a copy of your data\n- right: Deletion\n  text: Request deletion of your data\n- right: Opt-out of analytics tracking\n  text: Opt-out of analytics\
  \ tracking\n- right: Data portability\n  text: Request data portability\nsale_or_sharing:\n  stance: conditional\n  text: 'We do not sell or share your data with third parties, except:'\n"
source_yaml_url: https://artifacts.apis.io/policycheck-tools/privacy/policycheck-tools-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from PolicyCheck's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Policy Analysis
- Consumer Protection
- E-Commerce
- Agentic Commerce
- Risk Assessment
- AI Agents
- A2A
- MCP
- x402
- Legal
- Returns
---
