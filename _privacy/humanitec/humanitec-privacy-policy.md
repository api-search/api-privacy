---
api_specs:
- filename: humanitec-agents-api-openapi.yml
  format: yaml
  label: Humanitec Agents API
  slug: humanitec-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanitec/openapi/humanitec-agents-api-openapi.yml
- filename: humanitec-public-api-openapi.yml
  format: yaml
  label: Humanitec Public API
  slug: humanitec-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanitec/openapi/humanitec-public-api-openapi.yml
- filename: humanitec-user-role-api-openapi.yml
  format: yaml
  label: Humanitec User Role API
  slug: humanitec-user-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanitec/openapi/humanitec-user-role-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Last name First name Date and time of registration company name
  - category: contact
    text: Phone number
  - category: device
    text: device metadata (screen size, language, etc.)
  - category: behavioral
    text: Tracking of the surfing behaviour
  deletion:
    route: Request form
    text: Please use this form to request the erasure of your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Product analytics
    text: We use Amplitude to collect data on user interactions inside the console application.
  - purpose: Newsletter delivery
    text: The user's email address is collected to deliver the newsletter to the recipient.
  - purpose: Website optimization and IT security
    text: The data is also used to optimize the website and to ensure the security of our IT systems.
  residency:
  - region: European Union / EEA (website server)
    text: The server of the website is geographically located in the European Union (EU) or the European Economic Area (EEA).
  retention:
  - period: 30 days
    scope: Account registration data
    text: If you terminate or delete your account, we will delete your personal information within 30 days of the deletion of your account.
  - period: seven days
    scope: Server log files
    text: If the data is stored in log files, this is the case after seven days at the latest.
  - period: null
    scope: Newsletter email address
    text: The user's email address will therefore be stored as long as the newsletter subscription is active.
  rights:
  - right: Access
    text: Right of access (Art. 15 GDPR)
  - right: Rectification
    text: Right to rectification (Art. 16 GDPR)
  - right: Restriction
    text: Right to the restriction of processing (Art. 18 GDPR)
  - right: Erasure
    text: Right to erasure ("Right to be forgotten") (Art. 17 GDPR)
  - right: Portability
    text: Right to data portability (Art. 20 GDPR)
  - right: Object
    text: Right to object (Art. 21 GDPR)
  - right: Complain to supervisory authority
    text: Right to complain to a supervisory authority
  role:
    text: 'The data controller responsible in accordance with the purposes of the General Data Protection Regulation (GDPR) of the European Union and other data protection regulations is: Ternki GmbH'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we have provided appropriate guarantees in form of standard data protection clauses pursuant to Art. 46(2)(c) GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Humanitec
provenance_date: '2026-11-09'
provider_name: Humanitec
provider_slug: humanitec
slug: humanitec-privacy-policy
source_date: '2026-11-09'
source_filename: humanitec-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://humanitec.com/policies/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Humanitec\naid: humanitec\nurl: https://humanitec.com/policies/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller responsible in accordance with the purposes of the General Data Protection Regulation\n    (GDPR) of the European Union and other data protection regulations is: Ternki GmbH'\ndata_categories:\n- category: identifying\n  text: Email address Last name First name Date and time of registration company name\n- category: contact\n  text: Phone number\n- category: device\n  text: device metadata (screen size, language, etc.)\n- category: behavioral\n \
  \ text: Tracking of the surfing behaviour\npurposes:\n- purpose: Product analytics\n  text: We use Amplitude to collect data on user interactions inside the console application.\n- purpose: Newsletter delivery\n  text: The user's email address is collected to deliver the newsletter to the recipient.\n- purpose: Website optimization and IT security\n  text: The data is also used to optimize the website and to ensure the security of our IT systems.\nretention:\n- scope: Account registration data\n  period: 30 days\n  text: If you terminate or delete your account, we will delete your personal information within 30 days of the\n    deletion of your account.\n- scope: Server log files\n  period: seven days\n  text: If the data is stored in log files, this is the case after seven days at the latest.\n- scope: Newsletter email address\n  period: null\n  text: The user's email address will therefore be stored as long as the newsletter subscription is active.\nresidency:\n- region: European Union\
  \ / EEA (website server)\n  text: The server of the website is geographically located in the European Union (EU) or the European Economic\n    Area (EEA).\ntransfers:\n- mechanism: SCC\n  text: we have provided appropriate guarantees in form of standard data protection clauses pursuant to Art. 46(2)(c)\n    GDPR.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request form\n  text: Please use this form to request the erasure of your personal data.\nrights:\n- right: Access\n  text: Right of access (Art. 15 GDPR)\n- right: Rectification\n  text: Right to rectification (Art. 16 GDPR)\n- right: Restriction\n  text: Right to the restriction of processing (Art. 18 GDPR)\n- right: Erasure\n  text: Right to erasure (\"Right to be forgotten\") (Art. 17 GDPR)\n- right: Portability\n  text: Right to data portability (Art. 20 GDPR)\n- right: Object\n  text: Right to object (Art. 21 GDPR)\n- right: Complain to supervisory authority\n\
  \  text: Right to complain to a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/humanitec/privacy/humanitec-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from Humanitec's own page on 2026-11-09.
synthetic: false
tags:
- Deployment
- DevOps
- Internal Developer Platform
- Platform Engineering
- Platform Orchestrator
---
