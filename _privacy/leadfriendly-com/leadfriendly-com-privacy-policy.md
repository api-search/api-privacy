---
api_specs:
- filename: leadfriendly-com-openapi-generated.yml
  format: yaml
  label: leadfriendly-com API
  slug: leadfriendly-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadfriendly-com/openapi/_ae-authored/leadfriendly-com-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email, password (hashed), organization name, role.'
  - category: contact
    text: Your name, address, phone number and email.
  - category: financial
    text: 'Billing information: processed by our payment processor (Stripe). We do not store full card numbers.'
  - category: communication
    text: 'Customer Content: contacts, call recordings, transcripts, CRM records, agent configurations, and other content you create or upload.'
  - category: behavioral
    text: 'Usage data: pages viewed, features used, timestamps, browser, device.'
  - category: device
    text: 'Log data: IP address, error reports, performance metrics.'
  - category: location
    text: your country, which our hosting provider derives from your connection
  deletion:
    route: Through the Service, by contacting us, or at leadfriendly.com/delete-account
    text: You can request deletion of specific Customer Content at any time through the Service or by contacting us; we honor such requests except where applicable law or an active legal hold requires retention.
  dpa:
    available: true
    text: Where Customer Data is processed under our Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide, operate, maintain and improve the Service
    text: To provide, operate, maintain, and improve the Service;
  - purpose: Process AI voice calls
    text: To process AI voice calls (text-to-speech, speech-to-text, agent reasoning) using the sub-processors listed at /legal/subprocessors ;
  - purpose: Process payments
    text: To process payments and manage subscriptions;
  - purpose: Fraud prevention
    text: To detect, investigate, and prevent fraud and abuse;
  residency:
  - region: United States
    text: We are headquartered in the United States and store information there.
  retention:
  - period: as long as your account is active
    scope: Account information and Customer Content
    text: We retain account information and Customer Content for as long as your account is active.
  - period: 30 days
    scope: General Customer Content after account closure
    text: After account closure we delete or de-identify general Customer Content within 30 days
  - period: 7 years
    scope: Identity-verification (KYC) records
    text: identity-verification (KYC) records for up to 7 years
  - period: null
    scope: Backups
    text: Backups cycle on a rolling 90-day basis.
  - period: null
    scope: Prequalification records
    text: For as long as the dealership’s account is active, unless it is deleted sooner.
  rights:
  - right: Confirm, access, correct, delete, port
    text: (i) confirm whether we process personal information about you; (ii) access the personal information; (iii) correct inaccurate personal information; (iv) delete personal information; (v) port personal information in a portable format;
  - right: Opt out of targeted advertising, sale, profiling
    text: (vi) opt out of targeted advertising, the sale of personal information, and profiling in furtherance of decisions producing legal or similarly significant effects
  - right: Appeal
    text: (vii) appeal a denial of any of the above.
  - right: Complaint to supervisory authority
    text: You may lodge a complaint with your local supervisory authority.
  role:
    text: As a controller for visitors to our marketing site, prospective customers, signed-up users, and our own employees and contractors; As a processor for personal information that Customers upload, generate, or process through the platform (“Service Data”).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade personal information, and we do not “sell” or “share” it for cross-context behavioral advertising
  subprocessors:
    text: See /legal/subprocessors for the current list.
    url: /legal/subprocessors
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as the European Commission’s Standard Contractual Clauses, the UK International Data Transfer Addendum, and equivalent mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: leadfriendly-com
provenance_date: '2026-11-09'
provider_name: leadfriendly-com
provider_slug: leadfriendly-com
slug: leadfriendly-com-privacy-policy
source_date: '2026-11-09'
source_filename: leadfriendly-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.leadfriendly.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: leadfriendly-com\naid: leadfriendly-com\nurl: https://www.leadfriendly.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As a controller for visitors to our marketing site, prospective customers, signed-up users, and our own\n    employees and contractors; As a processor for personal information that Customers upload, generate, or process\n    through the platform (“Service Data”).\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email, password (hashed), organization name, role.'\n- category: contact\n  text: Your name, address, phone number and email.\n\
  - category: financial\n  text: 'Billing information: processed by our payment processor (Stripe). We do not store full card numbers.'\n- category: communication\n  text: 'Customer Content: contacts, call recordings, transcripts, CRM records, agent configurations, and other\n    content you create or upload.'\n- category: behavioral\n  text: 'Usage data: pages viewed, features used, timestamps, browser, device.'\n- category: device\n  text: 'Log data: IP address, error reports, performance metrics.'\n- category: location\n  text: your country, which our hosting provider derives from your connection\npurposes:\n- purpose: Provide, operate, maintain and improve the Service\n  text: To provide, operate, maintain, and improve the Service;\n- purpose: Process AI voice calls\n  text: To process AI voice calls (text-to-speech, speech-to-text, agent reasoning) using the sub-processors listed\n    at /legal/subprocessors ;\n- purpose: Process payments\n  text: To process payments and manage subscriptions;\n\
  - purpose: Fraud prevention\n  text: To detect, investigate, and prevent fraud and abuse;\nretention:\n- scope: Account information and Customer Content\n  period: as long as your account is active\n  text: We retain account information and Customer Content for as long as your account is active.\n- scope: General Customer Content after account closure\n  period: 30 days\n  text: After account closure we delete or de-identify general Customer Content within 30 days\n- scope: Identity-verification (KYC) records\n  period: 7 years\n  text: identity-verification (KYC) records for up to 7 years\n- scope: Backups\n  period: null\n  text: Backups cycle on a rolling 90-day basis.\n- scope: Prequalification records\n  period: null\n  text: For as long as the dealership’s account is active, unless it is deleted sooner.\nresidency:\n- region: United States\n  text: We are headquartered in the United States and store information there.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate\
  \ safeguards such as the European Commission’s Standard Contractual Clauses, the UK\n    International Data Transfer Addendum, and equivalent mechanisms.\nsubprocessors:\n  url: /legal/subprocessors\n  text: See /legal/subprocessors for the current list.\ndpa:\n  available: true\n  url: null\n  text: Where Customer Data is processed under our Data Processing Addendum\ndeletion:\n  route: Through the Service, by contacting us, or at leadfriendly.com/delete-account\n  text: You can request deletion of specific Customer Content at any time through the Service or by contacting us;\n    we honor such requests except where applicable law or an active legal hold requires retention.\nrights:\n- right: Confirm, access, correct, delete, port\n  text: (i) confirm whether we process personal information about you; (ii) access the personal information; (iii)\n    correct inaccurate personal information; (iv) delete personal information; (v) port personal information in\n    a portable format;\n- right:\
  \ Opt out of targeted advertising, sale, profiling\n  text: (vi) opt out of targeted advertising, the sale of personal information, and profiling in furtherance of\n    decisions producing legal or similarly significant effects\n- right: Appeal\n  text: (vii) appeal a denial of any of the above.\n- right: Complaint to supervisory authority\n  text: You may lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade personal information, and we do not “sell” or “share” it for cross-context\n    behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/leadfriendly-com/privacy/leadfriendly-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from leadfriendly-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- CRM
- Voice
- Small Business
- Telephony
---
