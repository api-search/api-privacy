---
api_specs:
- filename: takehomeapi-com-compare-api-openapi.yml
  format: yaml
  label: takehomeapi-com Compare API
  slug: takehomeapi-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/takehomeapi-com/openapi/takehomeapi-com-compare-api-openapi.yml
- filename: takehomeapi-com-rates-api-openapi.yml
  format: yaml
  label: takehomeapi-com Rates API
  slug: takehomeapi-com-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/takehomeapi-com/openapi/takehomeapi-com-rates-api-openapi.yml
- filename: takehomeapi-com-take-home-api-openapi.yml
  format: yaml
  label: takehomeapi-com Take Home API
  slug: takehomeapi-com-take-home-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/takehomeapi-com/openapi/takehomeapi-com-take-home-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address
  - category: identifying
    text: A one-way hash of your API key (never the key itself)
  - category: behavioral
    text: 'Usage records: which endpoint was called and when'
  - category: financial
    text: Stripe customer and subscription references
  - category: financial
    text: Billing records
  - category: device
    text: Technical logs kept by our hosting provider, such as IP addresses
  deletion:
    route: Contact us at lee.day@leeday.uk
    text: Contact us at lee.day@leeday.uk .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Issue API key and contact about account
    text: To issue your API key, link it to your plan and contact you about your account
  - purpose: Check calls are authorised
    text: To check calls are authorised
  - purpose: Enforce limits and prevent abuse
    text: To enforce plan limits, prevent abuse and run the service
  - purpose: Manage plan
    text: To manage your plan. Card details go straight to Stripe; we never see them
  - purpose: Tax and accounting
    text: To meet tax and accounting obligations
  - purpose: Security
    text: Security and keeping the service running
  residency:
  - region: UK
    text: 'Supabase : database, hosted in London (UK).'
  retention:
  - period: up to 12 months after closure
    scope: Account data
    text: 'Account data (email, key hashes, plan): while your account is active, then up to 12 months after closure.'
  - period: up to 24 months
    scope: Usage records
    text: 'Usage records: up to 24 months.'
  - period: 6 years
    scope: Billing records
    text: 'Billing records: 6 years, as UK tax law requires.'
  rights:
  - right: access
    text: you can ask for a copy of your data
  - right: rectification
    text: ask us to correct it
  - right: erasure
    text: delete it
  - right: restriction and objection
    text: restrict or object to its use
  - right: portability
    text: move it to another service
  - right: complain to regulator
    text: you can complain to the Information Commissioner's Office at ico.org.uk
  role:
    text: Hosting Easy Ltd (“we”) runs TakeHome API and is the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we don't sell or share your data for marketing
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Data may be processed outside the UK, including in the US, under appropriate safeguards such as the UK International Data Transfer Addendum or the UK–US data bridge.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: takehomeapi-com
provenance_date: '2026-11-10'
provider_name: takehomeapi-com
provider_slug: takehomeapi-com
slug: takehomeapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: takehomeapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://takehomeapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: takehomeapi-com\naid: takehomeapi-com\nurl: https://takehomeapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Hosting Easy Ltd (“we”) runs TakeHome API and is the data controller for the personal data described here.\ndata_categories:\n- category: contact\n  text: Your email address\n- category: identifying\n  text: A one-way hash of your API key (never the key itself)\n- category: behavioral\n  text: 'Usage records: which endpoint was called and when'\n- category: financial\n  text: Stripe customer and subscription references\n- category: financial\n  text: Billing records\n\
  - category: device\n  text: Technical logs kept by our hosting provider, such as IP addresses\npurposes:\n- purpose: Issue API key and contact about account\n  text: To issue your API key, link it to your plan and contact you about your account\n- purpose: Check calls are authorised\n  text: To check calls are authorised\n- purpose: Enforce limits and prevent abuse\n  text: To enforce plan limits, prevent abuse and run the service\n- purpose: Manage plan\n  text: To manage your plan. Card details go straight to Stripe; we never see them\n- purpose: Tax and accounting\n  text: To meet tax and accounting obligations\n- purpose: Security\n  text: Security and keeping the service running\nretention:\n- scope: Account data\n  period: up to 12 months after closure\n  text: 'Account data (email, key hashes, plan): while your account is active, then up to 12 months after closure.'\n- scope: Usage records\n  period: up to 24 months\n  text: 'Usage records: up to 24 months.'\n- scope: Billing records\n\
  \  period: 6 years\n  text: 'Billing records: 6 years, as UK tax law requires.'\nresidency:\n- region: UK\n  text: 'Supabase : database, hosted in London (UK).'\ntransfers:\n- mechanism: other\n  text: Data may be processed outside the UK, including in the US, under appropriate safeguards such as the UK International\n    Data Transfer Addendum or the UK–US data bridge.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us at lee.day@leeday.uk\n  text: Contact us at lee.day@leeday.uk .\nrights:\n- right: access\n  text: you can ask for a copy of your data\n- right: rectification\n  text: ask us to correct it\n- right: erasure\n  text: delete it\n- right: restriction and objection\n  text: restrict or object to its use\n- right: portability\n  text: move it to another service\n- right: complain to regulator\n  text: you can complain to the Information Commissioner's Office at ico.org.uk\nsale_or_sharing:\n  stance:\
  \ prohibited\n  text: we don't sell or share your data for marketing\n"
source_yaml_url: https://artifacts.apis.io/takehomeapi-com/privacy/takehomeapi-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from takehomeapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- United Kingdom
- Finance
- Tax
- Payroll
---
