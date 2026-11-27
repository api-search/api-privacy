---
api_specs:
- filename: bankcodelookup-com-dataset-api-openapi.yml
  format: yaml
  label: Bank Code Lookup Dataset API
  slug: bankcodelookup-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankcodelookup-com/openapi/bankcodelookup-com-dataset-api-openapi.yml
- filename: bankcodelookup-com-enquiry-api-openapi.yml
  format: yaml
  label: Bank Code Lookup Enquiry API
  slug: bankcodelookup-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankcodelookup-com/openapi/bankcodelookup-com-enquiry-api-openapi.yml
- filename: bankcodelookup-com-mcp-api-openapi.yml
  format: yaml
  label: Bank Code Lookup MCP API
  slug: bankcodelookup-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankcodelookup-com/openapi/bankcodelookup-com-mcp-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name and email
  - category: contact
    text: we store your email address
  - category: communication
    text: the code or bank, what you are trying to check, your name and email
  - category: device
    text: We stamp the submission with a truncated IP and the version of the consent notice you saw.
  deletion:
    route: email request to contact@bankcodelookup.com
    text: 'or ask for deletion at any time: contact@bankcodelookup.com'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer enquiries
    text: We email you the answer and share your details with nobody.
  - purpose: email updates
    text: We email you only about what that sentence names.
  - purpose: aggregate analytics
    text: This site uses cookieless, aggregate analytics.
  retention:
  - period: 24 months
    scope: enquiry records
    text: Enquiry records are kept for 24 months from when they are sent, then deleted
  - period: 30 days
    scope: unconfirmed sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: indefinitely
    scope: aggregate statistics
    text: Aggregate statistics that identify nobody are kept indefinitely.
  rights:
  - right: access
    text: You can ask what we hold about you
  - right: copy
    text: ask for a copy
  - right: deletion
    text: ask for deletion at any time
  - right: complaint
    text: You can complain to the Office of the Information and Data Protection Commissioner (idpc.org.mt)
  role:
    text: The controller of the personal data on this site is Joseph Ellul
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We email you the answer and share your details with nobody.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bank Code Lookup
provenance_date: '2026-11-09'
provider_name: Bank Code Lookup
provider_slug: bankcodelookup-com
slug: bankcodelookup-com-privacy-policy
source_date: '2026-11-09'
source_filename: bankcodelookup-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bankcodelookup.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bank Code Lookup\naid: bankcodelookup-com\nurl: https://bankcodelookup.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Joseph Ellul\ndata_categories:\n- category: identifying\n  text: your name and email\n- category: contact\n  text: we store your email address\n- category: communication\n  text: the code or bank, what you are trying to check, your name and email\n- category: device\n  text: We stamp the submission with a truncated IP and the version of the consent notice you saw.\npurposes:\n- purpose: answer enquiries\n  text:\
  \ We email you the answer and share your details with nobody.\n- purpose: email updates\n  text: We email you only about what that sentence names.\n- purpose: aggregate analytics\n  text: This site uses cookieless, aggregate analytics.\nretention:\n- scope: enquiry records\n  period: 24 months\n  text: Enquiry records are kept for 24 months from when they are sent, then deleted\n- scope: unconfirmed sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: aggregate statistics\n  period: indefinitely\n  text: Aggregate statistics that identify nobody are kept indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to contact@bankcodelookup.com\n  text: 'or ask for deletion at any time: contact@bankcodelookup.com'\nrights:\n- right: access\n  text: You can ask what we hold about you\n- right: copy\n  text: ask for a copy\n- right:\
  \ deletion\n  text: ask for deletion at any time\n- right: complaint\n  text: You can complain to the Office of the Information and Data Protection Commissioner (idpc.org.mt)\nsale_or_sharing:\n  stance: unstated\n  text: We email you the answer and share your details with nobody.\n"
source_yaml_url: https://artifacts.apis.io/bankcodelookup-com/privacy/bankcodelookup-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from Bank Code Lookup's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Finance
- Lookup
- Codes
---
