---
api_specs:
- filename: redocly-health-api-openapi.yml
  format: yaml
  label: Redocly Health API
  slug: redocly-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-health-api-openapi.yml
- filename: redocly-metadata-api-openapi.yml
  format: yaml
  label: Redocly Metadata API
  slug: redocly-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-metadata-api-openapi.yml
- filename: redocly-remotes-api-openapi.yml
  format: yaml
  label: Redocly Remotes API
  slug: redocly-remotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-remotes-api-openapi.yml
- filename: redocly-search-api-openapi.yml
  format: yaml
  label: Redocly Search API
  slug: redocly-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-search-api-openapi.yml
- filename: redocly-status-api-openapi.yml
  format: yaml
  label: Redocly Status API
  slug: redocly-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-status-api-openapi.yml
- filename: redocly-tasks-api-openapi.yml
  format: yaml
  label: Redocly Tasks API
  slug: redocly-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-tasks-api-openapi.yml
- filename: redocly-webhooks-api-openapi.yml
  format: yaml
  label: Redocly Webhooks API
  slug: redocly-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-webhooks-api-openapi.yml
- filename: redocly-to-dos-api-openapi.yml
  format: yaml
  label: Redocly To Dos API
  slug: redocly-to-dos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-to-dos-api-openapi.yml
