---
api_specs:
- filename: contracko-com-authentication-api-openapi.yml
  format: yaml
  label: Contracko Authentication API
  slug: contracko-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contracko-com/openapi/contracko-com-authentication-api-openapi.yml
- filename: contracko-com-contract-types-api-openapi.yml
  format: yaml
  label: Contracko Contract Types API
  slug: contracko-com-contract-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contracko-com/openapi/contracko-com-contract-types-api-openapi.yml
- filename: contracko-com-parsing-api-api-openapi.yml
  format: yaml
  label: Contracko Parsing API
  slug: contracko-com-parsing-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contracko-com/openapi/contracko-com-parsing-api-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and profile data: name, email, password or authentication data, job title, organisation, contact preferences.'
  - category: contact
    text: Business-contact data (name, job title, organisation, business email, LinkedIn profile)
  - category: financial
    text: 'Billing data: billing contact and address. Card details are entered directly with our payment processor and are not stored by us.'
  - category: device
    text: IP address, approximate location inferred from IP, browser and device type, operating system, referring URLs, pages viewed, and actions taken
  - category: communication
    text: 'Communications: messages you send us (support, sales, email).'
  deletion:
    route: null
    text: When personal data is no longer needed, we delete or anonymise it; residual copies in backups are purged on the normal backup cycle.
  dpa:
    available: true
    text: governed by our Data Processing Agreement (DPA), not this policy
    url: null
  purposes:
  - purpose: Provide, operate and secure the platform
    text: Provide, operate and secure the platform; manage your account and authentication
  - purpose: Billing and payments
    text: Billing and payments
  - purpose: Product and website analytics
    text: Product and website analytics, service improvement, fraud and abuse prevention
  - purpose: Advertising measurement and retargeting
    text: Advertising measurement and retargeting
  - purpose: Business-to-business sales outreach
    text: Business-to-business sales outreach to prospects
  - purpose: Marketing and lifecycle email
    text: Marketing and lifecycle email
  residency:
  - region: EU
    text: Our hosting and primary storage are in the EU.
  retention:
  - period: 7 years
    scope: Billing and tax records
    text: billing and tax records are retained for the statutory period (7 years under Dutch law)
  rights:
  - right: access, rectification, erasure, restriction, data portability, objection
    text: Under the GDPR you have the right to access, rectification, erasure, restriction, data portability, and objection
  - right: withdraw consent
    text: Where we rely on consent, you may withdraw it at any time (without affecting prior processing).
  - right: not subject to solely automated decisions
    text: the right not to be subject to solely automated decisions with legal or similarly significant effects
  - right: lodge complaint with supervisory authority
    text: you have the right to lodge a complaint with the Dutch supervisory authority
  role:
    text: We are the controller for the processing described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not use it to train AI models .
  subprocessors:
    text: The sub-processors that handle customer content are listed separately in the sub-processor list referenced in our DPA.
    url: null
  transfers:
  - mechanism: adequacy
    text: For those transfers we rely on an adequacy decision or the EU-US Data Privacy Framework where the recipient is certified
  - mechanism: DPF
    text: the EU-US Data Privacy Framework where the recipient is certified
  - mechanism: SCC
    text: otherwise on the EU Standard Contractual Clauses with supplementary measures
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Contracko
provenance_date: '2026-11-09'
provider_name: Contracko
provider_slug: contracko-com
slug: contracko-com-privacy-policy
source_date: '2026-11-09'
source_filename: contracko-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://contracko.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Contracko\naid: contracko-com\nurl: https://contracko.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller for the processing described here.\ndata_categories:\n- category: identifying\n  text: 'Account and profile data: name, email, password or authentication data, job title, organisation, contact\n    preferences.'\n- category: contact\n  text: Business-contact data (name, job title, organisation, business email, LinkedIn profile)\n- category: financial\n  text: 'Billing data: billing contact and address. Card details are entered directly with our\
  \ payment processor\n    and are not stored by us.'\n- category: device\n  text: IP address, approximate location inferred from IP, browser and device type, operating system, referring\n    URLs, pages viewed, and actions taken\n- category: communication\n  text: 'Communications: messages you send us (support, sales, email).'\npurposes:\n- purpose: Provide, operate and secure the platform\n  text: Provide, operate and secure the platform; manage your account and authentication\n- purpose: Billing and payments\n  text: Billing and payments\n- purpose: Product and website analytics\n  text: Product and website analytics, service improvement, fraud and abuse prevention\n- purpose: Advertising measurement and retargeting\n  text: Advertising measurement and retargeting\n- purpose: Business-to-business sales outreach\n  text: Business-to-business sales outreach to prospects\n- purpose: Marketing and lifecycle email\n  text: Marketing and lifecycle email\nretention:\n- scope: Billing and tax\
  \ records\n  period: 7 years\n  text: billing and tax records are retained for the statutory period (7 years under Dutch law)\nresidency:\n- region: EU\n  text: Our hosting and primary storage are in the EU.\ntransfers:\n- mechanism: adequacy\n  text: For those transfers we rely on an adequacy decision or the EU-US Data Privacy Framework where the recipient\n    is certified\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework where the recipient is certified\n- mechanism: SCC\n  text: otherwise on the EU Standard Contractual Clauses with supplementary measures\nsubprocessors:\n  url: null\n  text: The sub-processors that handle customer content are listed separately in the sub-processor list referenced\n    in our DPA.\ndpa:\n  available: true\n  url: null\n  text: governed by our Data Processing Agreement (DPA), not this policy\ndeletion:\n  route: null\n  text: When personal data is no longer needed, we delete or anonymise it; residual copies in backups are purged\n    on the\
  \ normal backup cycle.\nrights:\n- right: access, rectification, erasure, restriction, data portability, objection\n  text: Under the GDPR you have the right to access, rectification, erasure, restriction, data portability, and\n    objection\n- right: withdraw consent\n  text: Where we rely on consent, you may withdraw it at any time (without affecting prior processing).\n- right: not subject to solely automated decisions\n  text: the right not to be subject to solely automated decisions with legal or similarly significant effects\n- right: lodge complaint with supervisory authority\n  text: you have the right to lodge a complaint with the Dutch supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not use it to train AI models .\n"
source_yaml_url: https://artifacts.apis.io/contracko-com/privacy/contracko-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Contracko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Contract Management
- Legal Technology
- Artificial Intelligence
- Document Parsing
- Data Extraction
- E-Signature
- MCP
---
