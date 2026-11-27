---
api_specs:
- filename: bind-policies-api-openapi.yml
  format: yaml
  label: Bind Policies API
  slug: bind-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-policies-api-openapi.yml
- filename: bind-quotes-api-openapi.yml
  format: yaml
  label: Bind Quotes API
  slug: bind-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-quotes-api-openapi.yml
- filename: bind-reports-api-openapi.yml
  format: yaml
  label: Bind Reports API
  slug: bind-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bind/openapi/bind-reports-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone number (optional), biography (optional)
  - category: device
    text: Browser type, language preference, referring URL, date/time of request
  - category: device
    text: Session ID, preference cookies
  - category: other
    text: Emails, files, insurance data uploaded or generated in the Services
  deletion:
    route: Email info@bindhq.com to request early deletion of Google user data
    text: You may also request early deletion of your Google user data at any time by emailing info@bindhq.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate and improve the Services
    text: We use personal information to provide, operate, and continually improve the Services
  - purpose: Secure login and collaboration
    text: enable secure login and collaboration features
  - purpose: Legal compliance
    text: comply with legal obligations—such as insurance record-keeping requirements
  - purpose: Aggregated statistics
    text: generate aggregated, de-identified statistics for internal analysis
  residency:
  - region: United States
    text: Because Owsy is headquartered in the United States, your information may be processed in countries where we or our service providers operate
  retention:
  - period: null
    scope: Personal information generally
    text: we retain personal information only as long as needed to provide the Services
  - period: 30 days
    scope: Customer data including Google user data after contract termination
    text: all customer data—including Google user data—is deleted within 30 days
  rights:
  - right: Access, correct, delete, restrict processing
    text: you may have rights to access, correct, delete, or restrict the processing of your personal information
  - right: California categories request
    text: California residents may also request information about categories of personal information we disclose for business purposes
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we protect such transfers with safeguards like Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bind
provenance_date: '2026-11-09'
provider_name: Bind
provider_slug: bind
slug: bind-privacy-policy
source_date: '2026-11-09'
source_filename: bind-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bindhq.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bind\naid: bind\nurl: https://www.bindhq.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, phone number (optional), biography (optional)\n- category: device\n  text: Browser type, language preference, referring URL, date/time of request\n- category: device\n  text: Session ID, preference cookies\n- category: other\n  text: Emails, files, insurance data uploaded or generated in the Services\npurposes:\n- purpose: Provide, operate and improve the Services\n  text: We use personal information to\
  \ provide, operate, and continually improve the Services\n- purpose: Secure login and collaboration\n  text: enable secure login and collaboration features\n- purpose: Legal compliance\n  text: comply with legal obligations—such as insurance record-keeping requirements\n- purpose: Aggregated statistics\n  text: generate aggregated, de-identified statistics for internal analysis\nretention:\n- scope: Personal information generally\n  period: null\n  text: we retain personal information only as long as needed to provide the Services\n- scope: Customer data including Google user data after contract termination\n  period: 30 days\n  text: all customer data—including Google user data—is deleted within 30 days\nresidency:\n- region: United States\n  text: Because Owsy is headquartered in the United States, your information may be processed in countries where\n    we or our service providers operate\ntransfers:\n- mechanism: SCC\n  text: we protect such transfers with safeguards like Standard\
  \ Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email info@bindhq.com to request early deletion of Google user data\n  text: You may also request early deletion of your Google user data at any time by emailing info@bindhq.com\nrights:\n- right: Access, correct, delete, restrict processing\n  text: you may have rights to access, correct, delete, or restrict the processing of your personal information\n- right: California categories request\n  text: California residents may also request information about categories of personal information we disclose for\n    business purposes\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/bind/privacy/bind-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Bind's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Platform
- Composable
- Specialty
---
