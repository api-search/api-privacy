---
api_specs:
- filename: snu-oai-pmh-api-openapi.yml
  format: yaml
  label: Seoul National University OAI PMH API
  slug: snu-oai-pmh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snu/openapi/snu-oai-pmh-api-openapi.yml
- filename: snu-open-search-api-openapi.yml
  format: yaml
  label: Seoul National University Open Search API
  slug: snu-open-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snu/openapi/snu-open-search-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, resident registration number (foreign registration number or passport number for international students)
  - category: contact
    text: address, phone number, mobile phone number, e-mail address
  - category: financial
    text: bank account information for possible refunds
  - category: health
    text: 'Health Status: Required'
  - category: behavioral
    text: records on service use, accessed IP information
  - category: device
    text: type of operating system and version information, USIM ICC ID, IMEI ID, mobile carrier code, mobile phone version, model, UUID
  - category: biometric
    text: hand vascular pattern recognition information
  deletion:
    route: Request to correct or delete personal information via the Request Form or the managing team
    text: Personal information files retained by Seoul National University are subject to correction or deletion by request pursuant to Article 35
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision of services
    text: Personal Information will be managed to provide various services for introducing the University and making announcements, providing educational content, verifying personal identity, issuing certificates (certificate of education), and for providing information on admissions.
  - purpose: Membership registration and management
    text: Personal Information will be managed for identity verification and personal authentication of users for access to the membership services provided by the University
  retention:
  - period: null
    scope: General
    text: The personal information of the users will be destroyed immediately after the purpose of its collection and use have been achieved.
  - period: Ten years
    scope: Admissions
    text: Ten years
  - period: Five Years
    scope: Residence hall residents
    text: Five Years
  rights:
  - right: Inspection
    text: users can request to inspect the personal information retained by the main website of Seoul National University.
  - right: Correction or deletion
    text: Personal information files retained by Seoul National University are subject to correction or deletion by request
  - right: Suspension of management
    text: Seoul National University will suspend the management of specific personal information entirely or partially at the request of a subject of information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Seoul National University
provenance_date: '2026-11-10'
provider_name: Seoul National University
provider_slug: snu
slug: snu-privacy-policy
source_date: '2026-11-10'
source_filename: snu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://en.snu.ac.kr/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Seoul National University\naid: snu\nurl: https://en.snu.ac.kr/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, resident registration number (foreign registration number or passport number for international students)\n- category: contact\n  text: address, phone number, mobile phone number, e-mail address\n- category: financial\n  text: bank account information for possible refunds\n- category: health\n  text: 'Health Status: Required'\n- category: behavioral\n  text: records on service use, accessed IP information\n\
  - category: device\n  text: type of operating system and version information, USIM ICC ID, IMEI ID, mobile carrier code, mobile phone\n    version, model, UUID\n- category: biometric\n  text: hand vascular pattern recognition information\npurposes:\n- purpose: Provision of services\n  text: Personal Information will be managed to provide various services for introducing the University and making\n    announcements, providing educational content, verifying personal identity, issuing certificates (certificate\n    of education), and for providing information on admissions.\n- purpose: Membership registration and management\n  text: Personal Information will be managed for identity verification and personal authentication of users for\n    access to the membership services provided by the University\nretention:\n- scope: General\n  period: null\n  text: The personal information of the users will be destroyed immediately after the purpose of its collection\n    and use have been achieved.\n\
  - scope: Admissions\n  period: Ten years\n  text: Ten years\n- scope: Residence hall residents\n  period: Five Years\n  text: Five Years\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to correct or delete personal information via the Request Form or the managing team\n  text: Personal information files retained by Seoul National University are subject to correction or deletion by\n    request pursuant to Article 35\nrights:\n- right: Inspection\n  text: users can request to inspect the personal information retained by the main website of Seoul National University.\n- right: Correction or deletion\n  text: Personal information files retained by Seoul National University are subject to correction or deletion by\n    request\n- right: Suspension of management\n  text: Seoul National University will suspend the management of specific personal information entirely or partially\n    at\
  \ the request of a subject of information\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/snu/privacy/snu-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from Seoul National University's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- South Korea
- Research
- Research Data
- Institutional Repository
- Research Repository
- Identity Federation
- OAI-PMH
- SAML
- Open Access
- Library
- National University
---
