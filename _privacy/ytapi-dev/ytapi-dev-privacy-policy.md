---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, avatar, sign-in provider id, session token, session IP address and user agent
  - category: financial
    text: Stripe customer id, Checkout Session id, price id, payment status, dispute and refund identifiers. Card numbers stay at Stripe
  - category: communication
    text: Messages you send through the contact form or to [email protected]
  - category: device
    text: browser and device type
  - category: location
    text: the country (derived from the IP address, which Umami does not store)
  deletion:
    route: Delete the account in the dashboard settings
    text: You can delete the account in the dashboard settings.
  dpa:
    available: true
    text: Business customers can request a data processing agreement at the same address.
    url: null
  purposes:
  - purpose: Create and secure account, send transactional email
    text: Create and secure your account, send transactional email
  - purpose: Operate the API, show usage, investigate abuse and billing disputes
    text: Operate the API, show usage, investigate abuse and billing disputes
  - purpose: Take payment, credit balance, handle refund or dispute
    text: Take payment, credit your balance, handle a refund or dispute
  - purpose: Website analytics via Umami Cloud
    text: We measure how the website and dashboard are used with Umami Cloud, a cookieless analytics service
  residency:
  - region: Germany and EU (servers)
    text: Germany (Nuremberg) and the EU
  - region: Global incl. United States (Cloudflare)
    text: Global, including the United States. Export files are stored in the EU
  retention:
  - period: Until you delete the account
    scope: Account data
    text: Until you delete the account
  - period: 31 to 62 days
    scope: API request log
    text: 31 to 62 days. Logs are deleted a calendar month at a time, once the newest entry of that month is 31 days old.
  - period: null
    scope: Cached API responses
    text: Cached API responses, including transcript text, in a shared server cache
  - period: Up to 20 minutes
    scope: Cached comment pages
    text: Up to 20 minutes; never stored after that
  - period: Tax retention period
    scope: Payment records
    text: Payment records for the tax retention period that applies to the operator
  rights:
  - right: Access, correct, delete
    text: you can ask to access, correct, or delete your personal data
  - right: Restrict or object
    text: to restrict or object to processing
  - right: Portability
    text: to receive a portable copy
  - right: Withdraw consent
    text: to withdraw consent where processing is based on consent
  - right: Complain to authority
    text: You can also complain to the data protection authority where you live or where the operator is established.
  role:
    text: We are the controller for account, billing, and service-operation data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on that processor’s Standard Contractual Clauses or an equivalent safeguard the processor offers
  - mechanism: DPF
    text: such as the EU-US Data Privacy Framework where the processor is certified
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ytapi-dev
provenance_date: '2026-11-10'
provider_name: ytapi-dev
provider_slug: ytapi-dev
slug: ytapi-dev-privacy-policy
source_date: '2026-11-10'
source_filename: ytapi-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ytapi.dev/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ytapi-dev\naid: ytapi-dev\nurl: https://ytapi.dev/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller for account, billing, and service-operation data.\ndata_categories:\n- category: identifying\n  text: Name, email, avatar, sign-in provider id, session token, session IP address and user agent\n- category: financial\n  text: Stripe customer id, Checkout Session id, price id, payment status, dispute and refund identifiers. Card\n    numbers stay at Stripe\n- category: communication\n  text: Messages you send through the contact form or to [email protected]\n\
  - category: device\n  text: browser and device type\n- category: location\n  text: the country (derived from the IP address, which Umami does not store)\npurposes:\n- purpose: Create and secure account, send transactional email\n  text: Create and secure your account, send transactional email\n- purpose: Operate the API, show usage, investigate abuse and billing disputes\n  text: Operate the API, show usage, investigate abuse and billing disputes\n- purpose: Take payment, credit balance, handle refund or dispute\n  text: Take payment, credit your balance, handle a refund or dispute\n- purpose: Website analytics via Umami Cloud\n  text: We measure how the website and dashboard are used with Umami Cloud, a cookieless analytics service\nretention:\n- scope: Account data\n  period: Until you delete the account\n  text: Until you delete the account\n- scope: API request log\n  period: 31 to 62 days\n  text: 31 to 62 days. Logs are deleted a calendar month at a time, once the newest entry of\
  \ that month is 31 days\n    old.\n- scope: Cached API responses\n  period: null\n  text: Cached API responses, including transcript text, in a shared server cache\n- scope: Cached comment pages\n  period: Up to 20 minutes\n  text: Up to 20 minutes; never stored after that\n- scope: Payment records\n  period: Tax retention period\n  text: Payment records for the tax retention period that applies to the operator\nresidency:\n- region: Germany and EU (servers)\n  text: Germany (Nuremberg) and the EU\n- region: Global incl. United States (Cloudflare)\n  text: Global, including the United States. Export files are stored in the EU\ntransfers:\n- mechanism: SCC\n  text: we rely on that processor’s Standard Contractual Clauses or an equivalent safeguard the processor offers\n- mechanism: DPF\n  text: such as the EU-US Data Privacy Framework where the processor is certified\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Business customers can request\
  \ a data processing agreement at the same address.\ndeletion:\n  route: Delete the account in the dashboard settings\n  text: You can delete the account in the dashboard settings.\nrights:\n- right: Access, correct, delete\n  text: you can ask to access, correct, or delete your personal data\n- right: Restrict or object\n  text: to restrict or object to processing\n- right: Portability\n  text: to receive a portable copy\n- right: Withdraw consent\n  text: to withdraw consent where processing is based on consent\n- right: Complain to authority\n  text: You can also complain to the data protection authority where you live or where the operator is established.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/ytapi-dev/privacy/ytapi-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from ytapi-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Transcripts
- YouTube
---
