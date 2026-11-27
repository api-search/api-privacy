---
api_specs:
- filename: telemetron-ai-customer-api-openapi.yml
  format: yaml
  label: Telemetron Customer API
  slug: telemetron-ai-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-customer-api-openapi.yml
- filename: telemetron-ai-device-api-openapi.yml
  format: yaml
  label: Telemetron Device API
  slug: telemetron-ai-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-device-api-openapi.yml
- filename: telemetron-ai-device-assignment-api-openapi.yml
  format: yaml
  label: Telemetron Device Assignment API
  slug: telemetron-ai-device-assignment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-device-assignment-api-openapi.yml
- filename: telemetron-ai-ticket-api-openapi.yml
  format: yaml
  label: Telemetron Ticket API
  slug: telemetron-ai-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telemetron-ai/openapi/telemetron-ai-ticket-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, company name, job title, phone number, and other contact information you provide when creating an account or contacting us.
  - category: financial
    text: Billing address, payment method details (e.g. credit card) via secure payment processors.
  - category: device
    text: IP address, device identifiers (including device ID, advertising ID, and browser fingerprint), browser type and version, operating system, log data
  - category: behavioral
    text: pages and features you use, time spent on pages, click patterns, crash reports, and referral URLs.
  - category: other
    text: 'Device Telemetry Data: Hardware device diagnostic data, telemetry readings, device status information, and support ticket data processed through our platform on behalf of our business customers.'
  deletion:
    route: Email to security@telemetron.ai with subject 'Data Deletion Request', or account deletion via account settings
    text: You may delete your account through your account settings in the Telemetron platform.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To provide, maintain, and improve our Services, including our AI-powered customer support platform and related applications.
  - purpose: Payment processing
    text: To process payments and manage subscriptions.
  - purpose: Analytics and improvement
    text: To analyze usage patterns, understand how our product is used, and improve our Services.
  - purpose: Personalization
    text: To personalize your experience and deliver content relevant to your interests.
  - purpose: Security and fraud prevention
    text: To detect, prevent, and address fraud, abuse, security risks, and technical issues.
  residency:
  - region: United States
    text: including the United States, where our servers and central database are located.
  retention:
  - period: up to 30 days after account deletion
    scope: Account data
    text: 'Account Data: Retained for the duration of your active account and up to 30 days after account deletion, to allow for recovery if needed.'
  - period: up to 7 years
    scope: Transaction and billing data
    text: 'Transaction & Billing Data: Retained for up to 7 years as required by tax and accounting regulations.'
  - period: up to 26 months
    scope: Usage and analytics data
    text: 'Usage & Analytics Data: Retained in identifiable form for up to 26 months, after which it is aggregated or anonymized.'
  rights:
  - right: Access
    text: 'Right of Access: Request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Right to Rectification: Request correction of inaccurate or incomplete personal data.'
  - right: Erasure
    text: 'Right to Erasure: Request deletion of your personal data, subject to certain legal exceptions.'
  - right: Restrict processing
    text: 'Right to Restrict Processing: Request that we limit how we use your data.'
  - right: Portability
    text: 'Right to Data Portability: Request your data in a structured, commonly used, machine-readable format.'
  - right: Object
    text: 'Right to Object: Object to processing based on legitimate interests or for direct marketing purposes.'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: Where processing is based on consent, you may withdraw it at any time without affecting the lawfulness of prior processing.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When we transfer personal data from the EEA, UK, or Switzerland to the United States or other countries, we rely on appropriate legal mechanisms such as Standard Contractual Clauses (SCCs) approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Telemetron
provenance_date: '2026-11-10'
provider_name: Telemetron
provider_slug: telemetron-ai
slug: telemetron-ai-privacy-policy
source_date: '2026-11-10'
source_filename: telemetron-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.telemetron.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Telemetron\naid: telemetron-ai\nurl: https://www.telemetron.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, company name, job title, phone number, and other contact information you provide when\n    creating an account or contacting us.\n- category: financial\n  text: Billing address, payment method details (e.g. credit card) via secure payment processors.\n- category: device\n  text: IP address, device identifiers (including device ID, advertising ID, and browser fingerprint), browser type\n    and\
  \ version, operating system, log data\n- category: behavioral\n  text: pages and features you use, time spent on pages, click patterns, crash reports, and referral URLs.\n- category: other\n  text: 'Device Telemetry Data: Hardware device diagnostic data, telemetry readings, device status information,\n    and support ticket data processed through our platform on behalf of our business customers.'\npurposes:\n- purpose: Service delivery\n  text: To provide, maintain, and improve our Services, including our AI-powered customer support platform and related\n    applications.\n- purpose: Payment processing\n  text: To process payments and manage subscriptions.\n- purpose: Analytics and improvement\n  text: To analyze usage patterns, understand how our product is used, and improve our Services.\n- purpose: Personalization\n  text: To personalize your experience and deliver content relevant to your interests.\n- purpose: Security and fraud prevention\n  text: To detect, prevent, and address\
  \ fraud, abuse, security risks, and technical issues.\nretention:\n- scope: Account data\n  period: up to 30 days after account deletion\n  text: 'Account Data: Retained for the duration of your active account and up to 30 days after account deletion,\n    to allow for recovery if needed.'\n- scope: Transaction and billing data\n  period: up to 7 years\n  text: 'Transaction & Billing Data: Retained for up to 7 years as required by tax and accounting regulations.'\n- scope: Usage and analytics data\n  period: up to 26 months\n  text: 'Usage & Analytics Data: Retained in identifiable form for up to 26 months, after which it is aggregated\n    or anonymized.'\nresidency:\n- region: United States\n  text: including the United States, where our servers and central database are located.\ntransfers:\n- mechanism: SCC\n  text: When we transfer personal data from the EEA, UK, or Switzerland to the United States or other countries,\n    we rely on appropriate legal mechanisms such as Standard Contractual\
  \ Clauses (SCCs) approved by the European\n    Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to security@telemetron.ai with subject 'Data Deletion Request', or account deletion via account settings\n  text: You may delete your account through your account settings in the Telemetron platform.\nrights:\n- right: Access\n  text: 'Right of Access: Request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Right to Rectification: Request correction of inaccurate or incomplete personal data.'\n- right: Erasure\n  text: 'Right to Erasure: Request deletion of your personal data, subject to certain legal exceptions.'\n- right: Restrict processing\n  text: 'Right to Restrict Processing: Request that we limit how we use your data.'\n- right: Portability\n  text: 'Right to Data Portability: Request your data in a structured, commonly used, machine-readable format.'\n- right: Object\n\
  \  text: 'Right to Object: Object to processing based on legitimate interests or for direct marketing purposes.'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent: Where processing is based on consent, you may withdraw it at any time without\n    affecting the lawfulness of prior processing.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/telemetron-ai/privacy/telemetron-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Telemetron's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Service
- IoT
- Hardware
- Telemetry
- Support Tickets
- MCP
---
