---
api_specs:
- filename: cloudrf-account-api-openapi.yml
  format: yaml
  label: CloudRF Account API
  slug: cloudrf-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-account-api-openapi.yml
- filename: cloudrf-analyse-api-openapi.yml
  format: yaml
  label: CloudRF Analyse API
  slug: cloudrf-analyse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-analyse-api-openapi.yml
- filename: cloudrf-create-api-openapi.yml
  format: yaml
  label: CloudRF Create API
  slug: cloudrf-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-create-api-openapi.yml
- filename: cloudrf-manage-api-openapi.yml
  format: yaml
  label: CloudRF Manage API
  slug: cloudrf-manage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-manage-api-openapi.yml
- filename: cloudrf-satellite-api-openapi.yml
  format: yaml
  label: CloudRF Satellite API
  slug: cloudrf-satellite-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-satellite-api-openapi.yml
- filename: cloudrf-template-api-openapi.yml
  format: yaml
  label: CloudRF Template API
  slug: cloudrf-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-template-api-openapi.yml
- filename: cloudrf-3-d-api-openapi.yml
  format: yaml
  label: CloudRF 3 D API
  slug: cloudrf-3-d-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudrf/openapi/cloudrf-3-d-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username, email address and password (stored hashed)
  - category: contact
    text: First and last name and billing address
  - category: financial
    text: We do not hold card details. Payments are handled by our payment providers, and we hold only a random token.
  - category: device
    text: Logs of account activity, including IP address and approximate location
  - category: communication
    text: Support tickets and emails
  deletion:
    route: Email support@cloudrf.com from the address on your account
    text: To use any of these rights, email support@cloudrf.com from the address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate service and provide ordered products
    text: We use your personal data only to operate the website and API and to provide the services and products you order.
  - purpose: Account creation and security
    text: To create and secure your account
  - purpose: Fraud prevention and misuse investigation
    text: To secure the service and investigate misuse
  - purpose: Website traffic statistics
    text: We use Google Analytics to measure website traffic in aggregate, such as which pages are visited and how often.
  residency:
  - region: United Kingdom
    text: Your account, your support tickets and the calculations you generate are stored and processed only within our own network in the United Kingdom, on dedicated servers in our UK data centre.
  retention:
  - period: Reviewed every 12 months
    scope: Account details
    text: Reviewed every 12 months; inactive accounts and past transactions are deleted
  - period: 30 days
    scope: Calculations on the Free plan
    text: Calculations on the Free plan 30 days
  - period: 2 years
    scope: Calculations on the Bronze plan
    text: Calculations on the Bronze plan 2 years
  - period: 3 years
    scope: Calculations on the Silver, Gold and Platinum plans
    text: Calculations on the Silver, Gold and Platinum plans 3 years
  rights:
  - right: Access
    text: give you a copy of your personal data
  - right: Rectification
    text: correct data that is wrong
  - right: Erasure
    text: delete your data
  - right: Restrict or object
    text: restrict or object to how we use it
  - right: Portability
    text: give you your data in a portable format
  - right: Withdraw consent
    text: Where we rely on consent, you can withdraw it at any time.
  role:
    text: The data controller is Farrant Consulting Ltd , trading as CloudRF.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, and we do not use third-party mailing list or marketing software.
  subprocessors:
    text: 'The third parties that process personal data for us are: Provider Purpose Stripe Card payments and fraud verification PayPal PayPal payments, if you choose it Microsoft Our email. Messages you send us, and that we send you, pass through Microsoft’s mail service Google Analytics Website traffic statistics, only if you accept non-necessary cookies'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CloudRF
provenance_date: '2026-11-09'
provider_name: CloudRF
provider_slug: cloudrf
slug: cloudrf-privacy-policy
source_date: '2026-11-09'
source_filename: cloudrf-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cloudrf.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CloudRF\naid: cloudrf\nurl: https://cloudrf.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Farrant Consulting Ltd , trading as CloudRF.\ndata_categories:\n- category: identifying\n  text: Username, email address and password (stored hashed)\n- category: contact\n  text: First and last name and billing address\n- category: financial\n  text: We do not hold card details. Payments are handled by our payment providers, and we hold only a random token.\n- category: device\n  text: Logs of account activity, including IP address and approximate location\n- category:\
  \ communication\n  text: Support tickets and emails\npurposes:\n- purpose: Operate service and provide ordered products\n  text: We use your personal data only to operate the website and API and to provide the services and products you\n    order.\n- purpose: Account creation and security\n  text: To create and secure your account\n- purpose: Fraud prevention and misuse investigation\n  text: To secure the service and investigate misuse\n- purpose: Website traffic statistics\n  text: We use Google Analytics to measure website traffic in aggregate, such as which pages are visited and how\n    often.\nretention:\n- scope: Account details\n  period: Reviewed every 12 months\n  text: Reviewed every 12 months; inactive accounts and past transactions are deleted\n- scope: Calculations on the Free plan\n  period: 30 days\n  text: Calculations on the Free plan 30 days\n- scope: Calculations on the Bronze plan\n  period: 2 years\n  text: Calculations on the Bronze plan 2 years\n- scope: Calculations\
  \ on the Silver, Gold and Platinum plans\n  period: 3 years\n  text: Calculations on the Silver, Gold and Platinum plans 3 years\nresidency:\n- region: United Kingdom\n  text: Your account, your support tickets and the calculations you generate are stored and processed only within\n    our own network in the United Kingdom, on dedicated servers in our UK data centre.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'The third parties that process personal data for us are: Provider Purpose Stripe Card payments and fraud\n    verification PayPal PayPal payments, if you choose it Microsoft Our email. Messages you send us, and that we\n    send you, pass through Microsoft’s mail service Google Analytics Website traffic statistics, only if you accept\n    non-necessary cookies'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@cloudrf.com from the address on your account\n  text: To use any of these rights, email support@cloudrf.com from the address\
  \ on your account.\nrights:\n- right: Access\n  text: give you a copy of your personal data\n- right: Rectification\n  text: correct data that is wrong\n- right: Erasure\n  text: delete your data\n- right: Restrict or object\n  text: restrict or object to how we use it\n- right: Portability\n  text: give you your data in a portable format\n- right: Withdraw consent\n  text: Where we rely on consent, you can withdraw it at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, and we do not use third-party mailing list or marketing software.\n"
source_yaml_url: https://artifacts.apis.io/cloudrf/privacy/cloudrf-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from CloudRF's own page on 2026-11-09.
synthetic: false
tags:
- Coverage Modeling
- HF Propagation
- Mesh Network
- Radio Frequency
- RF
- Satellite
- Signal Analysis
- Telecommunications
- Wireless Planning
---
