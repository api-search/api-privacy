---
api_specs:
- filename: openapi.json
  format: json
  label: A-du API
  slug: a-du-api
  spec_type: OpenAPI
  url: https://a-du.homes/openapi.json
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full legal name
  - category: contact
    text: Email address and phone number
  - category: financial
    text: Bank account information for payment processing (stored by Stripe)
  - category: location
    text: IP address and geolocation data
  - category: device
    text: Mobile device identifiers (IDFA, Android Advertising ID)
  - category: demographic
    text: Date of birth
  - category: behavioral
    text: Click-stream data and interaction patterns
  - category: communication
    text: Messages exchanged through the A-du Platform
  deletion:
    route: Privacy request by email, phone, online portal or mail
    text: Right to Delete You have the right to request deletion of your personal information that we collected from you, subject to certain exceptions
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Platform operations
    text: Create and manage Member accounts
  - purpose: Payment processing
    text: Process rent payments and A-du's fees and surcharges
  - purpose: Trust and safety
    text: Conduct background and credit checks
  - purpose: Platform improvement
    text: Develop new features and services
  - purpose: Marketing
    text: Send marketing communications (with your consent)
  retention:
  - period: 90 days
    scope: Closed accounts
    text: Most information deleted within 90 days of account closure, except as required for legal compliance
  - period: 7 years
    scope: Transaction records
    text: 'Transaction Records: Retained for 7 years for tax and accounting purposes'
  - period: 3 years
    scope: Communications
    text: Messages retained for 3 years after rental completion
  - period: 5 years
    scope: Identity verification
    text: Verification records retained for 5 years for compliance
  - period: 7 years
    scope: Background checks
    text: 'Background Checks: Retained for 7 years per FCRA requirements'
  rights:
  - right: Right to know
    text: 'Right to Know You have the right to request disclosure of: (1) the categories of personal information we collected about you'
  - right: Right to delete
    text: Right to Delete You have the right to request deletion of your personal information that we collected from you
  - right: Right to correct
    text: Right to Correct You have the right to request correction of inaccurate personal information we maintain about you.
  - right: Right to limit sensitive personal information
    text: Right to Limit the Use and Disclosure of Sensitive Personal Information (Cal. Civ. Code § 1798.121)
  - right: Right to non-discrimination
    text: Right to Non-Discrimination You have the right to not receive discriminatory treatment for exercising your CCPA/CPRA privacy rights.
  role:
    text: A-du, LLC ("A-du," "we," "us," or "our") is committed to protecting your privacy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: A-du does not sell your personal information. We do not share your information for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: A-du, LLC
provenance_date: '2026-11-09'
provider_name: A-du, LLC
provider_slug: a-du-homes
slug: a-du-homes-privacy-policy
source_date: '2026-11-09'
source_filename: a-du-homes-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://a-du.homes/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: A-du, LLC\naid: a-du-homes\nurl: https://a-du.homes/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: A-du, LLC (\"A-du,\" \"we,\" \"us,\" or \"our\") is committed to protecting your privacy\ndata_categories:\n- category: identifying\n  text: Full legal name\n- category: contact\n  text: Email address and phone number\n- category: financial\n  text: Bank account information for payment processing (stored by Stripe)\n- category: location\n  text: IP address and geolocation data\n- category: device\n  text: Mobile device identifiers (IDFA, Android Advertising ID)\n- category: demographic\n\
  \  text: Date of birth\n- category: behavioral\n  text: Click-stream data and interaction patterns\n- category: communication\n  text: Messages exchanged through the A-du Platform\npurposes:\n- purpose: Platform operations\n  text: Create and manage Member accounts\n- purpose: Payment processing\n  text: Process rent payments and A-du's fees and surcharges\n- purpose: Trust and safety\n  text: Conduct background and credit checks\n- purpose: Platform improvement\n  text: Develop new features and services\n- purpose: Marketing\n  text: Send marketing communications (with your consent)\nretention:\n- scope: Closed accounts\n  period: 90 days\n  text: Most information deleted within 90 days of account closure, except as required for legal compliance\n- scope: Transaction records\n  period: 7 years\n  text: 'Transaction Records: Retained for 7 years for tax and accounting purposes'\n- scope: Communications\n  period: 3 years\n  text: Messages retained for 3 years after rental completion\n\
  - scope: Identity verification\n  period: 5 years\n  text: Verification records retained for 5 years for compliance\n- scope: Background checks\n  period: 7 years\n  text: 'Background Checks: Retained for 7 years per FCRA requirements'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy request by email, phone, online portal or mail\n  text: Right to Delete You have the right to request deletion of your personal information that we collected from\n    you, subject to certain exceptions\nrights:\n- right: Right to know\n  text: 'Right to Know You have the right to request disclosure of: (1) the categories of personal information we\n    collected about you'\n- right: Right to delete\n  text: Right to Delete You have the right to request deletion of your personal information that we collected from\n    you\n- right: Right to correct\n  text: Right to Correct You have the right to request\
  \ correction of inaccurate personal information we maintain\n    about you.\n- right: Right to limit sensitive personal information\n  text: Right to Limit the Use and Disclosure of Sensitive Personal Information (Cal. Civ. Code § 1798.121)\n- right: Right to non-discrimination\n  text: Right to Non-Discrimination You have the right to not receive discriminatory treatment for exercising your\n    CCPA/CPRA privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: A-du does not sell your personal information. We do not share your information for cross-context behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/a-du-homes/privacy/a-du-homes-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from A-du, LLC's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Property Management
- ADU
- Rentals
- Construction
---
