---
api_specs:
- filename: whatsync-app-account-api-openapi.yml
  format: yaml
  label: whatsync-app Account API
  slug: whatsync-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-account-api-openapi.yml
- filename: whatsync-app-business-and-pricing-api-openapi.yml
  format: yaml
  label: whatsync-app Business and pricing API
  slug: whatsync-app-business-and-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-business-and-pricing-api-openapi.yml
- filename: whatsync-app-business-templates-attio-workflows-api-openapi.yml
  format: yaml
  label: whatsync-app Business templates (Attio workflows) API
  slug: whatsync-app-business-templates-attio-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-business-templates-attio-workflows-api-openapi.yml
- filename: whatsync-app-campaigns-api-openapi.yml
  format: yaml
  label: whatsync-app Campaigns API
  slug: whatsync-app-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-campaigns-api-openapi.yml
- filename: whatsync-app-forms-api-openapi.yml
  format: yaml
  label: whatsync-app Forms API
  slug: whatsync-app-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-forms-api-openapi.yml
- filename: whatsync-app-groups-api-openapi.yml
  format: yaml
  label: whatsync-app Groups API
  slug: whatsync-app-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-groups-api-openapi.yml
- filename: whatsync-app-reading-and-account-api-openapi.yml
  format: yaml
  label: whatsync-app Reading and account API
  slug: whatsync-app-reading-and-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-reading-and-account-api-openapi.yml
- filename: whatsync-app-saving-and-filters-api-openapi.yml
  format: yaml
  label: whatsync-app Saving and filters API
  slug: whatsync-app-saving-and-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-saving-and-filters-api-openapi.yml
- filename: whatsync-app-sending-and-message-actions-api-openapi.yml
  format: yaml
  label: whatsync-app Sending and message actions API
  slug: whatsync-app-sending-and-message-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-sending-and-message-actions-api-openapi.yml
- filename: whatsync-app-webhooks-api-openapi.yml
  format: yaml
  label: whatsync-app Webhooks API
  slug: whatsync-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whatsync-app/openapi/whatsync-app-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: including names, email addresses, phone numbers, session identifiers, authentication tokens, and account administration records
  - category: communication
    text: including message text, media, documents, voice notes, images, and other attachments, timestamps, directionality
  - category: financial
    text: plan status, subscription, invoicing and billing metadata, payment processor references, messaging platform billing and usage data
  - category: location
    text: approximate geolocation inferred from network metadata
  - category: device
    text: browser, device, and operating system information
  - category: behavioral
    text: product interaction telemetry
  deletion:
    route: request or account closure
    text: Upon a valid deletion request or account closure, we will take commercially reasonable steps to delete or de-identify the relevant Personal Data within a reasonable period
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve the Service
    text: To provision, authenticate, operate, maintain, troubleshoot, support, and improve the Service.
  - purpose: security and fraud prevention
    text: To secure the Service and to detect, investigate, prevent, and respond to misuse, fraud, spam, abuse, unauthorized access, unlawful conduct, violations of the Terms or of Third-Party Service policies, and operational failures.
  - purpose: product analytics
    text: To analyze product usage, service quality, performance, and reliability, including through session replay, diagnostics, logging, and analytics technologies.
  - purpose: marketing communications
    text: and, only to Users who have actively opted in, marketing communications.
  retention:
  - period: null
    scope: active account
    text: We retain Personal Data for as long as reasonably necessary to maintain an active account and provide the features the Customer has enabled
  - period: at least 7 days after the email
    scope: account with no active plan
    text: which is at least 7 days after the email, we unlink the connected WhatsApp numbers and delete the saved messages and files
  rights:
  - right: access
    text: have rights to request access to Personal Data
  - right: deletion
    text: to delete Personal Data
  - right: opt out of targeted advertising, sale, sharing, or profiling
    text: to opt out of certain processing for targeted advertising, sale, sharing, or profiling
  - right: complaint to supervisory authority
    text: to lodge a complaint with a competent supervisory authority
  role:
    text: With respect to account administration, billing, fraud and abuse prevention, security, product analytics, service improvement, legal compliance, and dispute management, we may independently determine the purposes and means of processing.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: we do not sell the content of messages processed through the Service
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses approved by the European Commission
  - mechanism: adequacy
    text: which may include adequacy decisions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: whatsync-app
provenance_date: '2026-11-10'
provider_name: whatsync-app
provider_slug: whatsync-app
slug: whatsync-app-privacy-policy
source_date: '2026-11-10'
source_filename: whatsync-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://whatsync.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: whatsync-app\naid: whatsync-app\nurl: https://whatsync.app/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: With respect to account administration, billing, fraud and abuse prevention, security, product analytics,\n    service improvement, legal compliance, and dispute management, we may independently determine the purposes and\n    means of processing.\ndata_categories:\n- category: contact\n  text: including names, email addresses, phone numbers, session identifiers, authentication tokens, and account\n    administration records\n- category: communication\n  text: including message\
  \ text, media, documents, voice notes, images, and other attachments, timestamps, directionality\n- category: financial\n  text: plan status, subscription, invoicing and billing metadata, payment processor references, messaging platform\n    billing and usage data\n- category: location\n  text: approximate geolocation inferred from network metadata\n- category: device\n  text: browser, device, and operating system information\n- category: behavioral\n  text: product interaction telemetry\npurposes:\n- purpose: provide and improve the Service\n  text: To provision, authenticate, operate, maintain, troubleshoot, support, and improve the Service.\n- purpose: security and fraud prevention\n  text: To secure the Service and to detect, investigate, prevent, and respond to misuse, fraud, spam, abuse, unauthorized\n    access, unlawful conduct, violations of the Terms or of Third-Party Service policies, and operational failures.\n- purpose: product analytics\n  text: To analyze product usage,\
  \ service quality, performance, and reliability, including through session replay,\n    diagnostics, logging, and analytics technologies.\n- purpose: marketing communications\n  text: and, only to Users who have actively opted in, marketing communications.\nretention:\n- scope: active account\n  period: null\n  text: We retain Personal Data for as long as reasonably necessary to maintain an active account and provide the\n    features the Customer has enabled\n- scope: account with no active plan\n  period: at least 7 days after the email\n  text: which is at least 7 days after the email, we unlink the connected WhatsApp numbers and delete the saved\n    messages and files\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses approved by the European Commission\n- mechanism: adequacy\n  text: which may include adequacy decisions\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request or account\
  \ closure\n  text: Upon a valid deletion request or account closure, we will take commercially reasonable steps to delete or\n    de-identify the relevant Personal Data within a reasonable period\nrights:\n- right: access\n  text: have rights to request access to Personal Data\n- right: deletion\n  text: to delete Personal Data\n- right: opt out of targeted advertising, sale, sharing, or profiling\n  text: to opt out of certain processing for targeted advertising, sale, sharing, or profiling\n- right: complaint to supervisory authority\n  text: to lodge a complaint with a competent supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell the content of messages processed through the Service\n"
source_yaml_url: https://artifacts.apis.io/whatsync-app/privacy/whatsync-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from whatsync-app's own page on 2026-11-10.
synthetic: false
tags:
- WhatsApp
- Artificial Intelligence
- ChatGPT
- Claude
- Integration
- MCP
---
