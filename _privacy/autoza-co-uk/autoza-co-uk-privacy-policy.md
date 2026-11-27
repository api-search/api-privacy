---
api_specs:
- filename: autoza-co-uk-dealers-api-openapi.yml
  format: yaml
  label: Autoza UK Dealers API
  slug: autoza-co-uk-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-dealers-api-openapi.yml
- filename: autoza-co-uk-listing-api-openapi.yml
  format: yaml
  label: Autoza UK Listing API
  slug: autoza-co-uk-listing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-listing-api-openapi.yml
- filename: autoza-co-uk-makes-api-openapi.yml
  format: yaml
  label: Autoza UK Makes API
  slug: autoza-co-uk-makes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-makes-api-openapi.yml
- filename: autoza-co-uk-market-api-openapi.yml
  format: yaml
  label: Autoza UK Market API
  slug: autoza-co-uk-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-market-api-openapi.yml
- filename: autoza-co-uk-search-api-openapi.yml
  format: yaml
  label: Autoza UK Search API
  slug: autoza-co-uk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-search-api-openapi.yml
- filename: autoza-co-uk-stats-api-openapi.yml
  format: yaml
  label: Autoza UK Stats API
  slug: autoza-co-uk-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-stats-api-openapi.yml
- filename: autoza-co-uk-vehicles-api-openapi.yml
  format: yaml
  label: Autoza UK Vehicles API
  slug: autoza-co-uk-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoza-co-uk/openapi/autoza-co-uk-vehicles-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email, password (hashed), phone number, profile photo.'
  - category: location
    text: 'Analytics: advert views, taps on an advert''s phone, WhatsApp and share buttons, and blog article reads, counted on our own servers.'
  - category: communication
    text: 'Mark chat history: the messages you exchange with Mark, our buyer-side AI assistant, including any vehicle criteria you share.'
  - category: financial
    text: 'Billing: billing address and Stripe customer reference when a paid subscription is active (card data is processed directly by Stripe and never touches our servers).'
  - category: professional
    text: 'Business details: trading name, company number, VAT/registered address, opening hours, services offered, social handles, logo and showroom imagery.'
  deletion:
    route: Email info@autoza.co.uk
    text: To exercise any of these rights, email info@autoza.co.uk .
  dpa:
    available: true
    text: Each is bound by a written data-processing agreement that mirrors Article 28 UK GDPR.
    url: null
  purposes:
  - purpose: Operating accounts and providing the platform
    text: Operating your buyer or dealer account and providing the platform
  - purpose: Fraud prevention and security
    text: Fraud prevention, platform abuse detection, security monitoring
  - purpose: Website analytics and product improvement
    text: Website analytics and product improvement
  - purpose: Marketing emails
    text: Marketing emails about Autoza features and dealer offers
  - purpose: Telling UK dealerships about Autoza
    text: Telling UK dealerships about Autoza, using business contact details we did not get from you, almost all from public sources (section 2.4)
  residency:
  - region: United Kingdom
    text: Our website, database and file storage are hosted in London, in the United Kingdom (Vercel's London region, Neon and Amazon Web Services' London region).
  retention:
  - period: 6 years
    scope: Closed accounts
    text: 'Closed accounts: retained for 6 years after closure to satisfy UK tax and accounting obligations (HMRC); then deleted or fully anonymised.'
  - period: 12 months
    scope: Mark chats of visitors not signed in
    text: Mark chats of visitors who are not signed in are saved without a name or IP address and deleted 12 months after the last message (see 2.3).
  - period: 14 months
    scope: Website analytics
    text: 'Website analytics: anonymised after 14 months.'
  - period: 12 months
    scope: Security and access logs
    text: 'Security and access logs: 12 months.'
  - period: null
    scope: Registration checks
    text: 'Registration checks: the registration you type and the result are not stored.'
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you.
  - right: Erasure
    text: Erasure — ask us to delete your data (the "right to be forgotten"), subject to legal retention obligations.
  - right: Objection
    text: Objection — object to processing based on legitimate interests, or to direct marketing at any time.
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format.
  role:
    text: We are the data controller for personal data processed through autoza.co.uk.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We do not currently share personal data with third-party advertising or marketing partners.
  subprocessors:
    text: Each is bound by a written data-processing agreement that mirrors Article 28 UK GDPR.
    url: null
  transfers:
  - mechanism: other
    text: For transfers out of the UK we rely on the UK's International Data Transfer Agreement (IDTA) or the UK Addendum to the EU Standard Contractual Clauses, together with the European Commission's Standard Contractual Clauses for transfers out of the EEA.
  - mechanism: adequacy
    text: Where the UK Government has recognised an adequacy decision or "Data Bridge" for the destination country, we rely on that.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Autoza UK
