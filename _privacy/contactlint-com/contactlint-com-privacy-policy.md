---
api_specs:
- filename: contactlint-com-openapi.json
  format: json
  label: ContactLint API
  slug: contactlint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-openapi.json
- filename: contactlint-com-demo-api-openapi.yml
  format: yaml
  label: contactlint-com Demo API
  slug: contactlint-com-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-demo-api-openapi.yml
- filename: contactlint-com-demo-preview-api-openapi.yml
  format: yaml
  label: contactlint-com Demo Preview API
  slug: contactlint-com-demo-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-demo-preview-api-openapi.yml
- filename: contactlint-com-demo-preview-rotation-api-openapi.yml
  format: yaml
  label: contactlint-com Demo Preview Rotation API
  slug: contactlint-com-demo-preview-rotation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-demo-preview-rotation-api-openapi.yml
- filename: contactlint-com-domain-api-openapi.yml
  format: yaml
  label: contactlint-com Domain API
  slug: contactlint-com-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-domain-api-openapi.yml
- filename: contactlint-com-go-api-openapi.yml
  format: yaml
  label: contactlint-com Go API
  slug: contactlint-com-go-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-go-api-openapi.yml
- filename: contactlint-com-health-api-openapi.yml
  format: yaml
  label: contactlint-com Health API
  slug: contactlint-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-health-api-openapi.yml
- filename: contactlint-com-lookup-api-openapi.yml
  format: yaml
  label: contactlint-com Lookup API
  slug: contactlint-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-lookup-api-openapi.yml
- filename: contactlint-com-metrics-api-openapi.yml
  format: yaml
  label: contactlint-com Metrics API
  slug: contactlint-com-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-metrics-api-openapi.yml
- filename: contactlint-com-monitor-api-openapi.yml
  format: yaml
  label: contactlint-com Monitor API
  slug: contactlint-com-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-monitor-api-openapi.yml
- filename: contactlint-com-payment-change-check-api-openapi.yml
  format: yaml
  label: contactlint-com Payment Change Check API
  slug: contactlint-com-payment-change-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-payment-change-check-api-openapi.yml
- filename: contactlint-com-report-api-openapi.yml
  format: yaml
  label: contactlint-com Report API
  slug: contactlint-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-report-api-openapi.yml
- filename: contactlint-com-reports-api-openapi.yml
  format: yaml
  label: contactlint-com Reports API
  slug: contactlint-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-reports-api-openapi.yml
- filename: contactlint-com-robots-txt-api-openapi.yml
  format: yaml
  label: contactlint-com Robots.txt API
  slug: contactlint-com-robots-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-robots-txt-api-openapi.yml
- filename: contactlint-com-sitemap-xml-api-openapi.yml
  format: yaml
  label: contactlint-com Sitemap.xml API
  slug: contactlint-com-sitemap-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contactlint-com/openapi/contactlint-com-sitemap-xml-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address is used to enforce the limit of 3 keys per email. We store a one-way hash of it (SHA-256), not the address.
  - category: financial
    text: 'Stripe Checkout collects your card and billing details. We store the purchase record: key, credits added or removed, reason, Stripe reference and time.'
  - category: device
    text: Your IP address is used for rate limits. It is grouped (IPv6 by /48) and stored only as a hash inside short-lived counters.
  - category: behavioral
    text: Cookieless page-view and load-time measurement through a small script on each page.
  deletion:
    route: Account deletion page or DELETE /v1/account API call with key prefix confirmation; or email support@contactlint.com
    text: 'Delete: go to contactlint.com/account/delete , paste your key (and, optionally, your signup email to delete every key made with it), review what will be deleted, and type your key prefix to confirm.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Enforcing signup key limit
    text: Your email address is used to enforce the limit of 3 keys per email.
  - purpose: Rate limiting
    text: Your IP address is used for rate limits.
  - purpose: Payments and credits
    text: 'We store the purchase record: key, credits added or removed, reason, Stripe reference and time.'
  - purpose: Service delivery and abuse prevention
    text: We do not use what you check to build lists, train models, or contact anyone.
  residency:
  - region: United States
    text: Our providers process data in the United States.
  retention:
  - period: null
    scope: Emails and phone numbers you check
    text: Not stored. The code writes no checked address or number to the database
  - period: Until the limit window passes
    scope: Rate-limit counters (hashed IP)
    text: Until the limit window passes; old windows are cleared as new requests arrive.
  - period: Until you delete your account
    scope: Key, usage records, auto-reload settings, referrals, widget keys
    text: Until you delete your account.
  - period: Up to 12 months
    scope: Checklist requests
    text: Up to 12 months, or until you ask us to delete them.
  - period: null
    scope: Error logs
    text: A few days, at most 7 (Cloudflare Workers Logs).
  - period: 30 days
    scope: Nightly database backups
    text: Our own nightly database backups roll off after 30 days
  rights:
  - right: Access/export
    text: You can ask us to tell you what we hold about you and give you a copy
  - right: Correction
    text: correct it
  - right: Deletion
    text: delete it
  - right: Opt out of contact
    text: or stop contacting you.
  - right: Non-discrimination
    text: We will not treat you differently for using these rights.
  - right: Withdraw consent (GDPR)
    text: You can withdraw consent at any time; that does not affect what happened before.
  - right: Complain to authority (GDPR)
    text: You can complain to your local data protection authority
  role:
    text: ContactLint is a trade name of Crypto Boutique LLC, a Missouri limited liability company run by John Alewine in Kansas City, Missouri ("we", "us").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, do not share it for cross-context behavioral advertising
  subprocessors:
    text: We use these service providers. Each gets only what it needs for the job listed.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: contactlint-com
