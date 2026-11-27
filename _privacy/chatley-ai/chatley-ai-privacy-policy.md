---
api_specs:
- filename: chatley-ai-openapi-generated.yml
  format: yaml
  label: Chatley Developer API
  slug: developer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatley-ai/openapi/_ae-authored/chatley-ai-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Registration Data: Name, work email address, telephone number, business name, and authentication credentials.'
  - category: financial
    text: Billing address and payment transaction tokens.
  - category: communication
    text: Voice audio is processed strictly to provide acoustic speech-to-text transcription and conversational generation.
  - category: location
    text: The app does not collect your location, contacts, photos, or microphone audio
  - category: device
    text: A random device identifier created by the app, your device name, operating system, and app version
  - category: behavioral
    text: 'System & Web Logs: IP address, browser type, operating system, referring URLs, and security event logs.'
  deletion:
    route: Email security@chatley.ai or privacy@chatley.ai, or request via the privacy team; end-user callers should contact the business operating the agent
    text: If you are an end-user caller seeking deletion of conversation data handled by an AI agent operated by a Chatley business customer, please direct your request to the business that operates that agent (the Data Controller).
  dpa:
    available: true
    text: Customers subject to GDPR, UK GDPR, or CPRA may request and sign our DPA by emailing security@chatley.ai .
    url: null
  purposes:
  - purpose: Operating, hosting, and delivering voice, web chat, and SMS agent platform
    text: Operating, hosting, and delivering our voice, web chat, and SMS agent platform.
  - purpose: Payment processing and billing
    text: Processing payments, subscription renewals, and administrative invoices.
  - purpose: Technical support and security
    text: Providing technical support, operational monitoring, and platform security.
  - purpose: Legal compliance
    text: Complying with regulatory obligations and legal requests.
  residency:
  - region: United States
    text: Chatley is headquartered in the United States and our primary production servers are located in U.S. data centers.
  retention:
  - period: default 30 days
    scope: Call audio and transcripts
    text: Customer-configured (default 30 days; 0-day retention available for Enterprise)
  - period: Up to 90 days
    scope: Telephony and SMS logs
    text: Up to 90 days for troubleshooting and fraud prevention
  - period: 30 days
    scope: Sign-in approval records
    text: These records are deleted automatically after 30 days.
  - period: Up to 7 years
    scope: Billing and tax records
    text: Up to 7 years in accordance with statutory accounting requirements
  - period: Maximum 14 months
    scope: Website analytics (GA4)
    text: Maximum 14 months (Google Consent Mode v2 enforced)
  rights:
  - right: Access
    text: 'Right to Know / Access: Request disclosure of categories and specific pieces of personal information collected.'
  - right: Rectification
    text: 'Right to Rectification: Request correction of inaccurate personal data.'
  - right: Deletion
    text: 'Right to Deletion: Request erasure of your personal data, subject to lawful retention exceptions.'
  - right: Restrict or object
    text: 'Right to Restrict or Object: Restrict or object to certain processing operations.'
  - right: Portability
    text: 'Right to Data Portability: Obtain your personal data in a structured, machine-readable format.'
  role:
    text: 'Chatley as Data Processor (or Service Provider): For all conversational content, voice audio recordings, call transcripts, SMS message bodies, customer contact phone numbers, and custom AI agent workflows configured and transmitted by our business customers, Chatley acts strictly as a Data Processor.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Every vendor listed below has been verified against our live production architecture.
    url: null
  transfers:
  - mechanism: SCC
    text: We provide a standardized Data Processing Addendum incorporating the European Commission's Standard Contractual Clauses (SCCs) and UK International Data Transfer Addendum to govern international transfers of customer data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chatley AI
