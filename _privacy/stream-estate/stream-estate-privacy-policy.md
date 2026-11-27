---
api_specs:
- filename: stream-estate-indicators-api-openapi.yml
  format: yaml
  label: stream-estate Indicators API
  slug: stream-estate-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-indicators-api-openapi.yml
- filename: stream-estate-properties-api-openapi.yml
  format: yaml
  label: stream-estate Properties API
  slug: stream-estate-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-properties-api-openapi.yml
- filename: stream-estate-searches-api-openapi.yml
  format: yaml
  label: stream-estate Searches API
  slug: stream-estate-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-searches-api-openapi.yml
- filename: stream-estate-webhooks-api-openapi.yml
  format: yaml
  label: stream-estate Webhooks API
  slug: stream-estate-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stream-estate/openapi/stream-estate-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes first name, last name, username or similar identifier.
  - category: contact
    text: Contact Data includes billing address, email address, and telephone numbers.
  - category: financial
    text: Financial Data includes your transaction history.
  - category: device
    text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location
  - category: behavioral
    text: Usage Data includes information about how you use our website and API services.
  - category: other
    text: API Request Data includes information about the API requests you make, including endpoint parameters and query data.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and subscription management
    text: To register you as a customer and manage your account and subscription (performance of a contract)
  - purpose: Processing API requests
    text: To process and deliver your API requests (performance of a contract)
  - purpose: Payments and accounting
    text: To keep invoices and accounting records (legal obligation)
  - purpose: Security and abuse prevention
    text: To administer and protect our business and website, including security, abuse prevention and rate limits (legitimate interest)
  - purpose: Audience measurement with consent
    text: To measure the audience of our website and improve it (consent)
  retention:
  - period: null
    scope: Personal data
    text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it for, including for the purposes of satisfying any legal, accounting, or reporting requirements.
  rights:
  - right: Access
    text: Request access to your personal data
  - right: Correction
    text: Request correction of your personal data
  - right: Erasure
    text: Request erasure of your personal data
  - right: Objection
    text: Object to processing of your personal data
  - right: Restriction
    text: Request restriction of processing your personal data
  - right: Portability
    text: Request transfer of your personal data
  - right: Withdraw consent
    text: Right to withdraw consent
  role:
    text: DLL SAS, which operates Stream.Estate, is the controller and responsible for your personal data
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare, for website hosting and content delivery; Stripe, for payment processing; PostHog, for website audience measurement, hosted in the European Union; Help Scout, for the support chat; IPGeolocation, to determine your location from your IP address when you confirm your account
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a transfer takes place, we rely on an adequacy decision of the European Commission, such as the EU-U.S. Data Privacy Framework for certified providers
  - mechanism: SCC
    text: or on the Standard Contractual Clauses adopted by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: stream-estate
provenance_date: '2026-11-10'
provider_name: stream-estate
provider_slug: stream-estate
slug: stream-estate-privacy-policy
source_date: '2026-11-10'
source_filename: stream-estate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://stream.estate/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: stream-estate\naid: stream-estate\nurl: https://stream.estate/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: DLL SAS, which operates Stream.Estate, is the controller and responsible for your personal data\ndata_categories:\n- category: identifying\n  text: Identity Data includes first name, last name, username or similar identifier.\n- category: contact\n  text: Contact Data includes billing address, email address, and telephone numbers.\n- category: financial\n  text: Financial Data includes your transaction history.\n- category: device\n  text: Technical Data includes internet protocol\
  \ (IP) address, your login data, browser type and version, time\n    zone setting and location\n- category: behavioral\n  text: Usage Data includes information about how you use our website and API services.\n- category: other\n  text: API Request Data includes information about the API requests you make, including endpoint parameters and\n    query data.\npurposes:\n- purpose: Account and subscription management\n  text: To register you as a customer and manage your account and subscription (performance of a contract)\n- purpose: Processing API requests\n  text: To process and deliver your API requests (performance of a contract)\n- purpose: Payments and accounting\n  text: To keep invoices and accounting records (legal obligation)\n- purpose: Security and abuse prevention\n  text: To administer and protect our business and website, including security, abuse prevention and rate limits\n    (legitimate interest)\n- purpose: Audience measurement with consent\n  text: To measure the audience\
  \ of our website and improve it (consent)\nretention:\n- scope: Personal data\n  period: null\n  text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it\n    for, including for the purposes of satisfying any legal, accounting, or reporting requirements.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where a transfer takes place, we rely on an adequacy decision of the European Commission, such as the EU-U.S.\n    Data Privacy Framework for certified providers\n- mechanism: SCC\n  text: or on the Standard Contractual Clauses adopted by the European Commission.\nsubprocessors:\n  url: null\n  text: Cloudflare, for website hosting and content delivery; Stripe, for payment processing; PostHog, for website\n    audience measurement, hosted in the European Union; Help Scout, for the support chat; IPGeolocation, to determine\n    your location from your IP address when you confirm your account\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Request access to your personal data\n- right: Correction\n  text: Request correction of your personal data\n- right: Erasure\n  text: Request erasure of your personal data\n- right: Objection\n  text: Object to processing of your personal data\n- right: Restriction\n  text: Request restriction of processing your personal data\n- right: Portability\n  text: Request transfer of your personal data\n- right: Withdraw consent\n  text: Right to withdraw consent\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stream-estate/privacy/stream-estate-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- rights
summary_line: 23 quoted statements, read from stream-estate's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- PropTech
- Data API
- Market Analytics
- Valuation
---
