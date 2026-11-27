---
api_specs:
- filename: logimu-com-coding-agents-json-api-openapi.yml
  format: yaml
  label: logimu-com Coding Agents.json API
  slug: logimu-com-coding-agents-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-coding-agents-json-api-openapi.yml
- filename: logimu-com-deprecations-json-api-openapi.yml
  format: yaml
  label: logimu-com Deprecations.json API
  slug: logimu-com-deprecations-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-deprecations-json-api-openapi.yml
- filename: logimu-com-rankings-json-api-openapi.yml
  format: yaml
  label: logimu-com Rankings.json API
  slug: logimu-com-rankings-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-rankings-json-api-openapi.yml
- filename: logimu-com-subscribe-api-openapi.yml
  format: yaml
  label: logimu-com Subscribe API
  slug: logimu-com-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logimu-com/openapi/logimu-com-subscribe-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register for API access we collect your name, email address, optional company name, and your password
  - category: financial
    text: We receive the transaction confirmation, order reference, billing name, email and country
  - category: device
    text: 'Our web servers log standard request data: IP address, browser user-agent, referring URL, pages requested and timestamps.'
  - category: behavioral
    text: Google Analytics sets cookies and processes an abbreviated identifier for your device.
  - category: communication
    text: When you submit our contact form we collect your name, email address, company name, and the details of your message.
  deletion:
    route: Account deletion request
    text: If you delete your account, we delete or anonymise your account and associated personal data within ninety (90) days, except where we must retain certain records
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account operation and API access
    text: To create and operate your account, authenticate you and issue your API key
  - purpose: Purchase processing
    text: To process purchases, maintain records of sale, and meet tax and accounting obligations
  - purpose: Security and abuse prevention
    text: To prevent, detect and investigate abuse, fraud and security incidents, and to enforce our terms
  - purpose: Service quality and improvement
    text: To monitor service quality and improve the product
  residency:
  - region: European Union (Germany)
    text: Your account and usage data are stored on servers located in the European Union (Germany).
  retention:
  - period: twenty-four (24) months
    scope: Usage and audit logs
    text: Usage and audit logs — up to twenty-four (24) months, for security, billing and compliance
  - period: 90 days
    scope: Web server logs
    text: Web server logs — up to 90 days, for security purposes
  - period: null
    scope: Account records
    text: Account records — for as long as your account is active
  rights:
  - right: Access
    text: You may request access to, correction of, portability of, or deletion of your personal information
  - right: Objection and restriction
    text: object to or restrict certain processing, and withdraw consent where processing is based on it
  - right: Complaint to supervisory authority
    text: You also have the right to lodge a complaint with a supervisory authority.
  - right: Opt out of sale or sharing (California)
    text: Opt out of the sale or sharing of personal information — we do not sell or share personal information as those terms are defined
  role:
    text: CP Development doo is the controller of your Logimu account data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent or share your personal information with third parties for marketing purposes
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where a provider processes data outside the EEA, that transfer is covered by the European Commission's Standard Contractual Clauses or another recognised safeguard.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: logimu-com
provenance_date: '2026-11-09'
provider_name: logimu-com
provider_slug: logimu-com
slug: logimu-com-privacy-policy
source_date: '2026-11-09'
source_filename: logimu-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.logimu.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: logimu-com\naid: logimu-com\nurl: https://www.logimu.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CP Development doo is the controller of your Logimu account data.\ndata_categories:\n- category: identifying\n  text: When you register for API access we collect your name, email address, optional company name, and your password\n- category: financial\n  text: We receive the transaction confirmation, order reference, billing name, email and country\n- category: device\n  text: 'Our web servers log standard request data: IP address, browser user-agent, referring URL, pages\
  \ requested\n    and timestamps.'\n- category: behavioral\n  text: Google Analytics sets cookies and processes an abbreviated identifier for your device.\n- category: communication\n  text: When you submit our contact form we collect your name, email address, company name, and the details of your\n    message.\npurposes:\n- purpose: Account operation and API access\n  text: To create and operate your account, authenticate you and issue your API key\n- purpose: Purchase processing\n  text: To process purchases, maintain records of sale, and meet tax and accounting obligations\n- purpose: Security and abuse prevention\n  text: To prevent, detect and investigate abuse, fraud and security incidents, and to enforce our terms\n- purpose: Service quality and improvement\n  text: To monitor service quality and improve the product\nretention:\n- scope: Usage and audit logs\n  period: twenty-four (24) months\n  text: Usage and audit logs — up to twenty-four (24) months, for security, billing and\
  \ compliance\n- scope: Web server logs\n  period: 90 days\n  text: Web server logs — up to 90 days, for security purposes\n- scope: Account records\n  period: null\n  text: Account records — for as long as your account is active\nresidency:\n- region: European Union (Germany)\n  text: Your account and usage data are stored on servers located in the European Union (Germany).\ntransfers:\n- mechanism: SCC\n  text: Where a provider processes data outside the EEA, that transfer is covered by the European Commission's Standard\n    Contractual Clauses or another recognised safeguard.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion request\n  text: If you delete your account, we delete or anonymise your account and associated personal data within ninety\n    (90) days, except where we must retain certain records\nrights:\n- right: Access\n  text: You may request access to, correction of, portability of, or deletion\
  \ of your personal information\n- right: Objection and restriction\n  text: object to or restrict certain processing, and withdraw consent where processing is based on it\n- right: Complaint to supervisory authority\n  text: You also have the right to lodge a complaint with a supervisory authority.\n- right: Opt out of sale or sharing (California)\n  text: Opt out of the sale or sharing of personal information — we do not sell or share personal information as\n    those terms are defined\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent or share your personal information with third parties for marketing purposes\n"
source_yaml_url: https://artifacts.apis.io/logimu-com/privacy/logimu-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from logimu-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Data API
- Amazon
- Walmart
---
