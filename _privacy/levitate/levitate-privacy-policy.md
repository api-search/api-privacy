---
api_specs:
- filename: levitate-companies-api-openapi.yml
  format: yaml
  label: Levitate Companies API
  slug: levitate-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levitate/openapi/levitate-companies-api-openapi.yml
- filename: levitate-contacts-api-openapi.yml
  format: yaml
  label: Levitate Contacts API
  slug: levitate-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levitate/openapi/levitate-contacts-api-openapi.yml
- filename: levitate-notes-api-openapi.yml
  format: yaml
  label: Levitate Notes API
  slug: levitate-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/levitate/openapi/levitate-notes-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: personal identifying data (given and surname, employee id/reference, job title, location, time zone, photograph, calendar information)
  - category: contact
    text: communication/contact details (email address, telephone number)
  - category: professional
    text: employment related data (employee reference identifier, job title and level, departments, work location, calendar and meeting information)
  - category: financial
    text: billing information
  - category: device
    text: we may automatically collect online identifiers such as internet protocol addresses, cookie information and advertising ID (for mobile users)
  - category: communication
    text: 'metadata about sent email messages (such as: name and email address of the email sender, recipient, and time and date when message was sent)'
  deletion:
    route: email support@levitateapp.com to request deletion
    text: you may contact us at support@levitateapp.com and request that we delete your Personal Information from our records
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Services
    text: to provide you with the Services
  - purpose: customer service
    text: to respond to your customer service requests
  - purpose: AI capabilities
    text: to generate user content through artificial intelligence capabilities in Levitate
  - purpose: website analytics
    text: to compile data regarding Website traffic and Website interaction to better user experience
  - purpose: advertising
    text: for our advertising and marketing efforts
  residency:
  - region: United States
    text: The Website and Levitate are hosted in the United States (" U.S. ") and are intended for users in the U.S. only.
  retention:
  - period: thirty (30) days
    scope: Levitate customer Personal Information
    text: For Levitate customers, Personal Information is securely deleted within thirty (30) days following the termination of your Account (and customer agreement)
  - period: thirty (30) days
    scope: deletion requests
    text: We will honor your Personal Information deletion requests within thirty (30) days
  - period: null
    scope: Inputs and Outputs
    text: We will retain Inputs (as defined in the Terms of Service) and Outputs (as defined in the Terms of Service) submitted through Levitate to perform the Services, and/or for research purposes, product improvement, or system monitoring.
  rights:
  - right: access, correct, verify, or remove
    text: You have the right to access, correct, verify, or remove your personal information at any time.
  - right: delete
    text: A California resident has the right to request that The Company delete their Personal Information.
  - right: opt-out of sale
    text: A California resident also has a right to "opt-out" of the sale of that resident's Personal Information.
  - right: non-discrimination
    text: A California resident has the right not to be discriminated against for exercising their privacy rights under the CA Privacy Laws.
  - right: limit use of sensitive personal information
    text: A California resident has the right to limit The Company's use and disclosure of sensitive Personal Information about the resident
  role:
    text: you understand and acknowledge we are a service provider and not a business
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or otherwise transfer your Personal Information, or data that you provide Levitate (including, but not limited to, your Contact Data) to outside parties
  subprocessors:
    text: a current list of which can be found at https://www.levitate.ai/underlying-ai-model-providers
    url: https://www.levitate.ai/underlying-ai-model-providers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Levitate
provenance_date: '2026-11-09'
provider_name: Levitate
provider_slug: levitate
slug: levitate-privacy-policy
source_date: '2026-11-09'
source_filename: levitate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.levitate.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Levitate\naid: levitate\nurl: https://www.levitate.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: you understand and acknowledge we are a service provider and not a business\ndata_categories:\n- category: identifying\n  text: personal identifying data (given and surname, employee id/reference, job title, location, time zone, photograph,\n    calendar information)\n- category: contact\n  text: communication/contact details (email address, telephone number)\n- category: professional\n  text: employment related data (employee reference identifier, job title and level, departments,\
  \ work location,\n    calendar and meeting information)\n- category: financial\n  text: billing information\n- category: device\n  text: we may automatically collect online identifiers such as internet protocol addresses, cookie information\n    and advertising ID (for mobile users)\n- category: communication\n  text: 'metadata about sent email messages (such as: name and email address of the email sender, recipient, and\n    time and date when message was sent)'\npurposes:\n- purpose: provide the Services\n  text: to provide you with the Services\n- purpose: customer service\n  text: to respond to your customer service requests\n- purpose: AI capabilities\n  text: to generate user content through artificial intelligence capabilities in Levitate\n- purpose: website analytics\n  text: to compile data regarding Website traffic and Website interaction to better user experience\n- purpose: advertising\n  text: for our advertising and marketing efforts\nretention:\n- scope: Levitate customer\
  \ Personal Information\n  period: thirty (30) days\n  text: For Levitate customers, Personal Information is securely deleted within thirty (30) days following the termination\n    of your Account (and customer agreement)\n- scope: deletion requests\n  period: thirty (30) days\n  text: We will honor your Personal Information deletion requests within thirty (30) days\n- scope: Inputs and Outputs\n  period: null\n  text: We will retain Inputs (as defined in the Terms of Service) and Outputs (as defined in the Terms of Service)\n    submitted through Levitate to perform the Services, and/or for research purposes, product improvement, or system\n    monitoring.\nresidency:\n- region: United States\n  text: The Website and Levitate are hosted in the United States (\" U.S. \") and are intended for users in the U.S.\n    only.\ntransfers: []\nsubprocessors:\n  url: https://www.levitate.ai/underlying-ai-model-providers\n  text: a current list of which can be found at https://www.levitate.ai/underlying-ai-model-providers\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@levitateapp.com to request deletion\n  text: you may contact us at support@levitateapp.com and request that we delete your Personal Information from\n    our records\nrights:\n- right: access, correct, verify, or remove\n  text: You have the right to access, correct, verify, or remove your personal information at any time.\n- right: delete\n  text: A California resident has the right to request that The Company delete their Personal Information.\n- right: opt-out of sale\n  text: A California resident also has a right to \"opt-out\" of the sale of that resident's Personal Information.\n- right: non-discrimination\n  text: A California resident has the right not to be discriminated against for exercising their privacy rights\n    under the CA Privacy Laws.\n- right: limit use of sensitive personal information\n  text: A California resident has the right to limit The Company's use and disclosure of sensitive\
  \ Personal Information\n    about the resident\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or otherwise transfer your Personal Information, or data that you provide Levitate\n    (including, but not limited to, your Contact Data) to outside parties\n"
source_yaml_url: https://artifacts.apis.io/levitate/privacy/levitate-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Levitate's own page on 2026-11-09.
synthetic: false
tags:
- relationship-marketing
- CRM
- Email Marketing
- Contacts
- Small Business
- Insurance
- Financial Services
- Non-Profit
- Marketing Automation
- MCP
- Agent-Native
- Software-as-a-Service
---
