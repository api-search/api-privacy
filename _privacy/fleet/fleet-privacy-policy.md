---
api_specs:
- filename: fleet-fleet-api-openapi.yml
  format: yaml
  label: Fleet API
  slug: fleet-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleet/openapi/fleet-fleet-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, username, and email address
  - category: device
    text: Device name, OS version, software installed, and system status
  - category: location
    text: Username associated with the device and approximate location
  - category: financial
    text: Payment or billing details (if applicable)
  - category: behavioral
    text: Pages viewed, referral sources, and usage analytics
  - category: communication
    text: Conversation and interaction data submitted through chat tools on our websites
  - category: professional
    text: Company or organization name, role, and contact details
  deletion:
    route: Account settings or contact Fleet
    text: Requests can be submitted through account settings or by contacting Fleet directly at fleetdm.com/contact .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Manage and secure enrolled devices
    text: Manage, monitor, and secure enrolled devices
  - purpose: Marketing and personalized content
    text: Deliver personalized content and marketing communications
  - purpose: Serve advertisements
    text: Serve relevant advertisements through third-party partners
  - purpose: Process payments
    text: Process payments and maintain billing records
  residency:
  - region: United States
    text: Our Services are hosted in the United States, and information we collect is stored and processed on our servers in the United States.
  retention:
  - period: null
    scope: Endpoint data
    text: Endpoint data is retained only as long as necessary to fulfill the purposes outlined above.
  - period: 12 months
    scope: Inactive accounts
    text: Inactive accounts and related data may be deleted after 12 months of inactivity.
  rights:
  - right: Access, correct, or delete
    text: 'Users may: Access, correct, or delete their data'
  - right: Opt out of marketing communications
    text: Opt out of marketing communications
  - right: Close account
    text: Close their accounts at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Fleet does not sell personal data and uses it only for legitimate business and operational purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Using Standard Contractual Clauses (SCCs) approved by the European Commission, or Obtaining your explicit consent for such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fleet
provenance_date: '2026-11-09'
provider_name: Fleet
provider_slug: fleet
slug: fleet-privacy-policy
source_date: '2026-11-09'
source_filename: fleet-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fleetdm.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fleet\naid: fleet\nurl: https://fleetdm.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, username, and email address\n- category: device\n  text: Device name, OS version, software installed, and system status\n- category: location\n  text: Username associated with the device and approximate location\n- category: financial\n  text: Payment or billing details (if applicable)\n- category: behavioral\n  text: Pages viewed, referral sources, and usage analytics\n- category: communication\n  text: Conversation and interaction\
  \ data submitted through chat tools on our websites\n- category: professional\n  text: Company or organization name, role, and contact details\npurposes:\n- purpose: Manage and secure enrolled devices\n  text: Manage, monitor, and secure enrolled devices\n- purpose: Marketing and personalized content\n  text: Deliver personalized content and marketing communications\n- purpose: Serve advertisements\n  text: Serve relevant advertisements through third-party partners\n- purpose: Process payments\n  text: Process payments and maintain billing records\nretention:\n- scope: Endpoint data\n  period: null\n  text: Endpoint data is retained only as long as necessary to fulfill the purposes outlined above.\n- scope: Inactive accounts\n  period: 12 months\n  text: Inactive accounts and related data may be deleted after 12 months of inactivity.\nresidency:\n- region: United States\n  text: Our Services are hosted in the United States, and information we collect is stored and processed on our\n  \
  \  servers in the United States.\ntransfers:\n- mechanism: SCC\n  text: Using Standard Contractual Clauses (SCCs) approved by the European Commission, or Obtaining your explicit\n    consent for such transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or contact Fleet\n  text: Requests can be submitted through account settings or by contacting Fleet directly at fleetdm.com/contact\n    .\nrights:\n- right: Access, correct, or delete\n  text: 'Users may: Access, correct, or delete their data'\n- right: Opt out of marketing communications\n  text: Opt out of marketing communications\n- right: Close account\n  text: Close their accounts at any time\nsale_or_sharing:\n  stance: prohibited\n  text: Fleet does not sell personal data and uses it only for legitimate business and operational purposes.\n"
source_yaml_url: https://artifacts.apis.io/fleet/privacy/fleet-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Fleet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Device Management
- MDM
- Endpoint Security
- Vulnerability Management
- osquery
- Open Source
- DevOps
---
