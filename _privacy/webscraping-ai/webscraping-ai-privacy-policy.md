---
api_specs:
- filename: webscraping-ai-account-api-openapi.yml
  format: yaml
  label: WebScraping.AI Account API
  slug: webscraping-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-account-api-openapi.yml
- filename: webscraping-ai-ai-api-openapi.yml
  format: yaml
  label: WebScraping.AI AI API
  slug: webscraping-ai-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-ai-api-openapi.yml
- filename: webscraping-ai-html-api-openapi.yml
  format: yaml
  label: WebScraping.AI HTML API
  slug: webscraping-ai-html-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-html-api-openapi.yml
- filename: webscraping-ai-selected-html-api-openapi.yml
  format: yaml
  label: WebScraping.AI Selected HTML API
  slug: webscraping-ai-selected-html-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-selected-html-api-openapi.yml
- filename: webscraping-ai-text-api-openapi.yml
  format: yaml
  label: WebScraping.AI Text API
  slug: webscraping-ai-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webscraping-ai/openapi/webscraping-ai-text-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: when you sign up, we ask for your email address, business name, and billing/payment information.
  - category: behavioral
    text: We also automatically collect and store usage logs about your use of the Service, including request metadata, timestamps, IP addresses associated with requests, and other operational telemetry.
  deletion:
    route: on request or account termination
    text: upon your request or termination of your Account, delete or anonymize your Personal Data in our possession no later than sixty (60) days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery and account authentication
    text: We use this information to allow you to authenticate to the Service, to select an appropriate plan, to deliver the Service, to send you transactional emails (account notifications, billing confirmations)
  - purpose: marketing with opt-in consent
    text: We send marketing communications only with your prior opt-in consent.
  residency:
  - region: United States and other jurisdictions
    text: Where you are located outside the United States, your Personal Data may be transferred to, and processed in, the United States or other jurisdictions in which we or our subprocessors operate.
  retention:
  - period: thirty (30) days
    scope: usage logs
    text: Usage logs are retained for thirty (30) days, after which they are permanently deleted.
  - period: sixty (60) days
    scope: Personal Data on request or account termination
    text: upon your request or termination of your Account, delete or anonymize your Personal Data in our possession no later than sixty (60) days
  rights:
  - right: access
    text: access to your Personal Data and certain supplementary information
  - right: correction
    text: correction of any mistakes in your Personal Data we hold
  - right: erasure
    text: erasure (deletion) of your Personal Data in certain situations
  - right: portability
    text: portability — receiving your Personal Data in a structured, commonly used, machine-readable format and transmitting it to a third party
  - right: objection to direct marketing
    text: objection to processing for direct marketing at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Personal Data.
  subprocessors:
    text: A list of our material subprocessors, including AI model providers, is available to enterprise customers upon request under non-disclosure agreement.
    url: null
  transfers:
  - mechanism: SCC
    text: we will implement appropriate safeguards such as the European Commission's Standard Contractual Clauses (SCCs) or the UK International Data Transfer Addendum, as applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WebScraping.AI
provenance_date: '2026-11-10'
provider_name: WebScraping.AI
provider_slug: webscraping-ai
slug: webscraping-ai-privacy-policy
source_date: '2026-11-10'
source_filename: webscraping-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://webscraping.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WebScraping.AI\naid: webscraping-ai\nurl: https://webscraping.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: when you sign up, we ask for your email address, business name, and billing/payment information.\n- category: behavioral\n  text: We also automatically collect and store usage logs about your use of the Service, including request metadata,\n    timestamps, IP addresses associated with requests, and other operational telemetry.\npurposes:\n- purpose: service delivery and account authentication\n  text: We use this information\
  \ to allow you to authenticate to the Service, to select an appropriate plan, to deliver\n    the Service, to send you transactional emails (account notifications, billing confirmations)\n- purpose: marketing with opt-in consent\n  text: We send marketing communications only with your prior opt-in consent.\nretention:\n- scope: usage logs\n  period: thirty (30) days\n  text: Usage logs are retained for thirty (30) days, after which they are permanently deleted.\n- scope: Personal Data on request or account termination\n  period: sixty (60) days\n  text: upon your request or termination of your Account, delete or anonymize your Personal Data in our possession\n    no later than sixty (60) days\nresidency:\n- region: United States and other jurisdictions\n  text: Where you are located outside the United States, your Personal Data may be transferred to, and processed\n    in, the United States or other jurisdictions in which we or our subprocessors operate.\ntransfers:\n- mechanism: SCC\n\
  \  text: we will implement appropriate safeguards such as the European Commission's Standard Contractual Clauses\n    (SCCs) or the UK International Data Transfer Addendum, as applicable.\nsubprocessors:\n  url: null\n  text: A list of our material subprocessors, including AI model providers, is available to enterprise customers\n    upon request under non-disclosure agreement.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: on request or account termination\n  text: upon your request or termination of your Account, delete or anonymize your Personal Data in our possession\n    no later than sixty (60) days\nrights:\n- right: access\n  text: access to your Personal Data and certain supplementary information\n- right: correction\n  text: correction of any mistakes in your Personal Data we hold\n- right: erasure\n  text: erasure (deletion) of your Personal Data in certain situations\n- right: portability\n  text: portability — receiving your Personal Data in a structured,\
  \ commonly used, machine-readable format and transmitting\n    it to a third party\n- right: objection to direct marketing\n  text: objection to processing for direct marketing at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/webscraping-ai/privacy/webscraping-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from WebScraping.AI's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- Proxies
- Artificial Intelligence
- Browser Automation
- MCP
- Development
- Public APIs
- HTML
- LLM Tools
- Structured Data
- CAPTCHA
---
