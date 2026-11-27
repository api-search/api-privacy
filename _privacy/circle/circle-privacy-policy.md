---
api_specs:
- filename: circle-audit-logs-api-openapi.yml
  format: yaml
  label: Circle Audit Logs API
  slug: circle-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/circle/openapi/circle-audit-logs-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes first name, middle name, maiden name, last name, title, tax ID, marital status, date of birth, gender, identity document number, nationality
  - category: contact
    text: Contact Data includes billing address, residential address, email address, telephone numbers and correspondence records.
  - category: financial
    text: Financial Data includes bank account details, source of funds, source of wealth and credit history, investment history, financial position and returns.
  - category: location
    text: Location Data includes information about your device location.
  - category: behavioral
    text: Usage Data includes information about how you use the Circle Services.
  - category: device
    text: Technical Data includes your internet protocol (IP) address, login data, browser type and version, time zone setting and location
  - category: communication
    text: Marketing and Communications Data includes your preferences in receiving marketing from us and our third parties and your communication preferences.
  deletion:
    route: Request deletion
    text: This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Circle Services
    text: We collect all of the information in Section 2 (The Data we Collect About You) so that we can provide you with the Circle Services.
  - purpose: Verify identity and prevent fraud
    text: Verify your identity so that we can prevent fraud or unauthorized activity, and to comply with applicable laws
  - purpose: Improve and personalize services and advertising
    text: We may combine your information with information we collect from other companies and use it to improve and personalize the Circle Services, as well as our content and advertising.
  retention:
  - period: null
    scope: Personal data generally
    text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it for, including for the purposes of satisfying any legal, accounting, regulatory or reporting requirements.
  rights:
  - right: Access
    text: Request access This enables you to receive a copy of whether your personal data is being processed or collected
  - right: Correction
    text: Request correction This enables you to have any incomplete or inaccurate data we hold about you corrected
  - right: Deletion
    text: Request deletion This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.
  - right: Object to processing
    text: Object to processing You have the right to object to the processing of your personal data where we are relying on a legitimate interest
  - right: Restriction
    text: Request restriction on processing This enables you to ask us to suspend the processing of your personal data in the following scenarios
  - right: Portability
    text: Request for data portability If you ask us, we will provide to you or a third party you have chosen, your personal data in a structured, commonly used, machine-readable format.
  - right: Withdraw consent
    text: Withdrawal of consent This applies where we are relying on consent to process your personal data.
  - right: Opt-out of sale and sharing (California)
    text: You may request to opt out of any “sale” or “sharing” of your personal information that may take place.
  role:
    text: Circle Internet Financial, LLC is the controller of your personal data
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Circle discloses personal information to third parties for its targeted advertising and data analytics purposes. These disclosures may be considered “selling” and/or “sharing” of personal information.
  subprocessors:
    text: A list of affiliates and partners that act as sub-processors for Circle who may process your personal data is available here.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the Standard Contractual Clauses (SCCs) to provide an adequate level of data protection for the transfer of your Personal Data from Cayman Islands, EEA, UK, or Switzerland
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Circle
provenance_date: '2026-11-09'
provider_name: Circle
provider_slug: circle
slug: circle-privacy-policy
source_date: '2026-11-09'
source_filename: circle-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.circle.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Circle\naid: circle\nurl: https://www.circle.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Circle Internet Financial, LLC is the controller of your personal data\ndata_categories:\n- category: identifying\n  text: Identity Data includes first name, middle name, maiden name, last name, title, tax ID, marital status, date\n    of birth, gender, identity document number, nationality\n- category: contact\n  text: Contact Data includes billing address, residential address, email address, telephone numbers and correspondence\n    records.\n- category: financial\n  text:\
  \ Financial Data includes bank account details, source of funds, source of wealth and credit history, investment\n    history, financial position and returns.\n- category: location\n  text: Location Data includes information about your device location.\n- category: behavioral\n  text: Usage Data includes information about how you use the Circle Services.\n- category: device\n  text: Technical Data includes your internet protocol (IP) address, login data, browser type and version, time\n    zone setting and location\n- category: communication\n  text: Marketing and Communications Data includes your preferences in receiving marketing from us and our third\n    parties and your communication preferences.\npurposes:\n- purpose: Provide Circle Services\n  text: We collect all of the information in Section 2 (The Data we Collect About You) so that we can provide you\n    with the Circle Services.\n- purpose: Verify identity and prevent fraud\n  text: Verify your identity so that we can prevent\
  \ fraud or unauthorized activity, and to comply with applicable\n    laws\n- purpose: Improve and personalize services and advertising\n  text: We may combine your information with information we collect from other companies and use it to improve and\n    personalize the Circle Services, as well as our content and advertising.\nretention:\n- scope: Personal data generally\n  period: null\n  text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it\n    for, including for the purposes of satisfying any legal, accounting, regulatory or reporting requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on the Standard Contractual Clauses (SCCs) to provide an adequate level of data protection for the\n    transfer of your Personal Data from Cayman Islands, EEA, UK, or Switzerland\nsubprocessors:\n  url: null\n  text: A list of affiliates and partners that act as sub-processors for Circle who may process your personal data\n\
  \    is available here.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion\n  text: This enables you to ask us to delete or remove personal data where there is no good reason for us continuing\n    to process it.\nrights:\n- right: Access\n  text: Request access This enables you to receive a copy of whether your personal data is being processed or collected\n- right: Correction\n  text: Request correction This enables you to have any incomplete or inaccurate data we hold about you corrected\n- right: Deletion\n  text: Request deletion This enables you to ask us to delete or remove personal data where there is no good reason\n    for us continuing to process it.\n- right: Object to processing\n  text: Object to processing You have the right to object to the processing of your personal data where we are relying\n    on a legitimate interest\n- right: Restriction\n  text: Request restriction on processing This enables you to ask us to suspend the processing\
  \ of your personal\n    data in the following scenarios\n- right: Portability\n  text: Request for data portability If you ask us, we will provide to you or a third party you have chosen, your\n    personal data in a structured, commonly used, machine-readable format.\n- right: Withdraw consent\n  text: Withdrawal of consent This applies where we are relying on consent to process your personal data.\n- right: Opt-out of sale and sharing (California)\n  text: You may request to opt out of any “sale” or “sharing” of your personal information that may take place.\nsale_or_sharing:\n  stance: conditional\n  text: Circle discloses personal information to third parties for its targeted advertising and data analytics purposes.\n    These disclosures may be considered “selling” and/or “sharing” of personal information.\n"
source_yaml_url: https://artifacts.apis.io/circle/privacy/circle-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Circle's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Compliance
- Cross-Chain
- Currency
- Money
- Payments
- Stablecoins
- Transfers
- USDC
- Wallets
- Stablecoin Issuance
---
