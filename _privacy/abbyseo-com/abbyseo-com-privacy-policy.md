---
api_specs:
- filename: abbyseo-com-email-results-api-openapi.yml
  format: yaml
  label: Abby SEO Email Results API
  slug: abbyseo-com-email-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abbyseo-com/openapi/abbyseo-com-email-results-api-openapi.yml
- filename: abbyseo-com-scan-api-openapi.yml
  format: yaml
  label: Abby SEO Scan API
  slug: abbyseo-com-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abbyseo-com/openapi/abbyseo-com-scan-api-openapi.yml
claim_count: 38
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Email Address: If you provide your email address to receive scan reports, purchase a product, or subscribe to a service, we collect and store it.'
  - category: financial
    text: 'Payment Information: When you make a purchase, payment details (credit card number, billing address) are collected and processed directly by our payment processor, Stripe, Inc.'
  - category: identifying
    text: 'IP Address: We collect your IP address for rate limiting, abuse prevention, security purposes, and to associate scan requests with sessions.'
  - category: device
    text: 'Browser and Device Information: We may collect your browser type, operating system, device type, and screen resolution through standard HTTP headers.'
  - category: behavioral
    text: 'Usage Data: We collect information about how you interact with the Service, including pages visited, scan requests made, features used, and timestamps of activity.'
  - category: behavioral
    text: 'Referrer Data: We may collect the URL of the page that referred you to our Service.'
  - category: professional
    text: a business contact email address, the website domain, and public technical information about the site
  deletion:
    route: Data deletion request form or email to privacy@abbyseo.com
    text: Request deletion of any data associated with your email address or scans via our data deletion request form
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Service
    text: To perform SEO and security scans, generate remediation guides, deliver monitoring reports, and process your purchases and subscriptions.
  - purpose: Payment processing
    text: To process payments, issue refunds, manage subscriptions, and maintain billing records.
  - purpose: Communication
    text: To send you scan reports, guide deliveries, subscription renewal notices, purchase receipts, and responses to your inquiries.
  - purpose: Rate limiting and security
    text: To prevent abuse, enforce usage limits, detect fraudulent transactions, and protect the integrity of our Service.
  - purpose: Service improvement
    text: To analyze usage patterns in aggregate to improve the Service's functionality and performance.
  - purpose: Legal compliance
    text: To comply with applicable laws, regulations, or legal processes.
  - purpose: Notifying site operators of issues
    text: to notify site operators of issues we have detected and to offer services relevant to those issues.
  residency:
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: 30 days
    scope: Free scan results
    text: 'Free Scan Results: Retained for 30 days from the date of the scan, then automatically and permanently deleted.'
  - period: 7 days
    scope: IP addresses (rate limiting)
    text: 'IP Addresses (Rate Limiting): Retained for no more than 7 days in rate-limiting logs, then automatically purged.'
  - period: 7 years
    scope: Purchase records
    text: 'Purchase Records: Retained for 7 years from the date of purchase for tax and accounting compliance, then deleted.'
  - period: duration of the subscription plus 90 days
    scope: Subscription data
    text: 'Subscription Data: Retained for the duration of the subscription plus 90 days after cancellation, then deleted.'
  - period: 1 year
    scope: Remediation guides (PDFs)
    text: 'Remediation Guides (PDFs): Stored on our servers for 1 year after purchase to allow re-downloads, then deleted.'
  - period: 12 months
    scope: Contact inquiries
    text: 'Contact Inquiries: Retained for up to 12 months for customer service purposes, then deleted.'
  - period: 90 days
    scope: Server logs
    text: 'Server Logs: Retained for up to 90 days for security and debugging purposes.'
  - period: 13 months
    scope: Analytics data (Umami)
    text: 'Analytics data (Umami): Kept on our self-hosted server for 13 months, then deleted automatically.'
  - period: indefinite
    scope: Suppression list
    text: 'Suppression List: Email addresses on the suppression list are retained indefinitely to ensure continued compliance with your unsubscribe request.'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate personal data.'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal data ("right to be forgotten") via our deletion request form or by emailing us.'
  - right: Restriction
    text: 'Restriction: Request that we restrict processing of your data.'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format.'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interest.'
  - right: Withdraw consent
    text: 'Withdraw Consent: Withdraw consent at any time where processing is based on consent.'
  - right: Know (California)
    text: 'Know: Request what personal information we collect, use, and disclose about you.'
  - right: Delete (California)
    text: 'Delete: Request deletion of your personal information.'
  - right: Correct (California)
    text: 'Correct: Request correction of inaccurate personal information.'
  role:
    text: Abby SEO ("we," "us," or "our") operates the website abbyseo.com and all related services
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share (as defined by the CCPA/CPRA) your personal information with third parties for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: For EEA/UK users, we rely on your explicit consent and the necessity of the transfer for performing our contract with you as the legal basis for international data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Abby SEO
provenance_date: '2026-11-09'
provider_name: Abby SEO
provider_slug: abbyseo-com
slug: abbyseo-com-privacy-policy
source_date: '2026-11-09'
source_filename: abbyseo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.abbyseo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Abby SEO\naid: abbyseo-com\nurl: https://www.abbyseo.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Abby SEO (\"we,\" \"us,\" or \"our\") operates the website abbyseo.com and all related services\ndata_categories:\n- category: contact\n  text: 'Email Address: If you provide your email address to receive scan reports, purchase a product, or subscribe\n    to a service, we collect and store it.'\n- category: financial\n  text: 'Payment Information: When you make a purchase, payment details (credit card number, billing address) are\n    collected and processed directly by our payment\
  \ processor, Stripe, Inc.'\n- category: identifying\n  text: 'IP Address: We collect your IP address for rate limiting, abuse prevention, security purposes, and to associate\n    scan requests with sessions.'\n- category: device\n  text: 'Browser and Device Information: We may collect your browser type, operating system, device type, and screen\n    resolution through standard HTTP headers.'\n- category: behavioral\n  text: 'Usage Data: We collect information about how you interact with the Service, including pages visited, scan\n    requests made, features used, and timestamps of activity.'\n- category: behavioral\n  text: 'Referrer Data: We may collect the URL of the page that referred you to our Service.'\n- category: professional\n  text: a business contact email address, the website domain, and public technical information about the site\npurposes:\n- purpose: Providing the Service\n  text: To perform SEO and security scans, generate remediation guides, deliver monitoring reports,\
  \ and process\n    your purchases and subscriptions.\n- purpose: Payment processing\n  text: To process payments, issue refunds, manage subscriptions, and maintain billing records.\n- purpose: Communication\n  text: To send you scan reports, guide deliveries, subscription renewal notices, purchase receipts, and responses\n    to your inquiries.\n- purpose: Rate limiting and security\n  text: To prevent abuse, enforce usage limits, detect fraudulent transactions, and protect the integrity of our\n    Service.\n- purpose: Service improvement\n  text: To analyze usage patterns in aggregate to improve the Service's functionality and performance.\n- purpose: Legal compliance\n  text: To comply with applicable laws, regulations, or legal processes.\n- purpose: Notifying site operators of issues\n  text: to notify site operators of issues we have detected and to offer services relevant to those issues.\nretention:\n- scope: Free scan results\n  period: 30 days\n  text: 'Free Scan Results: Retained\
  \ for 30 days from the date of the scan, then automatically and permanently deleted.'\n- scope: IP addresses (rate limiting)\n  period: 7 days\n  text: 'IP Addresses (Rate Limiting): Retained for no more than 7 days in rate-limiting logs, then automatically\n    purged.'\n- scope: Purchase records\n  period: 7 years\n  text: 'Purchase Records: Retained for 7 years from the date of purchase for tax and accounting compliance, then\n    deleted.'\n- scope: Subscription data\n  period: duration of the subscription plus 90 days\n  text: 'Subscription Data: Retained for the duration of the subscription plus 90 days after cancellation, then\n    deleted.'\n- scope: Remediation guides (PDFs)\n  period: 1 year\n  text: 'Remediation Guides (PDFs): Stored on our servers for 1 year after purchase to allow re-downloads, then\n    deleted.'\n- scope: Contact inquiries\n  period: 12 months\n  text: 'Contact Inquiries: Retained for up to 12 months for customer service purposes, then deleted.'\n- scope:\
  \ Server logs\n  period: 90 days\n  text: 'Server Logs: Retained for up to 90 days for security and debugging purposes.'\n- scope: Analytics data (Umami)\n  period: 13 months\n  text: 'Analytics data (Umami): Kept on our self-hosted server for 13 months, then deleted automatically.'\n- scope: Suppression list\n  period: indefinite\n  text: 'Suppression List: Email addresses on the suppression list are retained indefinitely to ensure continued\n    compliance with your unsubscribe request.'\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\ntransfers:\n- mechanism: other\n  text: For EEA/UK users, we rely on your explicit consent and the necessity of the transfer for performing our\n    contract with you as the legal basis for international data transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data deletion request form or email to privacy@abbyseo.com\n  text: Request\
  \ deletion of any data associated with your email address or scans via our data deletion request form\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Rectification: Request correction of inaccurate personal data.'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal data (\"right to be forgotten\") via our deletion request form\n    or by emailing us.'\n- right: Restriction\n  text: 'Restriction: Request that we restrict processing of your data.'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interest.'\n- right: Withdraw consent\n  text: 'Withdraw Consent: Withdraw consent at any time where processing is based on consent.'\n- right: Know (California)\n  text: 'Know: Request what personal information we collect, use, and disclose about you.'\n-\
  \ right: Delete (California)\n  text: 'Delete: Request deletion of your personal information.'\n- right: Correct (California)\n  text: 'Correct: Request correction of inaccurate personal information.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share (as defined by the CCPA/CPRA) your personal information with third parties for cross-context\n    behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/abbyseo-com/privacy/abbyseo-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 38 quoted statements, read from Abby SEO's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- Audit
- Tool
- Free
- Websites
- Analytics
---
