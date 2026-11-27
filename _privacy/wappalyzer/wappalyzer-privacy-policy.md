---
api_specs:
- filename: wappalyzer-metadata-api-openapi.yml
  format: yaml
  label: Wappalyzer Metadata API
  slug: wappalyzer-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-metadata-api-openapi.yml
- filename: wappalyzer-basics-api-openapi.yml
  format: yaml
  label: Wappalyzer Basics API
  slug: wappalyzer-basics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-basics-api-openapi.yml
- filename: wappalyzer-lists-api-openapi.yml
  format: yaml
  label: Wappalyzer Lists API
  slug: wappalyzer-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-lists-api-openapi.yml
- filename: wappalyzer-lookup-api-openapi.yml
  format: yaml
  label: Wappalyzer Lookup API
  slug: wappalyzer-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-lookup-api-openapi.yml
- filename: wappalyzer-subdomains-api-openapi.yml
  format: yaml
  label: Wappalyzer Subdomains API
  slug: wappalyzer-subdomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-subdomains-api-openapi.yml
- filename: wappalyzer-verify-api-openapi.yml
  format: yaml
  label: Wappalyzer Verify API
  slug: wappalyzer-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-verify-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, you provide personal information such as your email address and password.
  - category: financial
    text: If you add a payment method, payment details are handled by our payment providers.
  - category: device
    text: browser and device details, and cookies or similar identifiers
  - category: communication
    text: When you submit a domain, URL, email address, or file to Wappalyzer, we process that data to provide the requested lookup, verification, enrichment, export, or other feature.
  deletion:
    route: contact
    text: If you want to request access to, correction of, or deletion of your personal information, please contact us at
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: security, authentication, analytics, billing, abuse prevention, service reliability
    text: We use this information for security, authentication, analytics, billing, abuse prevention, and service reliability.
  - purpose: improve dataset and commercial products
    text: Data collected through the extension may be used to improve our dataset and may be shared or sold as part of our commercial products and services.
  residency:
  - region: Australia
    text: Wappalyzer operates from Australia and uses providers and infrastructure that may process information in Australia, the United States, and other countries where we or our providers operate.
  retention:
  - period: null
    scope: personal information
    text: We retain personal information for as long as reasonably necessary to provide the Services
  rights:
  - right: access, correction, deletion
    text: request access to, correction of, or deletion of your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Data collected through the extension may be used to improve our dataset and may be shared or sold as part of our commercial products and services.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Wappalyzer
provenance_date: '2026-11-10'
provider_name: Wappalyzer
provider_slug: wappalyzer
slug: wappalyzer-privacy-policy
source_date: '2026-11-10'
source_filename: wappalyzer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.wappalyzer.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Wappalyzer\naid: wappalyzer\nurl: https://www.wappalyzer.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, you provide personal information such as your email address and password.\n- category: financial\n  text: If you add a payment method, payment details are handled by our payment providers.\n- category: device\n  text: browser and device details, and cookies or similar identifiers\n- category: communication\n  text: When you submit a domain, URL, email address, or file to Wappalyzer, we process\
  \ that data to provide the\n    requested lookup, verification, enrichment, export, or other feature.\npurposes:\n- purpose: security, authentication, analytics, billing, abuse prevention, service reliability\n  text: We use this information for security, authentication, analytics, billing, abuse prevention, and service\n    reliability.\n- purpose: improve dataset and commercial products\n  text: Data collected through the extension may be used to improve our dataset and may be shared or sold as part\n    of our commercial products and services.\nretention:\n- scope: personal information\n  period: null\n  text: We retain personal information for as long as reasonably necessary to provide the Services\nresidency:\n- region: Australia\n  text: Wappalyzer operates from Australia and uses providers and infrastructure that may process information in\n    Australia, the United States, and other countries where we or our providers operate.\ntransfers: []\nsubprocessors:\n  url: null\n  text:\
  \ null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact\n  text: If you want to request access to, correction of, or deletion of your personal information, please contact\n    us at\nrights:\n- right: access, correction, deletion\n  text: request access to, correction of, or deletion of your personal information\nsale_or_sharing:\n  stance: conditional\n  text: Data collected through the extension may be used to improve our dataset and may be shared or sold as part\n    of our commercial products and services.\n"
source_yaml_url: https://artifacts.apis.io/wappalyzer/privacy/wappalyzer-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from Wappalyzer's own page on 2026-11-10.
synthetic: false
tags:
- Technology Detection
- Technographics
- Website Analysis
- CMS Detection
- Framework Detection
- Lead Enrichment
- Sales Intelligence
- Subdomain Discovery
- Email Verification
- Market Research
- Data Enrichment
---
