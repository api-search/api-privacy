---
api_specs:
- filename: splitforms-openapi.json
  format: json
  label: Form Submission API
  slug: form-submission-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/splitforms/openapi/splitforms-openapi.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up, we store your email address and (optionally) a display name.
  - category: contact
    text: we also store your customer legal name and mailing address, authorized signer’s name, role, contact email, agreement version and acceptance time with your account for contractual records.
  - category: device
    text: the visitor's IP address, user agent, and referer.
  - category: behavioral
    text: We log basic request metadata (IP, path, status code) for operational monitoring and abuse prevention.
  deletion:
    route: dashboard deletion of submissions or account, or email to hello@splitforms.com
    text: You can delete individual submissions or your entire account at any time from the dashboard.
  dpa:
    available: true
    text: If you record electronic acceptance of the DPA, we also store your customer legal name and mailing address
    url: null
  purposes:
  - purpose: operational monitoring and abuse prevention
    text: We log basic request metadata (IP, path, status code) for operational monitoring and abuse prevention.
  - purpose: support and spam prevention
    text: Submissions are visible only to you (the form owner) and our service operators for support and spam-prevention purposes.
  retention:
  - period: no automatic expiry
    scope: form submissions
    text: 'Submissions have no automatic expiry on any plan, Free included: they are kept until you delete them or delete your account.'
  - period: 180 days
    scope: deleted submissions
    text: A deleted submission moves to the recycle bin and is permanently deleted after 180 days, or immediately if you empty the bin.
  - period: within 30 days
    scope: account deletion backups
    text: When you delete your account, its primary data is removed and associated backups rotate within 30 days.
  - period: 30 days
    scope: stored files after plan lapse
    text: Stored files are kept for 30 days after the lapse and then deleted; submissions themselves are not deleted.
  rights:
  - right: access, correct, export, delete
    text: You can access, correct, export, or delete any of your data at any time from the dashboard.
  - right: GDPR/CCPA requests
    text: For GDPR/CCPA-specific requests, email hello@splitforms.com and we'll respond within 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or rent your data.
  subprocessors:
    text: 'We use the following services to operate splitforms.com: Supabase / AWS (database, auth, file storage) — submissions, account data, and connected storage uploads are stored on Supabase-managed AWS infrastructure.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Split Forms
provenance_date: '2026-11-10'
provider_name: Split Forms
provider_slug: splitforms
slug: splitforms-privacy-policy
source_date: '2026-11-10'
source_filename: splitforms-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://splitforms.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Split Forms\naid: splitforms\nurl: https://splitforms.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up, we store your email address and (optionally) a display name.\n- category: contact\n  text: we also store your customer legal name and mailing address, authorized signer’s name, role, contact email,\n    agreement version and acceptance time with your account for contractual records.\n- category: device\n  text: the visitor's IP address, user agent, and referer.\n- category: behavioral\n  text: We log basic\
  \ request metadata (IP, path, status code) for operational monitoring and abuse prevention.\npurposes:\n- purpose: operational monitoring and abuse prevention\n  text: We log basic request metadata (IP, path, status code) for operational monitoring and abuse prevention.\n- purpose: support and spam prevention\n  text: Submissions are visible only to you (the form owner) and our service operators for support and spam-prevention\n    purposes.\nretention:\n- scope: form submissions\n  period: no automatic expiry\n  text: 'Submissions have no automatic expiry on any plan, Free included: they are kept until you delete them or\n    delete your account.'\n- scope: deleted submissions\n  period: 180 days\n  text: A deleted submission moves to the recycle bin and is permanently deleted after 180 days, or immediately\n    if you empty the bin.\n- scope: account deletion backups\n  period: within 30 days\n  text: When you delete your account, its primary data is removed and associated backups rotate\
  \ within 30 days.\n- scope: stored files after plan lapse\n  period: 30 days\n  text: Stored files are kept for 30 days after the lapse and then deleted; submissions themselves are not deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use the following services to operate splitforms.com: Supabase / AWS (database, auth, file storage)\n    — submissions, account data, and connected storage uploads are stored on Supabase-managed AWS infrastructure.'\ndpa:\n  available: true\n  url: null\n  text: If you record electronic acceptance of the DPA, we also store your customer legal name and mailing address\ndeletion:\n  route: dashboard deletion of submissions or account, or email to hello@splitforms.com\n  text: You can delete individual submissions or your entire account at any time from the dashboard.\nrights:\n- right: access, correct, export, delete\n  text: You can access, correct, export, or delete any of your data at any time from the dashboard.\n- right:\
  \ GDPR/CCPA requests\n  text: For GDPR/CCPA-specific requests, email hello@splitforms.com and we'll respond within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or rent your data.\n"
source_yaml_url: https://artifacts.apis.io/splitforms/privacy/splitforms-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Split Forms's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Form Backend
- Developer Tools
- Free Tier
- Webhook
---
