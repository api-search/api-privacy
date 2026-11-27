---
api_specs:
- filename: bottled-email-openapi-generated.yml
  format: yaml
  label: Bottled API
  slug: bottled-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bottled-email/openapi/_ae-authored/bottled-email-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Google Account Data: Your name, email address, and profile picture via Google OAuth for authentication'
  - category: contact
    text: 'Email Addresses: Custom email addresses you create and their forwarding destinations'
  - category: financial
    text: 'Payment Information: Subscription status and plan tier are stored in our database.'
  - category: communication
    text: 'Email Metadata: Basic information about emails you send and receive (sender, recipient, subject, timestamp) for logging purposes'
  - category: behavioral
    text: Campaign Tracking Email campaigns sent on the Pro plan may include tracking pixels and wrapped links to measure open and click activity.
  - category: device
    text: When a recipient opens an email or clicks a link, we record the event type, timestamp, user agent, and approximate location (IP address).
  deletion:
    route: Delete your account
    text: If you delete your account, we will remove your personal data within 30 days, except where required by law to retain it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision
    text: This policy explains what data we collect and how we use it to provide our email forwarding and sending service.
  - purpose: campaign performance reporting
    text: This data is used solely to report campaign performance to the sender.
  - purpose: push notifications
    text: We use this data only to deliver notifications you have requested (e.g. new inbound email, domain verified).
  retention:
  - period: 3 days
    scope: Starter (Free) email history
    text: 'Starter (Free): 3 days'
  - period: 30 days
    scope: Essentials email history
    text: 'Essentials: 30 days'
  - period: 90 days
    scope: Pro email history
    text: 'Pro: 90 days'
  - period: 30 days
    scope: Account data after deletion
    text: If you delete your account, we will remove your personal data within 30 days, except where required by law to retain it.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your account and associated data
  - right: Export
    text: Export your data
  role:
    text: Spark Games Ltd is the data controller for the personal information described in this policy.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Third-Party Services Bottled uses the following third-party services: Google OAuth: For user authentication Cloudflare Email Routing: For receiving and forwarding emails Email delivery provider: For sending emails Stripe: For payment processing Neon PostgreSQL: For storing account and configuration data Vercel: For hosting and privacy-friendly web analytics (page views, no cookies, no personal data) Sparkbrain: For in-app chat support'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bottled
provenance_date: '2026-11-09'
provider_name: Bottled
provider_slug: bottled-email
slug: bottled-email-privacy-policy
source_date: '2026-11-09'
source_filename: bottled-email-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bottled.email/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bottled\naid: bottled-email\nurl: https://bottled.email/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Spark Games Ltd is the data controller for the personal information described in this policy.\ndata_categories:\n- category: identifying\n  text: 'Google Account Data: Your name, email address, and profile picture via Google OAuth for authentication'\n- category: contact\n  text: 'Email Addresses: Custom email addresses you create and their forwarding destinations'\n- category: financial\n  text: 'Payment Information: Subscription status and plan tier are stored in our database.'\n\
  - category: communication\n  text: 'Email Metadata: Basic information about emails you send and receive (sender, recipient, subject, timestamp)\n    for logging purposes'\n- category: behavioral\n  text: Campaign Tracking Email campaigns sent on the Pro plan may include tracking pixels and wrapped links to\n    measure open and click activity.\n- category: device\n  text: When a recipient opens an email or clicks a link, we record the event type, timestamp, user agent, and approximate\n    location (IP address).\npurposes:\n- purpose: service provision\n  text: This policy explains what data we collect and how we use it to provide our email forwarding and sending\n    service.\n- purpose: campaign performance reporting\n  text: This data is used solely to report campaign performance to the sender.\n- purpose: push notifications\n  text: We use this data only to deliver notifications you have requested (e.g. new inbound email, domain verified).\nretention:\n- scope: Starter (Free) email\
  \ history\n  period: 3 days\n  text: 'Starter (Free): 3 days'\n- scope: Essentials email history\n  period: 30 days\n  text: 'Essentials: 30 days'\n- scope: Pro email history\n  period: 90 days\n  text: 'Pro: 90 days'\n- scope: Account data after deletion\n  period: 30 days\n  text: If you delete your account, we will remove your personal data within 30 days, except where required by law\n    to retain it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Third-Party Services Bottled uses the following third-party services: Google OAuth: For user authentication\n    Cloudflare Email Routing: For receiving and forwarding emails Email delivery provider: For sending emails Stripe:\n    For payment processing Neon PostgreSQL: For storing account and configuration data Vercel: For hosting and privacy-friendly\n    web analytics (page views, no cookies, no personal data) Sparkbrain: For in-app chat support'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n \
  \ route: Delete your account\n  text: If you delete your account, we will remove your personal data within 30 days, except where required by law\n    to retain it.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your account and associated data\n- right: Export\n  text: Export your data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bottled-email/privacy/bottled-email-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 20 quoted statements, read from Bottled's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Software-as-a-Service
- Cloud
- Productivity
- CustomDomain
---
