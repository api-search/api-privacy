---
api_specs:
- filename: biobricks-org-dataset-api-openapi.yml
  format: yaml
  label: biobricks-org Dataset API
  slug: biobricks-org-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biobricks-org/openapi/biobricks-org-dataset-api-openapi.yml
- filename: biobricks-org-enquiry-api-openapi.yml
  format: yaml
  label: biobricks-org Enquiry API
  slug: biobricks-org-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biobricks-org/openapi/biobricks-org-enquiry-api-openapi.yml
- filename: biobricks-org-mcp-api-openapi.yml
  format: yaml
  label: biobricks-org MCP API
  slug: biobricks-org-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biobricks-org/openapi/biobricks-org-mcp-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: 'The shortlist form collects what you type: what you are having made, your institution or company, your project notes, your name and email.'
  - category: behavioral
    text: Cookieless aggregate analytics record how pages are used, with no personal identifier.
  deletion:
    route: email request to enquiries@biobricks.org
    text: 'You can ask what we hold about you, ask for a copy, or ask for deletion at any time: enquiries@biobricks.org.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: build and send vendor shortlist
    text: It exists to build and send your vendor shortlist.
  - purpose: pass enquiries to gene synthesis firms
    text: BioBricks passes your contact details to at most three gene synthesis and research supply firms, chosen by us.
  retention:
  - period: 24 months
    scope: enquiry records
    text: Enquiry records are kept for 24 months from when they are sent, then deleted
  - period: indefinitely
    scope: aggregate statistics
    text: Aggregate statistics that identify nobody are kept indefinitely.
  rights:
  - right: access
    text: You can ask what we hold about you, ask for a copy
  - right: erasure
    text: or ask for deletion at any time
  - right: complain to supervisory authority
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell data, run third-party advertising, or load third-party scripts on this site.
  subprocessors:
    text: We use service providers to host and store this site and its data, to route email, and to help us read and answer enquiries, including AI tools.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: biobricks-org
provenance_date: '2026-11-09'
provider_name: biobricks-org
provider_slug: biobricks-org
slug: biobricks-org-privacy-policy
source_date: '2026-11-09'
source_filename: biobricks-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://biobricks.org/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: biobricks-org\naid: biobricks-org\nurl: https://biobricks.org/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House)\ndata_categories:\n- category: contact\n  text: 'The shortlist form collects what you type: what you are having made, your institution or company, your\n    project notes, your name and email.'\n- category: behavioral\n  text: Cookieless aggregate analytics record how pages are used, with no personal identifier.\npurposes:\n- purpose:\
  \ build and send vendor shortlist\n  text: It exists to build and send your vendor shortlist.\n- purpose: pass enquiries to gene synthesis firms\n  text: BioBricks passes your contact details to at most three gene synthesis and research supply firms, chosen\n    by us.\nretention:\n- scope: enquiry records\n  period: 24 months\n  text: Enquiry records are kept for 24 months from when they are sent, then deleted\n- scope: aggregate statistics\n  period: indefinitely\n  text: Aggregate statistics that identify nobody are kept indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use service providers to host and store this site and its data, to route email, and to help us read and\n    answer enquiries, including AI tools.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to enquiries@biobricks.org\n  text: 'You can ask what we hold about you, ask for a copy, or ask for deletion at any time: enquiries@biobricks.org.'\nrights:\n\
  - right: access\n  text: You can ask what we hold about you, ask for a copy\n- right: erasure\n  text: or ask for deletion at any time\n- right: complain to supervisory authority\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell data, run third-party advertising, or load third-party scripts on this site.\n"
source_yaml_url: https://artifacts.apis.io/biobricks-org/privacy/biobricks-org-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from biobricks-org's own page on 2026-11-09.
synthetic: false
tags:
- Bioinformatics
- Gene Synthesis
- Pricing
- Laboratory Equipment
- Open Data
---
