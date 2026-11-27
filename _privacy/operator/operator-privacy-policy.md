---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address and authentication credentials are handled through our authentication provider, Clerk
  - category: financial
    text: our payment processor, Stripe, collects and stores your payment details
  - category: device
    text: standard log and device data such as IP address, browser type, and pages viewed
  - category: communication
    text: If you contact us, we keep your messages and contact details so we can respond.
  - category: behavioral
    text: instance identifiers, timestamps, request counts, and token consumption
  deletion:
    route: Delete account or instances via dashboard, or request full account deletion by email to support@operator.io
    text: you can delete your instances through the dashboard, which removes the associated container and files. To exercise any of these rights, or to request full account deletion or a copy of all data we hold about you, contact us at support@operator.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service, including provisioning instances and routing AI requests.
  - purpose: Process payments and subscriptions
    text: Process payments, manage subscriptions, and send transactional messages such as billing receipts and service notifications.
  - purpose: Security and abuse prevention
    text: Enforce usage limits and protect the Service against fraud, abuse, and security threats.
  - purpose: Support communications
    text: Respond to your support requests and communicate with you about the Service.
  residency:
  - region: United States
    text: We are based in the United States and process data there and in other countries where we or our providers operate.
  retention:
  - period: fourteen days
    scope: Instance data while account active
    text: After a billing suspension, we retain the affected instance data for fourteen days so we can restore it if Stripe confirms payment.
  - period: 30 days
    scope: Account deletion
    text: If you delete your account, we remove your instance data and personal information within 30 days, except where we must retain certain records longer, such as billing records kept for tax and accounting obligations.
  rights:
  - right: access
    text: the right to access a copy of it
  - right: correction
    text: to correct inaccurate data
  - right: deletion
    text: to delete it
  - right: restrict or object
    text: to restrict or object to certain processing
  - right: portability
    text: and to data portability
  - right: opt out of sale or sharing and targeted advertising
    text: and to opt out of the sale or sharing of personal information and of targeted advertising
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, we do not share it for cross-context behavioral advertising
  subprocessors:
    text: 'We rely on the following providers to operate the Service, and we share with each only the minimum data required for it to function: Clerk, for authentication and session management. Stripe, for payment processing and subscription billing. Microsoft Azure, for infrastructure including container hosting, file storage, and AI inference. Vercel, for hosting the dashboard and API.'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses for such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Operator.io
provenance_date: '2026-11-10'
provider_name: Operator.io
provider_slug: operator
slug: operator-privacy-policy
source_date: '2026-11-10'
source_filename: operator-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://operator.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Operator.io\naid: operator\nurl: https://operator.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your email address and authentication credentials are handled through our authentication provider, Clerk\n- category: financial\n  text: our payment processor, Stripe, collects and stores your payment details\n- category: device\n  text: standard log and device data such as IP address, browser type, and pages viewed\n- category: communication\n  text: If you contact us, we keep your messages and contact details so we can respond.\n\
  - category: behavioral\n  text: instance identifiers, timestamps, request counts, and token consumption\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service, including provisioning instances and routing AI requests.\n- purpose: Process payments and subscriptions\n  text: Process payments, manage subscriptions, and send transactional messages such as billing receipts and service\n    notifications.\n- purpose: Security and abuse prevention\n  text: Enforce usage limits and protect the Service against fraud, abuse, and security threats.\n- purpose: Support communications\n  text: Respond to your support requests and communicate with you about the Service.\nretention:\n- scope: Instance data while account active\n  period: fourteen days\n  text: After a billing suspension, we retain the affected instance data for fourteen days so we can restore it\n    if Stripe confirms payment.\n- scope: Account deletion\n  period: 30 days\n  text: If\
  \ you delete your account, we remove your instance data and personal information within 30 days, except\n    where we must retain certain records longer, such as billing records kept for tax and accounting obligations.\nresidency:\n- region: United States\n  text: We are based in the United States and process data there and in other countries where we or our providers\n    operate.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as the European Commission's Standard Contractual\n    Clauses for such transfers.\nsubprocessors:\n  url: null\n  text: 'We rely on the following providers to operate the Service, and we share with each only the minimum data\n    required for it to function: Clerk, for authentication and session management. Stripe, for payment processing\n    and subscription billing. Microsoft Azure, for infrastructure including container hosting, file storage, and\n    AI inference. Vercel, for hosting the dashboard and API.'\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account or instances via dashboard, or request full account deletion by email to support@operator.io\n  text: you can delete your instances through the dashboard, which removes the associated container and files. To\n    exercise any of these rights, or to request full account deletion or a copy of all data we hold about you, contact\n    us at support@operator.io .\nrights:\n- right: access\n  text: the right to access a copy of it\n- right: correction\n  text: to correct inaccurate data\n- right: deletion\n  text: to delete it\n- right: restrict or object\n  text: to restrict or object to certain processing\n- right: portability\n  text: and to data portability\n- right: opt out of sale or sharing and targeted advertising\n  text: and to opt out of the sale or sharing of personal information and of targeted advertising\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, we\
  \ do not share it for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/operator/privacy/operator-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Operator.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Productivity
- Automation
- Software-as-a-Service
---
