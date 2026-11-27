---
api_specs:
- filename: oximy-init-api-openapi.yml
  format: yaml
  label: Oximy Init API
  slug: oximy-init-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oximy/openapi/oximy-init-api-openapi.yml
- filename: oximy-policy-api-openapi.yml
  format: yaml
  label: Oximy Policy API
  slug: oximy-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oximy/openapi/oximy-policy-api-openapi.yml
- filename: oximy-telemetry-api-openapi.yml
  format: yaml
  label: Oximy Telemetry API
  slug: oximy-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oximy/openapi/oximy-telemetry-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: names email addresses job titles contact or authentication data
  - category: device
    text: device and usage information, such as your IP address, browser and device characteristics, operating system, language preferences, referring URLs, device name, country, location
  - category: location
    text: We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about how and when you use our Services
  - category: financial
    text: Transaction information, purchase history, financial details, and payment information
  deletion:
    route: email
    text: To request to review, update, or delete your personal information, please email support@oximy.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver and facilitate services
    text: To deliver and facilitate delivery of services to the user.
  - purpose: security and fraud prevention
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  - purpose: analytics
    text: for our internal analytics and reporting purposes
  retention:
  - period: 6 months
    scope: Category A identifiers
    text: Category A - 6 months
  - period: 6 months
    scope: Category B California customer records
    text: Category B - 6 months
  - period: As long as the user has an account with us
    scope: Category D commercial information
    text: Category D - As long as the user has an account with us
  rights:
  - right: access
    text: Right to access your personal data
  - right: correction
    text: Right to correct inaccuracies in your personal data
  - right: deletion
    text: Right to request the deletion of your personal data
  - right: portability
    text: Right to obtain a copy of the personal data you previously shared with us
  - right: opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We will not sell or share personal information in the future belonging to website visitors, users, and other consumers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Oximy
provenance_date: '2026-11-10'
provider_name: Oximy
provider_slug: oximy
slug: oximy-privacy-policy
source_date: '2026-11-10'
source_filename: oximy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://oximy.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Oximy\naid: oximy\nurl: https://oximy.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: names email addresses job titles contact or authentication data\n- category: device\n  text: device and usage information, such as your IP address, browser and device characteristics, operating system,\n    language preferences, referring URLs, device name, country, location\n- category: location\n  text: We collect location data such as information about\
  \ your device's location, which can be either precise or\n    imprecise.\n- category: behavioral\n  text: information about how and when you use our Services\n- category: financial\n  text: Transaction information, purchase history, financial details, and payment information\npurposes:\n- purpose: deliver and facilitate services\n  text: To deliver and facilitate delivery of services to the user.\n- purpose: security and fraud prevention\n  text: To protect our Services. We may process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\n- purpose: analytics\n  text: for our internal analytics and reporting purposes\nretention:\n- scope: Category A identifiers\n  period: 6 months\n  text: Category A - 6 months\n- scope: Category B California customer records\n  period: 6 months\n  text: Category B - 6 months\n- scope: Category D commercial information\n  period: As long as the user has an account with us\n  text:\
  \ Category D - As long as the user has an account with us\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: To request to review, update, or delete your personal information, please email support@oximy.com .\nrights:\n- right: access\n  text: Right to access your personal data\n- right: correction\n  text: Right to correct inaccuracies in your personal data\n- right: deletion\n  text: Right to request the deletion of your personal data\n- right: portability\n  text: Right to obtain a copy of the personal data you previously shared with us\n- right: opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects\
  \ (\"profiling\")\nsale_or_sharing:\n  stance: conditional\n  text: We will not sell or share personal information in the future belonging to website visitors, users, and other\n    consumers.\n"
source_yaml_url: https://artifacts.apis.io/oximy/privacy/oximy-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Oximy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- LLM Observability
- AI Adoption
- Telemetry
- Policy Enforcement
- Artificial Intelligence
- Developer Tools
---
