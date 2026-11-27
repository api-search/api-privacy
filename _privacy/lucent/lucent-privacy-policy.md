---
api_specs:
- filename: lucent-insights-api-openapi.yml
  format: yaml
  label: Lucent Insights API
  slug: lucent-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-insights-api-openapi.yml
- filename: lucent-issues-api-openapi.yml
  format: yaml
  label: Lucent Issues API
  slug: lucent-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-issues-api-openapi.yml
- filename: lucent-sdk-api-openapi.yml
  format: yaml
  label: Lucent Sdk API
  slug: lucent-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-sdk-api-openapi.yml
- filename: lucent-signals-api-openapi.yml
  format: yaml
  label: Lucent Signals API
  slug: lucent-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lucent/openapi/lucent-signals-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: behavioral
    text: 'Session replay data: Information about how end users interact with our customers'' websites or applications, including browsing behavior, clicks, scrolling, and navigation patterns'
  - category: contact
    text: 'Contact information: Name, email address, phone number, and company information when you register for an account, request a demo, or contact us'
  - category: financial
    text: 'Payment information: Billing details processed through our third-party payment provider (Stripe). We do not store payment card numbers'
  - category: communication
    text: 'Communications: Content of messages you send us through email, chat, or other channels'
  - category: device
    text: 'Device and technical information: Browser type, operating system, IP address, and device identifiers'
  - category: identifying
    text: 'User identifiers: Email addresses, user IDs, or other identifiers used by our customers to identify their end users'
  deletion:
    route: null
    text: If we learn we have collected personal data from a child, we will delete it promptly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing our services
    text: To analyze session replays, diagnose issues, and deliver insights to our customers
  - purpose: Account management
    text: To create and manage customer accounts, process payments, and provide customer support
  - purpose: Service improvement
    text: To improve, develop, and enhance our products and services
  - purpose: Communications
    text: To send service-related communications and, with your consent, marketing messages
  - purpose: Security and compliance
    text: To protect against fraud, enforce our terms, and comply with legal obligations
  - purpose: Analytics
    text: To understand how our services are used and measure their effectiveness
  retention:
  - period: null
    scope: Personal data generally
    text: We retain personal data for as long as necessary to fulfill the purposes described in this Privacy Notice, unless a longer retention period is required or permitted by law.
  - period: null
    scope: Customer-processed data
    text: Data processed on behalf of our customers is retained according to our agreements with those customers.
  rights:
  - right: Access
    text: The right to access and obtain a copy of your personal data
  - right: Correction
    text: The right to correct inaccurate personal data
  - right: Deletion
    text: The right to delete your personal data
  - right: Opt out of certain processing
    text: The right to opt out of certain processing activities
  - right: Withdraw consent
    text: The right to withdraw consent where processing is based on consent
  role:
    text: we process data on behalf of our business customers
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any customer data or end-user data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lucent
provenance_date: '2026-11-09'
provider_name: Lucent
provider_slug: lucent
slug: lucent-privacy-policy
source_date: '2026-11-09'
source_filename: lucent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lucenthq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lucent\naid: lucent\nurl: https://lucenthq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: we process data on behalf of our business customers\ndata_categories:\n- category: behavioral\n  text: 'Session replay data: Information about how end users interact with our customers'' websites or applications,\n    including browsing behavior, clicks, scrolling, and navigation patterns'\n- category: contact\n  text: 'Contact information: Name, email address, phone number, and company information when you register for an\n    account, request a demo, or contact us'\n- category: financial\n\
  \  text: 'Payment information: Billing details processed through our third-party payment provider (Stripe). We do\n    not store payment card numbers'\n- category: communication\n  text: 'Communications: Content of messages you send us through email, chat, or other channels'\n- category: device\n  text: 'Device and technical information: Browser type, operating system, IP address, and device identifiers'\n- category: identifying\n  text: 'User identifiers: Email addresses, user IDs, or other identifiers used by our customers to identify their\n    end users'\npurposes:\n- purpose: Providing our services\n  text: To analyze session replays, diagnose issues, and deliver insights to our customers\n- purpose: Account management\n  text: To create and manage customer accounts, process payments, and provide customer support\n- purpose: Service improvement\n  text: To improve, develop, and enhance our products and services\n- purpose: Communications\n  text: To send service-related communications\
  \ and, with your consent, marketing messages\n- purpose: Security and compliance\n  text: To protect against fraud, enforce our terms, and comply with legal obligations\n- purpose: Analytics\n  text: To understand how our services are used and measure their effectiveness\nretention:\n- scope: Personal data generally\n  period: null\n  text: We retain personal data for as long as necessary to fulfill the purposes described in this Privacy Notice,\n    unless a longer retention period is required or permitted by law.\n- scope: Customer-processed data\n  period: null\n  text: Data processed on behalf of our customers is retained according to our agreements with those customers.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: If we learn we have collected personal data from a child, we will delete it promptly.\nrights:\n- right: Access\n  text: The right to access and obtain a copy\
  \ of your personal data\n- right: Correction\n  text: The right to correct inaccurate personal data\n- right: Deletion\n  text: The right to delete your personal data\n- right: Opt out of certain processing\n  text: The right to opt out of certain processing activities\n- right: Withdraw consent\n  text: The right to withdraw consent where processing is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any customer data or end-user data.\n"
source_yaml_url: https://artifacts.apis.io/lucent/privacy/lucent-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Lucent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Session Replay
- Product Analytics
- Bug Detection
- Observability
- Artificial Intelligence
- Developer Tools
- MCP
- Webhook
---
