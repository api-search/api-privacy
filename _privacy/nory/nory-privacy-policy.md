---
api_specs:
- filename: nory-authorization-api-openapi.yml
  format: yaml
  label: Nory Authorization API
  slug: nory-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-authorization-api-openapi.yml
- filename: nory-branch-api-openapi.yml
  format: yaml
  label: Nory Branch API
  slug: nory-branch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-branch-api-openapi.yml
- filename: nory-brands-api-openapi.yml
  format: yaml
  label: Nory Brands API
  slug: nory-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-brands-api-openapi.yml
- filename: nory-employee-punch-api-openapi.yml
  format: yaml
  label: Nory Employee Punch API
  slug: nory-employee-punch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-employee-punch-api-openapi.yml
- filename: nory-integration-api-openapi.yml
  format: yaml
  label: Nory Integration API
  slug: nory-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-integration-api-openapi.yml
- filename: nory-inventory-api-openapi.yml
  format: yaml
  label: Nory Inventory API
  slug: nory-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-inventory-api-openapi.yml
- filename: nory-inventory-orders-api-openapi.yml
  format: yaml
  label: Nory Inventory Orders API
  slug: nory-inventory-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-inventory-orders-api-openapi.yml
- filename: nory-location-settings-api-openapi.yml
  format: yaml
  label: Nory Location Settings API
  slug: nory-location-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-location-settings-api-openapi.yml
- filename: nory-refresh-token-api-openapi.yml
  format: yaml
  label: Nory Refresh token API
  slug: nory-refresh-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-refresh-token-api-openapi.yml
- filename: nory-templates-api-openapi.yml
  format: yaml
  label: Nory Templates API
  slug: nory-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nory/openapi/nory-templates-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information such as name, email and contact number
  - category: device
    text: Device information and identifiers
  - category: behavioral
    text: Analyze our web traffic using an analytics package.
  - category: financial
    text: Transactional information (as permitted by law)
  deletion:
    route: Email privacy@nory.ai to submit a request
    text: To exercise any of your rights as set out above, please contact us by submitting a request to privacy@nory.ai .
  dpa:
    available: true
    text: Our General Terms and Data Processing Agreement sets out how we handle any personal data contained in Customer Data when we act as your processor.
    url: null
  purposes:
  - purpose: Provide services and register account
    text: Provide you with our Services, and register your account on the platform
  - purpose: Marketing and advertising
    text: Send you relevant marketing and advertising
  - purpose: Safety and security
    text: Safety and security
  - purpose: Analytics
    text: Obtain analytics through SDK providers such as (Google and Facebook) to improve performance
  residency:
  - region: EU
    text: Whilst most of our data processing is carried out in the EU
  retention:
  - period: null
    scope: Personal information generally
    text: Generally, we retain personal information for the period necessary to fulfil the purposes outlined in this privacy notice and in accordance with our internal policies, our data retention and regulatory obligations, and applicable law.
  rights:
  - right: access
    text: access to your information
  - right: delete or erase
    text: delete or erase your information (sometimes called the right to be forgotten)
  - right: object
    text: object to our processing your information
  - right: data portability
    text: request the transfer of some of the information we hold about you (known as data portability)
  - right: withdraw consent
    text: withdrawal of your consent (where consent is relied on for processing purposes)
  role:
    text: If you are already a valued Nory customer, then you are a controller of any Customer Data (as defined in our General Terms) that you upload to our platform, and Nory processes that data on your behalf as a data processor.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: These measures include data transfer agreements.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nory
provenance_date: '2026-11-10'
provider_name: Nory
provider_slug: nory
slug: nory-privacy-policy
source_date: '2026-11-10'
source_filename: nory-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.nory.ai/legal/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nory\naid: nory\nurl: https://www.nory.ai/legal/terms-privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: If you are already a valued Nory customer, then you are a controller of any Customer Data (as defined in\n    our General Terms) that you upload to our platform, and Nory processes that data on your behalf as a data processor.\ndata_categories:\n- category: contact\n  text: Contact information such as name, email and contact number\n- category: device\n  text: Device information and identifiers\n- category: behavioral\n  text: Analyze our web traffic using an analytics package.\n- category:\
  \ financial\n  text: Transactional information (as permitted by law)\npurposes:\n- purpose: Provide services and register account\n  text: Provide you with our Services, and register your account on the platform\n- purpose: Marketing and advertising\n  text: Send you relevant marketing and advertising\n- purpose: Safety and security\n  text: Safety and security\n- purpose: Analytics\n  text: Obtain analytics through SDK providers such as (Google and Facebook) to improve performance\nretention:\n- scope: Personal information generally\n  period: null\n  text: Generally, we retain personal information for the period necessary to fulfil the purposes outlined in this\n    privacy notice and in accordance with our internal policies, our data retention and regulatory obligations,\n    and applicable law.\nresidency:\n- region: EU\n  text: Whilst most of our data processing is carried out in the EU\ntransfers:\n- mechanism: other\n  text: These measures include data transfer agreements.\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Our General Terms and Data Processing Agreement sets out how we handle any personal data contained in Customer\n    Data when we act as your processor.\ndeletion:\n  route: Email privacy@nory.ai to submit a request\n  text: To exercise any of your rights as set out above, please contact us by submitting a request to privacy@nory.ai\n    .\nrights:\n- right: access\n  text: access to your information\n- right: delete or erase\n  text: delete or erase your information (sometimes called the right to be forgotten)\n- right: object\n  text: object to our processing your information\n- right: data portability\n  text: request the transfer of some of the information we hold about you (known as data portability)\n- right: withdraw consent\n  text: withdrawal of your consent (where consent is relied on for processing purposes)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nory/privacy/nory-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Nory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant
- Hospitality
- Inventory
- Workforce
- Payroll
- Point-of-Sale
- Artificial Intelligence
- Food and Beverage
---
