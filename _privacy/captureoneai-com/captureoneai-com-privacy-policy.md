---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up via Google OAuth, we receive your name, email address, and profile picture from Google.
  - category: financial
    text: Payment information is processed by our payment processor (Stripe or similar) and we only receive a transaction reference.
  - category: device
    text: Server logs may include your IP address, browser type, pages visited, and timestamps.
  - category: behavioral
    text: Every API request is logged with the endpoint called, HTTP status code, response time, and the API key used (masked).
  - category: other
    text: When you call our API with a URL, we navigate to that URL server-side to capture a screenshot.
  deletion:
    route: Delete account
    text: If you delete your account, we delete your personal data within 30 days
  dpa:
    available: null
    text: 'Cloud infrastructure providers: Our servers and databases are hosted on providers that process data under data processing agreements.'
    url: null
  purposes:
  - purpose: Create and manage account
    text: To create and manage your account
  - purpose: Provide, operate, and improve the Service
    text: To provide, operate, and improve the Service
  - purpose: Process payments and enforce usage limits
    text: To process payments and enforce usage limits per your plan
  - purpose: Detect and prevent abuse, fraud
    text: To detect and prevent abuse, fraud, or illegal activity
  - purpose: Anonymised aggregated analytics
    text: To generate anonymised, aggregated analytics about Service usage
  residency:
  - region: European Union
    text: Our servers are located in the European Union.
  retention:
  - period: null
    scope: Account data
    text: We retain account data for as long as your account is active.
  - period: 90 days
    scope: API usage logs
    text: API usage logs are retained for 90 days for billing and abuse-prevention purposes.
  - period: 30 days
    scope: Deleted account data
    text: If you delete your account, we delete your personal data within 30 days, except where retention is required by law
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your account and associated data.'
  - right: Portability
    text: 'Portability: Receive your data in a structured, machine-readable format.'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests.'
  - right: Withdraw consent
    text: 'Withdraw consent: Where processing is based on consent, withdraw it at any time.'
  role:
    text: CaptureOneAI (“we”, “us”, or “our”) operates the website https://captureoneai.com and provides a screenshot API service
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for any such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CaptureOneAI
provenance_date: '2026-11-09'
provider_name: CaptureOneAI
provider_slug: captureoneai-com
slug: captureoneai-com-privacy-policy
source_date: '2026-11-09'
source_filename: captureoneai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://captureoneai.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CaptureOneAI\naid: captureoneai-com\nurl: https://captureoneai.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CaptureOneAI (“we”, “us”, or “our”) operates the website https://captureoneai.com and provides a screenshot\n    API service\ndata_categories:\n- category: identifying\n  text: When you sign up via Google OAuth, we receive your name, email address, and profile picture from Google.\n- category: financial\n  text: Payment information is processed by our payment processor (Stripe or similar) and we only receive a transaction\n    reference.\n- category: device\n  text: Server\
  \ logs may include your IP address, browser type, pages visited, and timestamps.\n- category: behavioral\n  text: Every API request is logged with the endpoint called, HTTP status code, response time, and the API key used\n    (masked).\n- category: other\n  text: When you call our API with a URL, we navigate to that URL server-side to capture a screenshot.\npurposes:\n- purpose: Create and manage account\n  text: To create and manage your account\n- purpose: Provide, operate, and improve the Service\n  text: To provide, operate, and improve the Service\n- purpose: Process payments and enforce usage limits\n  text: To process payments and enforce usage limits per your plan\n- purpose: Detect and prevent abuse, fraud\n  text: To detect and prevent abuse, fraud, or illegal activity\n- purpose: Anonymised aggregated analytics\n  text: To generate anonymised, aggregated analytics about Service usage\nretention:\n- scope: Account data\n  period: null\n  text: We retain account data for as long\
  \ as your account is active.\n- scope: API usage logs\n  period: 90 days\n  text: API usage logs are retained for 90 days for billing and abuse-prevention purposes.\n- scope: Deleted account data\n  period: 30 days\n  text: If you delete your account, we delete your personal data within 30 days, except where retention is required\n    by law\nresidency:\n- region: European Union\n  text: Our servers are located in the European Union.\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place for any such transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: 'Cloud infrastructure providers: Our servers and databases are hosted on providers that process data under\n    data processing agreements.'\ndeletion:\n  route: Delete account\n  text: If you delete your account, we delete your personal data within 30 days\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n-\
  \ right: Correction\n  text: 'Correction: Request correction of inaccurate data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your account and associated data.'\n- right: Portability\n  text: 'Portability: Receive your data in a structured, machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests.'\n- right: Withdraw consent\n  text: 'Withdraw consent: Where processing is based on consent, withdraw it at any time.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/captureoneai-com/privacy/captureoneai-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from CaptureOneAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Website Monitoring
- Change Detection
- Screenshots
- PDF Generation
- Web Capture
- Artificial Intelligence
- Alerts
---