provenance_date: '2026-11-09'
provider_name: Autoza UK
provider_slug: autoza-co-uk
slug: autoza-co-uk-privacy-policy
source_date: '2026-11-09'
source_filename: autoza-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://autoza.co.uk/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Autoza UK\naid: autoza-co-uk\nurl: https://autoza.co.uk/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for personal data processed through autoza.co.uk.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email, password (hashed), phone number, profile photo.'\n- category: location\n  text: 'Analytics: advert views, taps on an advert''s phone, WhatsApp and share buttons, and blog article reads,\n    counted on our own servers.'\n- category: communication\n  text: 'Mark chat history: the messages you exchange with Mark, our buyer-side\
  \ AI assistant, including any vehicle\n    criteria you share.'\n- category: financial\n  text: 'Billing: billing address and Stripe customer reference when a paid subscription is active (card data is\n    processed directly by Stripe and never touches our servers).'\n- category: professional\n  text: 'Business details: trading name, company number, VAT/registered address, opening hours, services offered,\n    social handles, logo and showroom imagery.'\npurposes:\n- purpose: Operating accounts and providing the platform\n  text: Operating your buyer or dealer account and providing the platform\n- purpose: Fraud prevention and security\n  text: Fraud prevention, platform abuse detection, security monitoring\n- purpose: Website analytics and product improvement\n  text: Website analytics and product improvement\n- purpose: Marketing emails\n  text: Marketing emails about Autoza features and dealer offers\n- purpose: Telling UK dealerships about Autoza\n  text: Telling UK dealerships about\
  \ Autoza, using business contact details we did not get from you, almost all\n    from public sources (section 2.4)\nretention:\n- scope: Closed accounts\n  period: 6 years\n  text: 'Closed accounts: retained for 6 years after closure to satisfy UK tax and accounting obligations (HMRC);\n    then deleted or fully anonymised.'\n- scope: Mark chats of visitors not signed in\n  period: 12 months\n  text: Mark chats of visitors who are not signed in are saved without a name or IP address and deleted 12 months\n    after the last message (see 2.3).\n- scope: Website analytics\n  period: 14 months\n  text: 'Website analytics: anonymised after 14 months.'\n- scope: Security and access logs\n  period: 12 months\n  text: 'Security and access logs: 12 months.'\n- scope: Registration checks\n  period: null\n  text: 'Registration checks: the registration you type and the result are not stored.'\nresidency:\n- region: United Kingdom\n  text: Our website, database and file storage are hosted in London,\
  \ in the United Kingdom (Vercel's London region,\n    Neon and Amazon Web Services' London region).\ntransfers:\n- mechanism: other\n  text: For transfers out of the UK we rely on the UK's International Data Transfer Agreement (IDTA) or the UK Addendum\n    to the EU Standard Contractual Clauses, together with the European Commission's Standard Contractual Clauses\n    for transfers out of the EEA.\n- mechanism: adequacy\n  text: Where the UK Government has recognised an adequacy decision or \"Data Bridge\" for the destination country,\n    we rely on that.\nsubprocessors:\n  url: null\n  text: Each is bound by a written data-processing agreement that mirrors Article 28 UK GDPR.\ndpa:\n  available: true\n  url: null\n  text: Each is bound by a written data-processing agreement that mirrors Article 28 UK GDPR.\ndeletion:\n  route: Email info@autoza.co.uk\n  text: To exercise any of these rights, email info@autoza.co.uk .\nrights:\n- right: Access\n  text: Access — request a copy of the\
  \ personal data we hold about you.\n- right: Erasure\n  text: Erasure — ask us to delete your data (the \"right to be forgotten\"), subject to legal retention obligations.\n- right: Objection\n  text: Objection — object to processing based on legitimate interests, or to direct marketing at any time.\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format.\nsale_or_sharing:\n  stance: unstated\n  text: We do not currently share personal data with third-party advertising or marketing partners.\n"
source_yaml_url: https://artifacts.apis.io/autoza-co-uk/privacy/autoza-co-uk-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Autoza UK's own page on 2026-11-09.
synthetic: false
tags:
- Automotive
- Marketplace
- Artificial Intelligence
- Used Vehicles
- United Kingdom
---
