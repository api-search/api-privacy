---
api_specs:
- filename: neo4j-query-api-openapi.yml
  format: yaml
  label: Neo4j Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-query-api-openapi.yml
- filename: neo4j-authentication-api-openapi.yml
  format: yaml
  label: Neo4j Authentication API
  slug: neo4j-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-authentication-api-openapi.yml
- filename: neo4j-discovery-api-openapi.yml
  format: yaml
  label: Neo4j Discovery API
  slug: neo4j-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-discovery-api-openapi.yml
- filename: neo4j-instances-api-openapi.yml
  format: yaml
  label: Neo4j Instances API
  slug: neo4j-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-instances-api-openapi.yml
- filename: neo4j-snapshots-api-openapi.yml
  format: yaml
  label: Neo4j Snapshots API
  slug: neo4j-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-snapshots-api-openapi.yml
- filename: neo4j-tenants-api-openapi.yml
  format: yaml
  label: Neo4j Tenants API
  slug: neo4j-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-tenants-api-openapi.yml
- filename: neo4j-transactions-api-openapi.yml
  format: yaml
  label: Neo4j Transactions API
  slug: neo4j-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-transactions-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone number, and mailing address.
  - category: contact
    text: Name, email address, phone number, and mailing address.
  - category: financial
    text: Billing and payment information, and records of services purchased.
  - category: device
    text: IP address, unique device identifiers, and device attributes, such as operating system and browser type.
  - category: behavioral
    text: Site and navigation history.
  - category: communication
    text: Support queries, talk proposals, feedback surveys, and community forum posts.
  deletion:
    route: https://preferences.neo4j.com/privacy
    text: If you would like to exercise any of these rights, you can visit https://preferences.neo4j.com/privacy .
  dpa:
    available: true
    text: if you want to obtain a copy of the Data Processing Agreement between our European entities and our United States entity
    url: null
  purposes:
  - purpose: Account and security
    text: Create and secure your account, verify your identity, and send product updates.
  - purpose: Product improvement
    text: analyze, develop, and improve performance and Offerings.
  - purpose: Marketing
    text: Deliver relevant content and measure our promotional reach.
  residency:
  - region: United States
    text: processing of that information by Neo4j on servers located in the United States of America
  retention:
  - period: null
    scope: Personal Data
    text: We keep your Personal Data only as long as necessary for the purpose for which it was collected or to meet legal obligations.
  rights:
  - right: Access
    text: Access your Personal Data.
  - right: Deletion
    text: Have Personal Data concerning you deleted.
  - right: Correction
    text: Require correction of incorrect data about you.
  - right: Objection
    text: Object to our processing of your Personal Data.
  - right: Restriction
    text: Restrict the processing of data concerning you.
  - right: Portability
    text: In certain cases, you may also have a right to data portability.
  role:
    text: Neo4j processes such data solely on behalf of the customer (the data controller)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Neo4j does not sell your Personal Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Neo4j, Inc. complies with the EU-U.S. Data Privacy Framework (“ EU-U.S. DPF ”), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Neo4j
provenance_date: '2026-11-10'
provider_name: Neo4j
provider_slug: neo4j
slug: neo4j-privacy-policy
source_date: '2026-11-10'
source_filename: neo4j-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://neo4j.com/legal-terms/privacy-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Neo4j\naid: neo4j\nurl: https://neo4j.com/legal-terms/privacy-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Neo4j processes such data solely on behalf of the customer (the data controller)\ndata_categories:\n- category: identifying\n  text: Name, email address, phone number, and mailing address.\n- category: contact\n  text: Name, email address, phone number, and mailing address.\n- category: financial\n  text: Billing and payment information, and records of services purchased.\n- category: device\n  text: IP address, unique device identifiers, and device attributes, such as operating\
  \ system and browser type.\n- category: behavioral\n  text: Site and navigation history.\n- category: communication\n  text: Support queries, talk proposals, feedback surveys, and community forum posts.\npurposes:\n- purpose: Account and security\n  text: Create and secure your account, verify your identity, and send product updates.\n- purpose: Product improvement\n  text: analyze, develop, and improve performance and Offerings.\n- purpose: Marketing\n  text: Deliver relevant content and measure our promotional reach.\nretention:\n- scope: Personal Data\n  period: null\n  text: We keep your Personal Data only as long as necessary for the purpose for which it was collected or to meet\n    legal obligations.\nresidency:\n- region: United States\n  text: processing of that information by Neo4j on servers located in the United States of America\ntransfers:\n- mechanism: DPF\n  text: Neo4j, Inc. complies with the EU-U.S. Data Privacy Framework (“ EU-U.S. DPF ”), the UK Extension to the\n \
  \   EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: if you want to obtain a copy of the Data Processing Agreement between our European entities and our United\n    States entity\ndeletion:\n  route: https://preferences.neo4j.com/privacy\n  text: If you would like to exercise any of these rights, you can visit https://preferences.neo4j.com/privacy .\nrights:\n- right: Access\n  text: Access your Personal Data.\n- right: Deletion\n  text: Have Personal Data concerning you deleted.\n- right: Correction\n  text: Require correction of incorrect data about you.\n- right: Objection\n  text: Object to our processing of your Personal Data.\n- right: Restriction\n  text: Restrict the processing of data concerning you.\n- right: Portability\n  text: In certain cases, you may also have a right to data portability.\nsale_or_sharing:\n  stance: prohibited\n  text: Neo4j does not sell your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/neo4j/privacy/neo4j-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Neo4j's own page on 2026-11-10.
synthetic: false
tags:
- Neo4j
- Graph Database
- Cypher
- Cloud
- GraphQL
- Drivers
- Database
---
