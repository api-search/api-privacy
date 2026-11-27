---
api_specs:
- filename: 7275-com-activity-api-openapi.yml
  format: yaml
  label: DEXUN Inc Activity API
  slug: 7275-com-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/7275-com/openapi/7275-com-activity-api-openapi.yml
- filename: 7275-com-identity-api-openapi.yml
  format: yaml
  label: DEXUN Inc Identity API
  slug: 7275-com-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/7275-com/openapi/7275-com-identity-api-openapi.yml
- filename: 7275-com-keys-api-openapi.yml
  format: yaml
  label: DEXUN Inc Keys API
  slug: 7275-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/7275-com/openapi/7275-com-keys-api-openapi.yml
- filename: 7275-com-public-api-openapi.yml
  format: yaml
  label: DEXUN Inc Public API
  slug: 7275-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/7275-com/openapi/7275-com-public-api-openapi.yml
- filename: 7275-com-quota-api-openapi.yml
  format: yaml
  label: DEXUN Inc Quota API
  slug: 7275-com-quota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/7275-com/openapi/7275-com-quota-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information : When you sign up, we collect your email, name (optional), password hash, and basic profile data from OAuth sign-in (avatar, username).'
  - category: other
    text: 'Ad account data : After you authorize via OAuth, we read your Google Ads / Meta Ads / TikTok Ads campaigns, keywords, bids, creatives, and performance metrics.'
  - category: financial
    text: We retain only the Stripe customer ID, subscription status, and billing address.
  - category: device
    text: 'Usage data : Access logs, browser type, IP, action history — used for security auditing and product improvement.'
  deletion:
    route: Danger Zone in Settings
    text: Delete — close your account with one click from the Danger Zone in Settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide and operate DEXUN AdWhiz (account management, AI ad optimization, reporting).
  - purpose: Process subscription payments
    text: Process subscription payments, refunds, and invoicing.
  - purpose: Analyze usage to improve the product
    text: Analyze usage to improve the product.
  - purpose: Comply with legal obligations
    text: Comply with legal obligations.
  residency:
  - region: US West (California)
    text: DEXUN AdWhiz is hosted in the AWS US West (California) region.
  rights:
  - right: Access
    text: Access — view your name, email, and account state in Settings .
  - right: Export
    text: Export — download a complete JSON snapshot of your data via /api/account/export (also linked from the Danger Zone in Settings).
  - right: Correct
    text: Correct — edit your display name and notification preferences directly in Settings.
  - right: Delete
    text: Delete — close your account with one click from the Danger Zone in Settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: DEXUN AdWhiz relies on the following vetted third-party services, each with their own privacy policy
    url: null
  transfers:
  - mechanism: other
    text: By using the Service from outside the United States, you consent to your data being transferred to and processed there.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DEXUN Inc
provenance_date: '2026-11-09'
provider_name: DEXUN Inc
provider_slug: 7275-com
slug: 7275-com-privacy-policy
source_date: '2026-11-09'
source_filename: 7275-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.7275.com/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DEXUN Inc\naid: 7275-com\nurl: https://www.7275.com/en/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information : When you sign up, we collect your email, name (optional), password hash, and basic\n    profile data from OAuth sign-in (avatar, username).'\n- category: other\n  text: 'Ad account data : After you authorize via OAuth, we read your Google Ads / Meta Ads / TikTok Ads campaigns,\n    keywords, bids, creatives, and performance metrics.'\n- category: financial\n  text: We retain only the Stripe customer\
  \ ID, subscription status, and billing address.\n- category: device\n  text: 'Usage data : Access logs, browser type, IP, action history — used for security auditing and product improvement.'\npurposes:\n- purpose: Provide and operate the service\n  text: Provide and operate DEXUN AdWhiz (account management, AI ad optimization, reporting).\n- purpose: Process subscription payments\n  text: Process subscription payments, refunds, and invoicing.\n- purpose: Analyze usage to improve the product\n  text: Analyze usage to improve the product.\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations.\nretention: []\nresidency:\n- region: US West (California)\n  text: DEXUN AdWhiz is hosted in the AWS US West (California) region.\ntransfers:\n- mechanism: other\n  text: By using the Service from outside the United States, you consent to your data being transferred to and processed\n    there.\nsubprocessors:\n  url: null\n  text: DEXUN AdWhiz relies on the following vetted\
  \ third-party services, each with their own privacy policy\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Danger Zone in Settings\n  text: Delete — close your account with one click from the Danger Zone in Settings.\nrights:\n- right: Access\n  text: Access — view your name, email, and account state in Settings .\n- right: Export\n  text: Export — download a complete JSON snapshot of your data via /api/account/export (also linked from the Danger\n    Zone in Settings).\n- right: Correct\n  text: Correct — edit your display name and notification preferences directly in Settings.\n- right: Delete\n  text: Delete — close your account with one click from the Danger Zone in Settings.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/7275-com/privacy/7275-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from DEXUN Inc's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Marketing
- Multi-Account
- Automation
---
