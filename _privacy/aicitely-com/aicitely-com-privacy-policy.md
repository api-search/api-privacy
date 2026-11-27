---
api_specs:
- filename: aicitely-com-health-api-openapi.yml
  format: yaml
  label: Citely Health API
  slug: aicitely-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicitely-com/openapi/aicitely-com-health-api-openapi.yml
- filename: aicitely-com-public-api-openapi.yml
  format: yaml
  label: Citely Public API
  slug: aicitely-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicitely-com/openapi/aicitely-com-public-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up, we collect your email address and authentication details through Firebase Auth.
  - category: financial
    text: We do not collect payment information — paid plans are handled directly via invoice or a future payment processor.
  deletion:
    route: Contact Citely to delete account and associated data
    text: You can delete your account and associated data by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Citely service
    text: 'We use your data to provide the Citely service: running AI visibility reports, storing query results, sending alerts, and improving the product.'
  - purpose: Analytics
    text: Cloudflare Zaraz is the single manager for Google Analytics 4 and Microsoft Clarity, which we use to understand how visitors use Citely.
  retention:
  - period: while your account is active
    scope: Account and report data
    text: We retain your account and report data while your account is active.
  - period: null
    scope: Public audit data
    text: Public audit data is not tied to any user and is not retained.
  - period: up to one year
    scope: Consent choice
    text: Your choice is stored in a first-party cookie for up to one year.
  rights:
  - right: Reject analytics or change saved choice
    text: You can reject analytics or change a saved choice at any time using Cookie settings in the site footer.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it to train third-party AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Citely
provenance_date: '2026-11-09'
provider_name: Citely
provider_slug: aicitely-com
slug: aicitely-com-privacy-policy
source_date: '2026-11-09'
source_filename: aicitely-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aicitely.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Citely\naid: aicitely-com\nurl: https://aicitely.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up, we collect your email address and authentication details through Firebase Auth.\n- category: financial\n  text: We do not collect payment information — paid plans are handled directly via invoice or a future payment\n    processor.\npurposes:\n- purpose: Provide the Citely service\n  text: 'We use your data to provide the Citely service: running AI visibility reports, storing query results, sending\n    alerts,\
  \ and improving the product.'\n- purpose: Analytics\n  text: Cloudflare Zaraz is the single manager for Google Analytics 4 and Microsoft Clarity, which we use to understand\n    how visitors use Citely.\nretention:\n- scope: Account and report data\n  period: while your account is active\n  text: We retain your account and report data while your account is active.\n- scope: Public audit data\n  period: null\n  text: Public audit data is not tied to any user and is not retained.\n- scope: Consent choice\n  period: up to one year\n  text: Your choice is stored in a first-party cookie for up to one year.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Citely to delete account and associated data\n  text: You can delete your account and associated data by contacting us.\nrights:\n- right: Reject analytics or change saved choice\n  text: You can reject analytics or change a saved choice\
  \ at any time using Cookie settings in the site footer.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use it to train third-party AI models.\n"
source_yaml_url: https://artifacts.apis.io/aicitely-com/privacy/aicitely-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Citely's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- BrandCitation
- SEO
- Analytics
---
