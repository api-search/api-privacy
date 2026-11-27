---
api_specs:
- filename: statable-stats-api-bootstrap-api-openapi.yml
  format: yaml
  label: Statable Stats API Bootstrap API
  slug: statable-stats-api-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-bootstrap-api-openapi.yml
- filename: statable-stats-api-keys-api-openapi.yml
  format: yaml
  label: Statable Stats API Keys API
  slug: statable-stats-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-keys-api-openapi.yml
- filename: statable-stats-api-sites-api-openapi.yml
  format: yaml
  label: Statable Stats API Sites API
  slug: statable-stats-api-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-sites-api-openapi.yml
- filename: statable-stats-api-stats-api-openapi.yml
  format: yaml
  label: Statable Stats API Stats API
  slug: statable-stats-api-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-stats-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: email address, authentication provider identifier (if you sign in through Google)
  - category: identifying
    text: we record the IP address, approximate location (country and city) and browser used
  - category: device
    text: browser type, operating system, device type, country, region and city (derived from the IP address via a local GeoIP database; the IP itself is not retained)
  - category: financial
    text: billing email address, payment status, subscription status, transaction identifiers
  - category: behavioral
    text: page view timestamps, session duration, engagement time and scroll depth, outbound link clicks and file downloads
  deletion:
    route: Customer deletes websites or account from the dashboard, or requests deletion
    text: the Customer can delete individual websites or the entire account at any time from the dashboard, and we delete the associated analytics data on request.
  dpa:
    available: true
    text: We process visitor data only to provide the analytics service under our Terms and our Data Processing Agreement
    url: null
  purposes:
  - purpose: provide analytics services
    text: provide the Services to Customers
  - purpose: security monitoring
    text: This information is used solely for security monitoring, preventing abuse or attacks and maintaining the availability of the Website.
  - purpose: marketing communications
    text: send marketing communications, including information about new services, newsletters, product offers, and promotions that may be relevant to you
  residency:
  - region: Netherlands
    text: Your analytics data is stored exclusively on servers in the Netherlands.
  retention:
  - period: null
    scope: analytics data
    text: Analytics data is retained while the Customer's account exists.
  - period: within 14 days
    scope: encrypted backup copies
    text: from encrypted backup copies automatically within 14 days
  rights:
  - right: access
    text: You have the right to request access to your personal data and to obtain a copy of it.
  - right: correction
    text: You have the right to request correction of inaccurate or incomplete personal data.
  - right: deletion
    text: You may request deletion of your personal data in certain circumstances
  - right: restriction
    text: You may request restriction of processing in certain situations
  - right: portability
    text: Where applicable, you may request that your personal data be provided in a structured, commonly used, and machine-readable format
  - right: objection
    text: You may object to the processing of your personal data in certain circumstances
  role:
    text: For this Website we are the controller of that measurement
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information, as those terms are defined by the CCPA/CPRA.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Statable Stats API
provenance_date: '2026-11-10'
provider_name: Statable Stats API
provider_slug: statable-stats-api
slug: statable-stats-api-privacy-policy
source_date: '2026-11-10'
source_filename: statable-stats-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://statable.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Statable Stats API\naid: statable-stats-api\nurl: https://statable.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For this Website we are the controller of that measurement\ndata_categories:\n- category: contact\n  text: email address, authentication provider identifier (if you sign in through Google)\n- category: identifying\n  text: we record the IP address, approximate location (country and city) and browser used\n- category: device\n  text: browser type, operating system, device type, country, region and city (derived from the IP address via a\n    local GeoIP database; the IP itself\
  \ is not retained)\n- category: financial\n  text: billing email address, payment status, subscription status, transaction identifiers\n- category: behavioral\n  text: page view timestamps, session duration, engagement time and scroll depth, outbound link clicks and file\n    downloads\npurposes:\n- purpose: provide analytics services\n  text: provide the Services to Customers\n- purpose: security monitoring\n  text: This information is used solely for security monitoring, preventing abuse or attacks and maintaining the\n    availability of the Website.\n- purpose: marketing communications\n  text: send marketing communications, including information about new services, newsletters, product offers, and\n    promotions that may be relevant to you\nretention:\n- scope: analytics data\n  period: null\n  text: Analytics data is retained while the Customer's account exists.\n- scope: encrypted backup copies\n  period: within 14 days\n  text: from encrypted backup copies automatically within\
  \ 14 days\nresidency:\n- region: Netherlands\n  text: Your analytics data is stored exclusively on servers in the Netherlands.\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We process visitor data only to provide the analytics service under our Terms and our Data Processing Agreement\ndeletion:\n  route: Customer deletes websites or account from the dashboard, or requests deletion\n  text: the Customer can delete individual websites or the entire account at any time from the dashboard, and we\n    delete the associated analytics data on request.\nrights:\n- right: access\n  text: You have the right to request access to your personal data and to obtain a copy of it.\n- right: correction\n  text: You have the right to request correction of inaccurate or incomplete personal data.\n- right: deletion\n \
  \ text: You may request deletion of your personal data in certain circumstances\n- right: restriction\n  text: You may request restriction of processing in certain situations\n- right: portability\n  text: Where applicable, you may request that your personal data be provided in a structured, commonly used, and\n    machine-readable format\n- right: objection\n  text: You may object to the processing of your personal data in certain circumstances\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information, as those terms are defined by the CCPA/CPRA.\n"
source_yaml_url: https://artifacts.apis.io/statable-stats-api/privacy/statable-stats-api-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Statable Stats API's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Cookieless
- Privacy
- GDPR
- OpenAPI
- MCP
- Llms.txt
- EU-hosted
---
