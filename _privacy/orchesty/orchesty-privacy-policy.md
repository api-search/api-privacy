---
api_specs:
- filename: orchesty-2.0-openapi-generated.yml
  format: yaml
  label: Orchesty.io 2.0 API
  slug: 2.0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orchesty/openapi/_ae-authored/orchesty-2.0-openapi-generated.yml
- filename: orchesty-3.0-openapi-generated.yml
  format: yaml
  label: Orchesty.io 3.0 API
  slug: 3.0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orchesty/openapi/_ae-authored/orchesty-3.0-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email, and company details provided via contact forms or registration.
  - category: device
    text: IP address, browser type, and interaction with our website.
  - category: financial
    text: billing information (processed securely via Stripe)
  - category: communication
    text: Technical details and communication provided via Jira Service Management for helpdesk support.
  - category: behavioral
    text: 'Analytics: We use Google Analytics 4 with IP anonymisation to understand website traffic and improve user experience.'
  deletion:
    route: request deletion of account and associated personal data
    text: 'Erasure: Request deletion of your account and associated personal data.'
  dpa:
    available: true
    text: Please refer to our Data Processing Agreement (DPA) .
    url: null
  purposes:
  - purpose: website traffic analytics
    text: to understand website traffic and improve user experience
  - purpose: secure payment processing
    text: 'Stripe: Secure payment processing.'
  - purpose: helpdesk support
    text: Helpdesk and technical support.
  - purpose: sales and CRM management
    text: 'Pipedrive: Sales and CRM management.'
  residency:
  - region: EU (europe-west1, Belgium)
    text: 'All data processed within the platform is stored in the EU (Region: europe-west1, Belgium) .'
  retention:
  - period: duration of your active subscription
    scope: account data
    text: 'Account Data: Retained for the duration of your active subscription.'
  - period: maximum 30 days
    scope: platform logs
    text: 'Platform Logs: Subject to your plan''s retention policy (maximum 30 days) or until storage capacity is reached.'
  - period: until you opt-out or request deletion
    scope: marketing data
    text: 'Marketing Data: Retained until you opt-out or request deletion.'
  - period: 14 months
    scope: analytics cookies
    text: Data retention is set to 14 months.
  rights:
  - right: access and portability
    text: 'Access & Portability: Request a copy of your personal data.'
  - right: rectification
    text: 'Rectification: Correct inaccurate or incomplete data.'
  - right: erasure
    text: 'Erasure: Request deletion of your account and associated personal data.'
  - right: object to processing
    text: 'Object to Processing: Unsubscribe from marketing communications at any time via the "unsubscribe" link.'
  role:
    text: For website visitors and sales leads, we act as a Data Controller. For data processed within Orchesty Cloud instances by our customers, we act as a Data Processor .
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Google Cloud Platform (GCP): Primary infrastructure and data storage (EU West 1). Stripe: Secure payment processing. Jira Service Management: Helpdesk and technical support. Pipedrive: Sales and CRM management. Ecomail: Email communication and newsletters. Google Analytics: Website usage statistics.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Orchesty.io
provenance_date: '2026-11-10'
provider_name: Orchesty.io
provider_slug: orchesty
slug: orchesty-privacy-policy
source_date: '2026-11-10'
source_filename: orchesty-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://orchesty.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Orchesty.io\naid: orchesty\nurl: https://orchesty.io/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For website visitors and sales leads, we act as a Data Controller. For data processed within Orchesty Cloud\n    instances by our customers, we act as a Data Processor .\ndata_categories:\n- category: contact\n  text: Name, email, and company details provided via contact forms or registration.\n- category: device\n  text: IP address, browser type, and interaction with our website.\n- category: financial\n  text: billing information (processed securely via Stripe)\n- category:\
  \ communication\n  text: Technical details and communication provided via Jira Service Management for helpdesk support.\n- category: behavioral\n  text: 'Analytics: We use Google Analytics 4 with IP anonymisation to understand website traffic and improve user\n    experience.'\npurposes:\n- purpose: website traffic analytics\n  text: to understand website traffic and improve user experience\n- purpose: secure payment processing\n  text: 'Stripe: Secure payment processing.'\n- purpose: helpdesk support\n  text: Helpdesk and technical support.\n- purpose: sales and CRM management\n  text: 'Pipedrive: Sales and CRM management.'\nretention:\n- scope: account data\n  period: duration of your active subscription\n  text: 'Account Data: Retained for the duration of your active subscription.'\n- scope: platform logs\n  period: maximum 30 days\n  text: 'Platform Logs: Subject to your plan''s retention policy (maximum 30 days) or until storage capacity is\n    reached.'\n- scope: marketing data\n\
  \  period: until you opt-out or request deletion\n  text: 'Marketing Data: Retained until you opt-out or request deletion.'\n- scope: analytics cookies\n  period: 14 months\n  text: Data retention is set to 14 months.\nresidency:\n- region: EU (europe-west1, Belgium)\n  text: 'All data processed within the platform is stored in the EU (Region: europe-west1, Belgium) .'\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Google Cloud Platform (GCP): Primary infrastructure and data storage (EU West 1). Stripe: Secure payment\n    processing. Jira Service Management: Helpdesk and technical support. Pipedrive: Sales and CRM management. Ecomail:\n    Email communication and newsletters. Google Analytics: Website usage statistics.'\ndpa:\n  available: true\n  url: null\n  text: Please refer to our Data Processing Agreement (DPA) .\ndeletion:\n  route: request deletion of account and associated personal data\n  text: 'Erasure: Request deletion of your account and associated personal data.'\n\
  rights:\n- right: access and portability\n  text: 'Access & Portability: Request a copy of your personal data.'\n- right: rectification\n  text: 'Rectification: Correct inaccurate or incomplete data.'\n- right: erasure\n  text: 'Erasure: Request deletion of your account and associated personal data.'\n- right: object to processing\n  text: 'Object to Processing: Unsubscribe from marketing communications at any time via the \"unsubscribe\" link.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/orchesty/privacy/orchesty-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 22 quoted statements, read from Orchesty.io's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Platform
- Automation
- Artificial Intelligence
- Open Source
---
