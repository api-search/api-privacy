---
api_specs:
- filename: sendspark-dvm-bundles-api-openapi.yml
  format: yaml
  label: Sendspark DVM Bundles API
  slug: sendspark-dvm-bundles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-dvm-bundles-api-openapi.yml
- filename: sendspark-dynamics-campaign-api-openapi.yml
  format: yaml
  label: Sendspark Dynamics Campaign API
  slug: sendspark-dynamics-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-dynamics-campaign-api-openapi.yml
- filename: sendspark-webhook-api-openapi.yml
  format: yaml
  label: Sendspark Webhook API
  slug: sendspark-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-webhook-api-openapi.yml
- filename: sendspark-workspace-api-openapi.yml
  format: yaml
  label: Sendspark Workspace API
  slug: sendspark-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendspark/openapi/sendspark-workspace-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact and/or account information such as your name, email address, physical address, phone number, username
  - category: contact
    text: your Voiceprint and a scan of your face geometry (only if you elect to use certain AI enabled functionality
  - category: device
    text: unique device identifiers (UDIDs), first party cookies (both session and persistent), third party cookies
  - category: location
    text: Through collecting your IP address, we may be able to approximate your geographic location
  - category: financial
    text: Our Payment Processor may collect information such as banking information or credit card number
  - category: biometric
    text: your Voiceprint and a scan of your face geometry
  deletion:
    route: email privacy@sendspark.com
    text: you may revise or edit your information through your account (If applicable) or by sending an email to privacy@sendspark.com .
  dpa:
    available: true
    text: Where we process personal data on behalf of our customers, that processing is governed by our Data Processing Addendum at https://www.sendspark.com/dpa .
    url: https://www.sendspark.com/dpa
  purposes:
  - purpose: provide the Service and products
    text: We accept and gather information in an effort to provide the Service and our products to you.
  - purpose: serve targeted advertisements
    text: We may use your PII to serve you advertisements with the Service that are targeted to your interests.
  - purpose: internal uses and analytics
    text: We may use your PII to respond to your inquiries, to fulfill your requests for information, track usage trends, conduct experiments, fraud prevention, develop and improve the Service and other offerings, and perform research and analytics.
  residency:
  - region: United States
    text: the information you provide will be securely stored in our servers and internal systems located within the US .
  retention:
  - period: null
    scope: Voiceprint
    text: in any event no later than three (3) months from the time it was created.
  - period: thirty (30) days after your account is deactivated
    scope: Original recordings and generated videos
    text: Original recordings and generated videos are deleted on request, or no later than thirty (30) days after your account is deactivated.
  - period: twelve (12) months
    scope: logs and technical records
    text: We keep our logs and other technical records for no longer than twelve (12) months.
  rights:
  - right: access
    text: The right of access. This is your right to see what data about you is held by us.
  - right: rectification
    text: The right to rectification. This is the right to have your data corrected or amended if what is held is incorrect in some way.
  - right: erasure
    text: The right to be forgotten. This is the right to have your personal data to be deleted
  - right: portability
    text: The right to data portability.
  - right: object
    text: The right to object.
  - right: restrict processing
    text: The right to restrict processing.
  role:
    text: Under the GDPR, Sendspark is a data “Controller.”
    value: controller
  sale_or_sharing:
    stance: unstated
    text: For the avoidance of doubt, we do not “sell” your “covered information”.
  subprocessors:
    text: The service providers that process personal data on our behalf, what each does and where, are listed in our Subprocessor List at https://www.sendspark.com/subprocessors .
    url: https://www.sendspark.com/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sendspark
provenance_date: '2026-11-10'
provider_name: Sendspark
provider_slug: sendspark
slug: sendspark-privacy-policy
source_date: '2026-11-10'
source_filename: sendspark-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sendspark.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sendspark\naid: sendspark\nurl: https://www.sendspark.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Under the GDPR, Sendspark is a data “Controller.”\ndata_categories:\n- category: identifying\n  text: Contact and/or account information such as your name, email address, physical address, phone number, username\n- category: contact\n  text: your Voiceprint and a scan of your face geometry (only if you elect to use certain AI enabled functionality\n- category: device\n  text: unique device identifiers (UDIDs), first party cookies (both session and persistent), third party cookies\n\
  - category: location\n  text: Through collecting your IP address, we may be able to approximate your geographic location\n- category: financial\n  text: Our Payment Processor may collect information such as banking information or credit card number\n- category: biometric\n  text: your Voiceprint and a scan of your face geometry\npurposes:\n- purpose: provide the Service and products\n  text: We accept and gather information in an effort to provide the Service and our products to you.\n- purpose: serve targeted advertisements\n  text: We may use your PII to serve you advertisements with the Service that are targeted to your interests.\n- purpose: internal uses and analytics\n  text: We may use your PII to respond to your inquiries, to fulfill your requests for information, track usage\n    trends, conduct experiments, fraud prevention, develop and improve the Service and other offerings, and perform\n    research and analytics.\nretention:\n- scope: Voiceprint\n  period: null\n  text: in\
  \ any event no later than three (3) months from the time it was created.\n- scope: Original recordings and generated videos\n  period: thirty (30) days after your account is deactivated\n  text: Original recordings and generated videos are deleted on request, or no later than thirty (30) days after\n    your account is deactivated.\n- scope: logs and technical records\n  period: twelve (12) months\n  text: We keep our logs and other technical records for no longer than twelve (12) months.\nresidency:\n- region: United States\n  text: the information you provide will be securely stored in our servers and internal systems located within the\n    US .\ntransfers: []\nsubprocessors:\n  url: https://www.sendspark.com/subprocessors\n  text: The service providers that process personal data on our behalf, what each does and where, are listed in\n    our Subprocessor List at https://www.sendspark.com/subprocessors .\ndpa:\n  available: true\n  url: https://www.sendspark.com/dpa\n  text: Where we\
  \ process personal data on behalf of our customers, that processing is governed by our Data Processing\n    Addendum at https://www.sendspark.com/dpa .\ndeletion:\n  route: email privacy@sendspark.com\n  text: you may revise or edit your information through your account (If applicable) or by sending an email to privacy@sendspark.com\n    .\nrights:\n- right: access\n  text: The right of access. This is your right to see what data about you is held by us.\n- right: rectification\n  text: The right to rectification. This is the right to have your data corrected or amended if what is held is\n    incorrect in some way.\n- right: erasure\n  text: The right to be forgotten. This is the right to have your personal data to be deleted\n- right: portability\n  text: The right to data portability.\n- right: object\n  text: The right to object.\n- right: restrict processing\n  text: The right to restrict processing.\nsale_or_sharing:\n  stance: unstated\n  text: For the avoidance of doubt, we do\
  \ not “sell” your “covered information”.\n"
source_yaml_url: https://artifacts.apis.io/sendspark/privacy/sendspark-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 23 quoted statements, read from Sendspark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Sales
- Marketing
- Personalization
- Artificial Intelligence
- Video Messaging
- Webhook
- MCP
- A2A
---
