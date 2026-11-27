---
api_specs:
- filename: bewary-account-api-openapi.yml
  format: yaml
  label: Bewary Account API
  slug: bewary-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-account-api-openapi.yml
- filename: bewary-app-api-openapi.yml
  format: yaml
  label: Bewary App API
  slug: bewary-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-app-api-openapi.yml
- filename: bewary-assess-api-openapi.yml
  format: yaml
  label: Bewary Assess API
  slug: bewary-assess-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-assess-api-openapi.yml
- filename: bewary-backtest-api-openapi.yml
  format: yaml
  label: Bewary Backtest API
  slug: bewary-backtest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-backtest-api-openapi.yml
- filename: bewary-batch-api-openapi.yml
  format: yaml
  label: Bewary Batch API
  slug: bewary-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-batch-api-openapi.yml
- filename: bewary-billing-api-openapi.yml
  format: yaml
  label: Bewary Billing API
  slug: bewary-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-billing-api-openapi.yml
- filename: bewary-bulk-api-openapi.yml
  format: yaml
  label: Bewary Bulk API
  slug: bewary-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-bulk-api-openapi.yml
- filename: bewary-calibration-api-openapi.yml
  format: yaml
  label: Bewary Calibration API
  slug: bewary-calibration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-calibration-api-openapi.yml
- filename: bewary-datasets-api-openapi.yml
  format: yaml
  label: Bewary Datasets API
  slug: bewary-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-datasets-api-openapi.yml
- filename: bewary-directory-api-openapi.yml
  format: yaml
  label: Bewary Directory API
  slug: bewary-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-directory-api-openapi.yml
- filename: bewary-domain-api-openapi.yml
  format: yaml
  label: Bewary Domain API
  slug: bewary-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-domain-api-openapi.yml
- filename: bewary-email-api-openapi.yml
  format: yaml
  label: Bewary Email API
  slug: bewary-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-email-api-openapi.yml
- filename: bewary-events-api-openapi.yml
  format: yaml
  label: Bewary Events API
  slug: bewary-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-events-api-openapi.yml
- filename: bewary-iban-api-openapi.yml
  format: yaml
  label: Bewary Iban API
  slug: bewary-iban-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-iban-api-openapi.yml
- filename: bewary-ip-api-openapi.yml
  format: yaml
  label: Bewary Ip API
  slug: bewary-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-ip-api-openapi.yml
- filename: bewary-keys-api-openapi.yml
  format: yaml
  label: Bewary Keys API
  slug: bewary-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-keys-api-openapi.yml
- filename: bewary-payment-handle-api-openapi.yml
  format: yaml
  label: Bewary Payment Handle API
  slug: bewary-payment-handle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-payment-handle-api-openapi.yml
- filename: bewary-phone-api-openapi.yml
  format: yaml
  label: Bewary Phone API
  slug: bewary-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-phone-api-openapi.yml
- filename: bewary-shortcode-api-openapi.yml
  format: yaml
  label: Bewary Shortcode API
  slug: bewary-shortcode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-shortcode-api-openapi.yml
- filename: bewary-url-api-openapi.yml
  format: yaml
  label: Bewary URL API
  slug: bewary-url-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-url-api-openapi.yml
- filename: bewary-wallet-api-openapi.yml
  format: yaml
  label: Bewary Wallet API
  slug: bewary-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-wallet-api-openapi.yml
- filename: bewary-watches-api-openapi.yml
  format: yaml
  label: Bewary Watches API
  slug: bewary-watches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-watches-api-openapi.yml
