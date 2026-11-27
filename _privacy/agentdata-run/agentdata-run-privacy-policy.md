---
api_specs:
- filename: agentdata-run-openapi-generated.yml
  format: yaml
  label: AgentData API
  slug: agentdata-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdata-run/openapi/_ae-authored/agentdata-run-openapi-generated.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data : email address, name (if provided), authentication method (email/password or Google OAuth)'
  - category: financial
    text: 'Payment data : processed and stored by Stripe. We do not store card numbers or bank details.'
  - category: behavioral
    text: 'Usage data : lookups performed, API calls made, exports purchased, features used, timestamps'
  - category: communication
    text: 'Communication data : support emails, feedback you send us'
  - category: professional
    text: Professional names and job titles, where publicly displayed
  - category: device
    text: Pages viewed and interactions, measured with Vercel Analytics (which uses no cookies) and Google Analytics 4
  deletion:
    route: Email privacy@useagentdata.com or use the form at useagentdata.com /legal/data-removal
    text: Remove your data within 14 days (we aim for 48 hours)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide account and service
    text: To provide and maintain your account and access to the service
  - purpose: Payments and subscriptions
    text: To process payments and manage subscriptions
  - purpose: Abuse prevention
    text: To monitor and prevent abuse of the service
  - purpose: B2B business intelligence
    text: enabling businesses to identify potential customers, partners, and technology trends using publicly available information
  residency:
  - region: EU (Frankfurt)
    text: Our primary database is hosted in the EU (Supabase, Frankfurt).
  retention:
  - period: 30 days
    scope: Account data
    text: Deleted within 30 days of an account deletion request.
  - period: 7 years
    scope: Payment records
    text: 'Payment records: retained for 7 years as required by UK tax law.'
  - period: 12 months
    scope: Usage logs
    text: 'Usage logs: retained for 12 months, then anonymised.'
  - period: 90 days
    scope: MCP server logs
    text: These server logs are deleted within 90 days.
  rights:
  - right: Access
    text: Access the personal data we hold about you (Article 15)
  - right: Rectification
    text: Rectify inaccurate personal data (Article 16)
  - right: Erasure
    text: Erase your personal data (Article 17, “right to be forgotten”)
  - right: Restriction
    text: Restrict processing of your personal data (Article 18)
  - right: Objection
    text: Object to processing based on legitimate interest (Article 21)
  - right: Portability
    text: 'Data portability : receive your data in a structured, machine-readable format (Article 20)'
  - right: Deletion (California)
    text: You have the right to request deletion of your personal information
  - right: Opt out of sale (California)
    text: You have the right to opt out of the sale of your personal information.
  role:
    text: DragApp.com Ltd is the data controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data to any third party. We do not share personal data with advertisers.
  subprocessors:
    text: A full sub-processor list is available on request to privacy@useagentdata.com .
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) as approved by the European Commission
  - mechanism: other
    text: The UK International Data Transfer Agreement (IDTA) where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentData
provenance_date: '2026-11-09'
provider_name: AgentData
provider_slug: agentdata-run
slug: agentdata-run-privacy-policy
source_date: '2026-11-09'
source_filename: agentdata-run-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://useagentdata.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentData\naid: agentdata-run\nurl: https://useagentdata.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: DragApp.com Ltd is the data controller for the personal data described in this policy.\ndata_categories:\n- category: contact\n  text: 'Account data : email address, name (if provided), authentication method (email/password or Google OAuth)'\n- category: financial\n  text: 'Payment data : processed and stored by Stripe. We do not store card numbers or bank details.'\n- category: behavioral\n  text: 'Usage data : lookups performed, API calls made, exports purchased, features\
  \ used, timestamps'\n- category: communication\n  text: 'Communication data : support emails, feedback you send us'\n- category: professional\n  text: Professional names and job titles, where publicly displayed\n- category: device\n  text: Pages viewed and interactions, measured with Vercel Analytics (which uses no cookies) and Google Analytics\n    4\npurposes:\n- purpose: Provide account and service\n  text: To provide and maintain your account and access to the service\n- purpose: Payments and subscriptions\n  text: To process payments and manage subscriptions\n- purpose: Abuse prevention\n  text: To monitor and prevent abuse of the service\n- purpose: B2B business intelligence\n  text: enabling businesses to identify potential customers, partners, and technology trends using publicly available\n    information\nretention:\n- scope: Account data\n  period: 30 days\n  text: Deleted within 30 days of an account deletion request.\n- scope: Payment records\n  period: 7 years\n  text: 'Payment\
  \ records: retained for 7 years as required by UK tax law.'\n- scope: Usage logs\n  period: 12 months\n  text: 'Usage logs: retained for 12 months, then anonymised.'\n- scope: MCP server logs\n  period: 90 days\n  text: These server logs are deleted within 90 days.\nresidency:\n- region: EU (Frankfurt)\n  text: Our primary database is hosted in the EU (Supabase, Frankfurt).\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) as approved by the European Commission\n- mechanism: other\n  text: The UK International Data Transfer Agreement (IDTA) where applicable\nsubprocessors:\n  url: null\n  text: A full sub-processor list is available on request to privacy@useagentdata.com .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@useagentdata.com or use the form at useagentdata.com /legal/data-removal\n  text: Remove your data within 14 days (we aim for 48 hours)\nrights:\n- right: Access\n  text: Access the personal data we hold about\
  \ you (Article 15)\n- right: Rectification\n  text: Rectify inaccurate personal data (Article 16)\n- right: Erasure\n  text: Erase your personal data (Article 17, “right to be forgotten”)\n- right: Restriction\n  text: Restrict processing of your personal data (Article 18)\n- right: Objection\n  text: Object to processing based on legitimate interest (Article 21)\n- right: Portability\n  text: 'Data portability : receive your data in a structured, machine-readable format (Article 20)'\n- right: Deletion (California)\n  text: You have the right to request deletion of your personal information\n- right: Opt out of sale (California)\n  text: You have the right to opt out of the sale of your personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data to any third party. We do not share personal data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/agentdata-run/privacy/agentdata-run-privacy-policy.yml
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
- sale_or_sharing
summary_line: 29 quoted statements, read from AgentData's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
