---
api_specs:
- filename: schema
  format: yaml
  label: Jamf Pro API
  slug: jamf-pro-api
  spec_type: OpenAPI
  url: https://your-instance.jamfcloud.com/api/schema
claim_count: 8
description: ''
doc:
  deletion:
    route: DSAR request
    text: Request that Jamf deletes the information we have about you.
  dpa:
    available: true
    text: Data Processing Agreements serve to provide guarantees that adequate technical and organizational measures are in place to protect the transfer of personal data obtained from citizens within the European Union to the United States.
    url: null
  residency:
  - region: cloud hosting
    text: While Jamf Cloud is hosted in multiple regions, availability of specific products may vary by region.
  rights:
  - right: access
    text: Request access to information that Jamf has about you.
  - right: correction
    text: Correct any information that Jamf has about you.
  - right: deletion
    text: Request that Jamf deletes the information we have about you.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Jamf may engage vendors to provide Product Offerings to our customers on our behalf.
    url: null
  transfers:
  - mechanism: other
    text: Jamf also has data transfer mechanisms in place with each one, as set out in our DPA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: JAMF
provenance_date: '2026-11-09'
provider_name: JAMF
provider_slug: jamf
slug: jamf-privacy-policy
source_date: '2026-11-09'
source_filename: jamf-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.jamf.com/trust-center/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: JAMF\naid: jamf\nurl: https://www.jamf.com/trust-center/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories: []\npurposes: []\nretention: []\nresidency:\n- region: cloud hosting\n  text: While Jamf Cloud is hosted in multiple regions, availability of specific products may vary by region.\ntransfers:\n- mechanism: other\n  text: Jamf also has data transfer mechanisms in place with each one, as set out in our DPA.\nsubprocessors:\n  url: null\n  text: Jamf may engage vendors to provide Product Offerings to our customers on our behalf.\ndpa:\n  available: true\n  url:\
  \ null\n  text: Data Processing Agreements serve to provide guarantees that adequate technical and organizational measures\n    are in place to protect the transfer of personal data obtained from citizens within the European Union to the\n    United States.\ndeletion:\n  route: DSAR request\n  text: Request that Jamf deletes the information we have about you.\nrights:\n- right: access\n  text: Request access to information that Jamf has about you.\n- right: correction\n  text: Correct any information that Jamf has about you.\n- right: deletion\n  text: Request that Jamf deletes the information we have about you.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jamf/privacy/jamf-privacy-policy.yml
stated_fields:
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 8 quoted statements, read from JAMF's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Apple Device Management
- MDM
- Endpoint Security
- Mobile Device Management
- IT Operations
- Identity
- Compliance
- Developer Tools
- Enterprise
---
