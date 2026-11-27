---
api_specs:
- filename: jobspipe-account-api-openapi.yml
  format: yaml
  label: JobsPipe Account API
  slug: jobspipe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-account-api-openapi.yml
- filename: jobspipe-billing-api-openapi.yml
  format: yaml
  label: JobsPipe Billing API
  slug: jobspipe-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-billing-api-openapi.yml
- filename: jobspipe-companies-api-openapi.yml
  format: yaml
  label: JobsPipe Companies API
  slug: jobspipe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-companies-api-openapi.yml
- filename: jobspipe-jobs-api-openapi.yml
  format: yaml
  label: JobsPipe Jobs API
  slug: jobspipe-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-jobs-api-openapi.yml
- filename: jobspipe-labour-market-insights-api-openapi.yml
  format: yaml
  label: JobsPipe Labour Market Insights API
  slug: jobspipe-labour-market-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-labour-market-insights-api-openapi.yml
- filename: jobspipe-monitors-api-openapi.yml
  format: yaml
  label: JobsPipe Monitors API
  slug: jobspipe-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-monitors-api-openapi.yml
- filename: jobspipe-sandbox-api-openapi.yml
  format: yaml
  label: JobsPipe Sandbox API
  slug: jobspipe-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-sandbox-api-openapi.yml
- filename: jobspipe-stack-api-openapi.yml
  format: yaml
  label: JobsPipe Stack API
  slug: jobspipe-stack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-stack-api-openapi.yml
- filename: jobspipe-technologies-api-openapi.yml
  format: yaml
  label: JobsPipe Technologies API
  slug: jobspipe-technologies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-technologies-api-openapi.yml
- filename: jobspipe-contacts-api-openapi.yml
  format: yaml
  label: JobsPipe Contacts API
  slug: jobspipe-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-contacts-api-openapi.yml
- filename: jobspipe-layoffs-api-openapi.yml
  format: yaml
  label: JobsPipe Layoffs API
  slug: jobspipe-layoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-layoffs-api-openapi.yml
- filename: jobspipe-live-api-openapi.yml
  format: yaml
  label: JobsPipe Live API
  slug: jobspipe-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jobspipe/openapi/jobspipe-live-api-openapi.yml
