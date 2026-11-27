---
api_specs:
- filename: deflectvo-com-dataset-api-openapi.yml
  format: yaml
  label: Deflectvo Dataset API
  slug: deflectvo-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deflectvo-com/openapi/deflectvo-com-dataset-api-openapi.yml
- filename: deflectvo-com-mcp-api-openapi.yml
  format: yaml
  label: Deflectvo MCP API
  slug: deflectvo-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deflectvo-com/openapi/deflectvo-com-mcp-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect what you type into an enquiry form (your name, your email address, your message)
  - category: identifying
    text: your name, your email address, your message
  - category: communication
    text: 'Email updates : If you sign up for updates from this site (the box at the foot of a page, or the tick on an enquiry form), we store your email address, the exact sentence you agreed to and its version, where you signed up and when.'
  deletion:
    route: Email hello@deflectvo.com
    text: 'You can ask what we hold about you, ask for a copy, or ask for deletion at any time: hello@deflectvo.com.'
  dpa:
    available: true
    text: Where you store your own customers' details in Deflectvo we act as your processor under UK GDPR Article 28 and the US state privacy laws that apply to you, on the written terms published on this site
    url: null
  purposes:
  - purpose: Responding to enquiries
    text: We collect what you type into an enquiry form
  - purpose: Sending email updates
    text: We email you only about what that sentence names.
  - purpose: Emailing results
    text: If you ask us to email you a result from a calculator or a checker, we send it to you once.
  retention:
  - period: 24 months
    scope: Enquiry records
    text: Enquiry records are kept for 24 months from when they are sent, then deleted
  - period: kept while you are subscribed
    scope: Email updates
    text: 'Email updates: kept while you are subscribed.'
  - period: 30 days
    scope: Unconfirmed sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: 24 months
    scope: Consent record after unsubscribe
    text: After you unsubscribe, the record of your consent and of the emails sent to you is kept for 24 months as evidence, then deleted.
  - period: indefinitely
    scope: Aggregate statistics
    text: Aggregate statistics that identify nobody are kept indefinitely.
  rights:
  - right: Access
    text: You can ask what we hold about you, ask for a copy
  - right: Erasure
    text: or ask for deletion at any time
  - right: Complaint to ICO
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your details and we do not pass them to lead buyers, help-desk vendors, call centres or advertising networks.
  subprocessors:
    text: we hold a current list of the sub-processors involved
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Deflectvo
provenance_date: '2026-11-09'
provider_name: Deflectvo
provider_slug: deflectvo-com
slug: deflectvo-com-privacy-policy
source_date: '2026-11-09'
source_filename: deflectvo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://deflectvo.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Deflectvo\naid: deflectvo-com\nurl: https://deflectvo.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The controller of the personal data on this site is Ellul Solutions Ltd\ndata_categories:\n- category: contact\n  text: We collect what you type into an enquiry form (your name, your email address, your message)\n- category: identifying\n  text: your name, your email address, your message\n- category: communication\n  text: 'Email updates : If you sign up for updates from this site (the box at the foot of a page, or the tick on\n    an enquiry form), we store your email address, the\
  \ exact sentence you agreed to and its version, where you signed\n    up and when.'\npurposes:\n- purpose: Responding to enquiries\n  text: We collect what you type into an enquiry form\n- purpose: Sending email updates\n  text: We email you only about what that sentence names.\n- purpose: Emailing results\n  text: If you ask us to email you a result from a calculator or a checker, we send it to you once.\nretention:\n- scope: Enquiry records\n  period: 24 months\n  text: Enquiry records are kept for 24 months from when they are sent, then deleted\n- scope: Email updates\n  period: kept while you are subscribed\n  text: 'Email updates: kept while you are subscribed.'\n- scope: Unconfirmed sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: Consent record after unsubscribe\n  period: 24 months\n  text: After you unsubscribe, the record of your consent and of the emails sent to you is kept for 24 months as\n    evidence, then deleted.\n- scope:\
  \ Aggregate statistics\n  period: indefinitely\n  text: Aggregate statistics that identify nobody are kept indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: we hold a current list of the sub-processors involved\ndpa:\n  available: true\n  url: null\n  text: Where you store your own customers' details in Deflectvo we act as your processor under UK GDPR Article\n    28 and the US state privacy laws that apply to you, on the written terms published on this site\ndeletion:\n  route: Email hello@deflectvo.com\n  text: 'You can ask what we hold about you, ask for a copy, or ask for deletion at any time: hello@deflectvo.com.'\nrights:\n- right: Access\n  text: You can ask what we hold about you, ask for a copy\n- right: Erasure\n  text: or ask for deletion at any time\n- right: Complaint to ICO\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your details and\
  \ we do not pass them to lead buyers, help-desk vendors, call centres or advertising\n    networks.\n"
source_yaml_url: https://artifacts.apis.io/deflectvo-com/privacy/deflectvo-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Deflectvo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Self-Service
- Customer Service
- Help Center
- Ticket Deflection
- Customer Portal
- Software-as-a-Service
---
