---
api_specs:
- filename: answercheckup-com-pricing-api-openapi.yml
  format: yaml
  label: Answer Checkup Pricing API
  slug: answercheckup-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-pricing-api-openapi.yml
- filename: answercheckup-com-report-api-openapi.yml
  format: yaml
  label: Answer Checkup Report API
  slug: answercheckup-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-report-api-openapi.yml
- filename: answercheckup-com-reports-api-openapi.yml
  format: yaml
  label: Answer Checkup Reports API
  slug: answercheckup-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-reports-api-openapi.yml
- filename: answercheckup-com-scan-api-openapi.yml
  format: yaml
  label: Answer Checkup Scan API
  slug: answercheckup-com-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-scan-api-openapi.yml
- filename: answercheckup-com-scan-details-api-openapi.yml
  format: yaml
  label: Answer Checkup Scan Details API
  slug: answercheckup-com-scan-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answercheckup-com/openapi/answercheckup-com-scan-details-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, entered on Stripe's checkout page.
  - category: identifying
    text: The website and business name you want the report about, plus any competitors you list.
  - category: financial
    text: We never receive or store your full payment details.
  - category: location
    text: your country
  - category: device
    text: your browser, operating system and device type (desktop, mobile or tablet)
  - category: communication
    text: If you email us, we receive your message and email address and use them to reply.
  deletion:
    route: Email us to ask for deletion
    text: You can ask us what we hold about you, or ask us to delete it, by email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run scans and deliver reports
    text: We collect only what we need to run scans, deliver reports, stop abuse and count, in anonymous hourly totals, how people find and use the site.
  - purpose: Stop abuse
    text: To limit abuse, we count scans per network and per site.
  - purpose: Send receipts and payment support
    text: Stripe and Link use it to send your receipt and for payment support.
  retention:
  - period: 30 days
    scope: Scan result
    text: We save the full scan result (the website address, the score, the checks and the fixes) under a random scan ID for 30 days
  - period: 90 days
    scope: Order record
    text: We keep it for 90 days.
  - period: 30 days
    scope: Finished report
    text: The finished report, which includes your website, business name, competitors and the answers, is kept for 30 days at a private link that is not listed or indexed.
  - period: 3 years after your plan ends
    scope: Subscription and box records
    text: We keep the subscription record and the box record for 3 years after your plan ends, so we can show what you agreed to.
  - period: 90 days
    scope: Hourly totals
    text: they are deleted after 90 days
  rights:
  - right: Access
    text: You can ask us what we hold about you
  - right: Deletion
    text: or ask us to delete it, by email.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Answer Checkup
provenance_date: '2026-11-09'
provider_name: Answer Checkup
provider_slug: answercheckup-com
slug: answercheckup-com-privacy-policy
source_date: '2026-11-09'
source_filename: answercheckup-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://answercheckup.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Answer Checkup\naid: answercheckup-com\nurl: https://answercheckup.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address, entered on Stripe's checkout page.\n- category: identifying\n  text: The website and business name you want the report about, plus any competitors you list.\n- category: financial\n  text: We never receive or store your full payment details.\n- category: location\n  text: your country\n- category: device\n  text: your browser, operating system and device type (desktop, mobile or tablet)\n- category:\
  \ communication\n  text: If you email us, we receive your message and email address and use them to reply.\npurposes:\n- purpose: Run scans and deliver reports\n  text: We collect only what we need to run scans, deliver reports, stop abuse and count, in anonymous hourly totals,\n    how people find and use the site.\n- purpose: Stop abuse\n  text: To limit abuse, we count scans per network and per site.\n- purpose: Send receipts and payment support\n  text: Stripe and Link use it to send your receipt and for payment support.\nretention:\n- scope: Scan result\n  period: 30 days\n  text: We save the full scan result (the website address, the score, the checks and the fixes) under a random scan\n    ID for 30 days\n- scope: Order record\n  period: 90 days\n  text: We keep it for 90 days.\n- scope: Finished report\n  period: 30 days\n  text: The finished report, which includes your website, business name, competitors and the answers, is kept for\n    30 days at a private link that is not listed\
  \ or indexed.\n- scope: Subscription and box records\n  period: 3 years after your plan ends\n  text: We keep the subscription record and the box record for 3 years after your plan ends, so we can show what\n    you agreed to.\n- scope: Hourly totals\n  period: 90 days\n  text: they are deleted after 90 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email us to ask for deletion\n  text: You can ask us what we hold about you, or ask us to delete it, by email.\nrights:\n- right: Access\n  text: You can ask us what we hold about you\n- right: Deletion\n  text: or ask us to delete it, by email.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your data.\n"
source_yaml_url: https://artifacts.apis.io/answercheckup-com/privacy/answercheckup-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Answer Checkup's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Marketing
- Analytics
- Business
---
