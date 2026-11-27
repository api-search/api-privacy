---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, hashed password, full name, postal code
  - category: financial
    text: Card name, last four digits, statement balance, credit limit, statement close date, next payment due date, minimum payment amount, overdue flag
  - category: device
    text: IP address at sign-in, user-agent string, sign-in timestamps, audit logs of access to your data
  - category: behavioral
    text: App interactions, recommendation history, feature usage, support requests
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: We rely on contractual safeguards (data-processing agreements with each sub-processor)
    url: null
  purposes:
  - purpose: Deliver the Service
    text: compute your next-move recommendation and show your account information to you
  - purpose: Bill the subscription
    text: process payments through Stripe and manage your plan
  - purpose: Communicate about the Service
    text: send transactional messages such as receipts, security alerts, and material policy changes
  - purpose: Security and fraud prevention
    text: detect unauthorized access and protect your account
  - purpose: Improve the recommendation engine
    text: analyze de-identified or aggregated usage data
  residency:
  - region: United States
    text: Most of our sub-processors are based in the United States.
  retention:
  - period: 90 days
    scope: Active accounts
    text: kept while your subscription is active, plus 90 days after cancellation for billing-dispute resolution
  - period: 7 days
    scope: Linked financial-account data
    text: deleted within 7 days of you unlinking the institution or closing your account
  - period: 30 days
    scope: Recommendation history
    text: deleted within 30 days of account closure
  - period: 90 days
    scope: Security and audit logs
    text: retained for 90 days
  - period: 7 years
    scope: Tax and accounting records
    text: retained for 7 years, with customer-identifying fields redacted where the law allows
  rights:
  - right: Access
    text: Access the personal information we hold about you.
  - right: Correction
    text: Request correction of inaccurate or incomplete information.
  - right: Withdraw consent
    text: Withdraw consent (subject to legal or contractual restrictions and reasonable notice).
  - right: Deletion
    text: Request deletion of your personal information, subject to our retention obligations under Section 8.
  - right: Portability
    text: Receive a copy of your personal information in a portable format.
  - right: Complaint
    text: File a complaint with the Office of the Privacy Commissioner of Canada if you are not satisfied with our response.
  role:
    text: This policy describes how Credit GPS Inc., an Ontario corporation, collects, uses, shares, and protects personal information when you use our website at creditgps.ca
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information. We do not share your personal information with advertisers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We rely on contractual safeguards (data-processing agreements with each sub-processor)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Credit GPS
provenance_date: '2026-11-09'
provider_name: Credit GPS
provider_slug: creditgps-ca
slug: creditgps-ca-privacy-policy
source_date: '2026-11-09'
source_filename: creditgps-ca-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://creditgps.ca/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Credit GPS\naid: creditgps-ca\nurl: https://creditgps.ca/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This policy describes how Credit GPS Inc., an Ontario corporation, collects, uses, shares, and protects\n    personal information when you use our website at creditgps.ca\ndata_categories:\n- category: contact\n  text: Email address, hashed password, full name, postal code\n- category: financial\n  text: Card name, last four digits, statement balance, credit limit, statement close date, next payment due date,\n    minimum payment amount, overdue flag\n- category: device\n  text:\
  \ IP address at sign-in, user-agent string, sign-in timestamps, audit logs of access to your data\n- category: behavioral\n  text: App interactions, recommendation history, feature usage, support requests\npurposes:\n- purpose: Deliver the Service\n  text: compute your next-move recommendation and show your account information to you\n- purpose: Bill the subscription\n  text: process payments through Stripe and manage your plan\n- purpose: Communicate about the Service\n  text: send transactional messages such as receipts, security alerts, and material policy changes\n- purpose: Security and fraud prevention\n  text: detect unauthorized access and protect your account\n- purpose: Improve the recommendation engine\n  text: analyze de-identified or aggregated usage data\nretention:\n- scope: Active accounts\n  period: 90 days\n  text: kept while your subscription is active, plus 90 days after cancellation for billing-dispute resolution\n- scope: Linked financial-account data\n  period: 7\
  \ days\n  text: deleted within 7 days of you unlinking the institution or closing your account\n- scope: Recommendation history\n  period: 30 days\n  text: deleted within 30 days of account closure\n- scope: Security and audit logs\n  period: 90 days\n  text: retained for 90 days\n- scope: Tax and accounting records\n  period: 7 years\n  text: retained for 7 years, with customer-identifying fields redacted where the law allows\nresidency:\n- region: United States\n  text: Most of our sub-processors are based in the United States.\ntransfers:\n- mechanism: other\n  text: We rely on contractual safeguards (data-processing agreements with each sub-processor)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: We rely on contractual safeguards (data-processing agreements with each sub-processor)\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Access the personal information we hold about you.\n- right: Correction\n  text: Request\
  \ correction of inaccurate or incomplete information.\n- right: Withdraw consent\n  text: Withdraw consent (subject to legal or contractual restrictions and reasonable notice).\n- right: Deletion\n  text: Request deletion of your personal information, subject to our retention obligations under Section 8.\n- right: Portability\n  text: Receive a copy of your personal information in a portable format.\n- right: Complaint\n  text: File a complaint with the Office of the Privacy Commissioner of Canada if you are not satisfied with our\n    response.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information. We do not share your personal information with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/creditgps-ca/privacy/creditgps-ca-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Credit GPS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit Score
- Personal Finance
- Fintech
- Canada
- Credit Cards
- Financial Education
---
