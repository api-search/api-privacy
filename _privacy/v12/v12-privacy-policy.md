---
api_specs:
- filename: v12-documents-api-openapi.yml
  format: yaml
  label: V12 Documents API
  slug: v12-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-documents-api-openapi.yml
- filename: v12-findings-api-openapi.yml
  format: yaml
  label: V12 Findings API
  slug: v12-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-findings-api-openapi.yml
- filename: v12-me-api-openapi.yml
  format: yaml
  label: V12 Me API
  slug: v12-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-me-api-openapi.yml
- filename: v12-members-api-openapi.yml
  format: yaml
  label: V12 Members API
  slug: v12-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-members-api-openapi.yml
- filename: v12-repositories-api-openapi.yml
  format: yaml
  label: V12 Repositories API
  slug: v12-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-repositories-api-openapi.yml
- filename: v12-runs-api-openapi.yml
  format: yaml
  label: V12 Runs API
  slug: v12-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-runs-api-openapi.yml
- filename: v12-steers-api-openapi.yml
  format: yaml
  label: V12 Steers API
  slug: v12-steers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/v12/openapi/v12-steers-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect names, business contact details, employer or organization, job title, account credentials
  - category: behavioral
    text: We collect Usage Data automatically when someone visits our website or uses the Service.
  - category: communication
    text: We collect information sent through support requests, sales conversations, surveys, feedback, incident reports
  - category: other
    text: We collect the Customer Materials that a Customer submits or connects, the Results the Service produces
  deletion:
    route: Valid deletion request or account closure
    text: After account closure, termination, or a valid deletion request, we delete them from active production systems within 30 days
  dpa:
    available: true
    text: A Data Processing Addendum with applicable transfer terms is available on request.
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: We use information to create and administer accounts; authenticate users; connect repositories and other tools
  - purpose: Secure, support, and monitor
    text: We use information to protect accounts and systems
  - purpose: Product improvement and training
    text: V12 may, without further permission, use Usage Data and Derived Data that meets the definition and safeguards in Sections 2 and 5.3 to develop, improve, and commercialize current and future V12 products, services, and models.
  - purpose: Communications and business management
    text: We use information to send service, security, billing, legal, support, and administrative messages
  residency:
  - region: United States and other countries
    text: V12 and our service providers may process information in the United States and other countries where we or they operate.
  retention:
  - period: 30 days
    scope: Raw Customer Materials and Results
    text: we delete them from active production systems within 30 days after the applicable export period ends or, if none applies, within 30 days after account closure, termination, or the request.
  - period: 90 days
    scope: Backup copies
    text: Backup copies are deleted or overwritten through ordinary backup cycles within 90 days after deletion from active systems.
  - period: indefinitely
    scope: Derived Data and trained state
    text: We may retain Derived Data and generalized datasets, evaluations, benchmarks, model weights, model state, detectors, rules, and other improvements indefinitely.
  rights:
  - right: access, correction, deletion, copy
    text: Depending on where a person lives, that person may have the right to request access to, correction of, deletion of, or a copy of personal information
  - right: object or restrict processing
    text: object to or restrict certain processing; withdraw consent; or complain to a privacy regulator
  - right: non-discrimination
    text: We will not discriminate against a person for exercising a privacy right.
  role:
    text: V12 acts as a controller when we decide why and how to process information for our own business
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioral advertising or targeted advertising
  subprocessors:
    text: Current information about material subprocessors is available in our documentation or on request.
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use contractual or other safeguards for international transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: V12
provenance_date: '2026-11-10'
provider_name: V12
provider_slug: v12
slug: v12-privacy-policy
source_date: '2026-11-10'
source_filename: v12-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://v12.sh/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: V12\naid: v12\nurl: https://v12.sh/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: V12 acts as a controller when we decide why and how to process information for our own business\ndata_categories:\n- category: identifying\n  text: We collect names, business contact details, employer or organization, job title, account credentials\n- category: behavioral\n  text: We collect Usage Data automatically when someone visits our website or uses the Service.\n- category: communication\n  text: We collect information sent through support requests, sales conversations, surveys, feedback, incident\
  \ reports\n- category: other\n  text: We collect the Customer Materials that a Customer submits or connects, the Results the Service produces\npurposes:\n- purpose: Provide and operate the Service\n  text: We use information to create and administer accounts; authenticate users; connect repositories and other\n    tools\n- purpose: Secure, support, and monitor\n  text: We use information to protect accounts and systems\n- purpose: Product improvement and training\n  text: V12 may, without further permission, use Usage Data and Derived Data that meets the definition and safeguards\n    in Sections 2 and 5.3 to develop, improve, and commercialize current and future V12 products, services, and\n    models.\n- purpose: Communications and business management\n  text: We use information to send service, security, billing, legal, support, and administrative messages\nretention:\n- scope: Raw Customer Materials and Results\n  period: 30 days\n  text: we delete them from active production systems\
  \ within 30 days after the applicable export period ends or,\n    if none applies, within 30 days after account closure, termination, or the request.\n- scope: Backup copies\n  period: 90 days\n  text: Backup copies are deleted or overwritten through ordinary backup cycles within 90 days after deletion from\n    active systems.\n- scope: Derived Data and trained state\n  period: indefinitely\n  text: We may retain Derived Data and generalized datasets, evaluations, benchmarks, model weights, model state,\n    detectors, rules, and other improvements indefinitely.\nresidency:\n- region: United States and other countries\n  text: V12 and our service providers may process information in the United States and other countries where we\n    or they operate.\ntransfers:\n- mechanism: other\n  text: Where required, we use contractual or other safeguards for international transfers.\nsubprocessors:\n  url: null\n  text: Current information about material subprocessors is available in our documentation\
  \ or on request.\ndpa:\n  available: true\n  url: null\n  text: A Data Processing Addendum with applicable transfer terms is available on request.\ndeletion:\n  route: Valid deletion request or account closure\n  text: After account closure, termination, or a valid deletion request, we delete them from active production systems\n    within 30 days\nrights:\n- right: access, correction, deletion, copy\n  text: Depending on where a person lives, that person may have the right to request access to, correction of, deletion\n    of, or a copy of personal information\n- right: object or restrict processing\n  text: object to or restrict certain processing; withdraw consent; or complain to a privacy regulator\n- right: non-discrimination\n  text: We will not discriminate against a person for exercising a privacy right.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for cross-context behavioral advertising or targeted advertising\n"
source_yaml_url: https://artifacts.apis.io/v12/privacy/v12-privacy-policy.yml
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
- sale_or_sharing
summary_line: 21 quoted statements, read from V12's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- DevOps
- Automation
- Code Analysis
---
