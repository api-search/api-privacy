---
api_specs:
- filename: artie-column-hashing-salts-api-openapi.yml
  format: yaml
  label: Artie Column Hashing Salts API
  slug: artie-column-hashing-salts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-column-hashing-salts-api-openapi.yml
- filename: artie-connectors-api-openapi.yml
  format: yaml
  label: Artie Connectors API
  slug: artie-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-connectors-api-openapi.yml
- filename: artie-data-catalog-api-openapi.yml
  format: yaml
  label: Artie Data Catalog API
  slug: artie-data-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-data-catalog-api-openapi.yml
- filename: artie-encryption-keys-api-openapi.yml
  format: yaml
  label: Artie Encryption Keys API
  slug: artie-encryption-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-encryption-keys-api-openapi.yml
- filename: artie-ingestion-api-keys-api-openapi.yml
  format: yaml
  label: Artie Ingestion API Keys API
  slug: artie-ingestion-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-ingestion-api-keys-api-openapi.yml
- filename: artie-pipelines-api-openapi.yml
  format: yaml
  label: Artie Pipelines API
  slug: artie-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-pipelines-api-openapi.yml
- filename: artie-privatelink-connections-api-openapi.yml
  format: yaml
  label: Artie PrivateLink Connections API
  slug: artie-privatelink-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-privatelink-connections-api-openapi.yml
- filename: artie-source-readers-api-openapi.yml
  format: yaml
  label: Artie Source Readers API
  slug: artie-source-readers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-source-readers-api-openapi.yml
- filename: artie-ssh-tunnels-api-openapi.yml
  format: yaml
  label: Artie SSH Tunnels API
  slug: artie-ssh-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-ssh-tunnels-api-openapi.yml
- filename: artie-artie-api-api-openapi.yml
  format: yaml
  label: Artie API
  slug: artie-artie-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-artie-api-api-openapi.yml
- filename: artie-company-api-openapi.yml
  format: yaml
  label: Artie Company API
  slug: artie-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-company-api-openapi.yml
- filename: artie-kafka-clusters-api-openapi.yml
  format: yaml
  label: Artie Kafka Clusters API
  slug: artie-kafka-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-kafka-clusters-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: we may ask for your email and name in order to register and log in to our dashboard
  - category: device
    text: Information that we collect may include your IP address, device type, unique device identification numbers, browser type, and general geographic location.
  - category: behavioral
    text: We may also collect information regarding how you have interacted with our Websites.
  deletion:
    route: Email request with subject line Privacy Rights Request
    text: To exercise any of the rights described above, please contact us at [email protected] with the subject line “Privacy Rights Request.”
  dpa:
    available: true
    text: Our DPA is available at https://www.artie.com/docs/legal/data-processing-addendum
    url: https://www.artie.com/docs/legal/data-processing-addendum
  purposes:
  - purpose: Providing and improving services
    text: Providing, operating, and improving the Artie Services and Websites
  - purpose: Security and fraud
    text: Detecting, preventing, and addressing security threats, fraud, or illegal activity
  - purpose: Marketing
    text: Sending newsletters, product updates, and marketing communications (you may opt out at any time)
  retention:
  - period: sixty (60) days
    scope: Customer Data after termination
    text: Upon termination or expiration of your services agreement, we will delete Customer Data within sixty (60) days, unless we are required by law to retain it longer.
  - period: null
    scope: Account information
    text: Account information is retained for the duration of your account and for a reasonable period afterward to comply with legal obligations, resolve disputes, and enforce our agreements.
  - period: indefinitely
    scope: Aggregated and de-identified data
    text: Aggregated and de-identified data, which cannot be used to identify you, may be retained indefinitely.
  rights:
  - right: Right to Know
    text: You may request that we disclose the categories and specific pieces of personal information we have collected about you
  - right: Right to Delete
    text: You may request that we delete personal information we have collected about you, subject to certain exceptions
  - right: Right to Correct
    text: You may request that we correct inaccurate personal information we hold about you.
  - right: Right to Non-Discrimination
    text: We will not discriminate against you for exercising any of your privacy rights.
  role:
    text: Artie acts as a data processor (or “service provider” under the CCPA)
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Enterprise customers may request our current sub-processor list by contacting [email protected] .
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Artie
provenance_date: '2026-11-09'
provider_name: Artie
provider_slug: artie
slug: artie-privacy-policy
source_date: '2026-11-09'
source_filename: artie-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.artie.com/docs/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Artie\naid: artie\nurl: https://www.artie.com/docs/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Artie acts as a data processor (or “service provider” under the CCPA)\ndata_categories:\n- category: contact\n  text: we may ask for your email and name in order to register and log in to our dashboard\n- category: device\n  text: Information that we collect may include your IP address, device type, unique device identification numbers,\n    browser type, and general geographic location.\n- category: behavioral\n  text: We may also collect information regarding how you have\
  \ interacted with our Websites.\npurposes:\n- purpose: Providing and improving services\n  text: Providing, operating, and improving the Artie Services and Websites\n- purpose: Security and fraud\n  text: Detecting, preventing, and addressing security threats, fraud, or illegal activity\n- purpose: Marketing\n  text: Sending newsletters, product updates, and marketing communications (you may opt out at any time)\nretention:\n- scope: Customer Data after termination\n  period: sixty (60) days\n  text: Upon termination or expiration of your services agreement, we will delete Customer Data within sixty (60)\n    days, unless we are required by law to retain it longer.\n- scope: Account information\n  period: null\n  text: Account information is retained for the duration of your account and for a reasonable period afterward to\n    comply with legal obligations, resolve disputes, and enforce our agreements.\n- scope: Aggregated and de-identified data\n  period: indefinitely\n  text: Aggregated\
  \ and de-identified data, which cannot be used to identify you, may be retained indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Enterprise customers may request our current sub-processor list by contacting [email protected] .\ndpa:\n  available: true\n  url: https://www.artie.com/docs/legal/data-processing-addendum\n  text: Our DPA is available at https://www.artie.com/docs/legal/data-processing-addendum\ndeletion:\n  route: Email request with subject line Privacy Rights Request\n  text: To exercise any of the rights described above, please contact us at [email protected] with the subject line\n    “Privacy Rights Request.”\nrights:\n- right: Right to Know\n  text: You may request that we disclose the categories and specific pieces of personal information we have collected\n    about you\n- right: Right to Delete\n  text: You may request that we delete personal information we have collected about you, subject to certain exceptions\n- right: Right to Correct\n\
  \  text: You may request that we correct inaccurate personal information we hold about you.\n- right: Right to Non-Discrimination\n  text: We will not discriminate against you for exercising any of your privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/artie/privacy/artie-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Artie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Replication
- Change Data Capture
- Data Integration
- ETL
- Streaming
- Database
- Data Warehouse
- Data Engineering
---
