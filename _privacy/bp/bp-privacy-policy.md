---
api_specs:
- filename: bp-cards-api-openapi.yml
  format: yaml
  label: BP Cards API
  slug: bp-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-cards-api-openapi.yml
- filename: bp-fueling-api-openapi.yml
  format: yaml
  label: BP Fueling API
  slug: bp-fueling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-fueling-api-openapi.yml
- filename: bp-openapiinvoices-api-openapi.yml
  format: yaml
  label: BP Open API Invoices API
  slug: bp-openapiinvoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-openapiinvoices-api-openapi.yml
- filename: bp-openapitransactions-api-openapi.yml
  format: yaml
  label: BP Open API Transactions API
  slug: bp-openapitransactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-openapitransactions-api-openapi.yml
- filename: bp-sitediscovery-api-openapi.yml
  format: yaml
  label: BP Site Discovery API
  slug: bp-sitediscovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-sitediscovery-api-openapi.yml
- filename: bp-token-api-openapi.yml
  format: yaml
  label: BP Token API
  slug: bp-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-token-api-openapi.yml
- filename: bp-health-check-api-openapi.yml
  format: yaml
  label: BP Health Check API
  slug: bp-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-health-check-api-openapi.yml
- filename: bp-payment-method-api-openapi.yml
  format: yaml
  label: BP Payment Method API
  slug: bp-payment-method-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bp/openapi/bp-payment-method-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Your telephone number, an email or postal address.
  - category: identifying
    text: Your account username(s) or password(s).
  - category: financial
    text: Payment details.
  - category: location
    text: Your time zone, location and your IP address
  - category: behavioral
    text: information about your browsing
  - category: professional
    text: Data such as your job title, company name, company email address, business phone number, business address.
  - category: communication
    text: We usually keep a record of our correspondence with you, including telephone calls.
  - category: other
    text: Video or voice recordings of you, through CCTV when you attend our sites or when you call our customer care or other support services.
  deletion:
    route: Contact us via the Data Protection Rights page or the contact details on the page
    text: You can ask us to delete or remove your personal data whenever you like.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Targeted advertising
    text: These ads may be customised based on your demographic data, inferred interests and browsing context.
  - purpose: Profiling
    text: We may use automated data processing to tailor your experience based on your preferences or provide promotional offers relevant to your interests.
  - purpose: Artificial intelligence
    text: We may use AI systems to support productivity and efficiency within our operations.
  - purpose: Analytics
    text: To conduct analytics, statistics, and derive insight.
  rights:
  - right: Access
    text: You may request confirmation of whether we process personal data relating to you and, if so, information about such processing and to request to receive a copy of personal data we hold about you.
  - right: Correction
    text: You can request that we correct any incomplete or inaccurate data we hold about you
  - right: Erasure
    text: You can ask us to delete or remove your personal data whenever you like.
  - right: Restriction of processing
    text: 'You can ask us to suspend processing your personal data where:'
  - right: Withdraw consent
    text: Withdrawal will not affect the lawfulness of any processing carried out before you withdraw your consent.
  - right: Object to processing
    text: you have the right to object to the processing, including to object to profiling on grounds relating to your particular situation.
  - right: Complain to supervisory authority
    text: you may have the right to complain to the competent supervisory authority.
  role:
    text: Your data will be collected and processed by a member of the bp group.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: implementing standard contractual clauses
  - mechanism: adequacy
    text: relying on adequacy decisions issued by relevant authorities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BP
provenance_date: '2026-11-09'
provider_name: BP
provider_slug: bp
slug: bp-privacy-policy
source_date: '2026-11-09'
source_filename: bp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bp.com/en/global/privacy/products-and-services/united-kingdom/privacy-notice.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BP\naid: bp\nurl: https://www.bp.com/en/global/privacy/products-and-services/united-kingdom/privacy-notice.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Your data will be collected and processed by a member of the bp group.\ndata_categories:\n- category: contact\n  text: Your telephone number, an email or postal address.\n- category: identifying\n  text: Your account username(s) or password(s).\n- category: financial\n  text: Payment details.\n- category: location\n  text: Your time zone, location and your IP address\n- category: behavioral\n  text: information about your browsing\n\
  - category: professional\n  text: Data such as your job title, company name, company email address, business phone number, business address.\n- category: communication\n  text: We usually keep a record of our correspondence with you, including telephone calls.\n- category: other\n  text: Video or voice recordings of you, through CCTV when you attend our sites or when you call our customer care\n    or other support services.\npurposes:\n- purpose: Targeted advertising\n  text: These ads may be customised based on your demographic data, inferred interests and browsing context.\n- purpose: Profiling\n  text: We may use automated data processing to tailor your experience based on your preferences or provide promotional\n    offers relevant to your interests.\n- purpose: Artificial intelligence\n  text: We may use AI systems to support productivity and efficiency within our operations.\n- purpose: Analytics\n  text: To conduct analytics, statistics, and derive insight.\nretention: []\nresidency:\
  \ []\ntransfers:\n- mechanism: SCC\n  text: implementing standard contractual clauses\n- mechanism: adequacy\n  text: relying on adequacy decisions issued by relevant authorities\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us via the Data Protection Rights page or the contact details on the page\n  text: You can ask us to delete or remove your personal data whenever you like.\nrights:\n- right: Access\n  text: You may request confirmation of whether we process personal data relating to you and, if so, information\n    about such processing and to request to receive a copy of personal data we hold about you.\n- right: Correction\n  text: You can request that we correct any incomplete or inaccurate data we hold about you\n- right: Erasure\n  text: You can ask us to delete or remove your personal data whenever you like.\n- right: Restriction of processing\n  text: 'You can ask us to suspend processing your personal\
  \ data where:'\n- right: Withdraw consent\n  text: Withdrawal will not affect the lawfulness of any processing carried out before you withdraw your consent.\n- right: Object to processing\n  text: you have the right to object to the processing, including to object to profiling on grounds relating to\n    your particular situation.\n- right: Complain to supervisory authority\n  text: you may have the right to complain to the competent supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bp/privacy/bp-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- transfers
- deletion
- rights
summary_line: 23 quoted statements, read from BP's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Oil
- Gas
- Renewables
- Developer Platform
- Fleet Management
- Fuel Cards
- Mobility
- Retail Fuel
- EV Charging
- Oil and Gas
---