provenance_date: '2026-11-09'
provider_name: contactlint-com
provider_slug: contactlint-com
slug: contactlint-com-privacy-policy
source_date: '2026-11-09'
source_filename: contactlint-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://contactlint.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: contactlint-com\naid: contactlint-com\nurl: https://contactlint.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ContactLint is a trade name of Crypto Boutique LLC, a Missouri limited liability company run by John Alewine\n    in Kansas City, Missouri (\"we\", \"us\").\ndata_categories:\n- category: contact\n  text: Your email address is used to enforce the limit of 3 keys per email. We store a one-way hash of it (SHA-256),\n    not the address.\n- category: financial\n  text: 'Stripe Checkout collects your card and billing details. We store the purchase record: key, credits added\n\
  \    or removed, reason, Stripe reference and time.'\n- category: device\n  text: Your IP address is used for rate limits. It is grouped (IPv6 by /48) and stored only as a hash inside short-lived\n    counters.\n- category: behavioral\n  text: Cookieless page-view and load-time measurement through a small script on each page.\npurposes:\n- purpose: Enforcing signup key limit\n  text: Your email address is used to enforce the limit of 3 keys per email.\n- purpose: Rate limiting\n  text: Your IP address is used for rate limits.\n- purpose: Payments and credits\n  text: 'We store the purchase record: key, credits added or removed, reason, Stripe reference and time.'\n- purpose: Service delivery and abuse prevention\n  text: We do not use what you check to build lists, train models, or contact anyone.\nretention:\n- scope: Emails and phone numbers you check\n  period: null\n  text: Not stored. The code writes no checked address or number to the database\n- scope: Rate-limit counters (hashed\
  \ IP)\n  period: Until the limit window passes\n  text: Until the limit window passes; old windows are cleared as new requests arrive.\n- scope: Key, usage records, auto-reload settings, referrals, widget keys\n  period: Until you delete your account\n  text: Until you delete your account.\n- scope: Checklist requests\n  period: Up to 12 months\n  text: Up to 12 months, or until you ask us to delete them.\n- scope: Error logs\n  period: null\n  text: A few days, at most 7 (Cloudflare Workers Logs).\n- scope: Nightly database backups\n  period: 30 days\n  text: Our own nightly database backups roll off after 30 days\nresidency:\n- region: United States\n  text: Our providers process data in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use these service providers. Each gets only what it needs for the job listed.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion page or DELETE /v1/account API call with key prefix confirmation;\
  \ or email support@contactlint.com\n  text: 'Delete: go to contactlint.com/account/delete , paste your key (and, optionally, your signup email to delete\n    every key made with it), review what will be deleted, and type your key prefix to confirm.'\nrights:\n- right: Access/export\n  text: You can ask us to tell you what we hold about you and give you a copy\n- right: Correction\n  text: correct it\n- right: Deletion\n  text: delete it\n- right: Opt out of contact\n  text: or stop contacting you.\n- right: Non-discrimination\n  text: We will not treat you differently for using these rights.\n- right: Withdraw consent (GDPR)\n  text: You can withdraw consent at any time; that does not affect what happened before.\n- right: Complain to authority (GDPR)\n  text: You can complain to your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, do not share it for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/contactlint-com/privacy/contactlint-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from contactlint-com's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Phone Validation
- MCP
- Developer Tools
- Company
---
