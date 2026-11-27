---
api_specs:
- filename: sanas-stream-asyncapi.yml
  format: yaml
  label: Sanas Stream API
  slug: sanas-stream-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/sanas/asyncapi/sanas-stream-asyncapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, password, and, if applicable, your company name.
  - category: device
    text: Your Internet protocol (IP) address, device identifiers, cookie identifiers, browser information (e.g. language settings, time zone, system), location information
  - category: biometric
    text: Physiological, biological, or behavioral, characteristics and voice recordings.
  - category: financial
    text: Your name and purchases, and payment information that a third party vendor of Sanas will have.
  - category: communication
    text: Your name, email address and whatever other personal information you may have provided to us.
  - category: behavioral
    text: pages that you visit before, during and after using our website, information about the links you click
  deletion:
    route: Email privacy@sanas.ai
    text: 'You can request deletion of your data associated with your account by emailing us here: privacy@sanas.ai'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products and services
    text: 'We use your information to provide you with services such as: Managing your information and accounts'
  - purpose: Marketing
    text: Generate and maintain leads as part of our customer relationship management database.
  - purpose: Product improvement
    text: Improving, upgrading or enhancing our products and services
  residency:
  - region: Worldwide
    text: All information processed by us may be transferred, processed, and stored anywhere in the world, including, but not limited to, the United States or other countries
  retention:
  - period: null
    scope: General personal information
    text: We retain your personal information for varying durations depending on the category of personal information and your relationship with us.
  rights:
  - right: Access
    text: Access Personal Information about you
  - right: Correction
    text: Request Correction of your personal information where it is inaccurate or incomplete.
  - right: Deletion
    text: Request Deletion of your personal information;
  - right: Objection/restriction
    text: Request Restriction of or Object to our processing of your personal information
  - right: Withdraw consent
    text: Withdraw your Consent to our processing of your personal information.
  role:
    text: In general, Sanas, headquartered in Palo Alto, is the data controller processing your personal information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers to Sanas subsidiaries and service providers outside UK, where Adequacy decision is not available, we use standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sanas
provenance_date: '2026-11-10'
provider_name: Sanas
provider_slug: sanas
slug: sanas-privacy-policy
source_date: '2026-11-10'
source_filename: sanas-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sanas.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sanas\naid: sanas\nurl: https://www.sanas.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: In general, Sanas, headquartered in Palo Alto, is the data controller processing your personal information.\ndata_categories:\n- category: identifying\n  text: Your name, email address, password, and, if applicable, your company name.\n- category: device\n  text: Your Internet protocol (IP) address, device identifiers, cookie identifiers, browser information (e.g. language\n    settings, time zone, system), location information\n- category: biometric\n  text: Physiological, biological,\
  \ or behavioral, characteristics and voice recordings.\n- category: financial\n  text: Your name and purchases, and payment information that a third party vendor of Sanas will have.\n- category: communication\n  text: Your name, email address and whatever other personal information you may have provided to us.\n- category: behavioral\n  text: pages that you visit before, during and after using our website, information about the links you click\npurposes:\n- purpose: Provide products and services\n  text: 'We use your information to provide you with services such as: Managing your information and accounts'\n- purpose: Marketing\n  text: Generate and maintain leads as part of our customer relationship management database.\n- purpose: Product improvement\n  text: Improving, upgrading or enhancing our products and services\nretention:\n- scope: General personal information\n  period: null\n  text: We retain your personal information for varying durations depending on the category of personal\
  \ information\n    and your relationship with us.\nresidency:\n- region: Worldwide\n  text: All information processed by us may be transferred, processed, and stored anywhere in the world, including,\n    but not limited to, the United States or other countries\ntransfers:\n- mechanism: SCC\n  text: For transfers to Sanas subsidiaries and service providers outside UK, where Adequacy decision is not available,\n    we use standard contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@sanas.ai\n  text: 'You can request deletion of your data associated with your account by emailing us here: privacy@sanas.ai'\nrights:\n- right: Access\n  text: Access Personal Information about you\n- right: Correction\n  text: Request Correction of your personal information where it is inaccurate or incomplete.\n- right: Deletion\n  text: Request Deletion of your personal information;\n- right: Objection/restriction\n\
  \  text: Request Restriction of or Object to our processing of your personal information\n- right: Withdraw consent\n  text: Withdraw your Consent to our processing of your personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/sanas/privacy/sanas-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Sanas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Speech AI
- Voice AI
- Accent Translation
- Language Translation
- Speech Enhancement
- Real-Time Audio
- SDK
- WebSocket
- Contact Center
- Real-Time
---
