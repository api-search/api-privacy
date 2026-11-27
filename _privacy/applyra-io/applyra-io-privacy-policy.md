---
api_specs:
- filename: applyra-io-openapi-generated.yml
  format: yaml
  label: Applyra API
  slug: applyra-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applyra-io/openapi/_ae-authored/applyra-io-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: your name, email address and password when you register'
  - category: financial
    text: 'Payment Information: processed by Stripe; we do not see or store card numbers'
  - category: behavioral
    text: 'Usage Data: pages visited, features used and actions taken'
  - category: device
    text: 'Device Information: browser type, operating system, device type'
  - category: location
    text: 'Log Data: IP address, access times, referring URLs'
  - category: communication
    text: 'Communications: the messages you send us by email or through the contact form'
  - category: professional
    text: When a listing names a person or shows a contact email, that public information is part of what we store about the app.
  deletion:
    route: Request deletion via email
    text: You can also ask us to delete it, and exercise the other rights in section 12, at hello@applyra.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: To provide and maintain the Service, including the API and the MCP server
  - purpose: Process subscriptions and payments
    text: To process your subscription and payments
  - purpose: Fraud and abuse prevention
    text: To detect and prevent fraud, abuse and excessive use
  - purpose: Contact app developers
    text: To contact app developers about their app, as described in section 7
  residency:
  - region: European Union
    text: Our database is hosted in the European Union.
  retention:
  - period: until account deletion
    scope: Account data
    text: 'Account Data: retained until account deletion'
  - period: up to 24 months
    scope: Usage data
    text: 'Usage Data: retained for up to 24 months for analytics'
  - period: within 30 days of account deletion
    scope: Deleted accounts
    text: 'Deleted Accounts: data is removed within 30 days of account deletion'
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate data'
  - right: Erasure
    text: 'Erasure: Request deletion of your data ("right to be forgotten")'
  - right: Portability
    text: 'Portability: Request your data in a portable format'
  - right: Restriction
    text: 'Restriction: Request limitation of data processing'
  - right: Objection
    text: 'Objection: Object to certain data processing activities'
  - right: Complaint
    text: 'Complaint: Lodge a complaint with a supervisory authority'
  role:
    text: 'Data Controller: Aurélien Weiss, trading as Krnel Studio, 3 rue des Petits Thibauds, 33240 Saint Laurent d''Arce, France.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): the EU Standard Contractual Clauses approved by the European Commission'
  - mechanism: DPF
    text: or the EU-U.S. Data Privacy Framework where the provider is certified
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Applyra
provenance_date: '2026-11-09'
provider_name: Applyra
provider_slug: applyra-io
slug: applyra-io-privacy-policy
source_date: '2026-11-09'
source_filename: applyra-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.applyra.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Applyra\naid: applyra-io\nurl: https://www.applyra.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller: Aurélien Weiss, trading as Krnel Studio, 3 rue des Petits Thibauds, 33240 Saint Laurent\n    d''Arce, France.'\ndata_categories:\n- category: identifying\n  text: 'Account Information: your name, email address and password when you register'\n- category: financial\n  text: 'Payment Information: processed by Stripe; we do not see or store card numbers'\n- category: behavioral\n  text: 'Usage Data: pages visited, features used and actions taken'\n- category: device\n\
  \  text: 'Device Information: browser type, operating system, device type'\n- category: location\n  text: 'Log Data: IP address, access times, referring URLs'\n- category: communication\n  text: 'Communications: the messages you send us by email or through the contact form'\n- category: professional\n  text: When a listing names a person or shows a contact email, that public information is part of what we store\n    about the app.\npurposes:\n- purpose: Provide and maintain the Service\n  text: To provide and maintain the Service, including the API and the MCP server\n- purpose: Process subscriptions and payments\n  text: To process your subscription and payments\n- purpose: Fraud and abuse prevention\n  text: To detect and prevent fraud, abuse and excessive use\n- purpose: Contact app developers\n  text: To contact app developers about their app, as described in section 7\nretention:\n- scope: Account data\n  period: until account deletion\n  text: 'Account Data: retained until account\
  \ deletion'\n- scope: Usage data\n  period: up to 24 months\n  text: 'Usage Data: retained for up to 24 months for analytics'\n- scope: Deleted accounts\n  period: within 30 days of account deletion\n  text: 'Deleted Accounts: data is removed within 30 days of account deletion'\nresidency:\n- region: European Union\n  text: Our database is hosted in the European Union.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): the EU Standard Contractual Clauses approved by the European Commission'\n- mechanism: DPF\n  text: or the EU-U.S. Data Privacy Framework where the provider is certified\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via email\n  text: You can also ask us to delete it, and exercise the other rights in section 12, at hello@applyra.io .\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Rectification:\
  \ Request correction of inaccurate data'\n- right: Erasure\n  text: 'Erasure: Request deletion of your data (\"right to be forgotten\")'\n- right: Portability\n  text: 'Portability: Request your data in a portable format'\n- right: Restriction\n  text: 'Restriction: Request limitation of data processing'\n- right: Objection\n  text: 'Objection: Object to certain data processing activities'\n- right: Complaint\n  text: 'Complaint: Lodge a complaint with a supervisory authority'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/applyra-io/privacy/applyra-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Applyra's own page on 2026-11-09.
synthetic: false
tags:
- ASO
- Mobile
- Analytics
- Artificial Intelligence
- Indie
---
