---
api_specs:
- filename: brellium-audits-api-openapi.yml
  format: yaml
  label: Brellium Audits API
  slug: brellium-audits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-audits-api-openapi.yml
- filename: brellium-auth-api-openapi.yml
  format: yaml
  label: Brellium Auth API
  slug: brellium-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-auth-api-openapi.yml
- filename: brellium-coding-api-openapi.yml
  format: yaml
  label: Brellium Coding API
  slug: brellium-coding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-coding-api-openapi.yml
- filename: brellium-documents-api-openapi.yml
  format: yaml
  label: Brellium Documents API
  slug: brellium-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-documents-api-openapi.yml
- filename: brellium-documents-multiple-api-openapi.yml
  format: yaml
  label: Brellium Documents Multiple API
  slug: brellium-documents-multiple-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-documents-multiple-api-openapi.yml
- filename: brellium-link-providers-api-openapi.yml
  format: yaml
  label: Brellium Link Providers API
  slug: brellium-link-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-link-providers-api-openapi.yml
- filename: brellium-question-sets-api-openapi.yml
  format: yaml
  label: Brellium Question Sets API
  slug: brellium-question-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-question-sets-api-openapi.yml
- filename: brellium-update-audits-flags-api-openapi.yml
  format: yaml
  label: Brellium Update Audits Flags API
  slug: brellium-update-audits-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-update-audits-flags-api-openapi.yml
- filename: brellium-users-api-openapi.yml
  format: yaml
  label: Brellium Users API
  slug: brellium-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brellium/openapi/brellium-users-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Information by which you may be personally identified, such as name, postal address, e-mail address, phone number, etc.
  - category: health
    text: Any medical record data or health information provided during the use of our Services.
  - category: location
    text: Details of your visits to our Website, including location data, logs, and other communication data and the resources that you access and use on the Website.
  - category: device
    text: Information about your internet connection, the equipment you use to access our Website, and usage details.
  deletion:
    route: request to Brellium
    text: You may ask us to delete all your Personal Data stored by us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: present website
    text: To present our Website and its contents to you.
  - purpose: provide services
    text: To provide you with our Services.
  - purpose: contractual obligations
    text: To carry out our obligations and enforce our rights arising from any contracts entered into between you and us.
  rights:
  - right: access and correction
    text: You can review and change your personal information by logging into the Website and visiting your account profile page.
  - right: deletion
    text: You may ask us to delete all your Personal Data stored by us.
  - right: restriction
    text: You have the right to restrict the processing of your Personal Data.
  - right: opt out of marketing advertising
    text: You may opt out of receiving this advertising by emailing privacy@brellium.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Brellium
provenance_date: '2026-11-09'
provider_name: Brellium
provider_slug: brellium
slug: brellium-privacy-policy
source_date: '2026-11-09'
source_filename: brellium-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.brellium.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Brellium\naid: brellium\nurl: https://www.brellium.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Information by which you may be personally identified, such as name, postal address, e-mail address, phone\n    number, etc.\n- category: health\n  text: Any medical record data or health information provided during the use of our Services.\n- category: location\n  text: Details of your visits to our Website, including location data, logs, and other communication data and the\n    resources that you access and use on the Website.\n\
  - category: device\n  text: Information about your internet connection, the equipment you use to access our Website, and usage details.\npurposes:\n- purpose: present website\n  text: To present our Website and its contents to you.\n- purpose: provide services\n  text: To provide you with our Services.\n- purpose: contractual obligations\n  text: To carry out our obligations and enforce our rights arising from any contracts entered into between you\n    and us.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to Brellium\n  text: You may ask us to delete all your Personal Data stored by us.\nrights:\n- right: access and correction\n  text: You can review and change your personal information by logging into the Website and visiting your account\n    profile page.\n- right: deletion\n  text: You may ask us to delete all your Personal Data stored by us.\n- right: restriction\n\
  \  text: You have the right to restrict the processing of your Personal Data.\n- right: opt out of marketing advertising\n  text: You may opt out of receiving this advertising by emailing privacy@brellium.com\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brellium/privacy/brellium-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
summary_line: 12 quoted statements, read from Brellium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Clinical Compliance
- Clinical Documentation
- Medical Coding
- Audit
- Behavioral Health
- Digital Health
---
