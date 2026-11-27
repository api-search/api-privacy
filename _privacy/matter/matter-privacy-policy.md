---
api_specs:
- filename: matter-account-api-openapi.yml
  format: yaml
  label: Matter Account API
  slug: matter-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matter/openapi/matter-account-api-openapi.yml
- filename: matter-annotations-api-openapi.yml
  format: yaml
  label: Matter Annotations API
  slug: matter-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matter/openapi/matter-annotations-api-openapi.yml
- filename: matter-items-api-openapi.yml
  format: yaml
  label: Matter Items API
  slug: matter-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matter/openapi/matter-items-api-openapi.yml
- filename: matter-reading-sessions-api-openapi.yml
  format: yaml
  label: Matter Reading Sessions API
  slug: matter-reading-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matter/openapi/matter-reading-sessions-api-openapi.yml
- filename: matter-search-api-openapi.yml
  format: yaml
  label: Matter Search API
  slug: matter-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matter/openapi/matter-search-api-openapi.yml
- filename: matter-tags-api-openapi.yml
  format: yaml
  label: Matter Tags API
  slug: matter-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/matter/openapi/matter-tags-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity & contact: name, email address.'
  - category: financial
    text: 'Payment & billing: card details (processed by our payment processor), billing address, subscription tier.'
  - category: device
    text: 'Device & log data: IP address, device ID, browser type, operating system, language, referring URL, crash reports, pages viewed, time spent, and actions taken.'
  - category: behavioral
    text: 'Content & usage: articles you save, highlights, notes, tags, reading statistics, folders, AI summaries you generate, and feedback you submit.'
  - category: location
    text: 'Device & log data: IP address, device ID, browser type, operating system, language, referring URL, crash reports, pages viewed, time spent, and actions taken.'
  deletion:
    route: Settings → Account → Delete Account
    text: 'Deletion: Settings → Account → Delete Account will erase your library and personal data within 30 days (back-ups within 90 days).'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service and marketing uses
    text: to provide and improve the app, sync your library, personalise recommendations, protect our service, comply with law, and—if you say yes—send you marketing.
  residency:
  - region: United States
    text: We store data primarily in the United States.
  retention:
  - period: as long as you have an account, then 30 days
    scope: Account data
    text: 'Account data: as long as you have an account, then 30 days for active deletion and up to 90 days in encrypted back-ups.'
  - period: up to 90 days
    scope: Back-ups
    text: up to 90 days in encrypted back-ups
  rights:
  - right: Access and download
    text: 'Access / download: visit Settings → Account → Export Data to obtain a machine-readable copy.'
  - right: Correction
    text: 'Correction: edit profile details in Settings.'
  - right: Erasure and portability, objection
    text: you can access, correct, erase, or port your data and object to certain processing.
  - right: Marketing opt-out
    text: 'Marketing opt-out: click “Unsubscribe” in any marketing email or disable Marketing Push in Settings.'
  - right: Opt out of sale or sharing
    text: Opt out of the “sale” or “sharing” of personal information.
  - right: Limit sensitive data use
    text: Limit the use of sensitive personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal data.
  subprocessors:
    text: 'Service providers: hosting (Amazon Web Services), crash and error monitoring (Sentry), analytics (Mixpanel), email delivery (Sendgrid), payment processing (Stripe), beta testing (TestFlight), customer-support tools, and content-recommendation infrastructure.'
    url: null
  transfers:
  - mechanism: SCC
    text: If you reside outside the U.S., we transfer your data under Standard Contractual Clauses (SCCs) approved by the European Commission, the UK International Data Transfer Addendum, or other legally recognised transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Matter
provenance_date: '2026-11-10'
provider_name: Matter
provider_slug: matter
slug: matter-privacy-policy
source_date: '2026-11-10'
source_filename: matter-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.getmatter.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Matter\naid: matter\nurl: https://www.getmatter.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Identity & contact: name, email address.'\n- category: financial\n  text: 'Payment & billing: card details (processed by our payment processor), billing address, subscription tier.'\n- category: device\n  text: 'Device & log data: IP address, device ID, browser type, operating system, language, referring URL, crash\n    reports, pages viewed, time spent, and actions taken.'\n- category: behavioral\n  text: 'Content & usage: articles\
  \ you save, highlights, notes, tags, reading statistics, folders, AI summaries\n    you generate, and feedback you submit.'\n- category: location\n  text: 'Device & log data: IP address, device ID, browser type, operating system, language, referring URL, crash\n    reports, pages viewed, time spent, and actions taken.'\npurposes:\n- purpose: Service and marketing uses\n  text: to provide and improve the app, sync your library, personalise recommendations, protect our service, comply\n    with law, and—if you say yes—send you marketing.\nretention:\n- scope: Account data\n  period: as long as you have an account, then 30 days\n  text: 'Account data: as long as you have an account, then 30 days for active deletion and up to 90 days in encrypted\n    back-ups.'\n- scope: Back-ups\n  period: up to 90 days\n  text: up to 90 days in encrypted back-ups\nresidency:\n- region: United States\n  text: We store data primarily in the United States.\ntransfers:\n- mechanism: SCC\n  text: If you reside\
  \ outside the U.S., we transfer your data under Standard Contractual Clauses (SCCs) approved\n    by the European Commission, the UK International Data Transfer Addendum, or other legally recognised transfer\n    mechanisms.\nsubprocessors:\n  url: null\n  text: 'Service providers: hosting (Amazon Web Services), crash and error monitoring (Sentry), analytics (Mixpanel),\n    email delivery (Sendgrid), payment processing (Stripe), beta testing (TestFlight), customer-support tools, and\n    content-recommendation infrastructure.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Account → Delete Account\n  text: 'Deletion: Settings → Account → Delete Account will erase your library and personal data within 30 days\n    (back-ups within 90 days).'\nrights:\n- right: Access and download\n  text: 'Access / download: visit Settings → Account → Export Data to obtain a machine-readable copy.'\n- right: Correction\n  text: 'Correction: edit profile details in Settings.'\n\
  - right: Erasure and portability, objection\n  text: you can access, correct, erase, or port your data and object to certain processing.\n- right: Marketing opt-out\n  text: 'Marketing opt-out: click “Unsubscribe” in any marketing email or disable Marketing Push in Settings.'\n- right: Opt out of sale or sharing\n  text: Opt out of the “sale” or “sharing” of personal information.\n- right: Limit sensitive data use\n  text: Limit the use of sensitive personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/matter/privacy/matter-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Matter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Reading
- Read Later
- Productivity
- Content
- Highlights
- Bookmarking
---
