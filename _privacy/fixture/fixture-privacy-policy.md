---
api_specs:
- filename: fixture-accounts-api-openapi.yml
  format: yaml
  label: Fixture Accounts API
  slug: fixture-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-accounts-api-openapi.yml
- filename: fixture-activities-api-openapi.yml
  format: yaml
  label: Fixture Activities API
  slug: fixture-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-activities-api-openapi.yml
- filename: fixture-contacts-api-openapi.yml
  format: yaml
  label: Fixture Contacts API
  slug: fixture-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-contacts-api-openapi.yml
- filename: fixture-deals-api-openapi.yml
  format: yaml
  label: Fixture Deals API
  slug: fixture-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-deals-api-openapi.yml
- filename: fixture-fixture-api-api-openapi.yml
  format: yaml
  label: Fixture API
  slug: fixture-fixture-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-fixture-api-api-openapi.yml
- filename: fixture-leads-api-openapi.yml
  format: yaml
  label: Fixture Leads API
  slug: fixture-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-leads-api-openapi.yml
- filename: fixture-notes-api-openapi.yml
  format: yaml
  label: Fixture Notes API
  slug: fixture-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-notes-api-openapi.yml
- filename: fixture-pipelines-api-openapi.yml
  format: yaml
  label: Fixture Pipelines API
  slug: fixture-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-pipelines-api-openapi.yml
- filename: fixture-task-statuses-api-openapi.yml
  format: yaml
  label: Fixture Task Statuses API
  slug: fixture-task-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-task-statuses-api-openapi.yml
- filename: fixture-tasks-api-openapi.yml
  format: yaml
  label: Fixture Tasks API
  slug: fixture-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-tasks-api-openapi.yml
- filename: fixture-users-api-openapi.yml
  format: yaml
  label: Fixture Users API
  slug: fixture-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-users-api-openapi.yml
- filename: fixture-custom-fields-api-openapi.yml
  format: yaml
  label: Fixture Custom Fields API
  slug: fixture-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-custom-fields-api-openapi.yml
- filename: fixture-lead-lists-api-openapi.yml
  format: yaml
  label: Fixture Lead Lists API
  slug: fixture-lead-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-lead-lists-api-openapi.yml
- filename: fixture-reporting-api-openapi.yml
  format: yaml
  label: Fixture Reporting API
  slug: fixture-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixture/openapi/fixture-reporting-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and workspace information (for example, name, email, profile details, workspace membership)
  - category: contact
    text: Research and enrichment data (for example, names, job titles, employers, professional profiles, locations, email addresses, phone numbers, source references, and provider-supplied do-not-call indicators)
  - category: behavioral
    text: Website and form data processed for Customers (for example, visitor identifiers, page/form interaction data, submission metadata)
  - category: device
    text: Cookie and similar technology data (for example, session identifiers, persistent visitor identifiers, referrer information, geolocation, and related attribution or identity-resolution data)
  - category: communication
    text: CRM data that Customers choose to store (for example, people, companies, leads, deals, notes, and activity data)
  deletion:
    route: Email privacy@fixture.app to submit a privacy request for access, correction, deletion, or other rights
    text: To submit a privacy request, email privacy@fixture.app .
  dpa:
    available: true
    text: A detailed subprocessor list and Data Processing Agreement (DPA) are available upon request.
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Provide and operate the Services
  - purpose: Visitor identification and marketing
    text: Support visitor identification, attribution, audience enrichment, marketing measurement, and related outreach workflows
  - purpose: Provide and improve AI assistant features
    text: Provide and improve AI assistant features
  residency:
  - region: United States
    text: Fixture is based in the United States. Data may be processed in the U.S. and other countries where we or our service providers operate.
  retention:
  - period: null
    scope: Customer CRM/tracking/forms data
    text: Customer CRM/tracking/forms data is retained until deleted by the Customer or required to be retained by law
  - period: null
    scope: Account/workspace data
    text: Account/workspace data is retained while the account is active, plus a reasonable period for legal and operational needs
  rights:
  - right: access
    text: Depending on where you live, you may have rights such as access, correction, deletion, portability, restriction, objection, withdrawal of consent, and opting out of certain sales, sharing, or targeted advertising.
  - right: opt out of sale, sharing, or targeted advertising
    text: opting out of certain sales, sharing, or targeted advertising
  role:
    text: When Customers use Fixture to manage their CRM data, we generally act as a processor/service provider and the Customer acts as the controller/business .
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for monetary consideration.
  subprocessors:
    text: A detailed subprocessor list and Data Processing Agreement (DPA) are available upon request.
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use appropriate safeguards for international data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fixture
provenance_date: '2026-11-09'
provider_name: Fixture
provider_slug: fixture
slug: fixture-privacy-policy
source_date: '2026-11-09'
source_filename: fixture-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fixture.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fixture\naid: fixture\nurl: https://www.fixture.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When Customers use Fixture to manage their CRM data, we generally act as a processor/service provider and\n    the Customer acts as the controller/business .\ndata_categories:\n- category: identifying\n  text: Account and workspace information (for example, name, email, profile details, workspace membership)\n- category: contact\n  text: Research and enrichment data (for example, names, job titles, employers, professional profiles, locations,\n    email addresses, phone numbers, source references,\
  \ and provider-supplied do-not-call indicators)\n- category: behavioral\n  text: Website and form data processed for Customers (for example, visitor identifiers, page/form interaction data,\n    submission metadata)\n- category: device\n  text: Cookie and similar technology data (for example, session identifiers, persistent visitor identifiers, referrer\n    information, geolocation, and related attribution or identity-resolution data)\n- category: communication\n  text: CRM data that Customers choose to store (for example, people, companies, leads, deals, notes, and activity\n    data)\npurposes:\n- purpose: Provide and operate the Services\n  text: Provide and operate the Services\n- purpose: Visitor identification and marketing\n  text: Support visitor identification, attribution, audience enrichment, marketing measurement, and related outreach\n    workflows\n- purpose: Provide and improve AI assistant features\n  text: Provide and improve AI assistant features\nretention:\n- scope:\
  \ Customer CRM/tracking/forms data\n  period: null\n  text: Customer CRM/tracking/forms data is retained until deleted by the Customer or required to be retained by\n    law\n- scope: Account/workspace data\n  period: null\n  text: Account/workspace data is retained while the account is active, plus a reasonable period for legal and operational\n    needs\nresidency:\n- region: United States\n  text: Fixture is based in the United States. Data may be processed in the U.S. and other countries where we or\n    our service providers operate.\ntransfers:\n- mechanism: other\n  text: Where required, we use appropriate safeguards for international data transfers.\nsubprocessors:\n  url: null\n  text: A detailed subprocessor list and Data Processing Agreement (DPA) are available upon request.\ndpa:\n  available: true\n  url: null\n  text: A detailed subprocessor list and Data Processing Agreement (DPA) are available upon request.\ndeletion:\n  route: Email privacy@fixture.app to submit a privacy\
  \ request for access, correction, deletion, or other rights\n  text: To submit a privacy request, email privacy@fixture.app .\nrights:\n- right: access\n  text: Depending on where you live, you may have rights such as access, correction, deletion, portability, restriction,\n    objection, withdrawal of consent, and opting out of certain sales, sharing, or targeted advertising.\n- right: opt out of sale, sharing, or targeted advertising\n  text: opting out of certain sales, sharing, or targeted advertising\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/fixture/privacy/fixture-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Fixture's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Sales
- B2B
- Artificial Intelligence
- Agents
- MCP
---