provenance_date: '2026-11-09'
provider_name: Chatley AI
provider_slug: chatley-ai
slug: chatley-ai-privacy-policy
source_date: '2026-11-09'
source_filename: chatley-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.chatley.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chatley AI\naid: chatley-ai\nurl: https://www.chatley.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Chatley as Data Processor (or Service Provider): For all conversational content, voice audio recordings,\n    call transcripts, SMS message bodies, customer contact phone numbers, and custom AI agent workflows configured\n    and transmitted by our business customers, Chatley acts strictly as a Data Processor.'\ndata_categories:\n- category: identifying\n  text: 'Account Registration Data: Name, work email address, telephone number, business name, and authentication\n    credentials.'\n\
  - category: financial\n  text: Billing address and payment transaction tokens.\n- category: communication\n  text: Voice audio is processed strictly to provide acoustic speech-to-text transcription and conversational generation.\n- category: location\n  text: The app does not collect your location, contacts, photos, or microphone audio\n- category: device\n  text: A random device identifier created by the app, your device name, operating system, and app version\n- category: behavioral\n  text: 'System & Web Logs: IP address, browser type, operating system, referring URLs, and security event logs.'\npurposes:\n- purpose: Operating, hosting, and delivering voice, web chat, and SMS agent platform\n  text: Operating, hosting, and delivering our voice, web chat, and SMS agent platform.\n- purpose: Payment processing and billing\n  text: Processing payments, subscription renewals, and administrative invoices.\n- purpose: Technical support and security\n  text: Providing technical support, operational\
  \ monitoring, and platform security.\n- purpose: Legal compliance\n  text: Complying with regulatory obligations and legal requests.\nretention:\n- scope: Call audio and transcripts\n  period: default 30 days\n  text: Customer-configured (default 30 days; 0-day retention available for Enterprise)\n- scope: Telephony and SMS logs\n  period: Up to 90 days\n  text: Up to 90 days for troubleshooting and fraud prevention\n- scope: Sign-in approval records\n  period: 30 days\n  text: These records are deleted automatically after 30 days.\n- scope: Billing and tax records\n  period: Up to 7 years\n  text: Up to 7 years in accordance with statutory accounting requirements\n- scope: Website analytics (GA4)\n  period: Maximum 14 months\n  text: Maximum 14 months (Google Consent Mode v2 enforced)\nresidency:\n- region: United States\n  text: Chatley is headquartered in the United States and our primary production servers are located in U.S. data\n    centers.\ntransfers:\n- mechanism: SCC\n  text:\
  \ We provide a standardized Data Processing Addendum incorporating the European Commission's Standard Contractual\n    Clauses (SCCs) and UK International Data Transfer Addendum to govern international transfers of customer data.\nsubprocessors:\n  url: null\n  text: Every vendor listed below has been verified against our live production architecture.\ndpa:\n  available: true\n  url: null\n  text: Customers subject to GDPR, UK GDPR, or CPRA may request and sign our DPA by emailing security@chatley.ai\n    .\ndeletion:\n  route: Email security@chatley.ai or privacy@chatley.ai, or request via the privacy team; end-user callers should\n    contact the business operating the agent\n  text: If you are an end-user caller seeking deletion of conversation data handled by an AI agent operated by a\n    Chatley business customer, please direct your request to the business that operates that agent (the Data Controller).\nrights:\n- right: Access\n  text: 'Right to Know / Access: Request disclosure\
  \ of categories and specific pieces of personal information collected.'\n- right: Rectification\n  text: 'Right to Rectification: Request correction of inaccurate personal data.'\n- right: Deletion\n  text: 'Right to Deletion: Request erasure of your personal data, subject to lawful retention exceptions.'\n- right: Restrict or object\n  text: 'Right to Restrict or Object: Restrict or object to certain processing operations.'\n- right: Portability\n  text: 'Right to Data Portability: Obtain your personal data in a structured, machine-readable format.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/chatley-ai/privacy/chatley-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Chatley AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice Agents
- Conversational AI
- AI Receptionist
- Telephony
- SMS
- White Label
- MCP
- Lead Generation
---
