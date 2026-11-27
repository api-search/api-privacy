---
api_specs:
- filename: dailylogdesk-com-dataset-api-openapi.yml
  format: yaml
  label: DailyLogDesk Dataset API
  slug: dailylogdesk-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailylogdesk-com/openapi/dailylogdesk-com-dataset-api-openapi.yml
- filename: dailylogdesk-com-mcp-api-openapi.yml
  format: yaml
  label: DailyLogDesk MCP API
  slug: dailylogdesk-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailylogdesk-com/openapi/dailylogdesk-com-mcp-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect what you type into an enquiry form (your name, your email address, your message)
  - category: identifying
    text: if you create an account, your email address and the project, client and site records you choose to store
  - category: financial
    text: Payment is taken by Stripe, who receive your card details directly; card numbers never reach DailyLogDesk.
  deletion:
    route: Email hello@dailylogdesk.com to ask for deletion
    text: 'You can ask what we hold about you, ask for a copy, or ask for deletion at any time: hello@dailylogdesk.com.'
  dpa:
    available: null
    text: on the written terms published on this site
    url: null
  purposes:
  - purpose: Enquiry handling
    text: We collect what you type into an enquiry form (your name, your email address, your message)
  - purpose: Email updates
    text: We email you only about what that sentence names.
  - purpose: Emailing a result
    text: If you ask us to email you a result from a calculator or a checker, we send it to you once.
  retention:
  - period: 24 months
    scope: Enquiry records
    text: Enquiry records are kept for 24 months from when they are sent, then deleted
  - period: 30 days
    scope: Unconfirmed email sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: null
    scope: Email updates
    text: 'Email updates: kept while you are subscribed.'
  - period: indefinitely
    scope: Aggregate statistics
    text: Aggregate statistics that identify nobody are kept indefinitely.
  rights:
  - right: Access
    text: You can ask what we hold about you, ask for a copy
  - right: Erasure
    text: or ask for deletion at any time
  - right: Complaint to supervisory authority
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your details and we do not pass them to contractors, lead buyers or advertising networks.
  subprocessors:
    text: we hold a current list of the sub-processors involved
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DailyLogDesk
provenance_date: '2026-11-09'
provider_name: DailyLogDesk
provider_slug: dailylogdesk-com
slug: dailylogdesk-com-privacy-policy
source_date: '2026-11-09'
source_filename: dailylogdesk-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dailylogdesk.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DailyLogDesk\naid: dailylogdesk-com\nurl: https://dailylogdesk.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.\ndata_categories:\n- category: contact\n  text: We collect what you type into an enquiry form (your name, your email address, your message)\n- category: identifying\n  text: if you create an account, your email address and the project, client and site records you choose to store\n\
  - category: financial\n  text: Payment is taken by Stripe, who receive your card details directly; card numbers never reach DailyLogDesk.\npurposes:\n- purpose: Enquiry handling\n  text: We collect what you type into an enquiry form (your name, your email address, your message)\n- purpose: Email updates\n  text: We email you only about what that sentence names.\n- purpose: Emailing a result\n  text: If you ask us to email you a result from a calculator or a checker, we send it to you once.\nretention:\n- scope: Enquiry records\n  period: 24 months\n  text: Enquiry records are kept for 24 months from when they are sent, then deleted\n- scope: Unconfirmed email sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: Email updates\n  period: null\n  text: 'Email updates: kept while you are subscribed.'\n- scope: Aggregate statistics\n  period: indefinitely\n  text: Aggregate statistics that identify nobody are kept indefinitely.\nresidency: []\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: we hold a current list of the sub-processors involved\ndpa:\n  available: null\n  url: null\n  text: on the written terms published on this site\ndeletion:\n  route: Email hello@dailylogdesk.com to ask for deletion\n  text: 'You can ask what we hold about you, ask for a copy, or ask for deletion at any time: hello@dailylogdesk.com.'\nrights:\n- right: Access\n  text: You can ask what we hold about you, ask for a copy\n- right: Erasure\n  text: or ask for deletion at any time\n- right: Complaint to supervisory authority\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your details and we do not pass them to contractors, lead buyers or advertising networks.\n"
source_yaml_url: https://artifacts.apis.io/dailylogdesk-com/privacy/dailylogdesk-com-privacy-policy.yml
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
summary_line: 18 quoted statements, read from DailyLogDesk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Site Records
- Incident Reporting
- Risk Assessment
- Health and Safety
- Contractors
- Quotes
---
