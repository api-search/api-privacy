---
api_specs:
- filename: closedloop-analytics-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Analytics API
  slug: closedloop-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-analytics-api-openapi.yml
- filename: closedloop-competitors-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Competitors API
  slug: closedloop-competitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-competitors-api-openapi.yml
- filename: closedloop-context-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Context API
  slug: closedloop-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-context-api-openapi.yml
- filename: closedloop-customers-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Customers API
  slug: closedloop-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-customers-api-openapi.yml
- filename: closedloop-features-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Features API
  slug: closedloop-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-features-api-openapi.yml
- filename: closedloop-insights-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Insights API
  slug: closedloop-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-insights-api-openapi.yml
- filename: closedloop-integrations-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Integrations API
  slug: closedloop-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-integrations-api-openapi.yml
- filename: closedloop-meta-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Meta API
  slug: closedloop-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-meta-api-openapi.yml
- filename: closedloop-products-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Products API
  slug: closedloop-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-products-api-openapi.yml
- filename: closedloop-themes-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Themes API
  slug: closedloop-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-themes-api-openapi.yml
- filename: closedloop-usage-api-openapi.yml
  format: yaml
  label: ClosedLoop AI Usage API
  slug: closedloop-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/closedloop/openapi/closedloop-usage-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: Your name, work email address, company name, job title, and account credentials'
  - category: financial
    text: 'Billing information: Payment details are collected and processed by our payment processor, Stripe.'
  - category: communication
    text: Conversation transcripts and recordings metadata from sales and customer success calls (for example, via Gong)
  - category: device
    text: IP addresses and approximate geolocation
  - category: behavioral
    text: Click patterns and navigation behavior
  deletion:
    route: Account settings or email support@closedloop.sh
    text: You may request deletion of your personal data at any time through your account settings or by contacting us at support@closedloop.sh . We will fulfill deletion requests within 30 days, subject to any legal obligations that require us to retain certain records for a longer period.
  dpa:
    available: true
    text: If you are a customer subject to a Data Processing Agreement (DPA) with us, the terms of that DPA supplement and, where applicable, take precedence over this Privacy Policy
    url: null
  purposes:
  - purpose: Provide and maintain services
    text: 'Provide and maintain our Services: Operating, maintaining, and improving the reliability and performance of our platform'
  - purpose: AI-powered insight generation
    text: 'AI-powered insight generation: Processing and analyzing communication data you provide through integrations to generate product insights, using Azure OpenAI. Your data is not used to train AI models'
  - purpose: Payment processing
    text: 'Payment processing: Processing subscription payments and managing billing through Stripe'
  - purpose: Security and fraud prevention
    text: 'Security and fraud prevention: Detecting, investigating, and preventing fraudulent, unauthorized, or illegal activity'
  residency:
  - region: United States and European Union
    text: Our platform infrastructure is hosted on Microsoft Azure in the United States and the European Union .
  - region: European Union (opt-in region)
    text: Subscribers who select the EU region during onboarding have their data stored and processed entirely within the European Union.
  retention:
  - period: duration of the subscription term
    scope: Raw customer communication data
    text: 'Raw customer data (conversation transcripts, integration data): Retained for the duration of the subscription term.'
  - period: deleted within 30 days of subscription termination
    scope: Account data
    text: 'Post-termination: Account data is deleted within 30 days of subscription termination, unless we are required to retain it for legal or compliance purposes'
  - period: up to 7 years
    scope: Billing records
    text: 'Billing records: Retained for up to 7 years to meet financial and tax compliance requirements'
  - period: one year
    scope: Audit logs and AI assistant request logs
    text: Audit logs and security-related records, including the AI assistant request logs described above, are kept for one year and then deleted.
  role:
    text: ClosedLoop Labs LLC, doing business as ClosedLoop AI, the entity responsible for the Services described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or lease your personal information to third parties for their own marketing purposes.
  subprocessors:
    text: A complete and up-to-date list of our subprocessors is available at closedloop.sh/subprocessors .
    url: closedloop.sh/subprocessors
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): We use the European Commission''s approved Standard Contractual Clauses for transfers from the EEA to third countries'
  - mechanism: other
    text: 'UK International Data Transfer Agreement (UK IDTA): For transfers from the United Kingdom, we use the UK International Data Transfer Agreement'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClosedLoop AI