- filename: bewary-webhooks-api-openapi.yml
  format: yaml
  label: Bewary Webhooks API
  slug: bewary-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bewary/openapi/bewary-webhooks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your account is your email address, your keys are stored as hashes, and card details go straight to Stripe.
  - category: financial
    text: We keep your Stripe customer reference, your purchase history and, if you save a card for auto top-up, its brand and last four digits so your account page can show which card will be charged.
  - category: behavioral
    text: For each call with a key we log the time, the endpoint, the key, the credits charged and the result status, and your account page shows your recent calls.
  - category: device
    text: The free tools use a bot check, and your IP address is used for rate limiting and abuse prevention.
  deletion:
    route: Delete account from account page or by emailing privacy@bewary.app
    text: You can delete it at any time from your account page or by emailing us, and we will remove your personal data except records we must keep, such as billing history for tax purposes.
  dpa:
    available: true
    text: If you need a data processing agreement, write to privacy@bewary.app .
    url: null
  purposes:
  - purpose: Answer lookups and run the account
    text: We collect the minimum we need to answer your calls, run your account and bill you.
  - purpose: Abuse prevention and rate limiting
    text: The free tools use a bot check, and your IP address is used for rate limiting and abuse prevention.
  retention:
  - period: 13 months
    scope: API call logs
    text: 'API call logs: 13 months, or 30 days for calls made without a key.'
  - period: 30 days
    scope: Free checker calls without a key
    text: The count is deleted after two days, and the log of those calls after 30 days.
  - period: 12 months
    scope: Transcripts
    text: 'Transcripts: 12 months.'
  - period: while it is active
    scope: Account
    text: 'Your account: while it is active.'
  rights:
  - right: access
    text: you can ask us to show you the data we hold about you
  - right: correction
    text: correct it
  - right: deletion
    text: delete it
  - right: portability
    text: or send you a copy
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell or rent your personal data, your account, your keys or what you and your users send us.
  subprocessors:
    text: 'Speech to text: OpenAI''s Whisper API transcribes recordings from our trap lines.'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on recognized safeguards such as the Standard Contractual Clauses to protect your data in transit and at rest.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bewary
provenance_date: '2026-11-09'
provider_name: Bewary
provider_slug: bewary
slug: bewary-privacy-policy
source_date: '2026-11-09'
source_filename: bewary-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bewary.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bewary\naid: bewary\nurl: https://bewary.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your account is your email address, your keys are stored as hashes, and card details go straight to Stripe.\n- category: financial\n  text: We keep your Stripe customer reference, your purchase history and, if you save a card for auto top-up, its\n    brand and last four digits so your account page can show which card will be charged.\n- category: behavioral\n  text: For each call with a key we log the time, the endpoint, the key, the credits\
  \ charged and the result status,\n    and your account page shows your recent calls.\n- category: device\n  text: The free tools use a bot check, and your IP address is used for rate limiting and abuse prevention.\npurposes:\n- purpose: Answer lookups and run the account\n  text: We collect the minimum we need to answer your calls, run your account and bill you.\n- purpose: Abuse prevention and rate limiting\n  text: The free tools use a bot check, and your IP address is used for rate limiting and abuse prevention.\nretention:\n- scope: API call logs\n  period: 13 months\n  text: 'API call logs: 13 months, or 30 days for calls made without a key.'\n- scope: Free checker calls without a key\n  period: 30 days\n  text: The count is deleted after two days, and the log of those calls after 30 days.\n- scope: Transcripts\n  period: 12 months\n  text: 'Transcripts: 12 months.'\n- scope: Account\n  period: while it is active\n  text: 'Your account: while it is active.'\nresidency: []\ntransfers:\n\
  - mechanism: SCC\n  text: Where required, we rely on recognized safeguards such as the Standard Contractual Clauses to protect your\n    data in transit and at rest.\nsubprocessors:\n  url: null\n  text: 'Speech to text: OpenAI''s Whisper API transcribes recordings from our trap lines.'\ndpa:\n  available: true\n  url: null\n  text: If you need a data processing agreement, write to privacy@bewary.app .\ndeletion:\n  route: Delete account from account page or by emailing privacy@bewary.app\n  text: You can delete it at any time from your account page or by emailing us, and we will remove your personal\n    data except records we must keep, such as billing history for tax purposes.\nrights:\n- right: access\n  text: you can ask us to show you the data we hold about you\n- right: correction\n  text: correct it\n- right: deletion\n  text: delete it\n- right: portability\n  text: or send you a copy\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell or rent your personal data, your\
  \ account, your keys or what you and your users send us.\n"
source_yaml_url: https://artifacts.apis.io/bewary/privacy/bewary-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Bewary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Fraud Prevention
- MCP
---
