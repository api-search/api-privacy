---
api_specs:
- filename: metaplane-connections-api-openapi.yml
  format: yaml
  label: Metaplane Connections API
  slug: metaplane-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metaplane/openapi/metaplane-connections-api-openapi.yml
- filename: metaplane-monitors-api-openapi.yml
  format: yaml
  label: Metaplane Monitors API
  slug: metaplane-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metaplane/openapi/metaplane-monitors-api-openapi.yml
- filename: metaplane-tags-api-openapi.yml
  format: yaml
  label: Metaplane Tags API
  slug: metaplane-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metaplane/openapi/metaplane-tags-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email address, telephone number, business address, title/position, and similar contact data.
  - category: identifying
    text: Account or login information, such as username, password, account number or other unique identifier.
  - category: behavioral
    text: Authorizations and usage data, such as subscription level, deployed integrations, account activities, etc.
  - category: device
    text: information about your computer and network environment, browser type and version, and session data
  - category: communication
    text: Headers and metadata of emails and other communications (time sent, recipients, file size, etc.).
  deletion:
    route: contact privacy email
    text: Please contact us at privacy@datadoghq.com if you have any questions about this section.
  dpa:
    available: true
    text: we will provide you or your organization with our data processing addendum (the “DPA”)
    url: null
  purposes:
  - purpose: deliver the Services
    text: We use Personal Data to deliver the Services under the terms of our customer agreements
  - purpose: marketing
    text: Develop and market products and services that may be of interest to you or your organization.
  - purpose: analytics and improvement
    text: Analyze and improve our website and the Services.
  residency:
  - region: United States
    text: We are based in the United States and our data processing activities occur in the United States.
  retention:
  - period: null
    scope: general
    text: We retain your Personal Data for as long as necessary for the purpose for which we originally collected it, such as to perform the Services.
  rights:
  - right: access or update
    text: You may access or update your Personal Data or notify us that you wish to exercise your rights under applicable data protection laws
  - right: opt out of marketing advertising
    text: You may opt out of receiving this advertising by visiting https://share.hsforms.com/1ttwNpzbgT-e-lHFzSpKXCgc8f37 .
  role:
    text: we are acting on their instructions
    value: both
  sale_or_sharing:
    stance: prohibited
    text: we do not sell Personal Data (or we fall under the service provider exemption under the CCPA), and we do not share Personal Data for purposes of cross-context behavioral advertising
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Metaplane complies with the EU-U.S. Data Privacy Framework (the “EU-U.S. DPF”), the UK Extension to the EU-U.S. DPF
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Metaplane
provenance_date: '2026-11-10'
provider_name: Metaplane
provider_slug: metaplane
slug: metaplane-privacy-policy
source_date: '2026-11-10'
source_filename: metaplane-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.metaplane.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Metaplane\naid: metaplane\nurl: https://www.metaplane.dev/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we are acting on their instructions\ndata_categories:\n- category: contact\n  text: Name, email address, telephone number, business address, title/position, and similar contact data.\n- category: identifying\n  text: Account or login information, such as username, password, account number or other unique identifier.\n- category: behavioral\n  text: Authorizations and usage data, such as subscription level, deployed integrations, account activities, etc.\n- category: device\n  text:\
  \ information about your computer and network environment, browser type and version, and session data\n- category: communication\n  text: Headers and metadata of emails and other communications (time sent, recipients, file size, etc.).\npurposes:\n- purpose: deliver the Services\n  text: We use Personal Data to deliver the Services under the terms of our customer agreements\n- purpose: marketing\n  text: Develop and market products and services that may be of interest to you or your organization.\n- purpose: analytics and improvement\n  text: Analyze and improve our website and the Services.\nretention:\n- scope: general\n  period: null\n  text: We retain your Personal Data for as long as necessary for the purpose for which we originally collected\n    it, such as to perform the Services.\nresidency:\n- region: United States\n  text: We are based in the United States and our data processing activities occur in the United States.\ntransfers:\n- mechanism: DPF\n  text: Metaplane complies\
  \ with the EU-U.S. Data Privacy Framework (the “EU-U.S. DPF”), the UK Extension to the\n    EU-U.S. DPF\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: we will provide you or your organization with our data processing addendum (the “DPA”)\ndeletion:\n  route: contact privacy email\n  text: Please contact us at privacy@datadoghq.com if you have any questions about this section.\nrights:\n- right: access or update\n  text: You may access or update your Personal Data or notify us that you wish to exercise your rights under applicable\n    data protection laws\n- right: opt out of marketing advertising\n  text: You may opt out of receiving this advertising by visiting https://share.hsforms.com/1ttwNpzbgT-e-lHFzSpKXCgc8f37\n    .\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell Personal Data (or we fall under the service provider exemption under the CCPA), and we do\n    not share Personal Data for purposes of cross-context behavioral\
  \ advertising\n"
source_yaml_url: https://artifacts.apis.io/metaplane/privacy/metaplane-privacy-policy.yml
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
summary_line: 17 quoted statements, read from Metaplane's own page on 2026-11-10.
synthetic: false
tags:
- AIOps
- Data Observability
- Data Quality
- Anomaly Detection
- Data Lineage
- Monitoring
- Analytics
- Data Engineering
- dbt
- Snowflake
---
