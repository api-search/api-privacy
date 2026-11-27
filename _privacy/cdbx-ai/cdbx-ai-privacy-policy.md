---
api_specs:
- filename: cdbx-ai-openapi-generated.yml
  format: yaml
  label: cdbx API
  slug: cdbx-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdbx-ai/openapi/_ae-authored/cdbx-ai-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: your display name, username (used as your CDBX username), primary email address and avatar
  - category: contact
    text: 'Email code: your email address.'
  - category: financial
    text: We store your Stripe customer ID and subscription status
  - category: behavioral
    text: Pages visited and features used within the app
  - category: behavioral
    text: PostHog may also record sessions — what was shown on screen and where you clicked
  - category: device
    text: Browser type, operating system, and IP address for security and abuse prevention
  - category: communication
    text: your messages and the associated code context (the files in your app)
  deletion:
    route: account deletion request
    text: If you ask us to delete your account, we will delete your personal data and the items you created within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: Authenticate your account, run your code, invoke AI models, serve your published experiments, and process payments.
  - purpose: improve the service
    text: Understand which features are used, diagnose errors, and prioritize improvements.
  - purpose: communication
    text: Send transactional emails (e.g., billing receipts, account security alerts).
  - purpose: security and abuse prevention
    text: Monitor for suspicious activity, enforce usage limits, and investigate violations of our Terms of Service.
  - purpose: legal compliance
    text: Respond to lawful requests from government or law enforcement authorities, and enforce our legal rights.
  residency:
  - region: EU or US
    text: Apps that run on a server are stored on Amazon Web Services in the EU or the US, whichever is closer to you when you create the App.
  - region: other countries, including the US
    text: which may process them in other countries, including the US.
  retention:
  - period: as long as your account is active
    scope: account data and created items
    text: We retain your account data and the items you create for as long as your account is active.
  - period: 30 days
    scope: personal data and items after account deletion request
    text: If you ask us to delete your account, we will delete your personal data and the items you created within 30 days.
  - period: 90 days
    scope: AI request log
    text: This log is retained for 90 days
  - period: up to 7 years
    scope: Stripe billing records and invoices
    text: Stripe billing records and invoices may be retained for up to 7 years
  - period: up to 90 days after deletion
    scope: backups
    text: Backups may retain data for up to 90 days after deletion before being overwritten.
  - period: indefinitely
    scope: anonymized aggregated usage statistics
    text: Anonymized and aggregated usage statistics may be retained indefinitely for product analytics.
  rights:
  - right: access
    text: Request a copy of the data we hold about you.
  - right: correction
    text: Ask us to correct inaccurate data.
  - right: deletion
    text: Request deletion of your account and associated personal data.
  - right: portability
    text: Export your apps and code from within the app (as a ZIP, or to GitHub).
  - right: objection
    text: Object to processing of your data in certain circumstances.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to any third party, and we do not share it with advertisers.
  subprocessors:
    text: 'We share data with the following categories of third-party services:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cdbx
provenance_date: '2026-11-09'
provider_name: cdbx
provider_slug: cdbx-ai
slug: cdbx-ai-privacy-policy
source_date: '2026-11-09'
source_filename: cdbx-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cdbx.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cdbx\naid: cdbx-ai\nurl: https://cdbx.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your display name, username (used as your CDBX username), primary email address and avatar\n- category: contact\n  text: 'Email code: your email address.'\n- category: financial\n  text: We store your Stripe customer ID and subscription status\n- category: behavioral\n  text: Pages visited and features used within the app\n- category: behavioral\n  text: PostHog may also record sessions — what was shown on screen and where you clicked\n- category:\
  \ device\n  text: Browser type, operating system, and IP address for security and abuse prevention\n- category: communication\n  text: your messages and the associated code context (the files in your app)\npurposes:\n- purpose: provide the service\n  text: Authenticate your account, run your code, invoke AI models, serve your published experiments, and process\n    payments.\n- purpose: improve the service\n  text: Understand which features are used, diagnose errors, and prioritize improvements.\n- purpose: communication\n  text: Send transactional emails (e.g., billing receipts, account security alerts).\n- purpose: security and abuse prevention\n  text: Monitor for suspicious activity, enforce usage limits, and investigate violations of our Terms of Service.\n- purpose: legal compliance\n  text: Respond to lawful requests from government or law enforcement authorities, and enforce our legal rights.\nretention:\n- scope: account data and created items\n  period: as long as your account\
  \ is active\n  text: We retain your account data and the items you create for as long as your account is active.\n- scope: personal data and items after account deletion request\n  period: 30 days\n  text: If you ask us to delete your account, we will delete your personal data and the items you created within\n    30 days.\n- scope: AI request log\n  period: 90 days\n  text: This log is retained for 90 days\n- scope: Stripe billing records and invoices\n  period: up to 7 years\n  text: Stripe billing records and invoices may be retained for up to 7 years\n- scope: backups\n  period: up to 90 days after deletion\n  text: Backups may retain data for up to 90 days after deletion before being overwritten.\n- scope: anonymized aggregated usage statistics\n  period: indefinitely\n  text: Anonymized and aggregated usage statistics may be retained indefinitely for product analytics.\nresidency:\n- region: EU or US\n  text: Apps that run on a server are stored on Amazon Web Services in the EU or\
  \ the US, whichever is closer to\n    you when you create the App.\n- region: other countries, including the US\n  text: which may process them in other countries, including the US.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data with the following categories of third-party services:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request\n  text: If you ask us to delete your account, we will delete your personal data and the items you created within\n    30 days.\nrights:\n- right: access\n  text: Request a copy of the data we hold about you.\n- right: correction\n  text: Ask us to correct inaccurate data.\n- right: deletion\n  text: Request deletion of your account and associated personal data.\n- right: portability\n  text: Export your apps and code from within the app (as a ZIP, or to GitHub).\n- right: objection\n  text: Object to processing of your data in certain circumstances.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell your personal data to any third party, and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/cdbx-ai/privacy/cdbx-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from cdbx's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Development
- Workspace
- Collaboration
- Company
---