claim_count: 49
description: ''
doc:
  data_categories:
  - category: identifying
    text: account email, hashed password (or OAuth identifier)
  - category: financial
    text: billing details processed by our payment provider
  - category: device
    text: 'usage and technical data: IP address, browser and device information, pages visited'
  - category: communication
    text: your conversations with our support chat and the dashboard assistant are processed by AI model providers in the USA
  - category: professional
    text: Some postings name a recruiter or hiring manager, or include their work contact details.
  - category: identifying
    source: https://jobspipe.dev/privacy.md
    text: account email, hashed password (or OAuth identifier)
  - category: financial
    source: https://jobspipe.dev/privacy.md
    text: billing details processed by our payment provider
  - category: device
    source: https://jobspipe.dev/privacy.md
    text: IP address, browser and device information, pages visited
  - category: behavioral
    source: https://jobspipe.dev/privacy.md
    text: the API and MCP requests you make (including tool names and arguments), tied to your account
  - category: communication
    source: https://jobspipe.dev/privacy.md
    text: your conversations with our support chat and the dashboard assistant are processed by AI model providers in the USA to answer them
  - category: financial
    source: https://jobspipe.dev/dpa
    text: account and billing data we hold about Customer
  - category: other
    source: https://jobspipe.dev/dpa
    text: personal data that appears in public job postings JobsPipe collects
  - category: other
    source: https://jobspipe.dev/dpa#sub-processors
    text: account and billing data we hold about Customer
  deletion:
    route: dashboard self-service
    text: You can delete your account yourself in the dashboard under Settings, Profile.
  dpa:
    available: true
    text: The full, current list with roles and regions is in the Data Processing Addendum
    url: null
  purposes:
  - purpose: operate, secure, improve service
    text: To operate, secure, and improve the service
  - purpose: billing
    text: to bill you
  - purpose: respond to contact
    text: to respond when you contact us
  - purpose: legal compliance
    text: to comply with legal obligations
  - purpose: legitimate interest in job postings
    text: We process that under our legitimate interest in making public job postings searchable
  - purpose: operate, secure, and improve the service
    source: https://jobspipe.dev/privacy.md
    text: To operate, secure, and improve the service; to bill you; to respond when you contact us; and to comply with legal obligations.
  - purpose: legitimate interest in public job postings
    source: https://jobspipe.dev/privacy.md
    text: We process that under our legitimate interest in making public job postings searchable
  - purpose: counting sign-ups and page consistency
    source: https://jobspipe.dev/privacy.md
    text: used only to keep the version of a page you see consistent while we test changes and to count whether visitors sign up
  - purpose: provide the service
    source: https://jobspipe.dev/dpa
    text: JobsPipe processes personal data only to provide the service in accordance with Customer instructions and the published API documentation.
  - purpose: collection and indexing of public job postings
    source: https://jobspipe.dev/dpa
    text: JobsPipe is an independent controller of its collection and indexing
  - purpose: provide the service
    source: https://jobspipe.dev/dpa#sub-processors
    text: JobsPipe processes personal data only to provide the service in accordance with Customer instructions and the published API documentation.
  residency:
  - region: USA
    text: processed by AI model providers in the USA to answer them
  - region: USA
    source: https://jobspipe.dev/privacy.md
    text: Search requests, including natural-language requests, and your conversations with our support chat and the dashboard assistant are processed by AI model providers in the USA to answer them.
  - region: EU
    source: https://jobspipe.dev/dpa
    text: Hetzner Online GmbH - application hosting and databases (EU)
  - region: EU
    source: https://jobspipe.dev/dpa#sub-processors
    text: Hetzner Online GmbH - application hosting and databases (EU)
  retention:
  - period: the life of the account plus 90 days
    scope: account data
    text: Account data is retained for the life of the account plus 90 days.
  - period: 90 days
    scope: per-account request history
    text: Your per-account request history is kept for 90 days so you can review it in the dashboard
  - period: up to 30 days
    scope: other API and diagnostic logs
    text: other API and diagnostic logs are kept for up to 30 days for debugging and abuse prevention.
  - period: life of the account plus 90 days
    scope: account data
    source: https://jobspipe.dev/privacy.md
    text: Account data is retained for the life of the account plus 90 days.
  - period: 90 days
    scope: per-account request history
    source: https://jobspipe.dev/privacy.md
    text: Your per-account request history is kept for 90 days so you can review it in the dashboard
  - period: up to 30 days
    scope: other API and diagnostic logs
    source: https://jobspipe.dev/privacy.md
    text: other API and diagnostic logs are kept for up to 30 days for debugging and abuse prevention
  - period: 90 days
    scope: on termination
    source: https://jobspipe.dev/dpa
    text: On termination, JobsPipe will delete Customer personal data within 90 days, except where retention is required by law.
  - period: 90 days
    scope: Customer personal data on termination
    source: https://jobspipe.dev/dpa#sub-processors
    text: On termination, JobsPipe will delete Customer personal data within 90 days, except where retention is required by law.
  rights:
  - right: access, correct, delete, export, object
    text: Depending on where you live, you may have the right to access, correct, delete, or export your personal data, and to object to certain processing.
  - right: access, correct, delete, or export
    source: https://jobspipe.dev/privacy.md
    text: you may have the right to access, correct, delete, or export your personal data
  - right: object
    source: https://jobspipe.dev/privacy.md
    text: and to object to certain processing
  - right: data subject requests
    source: https://jobspipe.dev/dpa
    text: JobsPipe will, on Customer request and at Customer’s cost, provide reasonable assistance to enable Customer to respond to data subject requests under applicable law.
  - right: audit
    source: https://jobspipe.dev/dpa
    text: JobsPipe will, on reasonable written request and no more than once per year, make available documentation reasonably necessary to demonstrate compliance with this DPA.
  - right: data subject request assistance
    source: https://jobspipe.dev/dpa#sub-processors
    text: JobsPipe will, on Customer request and at Customer’s cost, provide reasonable assistance to enable Customer to respond to data subject requests under applicable law.
  role:
    text: JobsPipe is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: The full, current list with roles and regions is in the Data Processing Addendum
    url: null
  transfers:
  - mechanism: SCC
    source: https://jobspipe.dev/dpa
    text: JobsPipe relies on the EU Standard Contractual Clauses (and UK Addendum where applicable)
  - mechanism: SCC
    source: https://jobspipe.dev/dpa#sub-processors
    text: JobsPipe relies on the EU Standard Contractual Clauses (and UK Addendum where applicable)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: JobsPipe
