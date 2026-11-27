---
api_specs:
- filename: senseon-openapi-generated.yml
  format: yaml
  label: SenseOn API
  slug: senseon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/senseon/openapi/_ae-authored/senseon-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Business contact details such as name, role, company, email address, phone number, and country.
  - category: device
    text: Website and device data such as IP address, browser, pages visited, referral source, consent choices, and basic security logs.
  - category: communication
    text: Enquiry, demo, event, support, and commercial communications you send to us.
  - category: behavioral
    text: Customer service data, including support tickets, audit events, usage records, and security telemetry when a customer uses the SenseOn platform or asks us to support it.
  - category: other
    text: Security and AI feature records, including investigation context, detections, prompts, responses, agent actions, approvals, and audit trails where those features are used.
  deletion:
    route: null
    text: Customer platform data is retained under the customer agreement and configured service terms.
  dpa:
    available: true
    text: Those processing terms are governed by the customer agreement and our Data Processing Agreement .
    url: null
  purposes:
  - purpose: Operate website and administer accounts
    text: Operate the website, respond to requests, arrange demos, manage trials, and administer customer accounts.
  - purpose: Deliver and secure platform
    text: Deliver, secure, monitor, support, and improve the SenseOn platform.
  - purpose: Process customer data as processor
    text: Process customer security telemetry, support cases, and investigation data where customers use the platform.
  - purpose: AI-based security detection
    text: Use AI and automation to detect, investigate, report, and respond to security events under customer governance.
  - purpose: Marketing to business contacts
    text: Send marketing communications to business contacts and measure campaign performance.
  retention:
  - period: 90 days
    scope: Anonymous analytics events
    text: SenseOn's retention policy is 90 days for anonymous analytics events and 2 years after last contact for identified records.
  - period: 2 years after last contact
    scope: Identified records
    text: SenseOn's retention policy is 90 days for anonymous analytics events and 2 years after last contact for identified records.
  - period: 24 months of inactivity
    scope: Enquiry and prospect records
    text: Enquiry and prospect records are normally reviewed after 24 months of inactivity.
  - period: three days
    scope: Website unique-visitor hashes
    text: We delete these hashes within three days and keep only the daily totals.
  - period: 90 days
    scope: Microsoft Entra AI-use records
    text: For customers who connect Microsoft Entra, AI-use records, including user names, are kept for 90 days to produce the weekly Insight report.
  rights:
  - right: access
    text: Depending on where you are, you may have rights to access, correct, delete, restrict, object to, or receive a copy of your personal data.
  - right: withdraw consent
    text: You may also withdraw consent, opt out of marketing, or object to certain automated or targeted advertising uses.
  - right: complain to regulator
    text: You can complain to the UK Information Commissioner's Office at ico.org.uk or to your local data protection authority.
  role:
    text: We are the controller for the personal data we collect through this website, our sales and marketing activity, and our own business operations. For customer security data processed in the SenseOn platform, SenseOn usually acts as a processor on behalf of the customer.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Where personal data is transferred from the UK, EEA, or Switzerland to another country, we use adequacy decisions, the UK International Data Transfer Addendum, standard contractual clauses, or another lawful transfer mechanism
  - mechanism: SCC
    text: we use adequacy decisions, the UK International Data Transfer Addendum, standard contractual clauses, or another lawful transfer mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SenseOn
provenance_date: '2026-11-10'
provider_name: SenseOn
provider_slug: senseon
slug: senseon-privacy-policy
source_date: '2026-11-10'
source_filename: senseon-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.senseon.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SenseOn\naid: senseon\nurl: https://www.senseon.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for the personal data we collect through this website, our sales and marketing activity,\n    and our own business operations. For customer security data processed in the SenseOn platform, SenseOn usually\n    acts as a processor on behalf of the customer.\ndata_categories:\n- category: contact\n  text: Business contact details such as name, role, company, email address, phone number, and country.\n- category: device\n  text: Website and device data such as IP address,\
  \ browser, pages visited, referral source, consent choices, and\n    basic security logs.\n- category: communication\n  text: Enquiry, demo, event, support, and commercial communications you send to us.\n- category: behavioral\n  text: Customer service data, including support tickets, audit events, usage records, and security telemetry when\n    a customer uses the SenseOn platform or asks us to support it.\n- category: other\n  text: Security and AI feature records, including investigation context, detections, prompts, responses, agent\n    actions, approvals, and audit trails where those features are used.\npurposes:\n- purpose: Operate website and administer accounts\n  text: Operate the website, respond to requests, arrange demos, manage trials, and administer customer accounts.\n- purpose: Deliver and secure platform\n  text: Deliver, secure, monitor, support, and improve the SenseOn platform.\n- purpose: Process customer data as processor\n  text: Process customer security telemetry,\
  \ support cases, and investigation data where customers use the platform.\n- purpose: AI-based security detection\n  text: Use AI and automation to detect, investigate, report, and respond to security events under customer governance.\n- purpose: Marketing to business contacts\n  text: Send marketing communications to business contacts and measure campaign performance.\nretention:\n- scope: Anonymous analytics events\n  period: 90 days\n  text: SenseOn's retention policy is 90 days for anonymous analytics events and 2 years after last contact for\n    identified records.\n- scope: Identified records\n  period: 2 years after last contact\n  text: SenseOn's retention policy is 90 days for anonymous analytics events and 2 years after last contact for\n    identified records.\n- scope: Enquiry and prospect records\n  period: 24 months of inactivity\n  text: Enquiry and prospect records are normally reviewed after 24 months of inactivity.\n- scope: Website unique-visitor hashes\n  period: three\
  \ days\n  text: We delete these hashes within three days and keep only the daily totals.\n- scope: Microsoft Entra AI-use records\n  period: 90 days\n  text: For customers who connect Microsoft Entra, AI-use records, including user names, are kept for 90 days to\n    produce the weekly Insight report.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where personal data is transferred from the UK, EEA, or Switzerland to another country, we use adequacy\n    decisions, the UK International Data Transfer Addendum, standard contractual clauses, or another lawful transfer\n    mechanism\n- mechanism: SCC\n  text: we use adequacy decisions, the UK International Data Transfer Addendum, standard contractual clauses, or\n    another lawful transfer mechanism\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Those processing terms are governed by the customer agreement and our Data Processing Agreement .\ndeletion:\n  route: null\n  text: Customer\
  \ platform data is retained under the customer agreement and configured service terms.\nrights:\n- right: access\n  text: Depending on where you are, you may have rights to access, correct, delete, restrict, object to, or receive\n    a copy of your personal data.\n- right: withdraw consent\n  text: You may also withdraw consent, opt out of marketing, or object to certain automated or targeted advertising\n    uses.\n- right: complain to regulator\n  text: You can complain to the UK Information Commissioner's Office at ico.org.uk or to your local data protection\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/senseon/privacy/senseon-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from SenseOn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Platform
- Incident Response
---
