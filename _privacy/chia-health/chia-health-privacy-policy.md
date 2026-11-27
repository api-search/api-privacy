---
api_specs:
- filename: chia-health-catalog-api-openapi.yml
  format: yaml
  label: Chia Health Catalog API
  slug: chia-health-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-catalog-api-openapi.yml
- filename: chia-health-handoff-sessions-api-openapi.yml
  format: yaml
  label: Chia Health Handoff sessions API
  slug: chia-health-handoff-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-handoff-sessions-api-openapi.yml
- filename: chia-health-settlements-api-openapi.yml
  format: yaml
  label: Chia Health Settlements API
  slug: chia-health-settlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-settlements-api-openapi.yml
- filename: chia-health-webhook-tests-api-openapi.yml
  format: yaml
  label: Chia Health Webhook tests API
  slug: chia-health-webhook-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chia-health/openapi/chia-health-webhook-tests-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers, such as your name, email address, physical address, telephone number, business contact information, and device identifiers (e.g., cookie IDs and IP address).
  - category: health
    text: Biometric information , such as a fingerprint or face scan.
  - category: health
    text: Information about your health.
  - category: behavioral
    text: Internet or other electronic network activity information , such as your browsing history, search history, preference information
  - category: location
    text: Non-precise geolocation data , such as your location as derived from your IP address.
  - category: financial
    text: Commercial information , such as information related to your transactions
  deletion:
    route: Email support@chia.health for deletion requests under California law
    text: Right to Delete. You may have the right to request that we delete personal information that we have collected from you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products and services
    text: To provide you products and services , such as making our Website available to you; providing customer service
  - purpose: Marketing and targeted advertising
    text: For marketing and targeted advertising , such as marketing our products or services or those of our affiliates, business partners, or other third parties.
  - purpose: AI training on de-identified information
    text: We may use this de-identified information to operate and improve our services, including to train, test, and evaluate the artificial intelligence (AI) and machine learning systems
  retention:
  - period: null
    scope: Personal Information generally
    text: Your Personal Information will be retained as long as necessary to fulfill the purposes we have outlined above unless we are required to do otherwise by applicable law.
  - period: minimum of 10 years
    scope: MCP audit trail
    text: This information is logged in our HIPAA-compliant audit trail and retained for a minimum of 10 years.
  rights:
  - right: Right to know
    text: Right to Know. You may have the right to request information about the categories of personal information we have collected about you
  - right: Right to correct
    text: Right to Correct. You may have the right to request that we correct inaccurate personal information that we maintain about you.
  - right: Right to opt out of sales and sharing
    text: Right to Opt Out of Sales and Sharing for Targeted Advertising. You may have the right to opt out of the sale or sharing of your personal information for targeted advertising.
  - right: Right to limit sensitive personal information
    text: Right to Limit Use and Disclosure of Sensitive personal information . You have the right to limit the use and disclosure of sensitive personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: we engage in routine practices involving third parties that could be considered a sale or sharing for targeted advertising
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chia Health
provenance_date: '2026-11-09'
provider_name: Chia Health
provider_slug: chia-health
slug: chia-health-privacy-policy
source_date: '2026-11-09'
source_filename: chia-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chia.health/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chia Health\naid: chia-health\nurl: https://chia.health/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers, such as your name, email address, physical address, telephone number, business contact information,\n    and device identifiers (e.g., cookie IDs and IP address).\n- category: health\n  text: Biometric information , such as a fingerprint or face scan.\n- category: health\n  text: Information about your health.\n- category: behavioral\n  text: Internet or other electronic network activity information ,\
  \ such as your browsing history, search history,\n    preference information\n- category: location\n  text: Non-precise geolocation data , such as your location as derived from your IP address.\n- category: financial\n  text: Commercial information , such as information related to your transactions\npurposes:\n- purpose: Provide products and services\n  text: To provide you products and services , such as making our Website available to you; providing customer service\n- purpose: Marketing and targeted advertising\n  text: For marketing and targeted advertising , such as marketing our products or services or those of our affiliates,\n    business partners, or other third parties.\n- purpose: AI training on de-identified information\n  text: We may use this de-identified information to operate and improve our services, including to train, test,\n    and evaluate the artificial intelligence (AI) and machine learning systems\nretention:\n- scope: Personal Information generally\n  period:\
  \ null\n  text: Your Personal Information will be retained as long as necessary to fulfill the purposes we have outlined\n    above unless we are required to do otherwise by applicable law.\n- scope: MCP audit trail\n  period: minimum of 10 years\n  text: This information is logged in our HIPAA-compliant audit trail and retained for a minimum of 10 years.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@chia.health for deletion requests under California law\n  text: Right to Delete. You may have the right to request that we delete personal information that we have collected\n    from you.\nrights:\n- right: Right to know\n  text: Right to Know. You may have the right to request information about the categories of personal information\n    we have collected about you\n- right: Right to correct\n  text: Right to Correct. You may have the right to request that we correct inaccurate\
  \ personal information that\n    we maintain about you.\n- right: Right to opt out of sales and sharing\n  text: Right to Opt Out of Sales and Sharing for Targeted Advertising. You may have the right to opt out of the\n    sale or sharing of your personal information for targeted advertising.\n- right: Right to limit sensitive personal information\n  text: Right to Limit Use and Disclosure of Sensitive personal information . You have the right to limit the use\n    and disclosure of sensitive personal information.\nsale_or_sharing:\n  stance: conditional\n  text: we engage in routine practices involving third parties that could be considered a sale or sharing for targeted\n    advertising\n"
source_yaml_url: https://artifacts.apis.io/chia-health/privacy/chia-health-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Chia Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Telehealth
- Healthcare
- Peptides
- GLP-1
- Weight Loss
- Partner API
- MCP
---