provenance_date: '2026-11-09'
provider_name: JobsPipe
provider_slug: jobspipe
slug: jobspipe-privacy-policy
source_date: '2026-11-09'
source_filename: jobspipe-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jobspipe.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: JobsPipe\naid: jobspipe\nurl: https://jobspipe.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://jobspipe.dev/dpa\n  - https://jobspipe.dev/dpa#sub-processors\n  - https://jobspipe.dev/privacy\n  - https://jobspipe.dev/privacy.md\nrole:\n  value: controller\n  text: JobsPipe is the controller of the personal data described here.\ndata_categories:\n- category: identifying\n  text: account email, hashed password (or OAuth identifier)\n- category: financial\n  text: billing details processed by our payment provider\n- category: device\n  text: 'usage and technical data: IP address, browser and device\
  \ information, pages visited'\n- category: communication\n  text: your conversations with our support chat and the dashboard assistant are processed by AI model providers\n    in the USA\n- category: professional\n  text: Some postings name a recruiter or hiring manager, or include their work contact details.\n- category: identifying\n  text: account email, hashed password (or OAuth identifier)\n  source: https://jobspipe.dev/privacy.md\n- category: financial\n  text: billing details processed by our payment provider\n  source: https://jobspipe.dev/privacy.md\n- category: device\n  text: IP address, browser and device information, pages visited\n  source: https://jobspipe.dev/privacy.md\n- category: behavioral\n  text: the API and MCP requests you make (including tool names and arguments), tied to your account\n  source: https://jobspipe.dev/privacy.md\n- category: communication\n  text: your conversations with our support chat and the dashboard assistant are processed by AI model providers\n\
  \    in the USA to answer them\n  source: https://jobspipe.dev/privacy.md\n- category: financial\n  text: account and billing data we hold about Customer\n  source: https://jobspipe.dev/dpa\n- category: other\n  text: personal data that appears in public job postings JobsPipe collects\n  source: https://jobspipe.dev/dpa\n- category: other\n  text: account and billing data we hold about Customer\n  source: https://jobspipe.dev/dpa#sub-processors\npurposes:\n- purpose: operate, secure, improve service\n  text: To operate, secure, and improve the service\n- purpose: billing\n  text: to bill you\n- purpose: respond to contact\n  text: to respond when you contact us\n- purpose: legal compliance\n  text: to comply with legal obligations\n- purpose: legitimate interest in job postings\n  text: We process that under our legitimate interest in making public job postings searchable\n- purpose: operate, secure, and improve the service\n  text: To operate, secure, and improve the service; to bill\
  \ you; to respond when you contact us; and to comply\n    with legal obligations.\n  source: https://jobspipe.dev/privacy.md\n- purpose: legitimate interest in public job postings\n  text: We process that under our legitimate interest in making public job postings searchable\n  source: https://jobspipe.dev/privacy.md\n- purpose: counting sign-ups and page consistency\n  text: used only to keep the version of a page you see consistent while we test changes and to count whether visitors\n    sign up\n  source: https://jobspipe.dev/privacy.md\n- purpose: provide the service\n  text: JobsPipe processes personal data only to provide the service in accordance with Customer instructions and\n    the published API documentation.\n  source: https://jobspipe.dev/dpa\n- purpose: collection and indexing of public job postings\n  text: JobsPipe is an independent controller of its collection and indexing\n  source: https://jobspipe.dev/dpa\n- purpose: provide the service\n  text: JobsPipe processes\
  \ personal data only to provide the service in accordance with Customer instructions and\n    the published API documentation.\n  source: https://jobspipe.dev/dpa#sub-processors\nretention:\n- scope: account data\n  period: the life of the account plus 90 days\n  text: Account data is retained for the life of the account plus 90 days.\n- scope: per-account request history\n  period: 90 days\n  text: Your per-account request history is kept for 90 days so you can review it in the dashboard\n- scope: other API and diagnostic logs\n  period: up to 30 days\n  text: other API and diagnostic logs are kept for up to 30 days for debugging and abuse prevention.\n- scope: account data\n  period: life of the account plus 90 days\n  text: Account data is retained for the life of the account plus 90 days.\n  source: https://jobspipe.dev/privacy.md\n- scope: per-account request history\n  period: 90 days\n  text: Your per-account request history is kept for 90 days so you can review it in the dashboard\n\
  \  source: https://jobspipe.dev/privacy.md\n- scope: other API and diagnostic logs\n  period: up to 30 days\n  text: other API and diagnostic logs are kept for up to 30 days for debugging and abuse prevention\n  source: https://jobspipe.dev/privacy.md\n- scope: on termination\n  period: 90 days\n  text: On termination, JobsPipe will delete Customer personal data within 90 days, except where retention is required\n    by law.\n  source: https://jobspipe.dev/dpa\n- scope: Customer personal data on termination\n  period: 90 days\n  text: On termination, JobsPipe will delete Customer personal data within 90 days, except where retention is required\n    by law.\n  source: https://jobspipe.dev/dpa#sub-processors\nresidency:\n- region: USA\n  text: processed by AI model providers in the USA to answer them\n- region: USA\n  text: Search requests, including natural-language requests, and your conversations with our support chat and the\n    dashboard assistant are processed by AI model providers\
  \ in the USA to answer them.\n  source: https://jobspipe.dev/privacy.md\n- region: EU\n  text: Hetzner Online GmbH - application hosting and databases (EU)\n  source: https://jobspipe.dev/dpa\n- region: EU\n  text: Hetzner Online GmbH - application hosting and databases (EU)\n  source: https://jobspipe.dev/dpa#sub-processors\ntransfers:\n- mechanism: SCC\n  text: JobsPipe relies on the EU Standard Contractual Clauses (and UK Addendum where applicable)\n  source: https://jobspipe.dev/dpa\n- mechanism: SCC\n  text: JobsPipe relies on the EU Standard Contractual Clauses (and UK Addendum where applicable)\n  source: https://jobspipe.dev/dpa#sub-processors\nsubprocessors:\n  url: null\n  text: The full, current list with roles and regions is in the Data Processing Addendum\ndpa:\n  available: true\n  url: null\n  text: The full, current list with roles and regions is in the Data Processing Addendum\ndeletion:\n  route: dashboard self-service\n  text: You can delete your account yourself in\
  \ the dashboard under Settings, Profile.\nrights:\n- right: access, correct, delete, export, object\n  text: Depending on where you live, you may have the right to access, correct, delete, or export your personal\n    data, and to object to certain processing.\n- right: access, correct, delete, or export\n  text: you may have the right to access, correct, delete, or export your personal data\n  source: https://jobspipe.dev/privacy.md\n- right: object\n  text: and to object to certain processing\n  source: https://jobspipe.dev/privacy.md\n- right: data subject requests\n  text: JobsPipe will, on Customer request and at Customer’s cost, provide reasonable assistance to enable Customer\n    to respond to data subject requests under applicable law.\n  source: https://jobspipe.dev/dpa\n- right: audit\n  text: JobsPipe will, on reasonable written request and no more than once per year, make available documentation\n    reasonably necessary to demonstrate compliance with this DPA.\n  source:\
  \ https://jobspipe.dev/dpa\n- right: data subject request assistance\n  text: JobsPipe will, on Customer request and at Customer’s cost, provide reasonable assistance to enable Customer\n    to respond to data subject requests under applicable law.\n  source: https://jobspipe.dev/dpa#sub-processors\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/jobspipe/privacy/jobspipe-privacy-policy.yml
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
summary_line: 49 quoted statements, read from JobsPipe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Data
- Hiring
- JobsAPI
---
