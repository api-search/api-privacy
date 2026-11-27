---
api_specs:
- filename: meditech-allergy-api-openapi.yml
  format: yaml
  label: meditech Allergy API
  slug: meditech-allergy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-allergy-api-openapi.yml
- filename: meditech-capability-api-openapi.yml
  format: yaml
  label: meditech Capability API
  slug: meditech-capability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-capability-api-openapi.yml
- filename: meditech-condition-api-openapi.yml
  format: yaml
  label: meditech Condition API
  slug: meditech-condition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-condition-api-openapi.yml
- filename: meditech-diagnostic-api-openapi.yml
  format: yaml
  label: meditech Diagnostic API
  slug: meditech-diagnostic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-diagnostic-api-openapi.yml
- filename: meditech-encounter-api-openapi.yml
  format: yaml
  label: meditech Encounter API
  slug: meditech-encounter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-encounter-api-openapi.yml
- filename: meditech-medication-api-openapi.yml
  format: yaml
  label: meditech Medication API
  slug: meditech-medication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-medication-api-openapi.yml
- filename: meditech-observation-api-openapi.yml
  format: yaml
  label: meditech Observation API
  slug: meditech-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-observation-api-openapi.yml
- filename: meditech-patient-api-openapi.yml
  format: yaml
  label: meditech Patient API
  slug: meditech-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-patient-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: First and last name
  - category: contact
    text: Physical address
  - category: contact
    text: Email address
  - category: device
    text: IP address
  - category: location
    text: Geolocation data
  - category: professional
    text: Professional or employment-related information
  - category: demographic
    text: Demographic data
  - category: other
    text: Education Information
  - category: device
    text: Browser type and version
  - category: behavioral
    text: Patterns of searching and browsing on the MEDITECH Website
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Improve functionality and usage of services
    text: to improve the functionality and usage of the MEDITECH Services
  - purpose: Marketing and promotion
    text: to facilitate MEDITECH’s own marketing, promotional, and informational purposes
  - purpose: Track feature popularity
    text: to track the popularity of features of the MEDITECH Services and to guide the development of new ones
  - purpose: Evaluate job candidates
    text: to evaluate your candidacy for a position
  - purpose: Legal and contractual obligations
    text: to meet certain legal, regulatory, or contractual obligations
  rights:
  - right: Access
    text: Access Correct Portability Delete
  - right: Correct
    text: Correct
  - right: Portability
    text: Portability
  - right: Delete
    text: Delete
  - right: Opt out of certain processing including automated decision making
    text: Opt out of certain processing including automated decision making
  - right: Opt out of sales
    text: Opt out of sales
  - right: Opt in for sensitive data processing
    text: Opt in for sensitive data processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: MEDITECH will never sell, trade, or rent your personal identification information to others.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MEDITECH
provenance_date: '2026-11-10'
provider_name: MEDITECH
provider_slug: meditech
slug: meditech-privacy-policy
source_date: '2026-11-10'
source_filename: meditech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ehr.meditech.com/meditechs-privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MEDITECH\naid: meditech\nurl: https://ehr.meditech.com/meditechs-privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: First and last name\n- category: contact\n  text: Physical address\n- category: contact\n  text: Email address\n- category: device\n  text: IP address\n- category: location\n  text: Geolocation data\n- category: professional\n  text: Professional or employment-related information\n- category: demographic\n  text: Demographic data\n- category: other\n  text: Education Information\n- category: device\n  text: Browser\
  \ type and version\n- category: behavioral\n  text: Patterns of searching and browsing on the MEDITECH Website\npurposes:\n- purpose: Improve functionality and usage of services\n  text: to improve the functionality and usage of the MEDITECH Services\n- purpose: Marketing and promotion\n  text: to facilitate MEDITECH’s own marketing, promotional, and informational purposes\n- purpose: Track feature popularity\n  text: to track the popularity of features of the MEDITECH Services and to guide the development of new ones\n- purpose: Evaluate job candidates\n  text: to evaluate your candidacy for a position\n- purpose: Legal and contractual obligations\n  text: to meet certain legal, regulatory, or contractual obligations\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Access Correct Portability Delete\n- right: Correct\n  text:\
  \ Correct\n- right: Portability\n  text: Portability\n- right: Delete\n  text: Delete\n- right: Opt out of certain processing including automated decision making\n  text: Opt out of certain processing including automated decision making\n- right: Opt out of sales\n  text: Opt out of sales\n- right: Opt in for sensitive data processing\n  text: Opt in for sensitive data processing\nsale_or_sharing:\n  stance: prohibited\n  text: MEDITECH will never sell, trade, or rent your personal identification information to others.\n"
source_yaml_url: https://artifacts.apis.io/meditech/privacy/meditech-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from MEDITECH's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Electronic Health Records
- Healthcare
- FHIR
- HL7
- Interoperability
---