claim_count: 37
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email, phone number, job title, company, etc.
  - category: device
    text: IP address, device type, operating system, browser type and version, screen resolution
  - category: behavioral
    text: usage information (such as access times, pages viewed, clicks, and interactions)
  - category: financial
    text: payment details
  - category: communication
    text: communications, and support requests
  - category: contact
    text: contact details, device data, transactional information
  - category: contact
    source: https://redocly.com/dpa
    text: Identification and contact data (name, address, e-mail address, telephone number, company name)
  - category: financial
    source: https://redocly.com/dpa
    text: order information
  - category: device
    source: https://redocly.com/dpa
    text: IT related data (IP addresses, unique device level identifiers, cookies data, online navigation data (including access date and times), location data, browser data language)
  deletion:
    route: null
    text: after which it is securely deleted or anonymized
  dpa:
    available: true
    source: https://redocly.com/dpa
    text: Data Processing Addendum
    url: https://redocly.com/dpa
  purposes:
  - purpose: respond to inquiries and marketing
    text: We use this information to respond to inquiries, provide updates, send marketing communications (subject to your preferences), improve our Website, and comply with legal obligations.
  - purpose: provide and secure Services
    text: We use this information to provide, manage, and secure the Services, communicate with Users, process billing, improve functionality, prevent fraud, and comply with legal obligations.
  - purpose: Provide the Products under the Agreement
    source: https://redocly.com/dpa
    text: (i) processing to provide the Products in accordance with the Agreement
  - purpose: Processing initiated by Users
    source: https://redocly.com/dpa
    text: (iii) processing initiated by Users in their use of the Products
  - purpose: Comply with customer instructions
    source: https://redocly.com/dpa
    text: (iv) processing to comply with other reasonable instructions provided by Customer (e.g. via email or support tickets)
  - purpose: AI search and assistant
    source: https://redocly.com/sub-processors
    text: LLM provider for AI search feature and AI-assistant feature
  - purpose: Analytics
    source: https://redocly.com/sub-processors
    text: Analytics data
  - purpose: Login and registration
    source: https://redocly.com/sub-processors
    text: Identity provider for login and registration (for Redocly Workflows only)
  - purpose: Support email and chat
    source: https://redocly.com/sub-processors
    text: Support email and chat
  residency:
  - region: United States and anywhere else in the world
    source: https://redocly.com/dpa
    text: Redocly may transfer and process Customer Data to and in the United States and anywhere else in the world where Redocly, its Affiliates or its Sub-processors maintain data processing operations.
  - region: US
    source: https://redocly.com/sub-processors
    text: AWS US For all services, including email service provider, storing and processing of data
  retention:
  - period: null
    scope: all data
    text: We retain data only as long as necessary for business or legal purposes, after which it is securely deleted or anonymized.
  - period: at least one year
    scope: Audit trail history
    source: https://redocly.com/dpa
    text: Retain audit trail history for at least one year, with a minimum of three months immediately available for analysis.
  rights:
  - right: access, correct, or delete
    text: access, correct, or delete your personal information
  - right: restrict or object
    text: restrict or object to processing
  - right: portability
    text: request portability
  - right: withdraw consent
    text: withdraw consent
  - right: lodge complaints
    text: lodge complaints with your local authority
  - right: Data subject request assistance
    source: https://redocly.com/dpa
    text: Redocly shall (at Customer's expense) taking into account the nature of the processing, provide reasonable cooperation to assist Customer
  - right: Audit rights
    source: https://redocly.com/dpa
    text: allow for and contribute to audits at a mutually agreeable time following reasonable written notice
  role:
    text: Redocly collects and processes personal information about you from various sources to provide our Services and to manage our Website.
    value: controller
  sale_or_sharing:
    source: https://redocly.com/dpa
    stance: prohibited
    text: Redocly shall not sell or share for cross-context behavioral advertising purposes any Customer Data.
  subprocessors:
    source: https://redocly.com/dpa
    text: The Sub-processors currently engaged by Redocly and authorized by Customer are listed here https://www.redocly.com/sub-processors .
    url: https://www.redocly.com/sub-processors
  transfers:
  - mechanism: SCC
    text: We rely on safeguards including the European Commission’s Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: may also participate in the EU–U.S. Data Privacy Framework (DPF), the UK Extension to the DPF, and the Swiss–U.S. DPF once certification is completed.
  - mechanism: SCC
    source: https://redocly.com/dpa
    text: the parties agree to comply with “Module Two” (Controller to Processor) of the EU SCCs, which are incorporated herein by reference.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Redocly
provenance_date: '2026-11-10'
provider_name: Redocly
provider_slug: redocly
slug: redocly-privacy-policy
source_date: '2026-11-10'
source_filename: redocly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://redocly.com/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Redocly\naid: redocly\nurl: https://redocly.com/privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://redocly.com/dpa\n  - https://redocly.com/privacy-notice\n  - https://redocly.com/sub-processors\nrole:\n  value: controller\n  text: Redocly collects and processes personal information about you from various sources to provide our Services\n    and to manage our Website.\ndata_categories:\n- category: identifying\n  text: name, email, phone number, job title, company, etc.\n- category: device\n  text: IP address, device type, operating system, browser type and version, screen resolution\n- category:\
  \ behavioral\n  text: usage information (such as access times, pages viewed, clicks, and interactions)\n- category: financial\n  text: payment details\n- category: communication\n  text: communications, and support requests\n- category: contact\n  text: contact details, device data, transactional information\n- category: contact\n  text: Identification and contact data (name, address, e-mail address, telephone number, company name)\n  source: https://redocly.com/dpa\n- category: financial\n  text: order information\n  source: https://redocly.com/dpa\n- category: device\n  text: IT related data (IP addresses, unique device level identifiers, cookies data, online navigation data (including\n    access date and times), location data, browser data language)\n  source: https://redocly.com/dpa\npurposes:\n- purpose: respond to inquiries and marketing\n  text: We use this information to respond to inquiries, provide updates, send marketing communications (subject\n    to your preferences), improve\
  \ our Website, and comply with legal obligations.\n- purpose: provide and secure Services\n  text: We use this information to provide, manage, and secure the Services, communicate with Users, process billing,\n    improve functionality, prevent fraud, and comply with legal obligations.\n- purpose: Provide the Products under the Agreement\n  text: (i) processing to provide the Products in accordance with the Agreement\n  source: https://redocly.com/dpa\n- purpose: Processing initiated by Users\n  text: (iii) processing initiated by Users in their use of the Products\n  source: https://redocly.com/dpa\n- purpose: Comply with customer instructions\n  text: (iv) processing to comply with other reasonable instructions provided by Customer (e.g. via email or support\n    tickets)\n  source: https://redocly.com/dpa\n- purpose: AI search and assistant\n  text: LLM provider for AI search feature and AI-assistant feature\n  source: https://redocly.com/sub-processors\n- purpose: Analytics\n  text:\
  \ Analytics data\n  source: https://redocly.com/sub-processors\n- purpose: Login and registration\n  text: Identity provider for login and registration (for Redocly Workflows only)\n  source: https://redocly.com/sub-processors\n- purpose: Support email and chat\n  text: Support email and chat\n  source: https://redocly.com/sub-processors\nretention:\n- scope: all data\n  period: null\n  text: We retain data only as long as necessary for business or legal purposes, after which it is securely deleted\n    or anonymized.\n- scope: Audit trail history\n  period: at least one year\n  text: Retain audit trail history for at least one year, with a minimum of three months immediately available for\n    analysis.\n  source: https://redocly.com/dpa\nresidency:\n- region: United States and anywhere else in the world\n  text: Redocly may transfer and process Customer Data to and in the United States and anywhere else in the world\n    where Redocly, its Affiliates or its Sub-processors maintain data\
  \ processing operations.\n  source: https://redocly.com/dpa\n- region: US\n  text: AWS US For all services, including email service provider, storing and processing of data\n  source: https://redocly.com/sub-processors\ntransfers:\n- mechanism: SCC\n  text: We rely on safeguards including the European Commission’s Standard Contractual Clauses (SCCs)\n- mechanism: DPF\n  text: may also participate in the EU–U.S. Data Privacy Framework (DPF), the UK Extension to the DPF, and the Swiss–U.S.\n    DPF once certification is completed.\n- mechanism: SCC\n  text: the parties agree to comply with “Module Two” (Controller to Processor) of the EU SCCs, which are incorporated\n    herein by reference.\n  source: https://redocly.com/dpa\nsubprocessors:\n  url: https://www.redocly.com/sub-processors\n  text: The Sub-processors currently engaged by Redocly and authorized by Customer are listed here https://www.redocly.com/sub-processors\n    .\n  source: https://redocly.com/dpa\ndpa:\n  available: true\n\
  \  url: https://redocly.com/dpa\n  text: Data Processing Addendum\n  source: https://redocly.com/dpa\ndeletion:\n  route: null\n  text: after which it is securely deleted or anonymized\nrights:\n- right: access, correct, or delete\n  text: access, correct, or delete your personal information\n- right: restrict or object\n  text: restrict or object to processing\n- right: portability\n  text: request portability\n- right: withdraw consent\n  text: withdraw consent\n- right: lodge complaints\n  text: lodge complaints with your local authority\n- right: Data subject request assistance\n  text: Redocly shall (at Customer's expense) taking into account the nature of the processing, provide reasonable\n    cooperation to assist Customer\n  source: https://redocly.com/dpa\n- right: Audit rights\n  text: allow for and contribute to audits at a mutually agreeable time following reasonable written notice\n  source: https://redocly.com/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: Redocly\
  \ shall not sell or share for cross-context behavioral advertising purposes any Customer Data.\n  source: https://redocly.com/dpa\n"
source_yaml_url: https://artifacts.apis.io/redocly/privacy/redocly-privacy-policy.yml
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
summary_line: 37 quoted statements, read from Redocly's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- API Catalog
- API Documentation
- Arazzo
- Developer Portal
- Governance
- Linting
- MCP
- Monitoring
- OpenAPI
- A2A
---
