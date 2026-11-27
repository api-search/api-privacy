---
api_specs:
- filename: openmail-sh-attachments-api-openapi.yml
  format: yaml
  label: openmail-sh Attachments API
  slug: openmail-sh-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-attachments-api-openapi.yml
- filename: openmail-sh-domains-api-openapi.yml
  format: yaml
  label: openmail-sh Domains API
  slug: openmail-sh-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-domains-api-openapi.yml
- filename: openmail-sh-feedback-api-openapi.yml
  format: yaml
  label: openmail-sh Feedback API
  slug: openmail-sh-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-feedback-api-openapi.yml
- filename: openmail-sh-inboxes-api-openapi.yml
  format: yaml
  label: openmail-sh Inboxes API
  slug: openmail-sh-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-inboxes-api-openapi.yml
- filename: openmail-sh-limits-api-openapi.yml
  format: yaml
  label: openmail-sh Limits API
  slug: openmail-sh-limits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-limits-api-openapi.yml
- filename: openmail-sh-messages-api-openapi.yml
  format: yaml
  label: openmail-sh Messages API
  slug: openmail-sh-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-messages-api-openapi.yml
- filename: openmail-sh-owned-domains-api-openapi.yml
  format: yaml
  label: openmail-sh Owned Domains API
  slug: openmail-sh-owned-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-owned-domains-api-openapi.yml
- filename: openmail-sh-pods-api-openapi.yml
  format: yaml
  label: openmail-sh Pods API
  slug: openmail-sh-pods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-pods-api-openapi.yml
- filename: openmail-sh-policy-api-openapi.yml
  format: yaml
  label: openmail-sh Policy API
  slug: openmail-sh-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-policy-api-openapi.yml
- filename: openmail-sh-threads-api-openapi.yml
  format: yaml
  label: openmail-sh Threads API
  slug: openmail-sh-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmail-sh/openapi/openmail-sh-threads-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name and last name
  - category: contact
    text: Email address
  - category: contact
    text: Address, State, Province, ZIP/Postal code, City
  - category: device
    text: unique device identifiers
  - category: behavioral
    text: the pages of our Service that you visit
  - category: communication
    text: OpenMail processes email metadata and content solely on behalf of customers, according to customer instructions.
  deletion:
    route: email support@openmail.to
    text: If you wish to be informed what Personal Data we hold about you and if you want it to be removed from our systems, please email us at support@openmail.to
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain the Service
  - purpose: Process billing and payments
    text: Process billing and payments
  - purpose: Detect and prevent abuse, fraud, or security issues
    text: Detect and prevent abuse, fraud, or security issues
  - purpose: Marketing communications
    text: Provide product announcements and marketing communications (unless opted out)
  residency:
  - region: European Union
    text: we transfer the data, including Personal Data, to the European Union and process it there.
  retention:
  - period: 30 days
    scope: Trashed email conversations
    text: Email conversations you delete are first moved to Trash, where they stay for up to 30 days unless you remove them sooner.
  - period: within a further 30 days
    scope: Email removed from Trash or deleted via API
    text: are permanently erased from our systems, including message content and attachments, within a further 30 days.
  - period: 1 hour
    scope: MCP access token
    text: an access token that expires after 1 hour
  - period: 30 days
    scope: MCP refresh token
    text: a refresh token that expires after 30 days
  rights:
  - right: access, update or delete
    text: the right to access, update or to delete the information we have on you
  - right: rectification
    text: the right of rectification.
  - right: object
    text: the right to object.
  - right: restriction
    text: the right of restriction.
  - right: data portability
    text: the right to data portability.
  - right: withdraw consent
    text: the right to withdraw consent.
  - right: CCPA deletion
    text: Deletion of Personal Data
  role:
    text: For purposes of this Privacy Policy, OpenMail is a Data Controller.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use the following subprocessors to operate the Service.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: openmail-sh
provenance_date: '2026-11-10'
provider_name: openmail-sh
provider_slug: openmail-sh
slug: openmail-sh-privacy-policy
source_date: '2026-11-10'
source_filename: openmail-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openmail.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: openmail-sh\naid: openmail-sh\nurl: https://openmail.sh/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For purposes of this Privacy Policy, OpenMail is a Data Controller.\ndata_categories:\n- category: identifying\n  text: First name and last name\n- category: contact\n  text: Email address\n- category: contact\n  text: Address, State, Province, ZIP/Postal code, City\n- category: device\n  text: unique device identifiers\n- category: behavioral\n  text: the pages of our Service that you visit\n- category: communication\n  text: OpenMail processes email metadata and content solely on\
  \ behalf of customers, according to customer instructions.\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain the Service\n- purpose: Process billing and payments\n  text: Process billing and payments\n- purpose: Detect and prevent abuse, fraud, or security issues\n  text: Detect and prevent abuse, fraud, or security issues\n- purpose: Marketing communications\n  text: Provide product announcements and marketing communications (unless opted out)\nretention:\n- scope: Trashed email conversations\n  period: 30 days\n  text: Email conversations you delete are first moved to Trash, where they stay for up to 30 days unless you remove\n    them sooner.\n- scope: Email removed from Trash or deleted via API\n  period: within a further 30 days\n  text: are permanently erased from our systems, including message content and attachments, within a further 30\n    days.\n- scope: MCP access token\n  period: 1 hour\n  text: an access token that expires after 1 hour\n\
  - scope: MCP refresh token\n  period: 30 days\n  text: a refresh token that expires after 30 days\nresidency:\n- region: European Union\n  text: we transfer the data, including Personal Data, to the European Union and process it there.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use the following subprocessors to operate the Service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@openmail.to\n  text: If you wish to be informed what Personal Data we hold about you and if you want it to be removed from our\n    systems, please email us at support@openmail.to\nrights:\n- right: access, update or delete\n  text: the right to access, update or to delete the information we have on you\n- right: rectification\n  text: the right of rectification.\n- right: object\n  text: the right to object.\n- right: restriction\n  text: the right of restriction.\n- right: data portability\n  text: the right to data portability.\n- right: withdraw consent\n\
  \  text: the right to withdraw consent.\n- right: CCPA deletion\n  text: Deletion of Personal Data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openmail-sh/privacy/openmail-sh-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 25 quoted statements, read from openmail-sh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Artificial Intelligence
- Developers
---
