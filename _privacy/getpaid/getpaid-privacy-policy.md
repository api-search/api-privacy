---
api_specs:
- filename: getpaid-accounts-api-openapi.yml
  format: yaml
  label: GetPaid Accounts API
  slug: getpaid-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-accounts-api-openapi.yml
- filename: getpaid-applications-api-openapi.yml
  format: yaml
  label: GetPaid Applications API
  slug: getpaid-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-applications-api-openapi.yml
- filename: getpaid-authentication-api-openapi.yml
  format: yaml
  label: GetPaid Authentication API
  slug: getpaid-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-authentication-api-openapi.yml
- filename: getpaid-checkouts-api-openapi.yml
  format: yaml
  label: GetPaid Checkouts API
  slug: getpaid-checkouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-checkouts-api-openapi.yml
- filename: getpaid-payments-api-openapi.yml
  format: yaml
  label: GetPaid Payments API
  slug: getpaid-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-payments-api-openapi.yml
- filename: getpaid-queries-api-openapi.yml
  format: yaml
  label: GetPaid Queries API
  slug: getpaid-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-queries-api-openapi.yml
- filename: getpaid-accept-payments-webhooks-api-openapi.yml
  format: yaml
  label: GetPaid Accept payments webhooks API
  slug: getpaid-accept-payments-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-accept-payments-webhooks-api-openapi.yml
- filename: getpaid-onboard-sellers-webhooks-api-openapi.yml
  format: yaml
  label: GetPaid Onboard sellers webhooks API
  slug: getpaid-onboard-sellers-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getpaid/openapi/getpaid-onboard-sellers-webhooks-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: server log data, cookies and data you submit through contact and demo request forms
  - category: identifying
    text: IP addresses, contact requests, communication data, contractual data, contact details, names, and website-access data
  deletion:
    route: email privacy@getpaid.io
    text: For privacy requests, contact privacy@getpaid.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: website hosting and service provision
    text: Hosting supports the performance of contracts with potential and existing customers and the secure, fast, and efficient provision of our online offering under Art. 6(1)(b) and Art. 6(1)(f) GDPR.
  - purpose: analytics cookies
    text: Google Analytics uses cookies to analyse website use.
  rights:
  - right: complaint to supervisory authority
    text: you may complain to the competent supervisory authority if data-protection law is breached
  - right: data portability
    text: You may request data processed automatically on the basis of consent or a contract in a machine-readable format, including transmission to another controller where technically feasible.
  - right: access, correction, blocking, deletion
    text: you may request information about stored personal data, its origin, recipients, purpose, correction, blocking, or deletion
  - right: withdraw consent
    text: You may revoke consent already given at any time by emailing privacy@getpaid.io .
  role:
    text: Nyx Payments Software Services GmbH is the controller for personal data processed in connection with your visit to this website
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: The resulting information is generally transferred to and stored on a Google server in the USA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GetPaid
provenance_date: '2026-11-09'
provider_name: GetPaid
provider_slug: getpaid
slug: getpaid-privacy-policy
source_date: '2026-11-09'
source_filename: getpaid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.getpaid.io/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GetPaid\naid: getpaid\nurl: https://www.getpaid.io/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Nyx Payments Software Services GmbH is the controller for personal data processed in connection with your\n    visit to this website\ndata_categories:\n- category: identifying\n  text: server log data, cookies and data you submit through contact and demo request forms\n- category: identifying\n  text: IP addresses, contact requests, communication data, contractual data, contact details, names, and website-access\n    data\npurposes:\n- purpose: website hosting and service provision\n\
  \  text: Hosting supports the performance of contracts with potential and existing customers and the secure, fast,\n    and efficient provision of our online offering under Art. 6(1)(b) and Art. 6(1)(f) GDPR.\n- purpose: analytics cookies\n  text: Google Analytics uses cookies to analyse website use.\nretention: []\nresidency: []\ntransfers:\n- mechanism: other\n  text: The resulting information is generally transferred to and stored on a Google server in the USA.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@getpaid.io\n  text: For privacy requests, contact privacy@getpaid.io .\nrights:\n- right: complaint to supervisory authority\n  text: you may complain to the competent supervisory authority if data-protection law is breached\n- right: data portability\n  text: You may request data processed automatically on the basis of consent or a contract in a machine-readable\n    format, including transmission\
  \ to another controller where technically feasible.\n- right: access, correction, blocking, deletion\n  text: you may request information about stored personal data, its origin, recipients, purpose, correction, blocking,\n    or deletion\n- right: withdraw consent\n  text: You may revoke consent already given at any time by emailing privacy@getpaid.io .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getpaid/privacy/getpaid-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- transfers
- deletion
- rights
summary_line: 11 quoted statements, read from GetPaid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Embedded Payments
- Split Settlement
- Checkout
- Marketplace
- Onboarding
- Subscription
- Agentic Payments
- Europe
---
