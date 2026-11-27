---
api_specs:
- filename: botmail-pro-account-api-openapi.yml
  format: yaml
  label: Botmail Account API
  slug: botmail-pro-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-account-api-openapi.yml
- filename: botmail-pro-billing-api-openapi.yml
  format: yaml
  label: Botmail Billing API
  slug: botmail-pro-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-billing-api-openapi.yml
- filename: botmail-pro-claim-api-openapi.yml
  format: yaml
  label: Botmail Claim API
  slug: botmail-pro-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-claim-api-openapi.yml
- filename: botmail-pro-events-api-openapi.yml
  format: yaml
  label: Botmail Events API
  slug: botmail-pro-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-events-api-openapi.yml
- filename: botmail-pro-keys-api-openapi.yml
  format: yaml
  label: Botmail Keys API
  slug: botmail-pro-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-keys-api-openapi.yml
- filename: botmail-pro-mail-api-openapi.yml
  format: yaml
  label: Botmail Mail API
  slug: botmail-pro-mail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-mail-api-openapi.yml
- filename: botmail-pro-mailboxes-api-openapi.yml
  format: yaml
  label: Botmail Mailboxes API
  slug: botmail-pro-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-mailboxes-api-openapi.yml
- filename: botmail-pro-meta-api-openapi.yml
  format: yaml
  label: Botmail Meta API
  slug: botmail-pro-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-meta-api-openapi.yml
- filename: botmail-pro-send-api-openapi.yml
  format: yaml
  label: Botmail Send API
  slug: botmail-pro-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-send-api-openapi.yml
- filename: botmail-pro-webhooks-api-openapi.yml
  format: yaml
  label: Botmail Webhooks API
  slug: botmail-pro-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botmail-pro/openapi/botmail-pro-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Sign-in identity from your provider (GitHub or Google): provider, account ID, username, email, whether it is verified'
  - category: communication
    text: 'Mail you send and receive: headers, bodies, attachments'
  - category: device
    text: 'Security signals: IP address, network (ASN), a device cookie set at sign-in'
  - category: behavioral
    text: 'Website analytics: pages viewed on botmail.pro, the referring site, campaign tags such as ?ref= or utm_source'
  - category: financial
    text: Cost and payment records required for accounting, detached from your account
  deletion:
    route: 'API: DELETE /v1/account, with a 30-day grace period'
    text: You can delete your account through the API ( DELETE /v1/account ). There is a 30-day grace period
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: To create and secure your account and contact you
  - purpose: Provide the mailbox
    text: To provide the mailbox. This is the core of the Service
  - purpose: Billing and cost tracking
    text: Limits, billing and cost tracking. Card details are handled by Stripe, never by us
  - purpose: Fraud and abuse prevention
    text: Fraud and abuse prevention, and your account's trust level
  - purpose: Spam and phishing classification
    text: To stop spam and phishing, messages you send are checked by an automated classifier before delivery.
  residency:
  - region: United States
    text: All data is stored in the United States (Amazon Web Services, region us-west-2, Oregon, and PlanetScale Postgres hosted in the same AWS region).
  retention:
  - period: Until you delete it or your account
    scope: Mail and account data
    text: Your mail and account data Until you delete it or your account
  - period: 30 days
    scope: Server logs
    text: Server logs (system journal) 30 days
  - period: 400 days
    scope: Website analytics page views
    text: Website analytics page views 400 days
  - period: 24 hours after creation
    scope: Unclaimed agent mailboxes
    text: Unclaimed agent mailboxes Deleted 24 hours after creation if no human claims them
  - period: about 2 days
    scope: Database backups
    text: Database backups Roll off within about 2 days
  rights:
  - right: Access, correct, export or delete
    text: You can access, correct, export or delete your data.
  - right: Object or complain to a regulator
    text: including to object or complain to a regulator
  role:
    text: Exon Enterprise LLC ("we") operates Botmail
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, show ads, or use your mail to train AI models.
  subprocessors:
    text: Only the service providers listed on our subprocessors page
    url: null
  transfers:
  - mechanism: other
    text: If you are outside the US, your data is transferred to and processed in the US.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Botmail
provenance_date: '2026-11-09'
provider_name: Botmail
provider_slug: botmail-pro
slug: botmail-pro-privacy-policy
source_date: '2026-11-09'
source_filename: botmail-pro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://botmail.pro/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Botmail\naid: botmail-pro\nurl: https://botmail.pro/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Exon Enterprise LLC (\"we\") operates Botmail\ndata_categories:\n- category: identifying\n  text: 'Sign-in identity from your provider (GitHub or Google): provider, account ID, username, email, whether\n    it is verified'\n- category: communication\n  text: 'Mail you send and receive: headers, bodies, attachments'\n- category: device\n  text: 'Security signals: IP address, network (ASN), a device cookie set at sign-in'\n- category: behavioral\n  text: 'Website analytics: pages viewed\
  \ on botmail.pro, the referring site, campaign tags such as ?ref= or utm_source'\n- category: financial\n  text: Cost and payment records required for accounting, detached from your account\npurposes:\n- purpose: Account creation and security\n  text: To create and secure your account and contact you\n- purpose: Provide the mailbox\n  text: To provide the mailbox. This is the core of the Service\n- purpose: Billing and cost tracking\n  text: Limits, billing and cost tracking. Card details are handled by Stripe, never by us\n- purpose: Fraud and abuse prevention\n  text: Fraud and abuse prevention, and your account's trust level\n- purpose: Spam and phishing classification\n  text: To stop spam and phishing, messages you send are checked by an automated classifier before delivery.\nretention:\n- scope: Mail and account data\n  period: Until you delete it or your account\n  text: Your mail and account data Until you delete it or your account\n- scope: Server logs\n  period: 30 days\n  text:\
  \ Server logs (system journal) 30 days\n- scope: Website analytics page views\n  period: 400 days\n  text: Website analytics page views 400 days\n- scope: Unclaimed agent mailboxes\n  period: 24 hours after creation\n  text: Unclaimed agent mailboxes Deleted 24 hours after creation if no human claims them\n- scope: Database backups\n  period: about 2 days\n  text: Database backups Roll off within about 2 days\nresidency:\n- region: United States\n  text: All data is stored in the United States (Amazon Web Services, region us-west-2, Oregon, and PlanetScale\n    Postgres hosted in the same AWS region).\ntransfers:\n- mechanism: other\n  text: If you are outside the US, your data is transferred to and processed in the US.\nsubprocessors:\n  url: null\n  text: Only the service providers listed on our subprocessors page\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'API: DELETE /v1/account, with a 30-day grace period'\n  text: You can delete your account through\
  \ the API ( DELETE /v1/account ). There is a 30-day grace period\nrights:\n- right: Access, correct, export or delete\n  text: You can access, correct, export or delete your data.\n- right: Object or complain to a regulator\n  text: including to object or complain to a regulator\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, show ads, or use your mail to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/botmail-pro/privacy/botmail-pro-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Botmail's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Email
- Messaging
- Automation
- Botmail
---
