---
api_specs:
- filename: confrere-room-api-openapi.yml
  format: yaml
  label: Confrere Room API
  slug: confrere-room-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confrere/openapi/confrere-room-api-openapi.yml
- filename: confrere-token-api-openapi.yml
  format: yaml
  label: Confrere Token API
  slug: confrere-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confrere/openapi/confrere-token-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Name Phone number Payment details if you pay by card
  - category: identifying
    text: Personal identification number (if you are located in Scandinavia)
  - category: financial
    text: Payment details
  - category: device
    text: Browser, browser version, and language Location Operating system and device
  - category: location
    text: Country/city level location (or the location of your IP address)
  - category: communication
    text: Support chat conversation history (in Zendesk)
  - category: professional
    text: Organization or place of work
  deletion:
    route: Contact us to request deletion
    text: You have the right to be deleted and forgotten, with a small exception for billing and payment data, which we are lawfully required to keep.
  dpa:
    available: null
    text: Looking for the DPA (data processing agreement) or BAA (business associate agreement)? Head on over to the Terms of service
    url: null
  purposes:
  - purpose: Provide video call service
    text: Confrere (the responsible body) lets you make video calls through a web browser on any modern web-enabled device.
  - purpose: Technical support
    text: In case you require technical support in connection with your call, we enable the chat tool Zendesk.
  - purpose: Billing and invoicing
    text: We do invoicing through Tripletex EU GDPR 6.1.b
  - purpose: Website statistics
    text: we use Matomo (a privacy-first web analytics tool) to track your browsing.
  residency:
  - region: EU
    text: Elastx Hosting of video infrastructure EU GDPR 6.1.b
  - region: USA
    text: USA (data is stored in the USA only if the customer resides there)
  retention:
  - period: 3 months
    scope: Visitor call data
    text: We retain this data for 3 months unless otherwise specified by the professional organization.
  - period: 5 years
    scope: Transaction data
    text: Transaction data is stored for 5 years.
  - period: 9 months
    scope: Support metadata
    text: Metadata such as this is automatically deleted after 9 months.
  - period: 90 days
    scope: Contact data after account ends
    text: If the customer relationship ends, we keep your contact data for another 90 days before we delete it from our systems
  rights:
  - right: Access
    text: You have the right to know exactly what data we have collected about you.
  - right: Rectification
    text: You have the right to change and update your information if what we have is incorrect.
  - right: Portability
    text: You have the right to move your data to another provider.
  - right: Erasure
    text: You have the right to be deleted and forgotten
  - right: Complain to authority
    text: You have the right to complain to a government instance about how we use data.
  role:
    text: Confrere (the responsible body) lets you make video calls through a web browser
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Stripe (for EEA residents) - Contact information - Financial info
    url: null
  transfers:
  - mechanism: SCC
    text: If data is transferred or stored outside of the EU, we ensure that the transfer is in compliance with Applicable Data Protection Law and protected by standard contractual clauses (SCC).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Confrere
provenance_date: '2026-11-09'
provider_name: Confrere
provider_slug: confrere
slug: confrere-privacy-policy
source_date: '2026-11-09'
source_filename: confrere-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://confrere.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Confrere\naid: confrere\nurl: https://confrere.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Confrere (the responsible body) lets you make video calls through a web browser\ndata_categories:\n- category: contact\n  text: Name Phone number Payment details if you pay by card\n- category: identifying\n  text: Personal identification number (if you are located in Scandinavia)\n- category: financial\n  text: Payment details\n- category: device\n  text: Browser, browser version, and language Location Operating system and device\n- category: location\n  text: Country/city level location\
  \ (or the location of your IP address)\n- category: communication\n  text: Support chat conversation history (in Zendesk)\n- category: professional\n  text: Organization or place of work\npurposes:\n- purpose: Provide video call service\n  text: Confrere (the responsible body) lets you make video calls through a web browser on any modern web-enabled\n    device.\n- purpose: Technical support\n  text: In case you require technical support in connection with your call, we enable the chat tool Zendesk.\n- purpose: Billing and invoicing\n  text: We do invoicing through Tripletex EU GDPR 6.1.b\n- purpose: Website statistics\n  text: we use Matomo (a privacy-first web analytics tool) to track your browsing.\nretention:\n- scope: Visitor call data\n  period: 3 months\n  text: We retain this data for 3 months unless otherwise specified by the professional organization.\n- scope: Transaction data\n  period: 5 years\n  text: Transaction data is stored for 5 years.\n- scope: Support metadata\n  period:\
  \ 9 months\n  text: Metadata such as this is automatically deleted after 9 months.\n- scope: Contact data after account ends\n  period: 90 days\n  text: If the customer relationship ends, we keep your contact data for another 90 days before we delete it from\n    our systems\nresidency:\n- region: EU\n  text: Elastx Hosting of video infrastructure EU GDPR 6.1.b\n- region: USA\n  text: USA (data is stored in the USA only if the customer resides there)\ntransfers:\n- mechanism: SCC\n  text: If data is transferred or stored outside of the EU, we ensure that the transfer is in compliance with Applicable\n    Data Protection Law and protected by standard contractual clauses (SCC).\nsubprocessors:\n  url: null\n  text: Stripe (for EEA residents) - Contact information - Financial info\ndpa:\n  available: null\n  url: null\n  text: Looking for the DPA (data processing agreement) or BAA (business associate agreement)? Head on over to the\n    Terms of service\ndeletion:\n  route: Contact us to\
  \ request deletion\n  text: You have the right to be deleted and forgotten, with a small exception for billing and payment data, which\n    we are lawfully required to keep.\nrights:\n- right: Access\n  text: You have the right to know exactly what data we have collected about you.\n- right: Rectification\n  text: You have the right to change and update your information if what we have is incorrect.\n- right: Portability\n  text: You have the right to move your data to another provider.\n- right: Erasure\n  text: You have the right to be deleted and forgotten\n- right: Complain to authority\n  text: You have the right to complain to a government instance about how we use data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/confrere/privacy/confrere-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Confrere's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Video Conferencing
- Communications
- Healthcare
- Telehealth
- Embeddable
- WebRTC
---
