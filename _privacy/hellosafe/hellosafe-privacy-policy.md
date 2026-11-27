---
api_specs:
- filename: hellosafe-conversion-api-openapi.yml
  format: yaml
  label: HelloSafe Conversion API
  slug: hellosafe-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-conversion-api-openapi.yml
- filename: hellosafe-links-api-openapi.yml
  format: yaml
  label: HelloSafe Links API
  slug: hellosafe-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-links-api-openapi.yml
- filename: hellosafe-quotes-api-openapi.yml
  format: yaml
  label: HelloSafe Quotes API
  slug: hellosafe-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-quotes-api-openapi.yml
- filename: hellosafe-coach-api-openapi.yml
  format: yaml
  label: HelloSafe Coach API
  slug: hellosafe-coach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-coach-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Registration data (email address, name, hashed password, company name, website, audience, country)
  - category: device
    text: Affiliate tracking data (hashed IP address, user agent, referrer, approximate country)
  - category: financial
    text: Conversion data (amount, commission, external order identifier, status)
  - category: behavioral
    text: Coach analytics data (client reference, age bracket, destination, etc.)
  - category: behavioral
    text: product analytics, error monitoring and session replay on the login and sign-up pages and in the partner space
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management
    text: to create and manage your partner account
  - purpose: click measurement
    text: to measure clicks on your tracking links
  - purpose: commission calculation
    text: to calculate your commissions
  - purpose: coverage analyses
    text: to generate the coverage analyses you provide to your clients
  - purpose: product improvement
    text: so that we can fix errors and improve the product
  residency:
  - region: European Union
    text: database and authentication hosted within the European Union
  - region: European Union
    text: with data hosted in the European Union
  retention:
  - period: for the duration of the relationship, plus 3 years after the last activity
    scope: Partner account
    text: 'Partner account: for the duration of the relationship, plus 3 years after the last activity (commercial limitation period).'
  - period: 13 months
    scope: Connection logs and tracking data
    text: 'Connection logs and tracking data: 13 months.'
  - period: 10 years
    scope: Billing and commission data
    text: 'Billing and commission data: 10 years (statutory accounting requirement).'
  - period: 3 years from creation
    scope: Coach analytics data
    text: 'Coach analytics data: 3 years from creation.'
  rights:
  - right: access, rectification, erasure, restriction, objection, portability, withdrawal of consent
    text: 'You have the following rights over your personal data: access, rectification, erasure, restriction, objection, portability, and withdrawal of consent (where applicable).'
  - right: CCPA right to delete and opt out of sale
    text: California residents also have the right to know, delete, and opt out of the sale of personal information under the CCPA/CPRA.
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with the relevant supervisory authority
  role:
    text: The data controller is HELLO SAFE
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use the following sub-processors, all of whom are contractually committed to comply with applicable data protection laws, including the GDPR
    url: null
  transfers:
  - mechanism: SCC
    text: Transfer outside the EU is governed by standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HelloSafe
provenance_date: '2026-11-09'
provider_name: HelloSafe
provider_slug: hellosafe
slug: hellosafe-privacy-policy
source_date: '2026-11-09'
source_filename: hellosafe-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://atlas.hellosafe.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HelloSafe\naid: hellosafe\nurl: https://atlas.hellosafe.com/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is HELLO SAFE\ndata_categories:\n- category: identifying\n  text: Registration data (email address, name, hashed password, company name, website, audience, country)\n- category: device\n  text: Affiliate tracking data (hashed IP address, user agent, referrer, approximate country)\n- category: financial\n  text: Conversion data (amount, commission, external order identifier, status)\n- category: behavioral\n  text: Coach analytics data (client reference,\
  \ age bracket, destination, etc.)\n- category: behavioral\n  text: product analytics, error monitoring and session replay on the login and sign-up pages and in the partner\n    space\npurposes:\n- purpose: account management\n  text: to create and manage your partner account\n- purpose: click measurement\n  text: to measure clicks on your tracking links\n- purpose: commission calculation\n  text: to calculate your commissions\n- purpose: coverage analyses\n  text: to generate the coverage analyses you provide to your clients\n- purpose: product improvement\n  text: so that we can fix errors and improve the product\nretention:\n- scope: Partner account\n  period: for the duration of the relationship, plus 3 years after the last activity\n  text: 'Partner account: for the duration of the relationship, plus 3 years after the last activity (commercial\n    limitation period).'\n- scope: Connection logs and tracking data\n  period: 13 months\n  text: 'Connection logs and tracking data: 13 months.'\n\
  - scope: Billing and commission data\n  period: 10 years\n  text: 'Billing and commission data: 10 years (statutory accounting requirement).'\n- scope: Coach analytics data\n  period: 3 years from creation\n  text: 'Coach analytics data: 3 years from creation.'\nresidency:\n- region: European Union\n  text: database and authentication hosted within the European Union\n- region: European Union\n  text: with data hosted in the European Union\ntransfers:\n- mechanism: SCC\n  text: Transfer outside the EU is governed by standard contractual clauses.\nsubprocessors:\n  url: null\n  text: We use the following sub-processors, all of whom are contractually committed to comply with applicable data\n    protection laws, including the GDPR\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, rectification, erasure, restriction, objection, portability, withdrawal of consent\n  text: 'You have the following rights over your personal\
  \ data: access, rectification, erasure, restriction, objection,\n    portability, and withdrawal of consent (where applicable).'\n- right: CCPA right to delete and opt out of sale\n  text: California residents also have the right to know, delete, and opt out of the sale of personal information\n    under the CCPA/CPRA.\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with the relevant supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hellosafe/privacy/hellosafe-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- rights
summary_line: 22 quoted statements, read from HelloSafe's own page on 2026-11-09.
synthetic: false
tags:
- Travel Insurance
- Insurance Distribution
- Pricing
- Travel
---
