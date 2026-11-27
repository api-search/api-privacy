---
api_specs:
- filename: archera-commitment-plans-api-openapi.yml
  format: yaml
  label: Archera Commitment Plans API
  slug: archera-commitment-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-commitment-plans-api-openapi.yml
- filename: archera-commitments-api-openapi.yml
  format: yaml
  label: Archera Commitments API
  slug: archera-commitments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-commitments-api-openapi.yml
- filename: archera-exchanges-api-openapi.yml
  format: yaml
  label: Archera Exchanges API
  slug: archera-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-exchanges-api-openapi.yml
- filename: archera-metrics-api-openapi.yml
  format: yaml
  label: Archera Metrics API
  slug: archera-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-metrics-api-openapi.yml
- filename: archera-orgs-api-openapi.yml
  format: yaml
  label: Archera Orgs API
  slug: archera-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-orgs-api-openapi.yml
- filename: archera-resources-api-openapi.yml
  format: yaml
  label: Archera Resources API
  slug: archera-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-resources-api-openapi.yml
- filename: archera-uploads-api-openapi.yml
  format: yaml
  label: Archera Uploads API
  slug: archera-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-uploads-api-openapi.yml
- filename: archera-well-known-api-openapi.yml
  format: yaml
  label: Archera Well-Known API
  slug: archera-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-well-known-api-openapi.yml
- filename: archera-oauth-api-openapi.yml
  format: yaml
  label: Archera O Auth API
  slug: archera-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archera/openapi/archera-oauth-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: During registration a user is required to give certain information (such as name and email address).
  - category: contact
    text: you must provide contact information (like name and billing address)
  - category: financial
    text: financial information (like credit card number, expiration date)
  - category: demographic
    text: At your option, you may also provide demographic information (such as gender or age) about yourself, but it is not required.
  - category: behavioral
    text: Cookies can also enable us to track and target the interests of our users to enhance the experience on our site.
  deletion:
    route: Contact us by email address or phone number on the website
    text: Have us delete any data we have about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to inquiries
    text: We will use your information to respond to you, regarding the reason you contacted us.
  - purpose: Contact about products or services
    text: This information is used to contact you about the products/services on our site in which you have expressed interest.
  - purpose: Billing and service delivery
    text: This information is used for billing purposes and to properly deliver our services.
  rights:
  - right: Access
    text: See what data we have about you, if any.
  - right: Correction
    text: Change/correct any data we have about you.
  - right: Deletion
    text: Have us delete any data we have about you.
  - right: Objection to contact
    text: You may opt out of any future contacts from us at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will not sell or rent this information to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Archera
provenance_date: '2026-11-09'
provider_name: Archera
provider_slug: archera
slug: archera-privacy-policy
source_date: '2026-11-09'
source_filename: archera-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.archera.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Archera\naid: archera\nurl: https://www.archera.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: During registration a user is required to give certain information (such as name and email address).\n- category: contact\n  text: you must provide contact information (like name and billing address)\n- category: financial\n  text: financial information (like credit card number, expiration date)\n- category: demographic\n  text: At your option, you may also provide demographic information (such as gender or age) about yourself, but\n\
  \    it is not required.\n- category: behavioral\n  text: Cookies can also enable us to track and target the interests of our users to enhance the experience on our\n    site.\npurposes:\n- purpose: Respond to inquiries\n  text: We will use your information to respond to you, regarding the reason you contacted us.\n- purpose: Contact about products or services\n  text: This information is used to contact you about the products/services on our site in which you have expressed\n    interest.\n- purpose: Billing and service delivery\n  text: This information is used for billing purposes and to properly deliver our services.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us by email address or phone number on the website\n  text: Have us delete any data we have about you.\nrights:\n- right: Access\n  text: See what data we have about you, if any.\n- right: Correction\n\
  \  text: Change/correct any data we have about you.\n- right: Deletion\n  text: Have us delete any data we have about you.\n- right: Objection to contact\n  text: You may opt out of any future contacts from us at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell or rent this information to anyone.\n"
source_yaml_url: https://artifacts.apis.io/archera/privacy/archera-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Archera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- FinOps
- Cloud Cost Management
- Cloud Commitments
- Cost Optimization
- MCP
- Amazon Web Services
- Microsoft Azure
- Google Cloud
- Reserved Instances
---
