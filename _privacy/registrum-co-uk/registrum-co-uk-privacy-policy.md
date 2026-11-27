---
api_specs:
- filename: registrum-co-uk-openapi.json
  format: json
  label: Registrum API
  slug: registrum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/registrum-co-uk/openapi/registrum-co-uk-openapi.json
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address - collected when you request an API key.
  - category: behavioral
    text: API usage logs - endpoint called, timestamp, response time, company number looked up, whether the result was cached.
  - category: financial
    text: we receive the payment confirmation and your email, not your card details.
  - category: professional
    text: we collect your email address, your firm, the approximate number of companies you mention and any company number you check.
  - category: device
    text: IP addresses - logged by our infrastructure for security and abuse prevention.
  - category: identifying
    text: 'For PSCs: name, the nature of control, notification and cessation dates, identity-verification status, and the month and year of birth, nationality, country of residence and service address recorded on the register.'
  deletion:
    route: email support@registrum.co.uk
    text: To exercise any right, email support@registrum.co.uk
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Rate limiting, billing, and service improvement
    text: Used for rate limiting, billing, and service improvement.
  - purpose: Send service notifications and deliver API key
    text: Used to deliver your key and send service notifications.
  - purpose: Letting businesses and others see who runs a company
    text: 'legitimate interests (Article 6(1)(f)): letting businesses, lenders, compliance professionals and the public see who runs and controls a company they deal with'
  - purpose: Measure marketing channels
    text: for 90 days, so we can measure which channels bring customers.
  residency:
  - region: EU (Ireland)
    text: Supabase - Database (API keys, usage logs, cached Companies House data) . EU (Ireland)
  - region: EU (Frankfurt)
    text: Railway - API hosting . EU (Frankfurt)
  retention:
  - period: while your account is active
    scope: Email addresses and API keys
    text: 'Email addresses and API keys: retained while your account is active, deleted within 30 days of account closure on request.'
  - period: 12 months
    scope: Usage logs
    text: 'Usage logs: retained for 12 months, then deleted.'
  - period: 30 days
    scope: IP address logs
    text: 'IP address logs: retained for 30 days.'
  - period: 30-day cycle
    scope: Companies House register copy
    text: our copy is refreshed from Companies House on a 30-day cycle
  rights:
  - right: access
    text: You have the right to access, correct, or delete your personal data
  - right: restrict or object
    text: to restrict or object to processing
  - right: portability
    text: and to data portability
  - right: object to officer/PSC processing
    text: you have the right to object to this processing on grounds relating to your particular situation (Article 21(1))
  - right: complain to ICO
    text: You also have the right to lodge a complaint with the ICO at ico.org.uk .
  role:
    text: We are the data controller for personal data collected through registrum.co.uk and the Registrum API
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not track visitors with advertising cookies or share data with ad networks.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: We rely on UK adequacy regulations, including the UK Extension to the EU-US Data Privacy Framework for certified US providers
  - mechanism: other
    text: or on the UK International Data Transfer Addendum to the EU Standard Contractual Clauses in the provider's data processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: registrum-co-uk
provenance_date: '2026-11-10'
provider_name: registrum-co-uk
provider_slug: registrum-co-uk
slug: registrum-co-uk-privacy-policy
source_date: '2026-11-10'
source_filename: registrum-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://registrum.co.uk/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: registrum-co-uk\naid: registrum-co-uk\nurl: https://registrum.co.uk/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for personal data collected through registrum.co.uk and the Registrum API\ndata_categories:\n- category: contact\n  text: Email address - collected when you request an API key.\n- category: behavioral\n  text: API usage logs - endpoint called, timestamp, response time, company number looked up, whether the result\n    was cached.\n- category: financial\n  text: we receive the payment confirmation and your email, not your card details.\n- category:\
  \ professional\n  text: we collect your email address, your firm, the approximate number of companies you mention and any company\n    number you check.\n- category: device\n  text: IP addresses - logged by our infrastructure for security and abuse prevention.\n- category: identifying\n  text: 'For PSCs: name, the nature of control, notification and cessation dates, identity-verification status,\n    and the month and year of birth, nationality, country of residence and service address recorded on the register.'\npurposes:\n- purpose: Rate limiting, billing, and service improvement\n  text: Used for rate limiting, billing, and service improvement.\n- purpose: Send service notifications and deliver API key\n  text: Used to deliver your key and send service notifications.\n- purpose: Letting businesses and others see who runs a company\n  text: 'legitimate interests (Article 6(1)(f)): letting businesses, lenders, compliance professionals and the public\n    see who runs and controls a company\
  \ they deal with'\n- purpose: Measure marketing channels\n  text: for 90 days, so we can measure which channels bring customers.\nretention:\n- scope: Email addresses and API keys\n  period: while your account is active\n  text: 'Email addresses and API keys: retained while your account is active, deleted within 30 days of account\n    closure on request.'\n- scope: Usage logs\n  period: 12 months\n  text: 'Usage logs: retained for 12 months, then deleted.'\n- scope: IP address logs\n  period: 30 days\n  text: 'IP address logs: retained for 30 days.'\n- scope: Companies House register copy\n  period: 30-day cycle\n  text: our copy is refreshed from Companies House on a 30-day cycle\nresidency:\n- region: EU (Ireland)\n  text: Supabase - Database (API keys, usage logs, cached Companies House data) . EU (Ireland)\n- region: EU (Frankfurt)\n  text: Railway - API hosting . EU (Frankfurt)\ntransfers:\n- mechanism: adequacy\n  text: We rely on UK adequacy regulations, including the UK Extension\
  \ to the EU-US Data Privacy Framework for certified\n    US providers\n- mechanism: other\n  text: or on the UK International Data Transfer Addendum to the EU Standard Contractual Clauses in the provider's\n    data processing terms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@registrum.co.uk\n  text: To exercise any right, email support@registrum.co.uk\nrights:\n- right: access\n  text: You have the right to access, correct, or delete your personal data\n- right: restrict or object\n  text: to restrict or object to processing\n- right: portability\n  text: and to data portability\n- right: object to officer/PSC processing\n  text: you have the right to object to this processing on grounds relating to your particular situation (Article\n    21(1))\n- right: complain to ICO\n  text: You also have the right to lodge a complaint with the ICO at ico.org.uk .\nsale_or_sharing:\n  stance: prohibited\n  text:\
  \ We do not track visitors with advertising cookies or share data with ad networks.\n"
source_yaml_url: https://artifacts.apis.io/registrum-co-uk/privacy/registrum-co-uk-privacy-policy.yml
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
summary_line: 26 quoted statements, read from registrum-co-uk's own page on 2026-11-10.
synthetic: false
tags:
- Companies House
- Financial Data
- JSON:API
- United Kingdom
- Business Intelligence
---
