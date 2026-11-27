---
api_specs:
- filename: everypage-co-account-api-openapi.yml
  format: yaml
  label: EveryPage Account API
  slug: everypage-co-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-account-api-openapi.yml
- filename: everypage-co-embedding-api-openapi.yml
  format: yaml
  label: EveryPage Embedding API
  slug: everypage-co-embedding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-embedding-api-openapi.yml
- filename: everypage-co-events-api-openapi.yml
  format: yaml
  label: EveryPage Events API
  slug: everypage-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-events-api-openapi.yml
- filename: everypage-co-files-api-openapi.yml
  format: yaml
  label: EveryPage Files API
  slug: everypage-co-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-files-api-openapi.yml
- filename: everypage-co-oauth-api-openapi.yml
  format: yaml
  label: EveryPage OAuth API
  slug: everypage-co-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-oauth-api-openapi.yml
- filename: everypage-co-variants-api-openapi.yml
  format: yaml
  label: EveryPage Variants API
  slug: everypage-co-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-variants-api-openapi.yml
- filename: everypage-co-webhooks-api-openapi.yml
  format: yaml
  label: EveryPage Webhooks API
  slug: everypage-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everypage-co/openapi/everypage-co-webhooks-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (name, email)
  - category: contact
    text: Account information (name, email)
  - category: behavioral
    text: Readership data for documents you share (page views, time spent, country)
  - category: location
    text: A reader's country is resolved in transit (via ip-api.com) and the IP is then discarded.
  - category: device
    text: the only cookie EveryPage itself sets is the first-party session cookie that keeps you signed in
  - category: other
    text: Where you first came from (the referring site or a campaign tag in the link) and the first page you landed on.
  deletion:
    route: Delete account from account settings
    text: You can delete your account and all associated data at any time from your account settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain services
    text: Provide and maintain our services
  - purpose: Process transactions
    text: Process transactions
  - purpose: Send important updates
    text: Send you important updates
  - purpose: Improve services
    text: Improve our services
  - purpose: Tailor offers inside the app
    text: so we can tailor offers inside the app
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your data for as long as your account is active.
  rights:
  - right: Access
    text: You can access, correct, export, or delete your personal data at any time
  - right: Correct
    text: You can access, correct, export, or delete your personal data at any time
  - right: Export
    text: You can access, correct, export, or delete your personal data at any time
  - right: Delete
    text: You can ask us to delete any of it at any time.
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
name: EveryPage
provenance_date: '2026-11-09'
provider_name: EveryPage
provider_slug: everypage-co
slug: everypage-co-privacy-policy
source_date: '2026-11-09'
source_filename: everypage-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://everypage.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EveryPage\naid: everypage-co\nurl: https://everypage.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (name, email)\n- category: contact\n  text: Account information (name, email)\n- category: behavioral\n  text: Readership data for documents you share (page views, time spent, country)\n- category: location\n  text: A reader's country is resolved in transit (via ip-api.com) and the IP is then discarded.\n- category: device\n  text: the only cookie EveryPage itself sets is the first-party session cookie that\
  \ keeps you signed in\n- category: other\n  text: Where you first came from (the referring site or a campaign tag in the link) and the first page you landed\n    on.\npurposes:\n- purpose: Provide and maintain services\n  text: Provide and maintain our services\n- purpose: Process transactions\n  text: Process transactions\n- purpose: Send important updates\n  text: Send you important updates\n- purpose: Improve services\n  text: Improve our services\n- purpose: Tailor offers inside the app\n  text: so we can tailor offers inside the app\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your data for as long as your account is active.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account from account settings\n  text: You can delete your account and all associated data at any time from your account settings.\nrights:\n- right: Access\n\
  \  text: You can access, correct, export, or delete your personal data at any time\n- right: Correct\n  text: You can access, correct, export, or delete your personal data at any time\n- right: Export\n  text: You can access, correct, export, or delete your personal data at any time\n- right: Delete\n  text: You can ask us to delete any of it at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/everypage-co/privacy/everypage-co-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from EveryPage's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Document Sharing
- ReaderAnalytics
- Privacy
- Software-as-a-Service
---