provenance_date: '2026-11-09'
provider_name: ClosedLoop AI
provider_slug: closedloop
slug: closedloop-privacy-policy
source_date: '2026-11-09'
source_filename: closedloop-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://closedloop.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClosedLoop AI\naid: closedloop\nurl: https://closedloop.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ClosedLoop Labs LLC, doing business as ClosedLoop AI, the entity responsible for the Services described\n    in this policy.\ndata_categories:\n- category: identifying\n  text: 'Account information: Your name, work email address, company name, job title, and account credentials'\n- category: financial\n  text: 'Billing information: Payment details are collected and processed by our payment processor, Stripe.'\n- category: communication\n  text: Conversation transcripts and recordings\
  \ metadata from sales and customer success calls (for example, via\n    Gong)\n- category: device\n  text: IP addresses and approximate geolocation\n- category: behavioral\n  text: Click patterns and navigation behavior\npurposes:\n- purpose: Provide and maintain services\n  text: 'Provide and maintain our Services: Operating, maintaining, and improving the reliability and performance\n    of our platform'\n- purpose: AI-powered insight generation\n  text: 'AI-powered insight generation: Processing and analyzing communication data you provide through integrations\n    to generate product insights, using Azure OpenAI. Your data is not used to train AI models'\n- purpose: Payment processing\n  text: 'Payment processing: Processing subscription payments and managing billing through Stripe'\n- purpose: Security and fraud prevention\n  text: 'Security and fraud prevention: Detecting, investigating, and preventing fraudulent, unauthorized, or illegal\n    activity'\nretention:\n- scope: Raw\
  \ customer communication data\n  period: duration of the subscription term\n  text: 'Raw customer data (conversation transcripts, integration data): Retained for the duration of the subscription\n    term.'\n- scope: Account data\n  period: deleted within 30 days of subscription termination\n  text: 'Post-termination: Account data is deleted within 30 days of subscription termination, unless we are required\n    to retain it for legal or compliance purposes'\n- scope: Billing records\n  period: up to 7 years\n  text: 'Billing records: Retained for up to 7 years to meet financial and tax compliance requirements'\n- scope: Audit logs and AI assistant request logs\n  period: one year\n  text: Audit logs and security-related records, including the AI assistant request logs described above, are kept\n    for one year and then deleted.\nresidency:\n- region: United States and European Union\n  text: Our platform infrastructure is hosted on Microsoft Azure in the United States and the European\
  \ Union .\n- region: European Union (opt-in region)\n  text: Subscribers who select the EU region during onboarding have their data stored and processed entirely within\n    the European Union.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): We use the European Commission''s approved Standard Contractual Clauses\n    for transfers from the EEA to third countries'\n- mechanism: other\n  text: 'UK International Data Transfer Agreement (UK IDTA): For transfers from the United Kingdom, we use the UK\n    International Data Transfer Agreement'\nsubprocessors:\n  url: closedloop.sh/subprocessors\n  text: A complete and up-to-date list of our subprocessors is available at closedloop.sh/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: If you are a customer subject to a Data Processing Agreement (DPA) with us, the terms of that DPA supplement\n    and, where applicable, take precedence over this Privacy Policy\ndeletion:\n  route: Account settings or email\
  \ support@closedloop.sh\n  text: You may request deletion of your personal data at any time through your account settings or by contacting\n    us at support@closedloop.sh . We will fulfill deletion requests within 30 days, subject to any legal obligations\n    that require us to retain certain records for a longer period.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or lease your personal information to third parties for their own marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/closedloop/privacy/closedloop-privacy-policy.yml
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
- sale_or_sharing
summary_line: 22 quoted statements, read from ClosedLoop AI's own page on 2026-11-09.
synthetic: false
tags:
- Product Intelligence
- Customer Feedback
- Voice of Customer
- Product Management
- AI Agents
- MCP
- SaaS Analytics
- A2A
- SCIM
- Product Discovery
---
