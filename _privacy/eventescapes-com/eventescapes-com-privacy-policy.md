---
api_specs:
- filename: eventescapes-com-events-api-openapi.yml
  format: yaml
  label: Event Escapes Events API
  slug: eventescapes-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-events-api-openapi.yml
- filename: eventescapes-com-experiences-api-openapi.yml
  format: yaml
  label: Event Escapes Experiences API
  slug: eventescapes-com-experiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-experiences-api-openapi.yml
- filename: eventescapes-com-packages-api-openapi.yml
  format: yaml
  label: Event Escapes Packages API
  slug: eventescapes-com-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-packages-api-openapi.yml
- filename: eventescapes-com-payment-links-api-openapi.yml
  format: yaml
  label: Event Escapes Payment Links API
  slug: eventescapes-com-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventescapes-com/openapi/eventescapes-com-payment-links-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and contact details
  - category: financial
    text: Payment details are processed securely by our third-party payment providers. We do not store full card details.
  - category: health
    text: Health or medical-related information (e.g. special assistance requests)
  - category: behavioral
    text: Usage data (pages visited, searches, interactions)
  - category: location
    text: Approximate location (via IP address)
  - category: device
    text: Device and browser information
  - category: communication
    text: Communications (support requests, emails)
  deletion:
    route: email privacy@eventescapes.com
    text: Request deletion (subject to legal obligations)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Process and fulfil bookings
    text: Process and fulfil bookings
  - purpose: Send marketing communications
    text: Send marketing communications (where you have opted in)
  - purpose: Detect fraud and maintain platform security
    text: Detect fraud and maintain platform security
  residency:
  - region: Australia or overseas
    text: We store personal information in secure systems operated by us and trusted third-party providers, which may be located in Australia or overseas.
  - region: United States
    text: These countries may include the United States
  retention:
  - period: up to 7 years
    scope: Booking and financial records
    text: 'Booking and financial records: up to 7 years'
  - period: until deletion is requested
    scope: User accounts
    text: 'User accounts: until deletion is requested'
  - period: up to 3 years
    scope: Support records
    text: 'Support records: up to 3 years'
  rights:
  - right: access
    text: Access your personal information
  - right: correction
    text: Request corrections
  - right: deletion
    text: Request deletion (subject to legal obligations)
  - right: opt out of sale or sharing
    text: opt out of the “sale” or “sharing” of personal information and of targeted advertising
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Aside from the advertising disclosures described above (which you can opt out of), we do not share your personal information for third parties’ own marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Both providers are certified under the EU–US Data Privacy Framework, and we rely on their standard data-processing terms for these transfers.
  - mechanism: other
    text: We take reasonable steps to ensure overseas recipients do not breach the Australian Privacy Principles.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Event Escapes
provenance_date: '2026-11-09'
provider_name: Event Escapes
provider_slug: eventescapes-com
slug: eventescapes-com-privacy-policy
source_date: '2026-11-09'
source_filename: eventescapes-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eventescapes.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Event Escapes\naid: eventescapes-com\nurl: https://eventescapes.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, and contact details\n- category: financial\n  text: Payment details are processed securely by our third-party payment providers. We do not store full card details.\n- category: health\n  text: Health or medical-related information (e.g. special assistance requests)\n- category: behavioral\n  text: Usage data (pages visited, searches, interactions)\n- category: location\n  text: Approximate location\
  \ (via IP address)\n- category: device\n  text: Device and browser information\n- category: communication\n  text: Communications (support requests, emails)\npurposes:\n- purpose: Process and fulfil bookings\n  text: Process and fulfil bookings\n- purpose: Send marketing communications\n  text: Send marketing communications (where you have opted in)\n- purpose: Detect fraud and maintain platform security\n  text: Detect fraud and maintain platform security\nretention:\n- scope: Booking and financial records\n  period: up to 7 years\n  text: 'Booking and financial records: up to 7 years'\n- scope: User accounts\n  period: until deletion is requested\n  text: 'User accounts: until deletion is requested'\n- scope: Support records\n  period: up to 3 years\n  text: 'Support records: up to 3 years'\nresidency:\n- region: Australia or overseas\n  text: We store personal information in secure systems operated by us and trusted third-party providers, which\n    may be located in Australia or overseas.\n\
  - region: United States\n  text: These countries may include the United States\ntransfers:\n- mechanism: DPF\n  text: Both providers are certified under the EU–US Data Privacy Framework, and we rely on their standard data-processing\n    terms for these transfers.\n- mechanism: other\n  text: We take reasonable steps to ensure overseas recipients do not breach the Australian Privacy Principles.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@eventescapes.com\n  text: Request deletion (subject to legal obligations)\nrights:\n- right: access\n  text: Access your personal information\n- right: correction\n  text: Request corrections\n- right: deletion\n  text: Request deletion (subject to legal obligations)\n- right: opt out of sale or sharing\n  text: opt out of the “sale” or “sharing” of personal information and of targeted advertising\nsale_or_sharing:\n  stance: conditional\n  text: Aside from the advertising\
  \ disclosures described above (which you can opt out of), we do not share your\n    personal information for third parties’ own marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/eventescapes-com/privacy/eventescapes-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Event Escapes's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Event
- Ticketing
- Hotels
- Sports
---
