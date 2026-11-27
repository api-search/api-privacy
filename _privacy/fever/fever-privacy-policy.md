---
api_specs:
- filename: fever-authentication-api-openapi.yml
  format: yaml
  label: Fever Authentication API
  slug: fever-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-authentication-api-openapi.yml
- filename: fever-feverzone-api-openapi.yml
  format: yaml
  label: Fever FeverZone API
  slug: fever-feverzone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-feverzone-api-openapi.yml
- filename: fever-order-items-api-openapi.yml
  format: yaml
  label: Fever Order Items API
  slug: fever-order-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-order-items-api-openapi.yml
- filename: fever-plans-api-openapi.yml
  format: yaml
  label: Fever Plans API
  slug: fever-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-plans-api-openapi.yml
- filename: fever-sessions-api-openapi.yml
  format: yaml
  label: Fever Sessions API
  slug: fever-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fever/openapi/fever-sessions-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name and surname; email address; phone number (if you add it to your profile)
  - category: contact
    text: email address; phone number (if you add it to your profile)
  - category: location
    text: If you turn on location services, we may track your location using GPS technology
  - category: behavioral
    text: Information about your visit, interests and preferences, including the links you’ve clicked on, through and from Platform
  - category: device
    text: Technical information, including the Internet Protocol (IP) address used to connect your computer, mobile device or tablet to the internet
  - category: financial
    text: Details and information about the transactions such as the tickets purchased
  - category: communication
    text: records of our conversations and messages, if you contact us or we contact you (including records of phone calls)
  deletion:
    route: Privacy Form or Data Protection Officer
    text: Ask us to delete your Personal Data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision of Services and account administration
    text: Provision of our Services, account administration and informing about changes to our Services;
  - purpose: Fraud detection and prevention
    text: Detect and prevent fraud;
  - purpose: Personalised recommendations
    text: Provision of personalised recommendations and content within the Services by collecting data about you in order to build a profile of your preferences based on your activity when you use the Services.
  - purpose: Marketing communications
    text: Sending newsletters or promotional communications about news, sponsorships or future special events
  - purpose: Advertising effectiveness
    text: Determine the effectiveness of our promotional campaigns and advertising;
  residency:
  - region: EEA
    text: Fever aims to store your Personal Data in the EEA territory.
  - region: Argentina, Australia, Brazil, Mexico
    text: Fever utilises Amazon Web Services (Ireland) as its service provider for storing your Personal Data.
  retention:
  - period: two year period
    scope: Inactive accounts
    text: We may delete your Personal Data (including any account that you set up to use our Services) if you do not use the Services during a two year period.
  - period: 12 months
    scope: Persistent cookies
    text: They should not last longer than 12 months, but in practice, they could remain on your device much longer if you do not take action.
  rights:
  - right: Access
    text: Ask for a copy of your Personal Data
  - right: Correction
    text: Ask us to correct your Personal Data if you think it’s wrong, inaccurate or incomplete.
  - right: Erasure
    text: Ask us to delete your Personal Data
  - right: Objection to marketing and legitimate-interest processing
    text: Object (opt-out) the processing of your Personal Data for marketing purposes (including profiling)
  - right: Restriction
    text: Restrict the way that we process your Personal Data and ask us to suspend using your Personal Data.
  - right: Portability
    text: Ask us to transfer all your Personal Data to another company.
  - right: Withdraw consent
    text: Withdraw your consent or update your permissions .
  role:
    text: Fever is the “controller” or “business” in charge of processing your personal data when providing the Services.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: there are specific circumstances outlined in section 7 where Fever may share personal information in accordance with applicable exemptions
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Fever will conduct those data transfers in accordance with standard contractual clauses pre-approved by the European Commission.
  - mechanism: other
    text: make sure that a contract with strict data protection safeguards and clauses are in place before we transfer your Personal Data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fever
provenance_date: '2026-11-09'
provider_name: Fever
provider_slug: fever
slug: fever-privacy-policy
source_date: '2026-11-09'
source_filename: fever-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://feverup.com/legal/privacy_en.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fever\naid: fever\nurl: https://feverup.com/legal/privacy_en.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Fever is the “controller” or “business” in charge of processing your personal data when providing the Services.\ndata_categories:\n- category: identifying\n  text: your name and surname; email address; phone number (if you add it to your profile)\n- category: contact\n  text: email address; phone number (if you add it to your profile)\n- category: location\n  text: If you turn on location services, we may track your location using GPS technology\n- category: behavioral\n  text:\
  \ Information about your visit, interests and preferences, including the links you’ve clicked on, through\n    and from Platform\n- category: device\n  text: Technical information, including the Internet Protocol (IP) address used to connect your computer, mobile\n    device or tablet to the internet\n- category: financial\n  text: Details and information about the transactions such as the tickets purchased\n- category: communication\n  text: records of our conversations and messages, if you contact us or we contact you (including records of phone\n    calls)\npurposes:\n- purpose: Provision of Services and account administration\n  text: Provision of our Services, account administration and informing about changes to our Services;\n- purpose: Fraud detection and prevention\n  text: Detect and prevent fraud;\n- purpose: Personalised recommendations\n  text: Provision of personalised recommendations and content within the Services by collecting data about you in\n    order to build a profile\
  \ of your preferences based on your activity when you use the Services.\n- purpose: Marketing communications\n  text: Sending newsletters or promotional communications about news, sponsorships or future special events\n- purpose: Advertising effectiveness\n  text: Determine the effectiveness of our promotional campaigns and advertising;\nretention:\n- scope: Inactive accounts\n  period: two year period\n  text: We may delete your Personal Data (including any account that you set up to use our Services) if you do not\n    use the Services during a two year period.\n- scope: Persistent cookies\n  period: 12 months\n  text: They should not last longer than 12 months, but in practice, they could remain on your device much longer\n    if you do not take action.\nresidency:\n- region: EEA\n  text: Fever aims to store your Personal Data in the EEA territory.\n- region: Argentina, Australia, Brazil, Mexico\n  text: Fever utilises Amazon Web Services (Ireland) as its service provider for storing\
  \ your Personal Data.\ntransfers:\n- mechanism: SCC\n  text: Fever will conduct those data transfers in accordance with standard contractual clauses pre-approved by\n    the European Commission.\n- mechanism: other\n  text: make sure that a contract with strict data protection safeguards and clauses are in place before we transfer\n    your Personal Data\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy Form or Data Protection Officer\n  text: Ask us to delete your Personal Data\nrights:\n- right: Access\n  text: Ask for a copy of your Personal Data\n- right: Correction\n  text: Ask us to correct your Personal Data if you think it’s wrong, inaccurate or incomplete.\n- right: Erasure\n  text: Ask us to delete your Personal Data\n- right: Objection to marketing and legitimate-interest processing\n  text: Object (opt-out) the processing of your Personal Data for marketing purposes (including profiling)\n- right: Restriction\n\
  \  text: Restrict the way that we process your Personal Data and ask us to suspend using your Personal Data.\n- right: Portability\n  text: Ask us to transfer all your Personal Data to another company.\n- right: Withdraw consent\n  text: Withdraw your consent or update your permissions .\nsale_or_sharing:\n  stance: conditional\n  text: there are specific circumstances outlined in section 7 where Fever may share personal information in accordance\n    with applicable exemptions\n"
source_yaml_url: https://artifacts.apis.io/fever/privacy/fever-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Fever's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Live Entertainment
- Event
- Ticketing
- Experience
- Reporting
- MCP
---
