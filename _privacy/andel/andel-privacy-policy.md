---
api_specs:
- filename: andel-purchases-api-openapi.yml
  format: yaml
  label: Andel Purchases API
  slug: andel-purchases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andel/openapi/andel-purchases-api-openapi.yml
- filename: andel-webhooks-api-openapi.yml
  format: yaml
  label: Andel Webhooks API
  slug: andel-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andel/openapi/andel-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: your first and last name, email address, telephone number, postal address, education or work history or background
  - category: device
    text: information about your web browser (e.g., browser type, domain names, access times, and operating system); “IP address”
  deletion:
    route: email request to privacy@andel.org
    text: If you would like your Personal Information to be permanently removed from our database, please contact us by email at privacy@andel.org .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing and communicating about products and services
    text: providing or communicating with you regarding our products and services (including responding to any inquiry or order you have initiated)
  - purpose: fraud and risk prevention
    text: helping us screen for and prevent potential risk and fraud (in particular, through any IP address we collect from you)
  - purpose: analytics and marketing assessment
    text: generating analytics about how our customers browse and interact with our Site; assessing the success of any marketing or advertising campaigns
  - purpose: processing job applications
    text: processing job applications
  residency:
  - region: United States
    text: Andel and its servers are located and operate in the United States, subject to the applicable state and federal laws of the United States.
  retention:
  - period: null
    scope: Personal Information
    text: Unless you ask us to delete your Personal Information sooner, we will maintain it until such time that we determine, in our sole discretion, that (1) it is no longer necessary for any purpose for which Andel may use it in accordance with this Policy
  rights:
  - right: access and correction
    text: allow you to access, review, correct, or add to your Personal Information held in our database
  - right: deletion
    text: Request that we delete Personal Information that pertains to you.
  - right: withdraw consent
    text: Fully or partially withdraw your consent to the collection, processing, and/or transfer of your Personal Information.
  - right: complaint to supervisory authority
    text: you have the right to complain to your local data protection supervisory authority.
  role:
    text: Andel Co-op, Inc. (“Andel”) and its subsidiaries, including Andel Pharmacy, LLC, collects, uses, and/or shares personal information
    value: controller
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
name: Andel
provenance_date: '2026-11-09'
provider_name: Andel
provider_slug: andel
slug: andel-privacy-policy
source_date: '2026-11-09'
source_filename: andel-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.andel.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Andel\naid: andel\nurl: https://www.andel.org/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Andel Co-op, Inc. (“Andel”) and its subsidiaries, including Andel Pharmacy, LLC, collects, uses, and/or\n    shares personal information\ndata_categories:\n- category: identifying\n  text: your first and last name, email address, telephone number, postal address, education or work history or\n    background\n- category: device\n  text: information about your web browser (e.g., browser type, domain names, access times, and operating system);\n    “IP address”\npurposes:\n- purpose: providing\
  \ and communicating about products and services\n  text: providing or communicating with you regarding our products and services (including responding to any inquiry\n    or order you have initiated)\n- purpose: fraud and risk prevention\n  text: helping us screen for and prevent potential risk and fraud (in particular, through any IP address we collect\n    from you)\n- purpose: analytics and marketing assessment\n  text: generating analytics about how our customers browse and interact with our Site; assessing the success of\n    any marketing or advertising campaigns\n- purpose: processing job applications\n  text: processing job applications\nretention:\n- scope: Personal Information\n  period: null\n  text: Unless you ask us to delete your Personal Information sooner, we will maintain it until such time that we\n    determine, in our sole discretion, that (1) it is no longer necessary for any purpose for which Andel may use\n    it in accordance with this Policy\nresidency:\n- region:\
  \ United States\n  text: Andel and its servers are located and operate in the United States, subject to the applicable state and\n    federal laws of the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy@andel.org\n  text: If you would like your Personal Information to be permanently removed from our database, please contact\n    us by email at privacy@andel.org .\nrights:\n- right: access and correction\n  text: allow you to access, review, correct, or add to your Personal Information held in our database\n- right: deletion\n  text: Request that we delete Personal Information that pertains to you.\n- right: withdraw consent\n  text: Fully or partially withdraw your consent to the collection, processing, and/or transfer of your Personal\n    Information.\n- right: complaint to supervisory authority\n  text: you have the right to complain to your local data protection\
  \ supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/andel/privacy/andel-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 14 quoted statements, read from Andel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Pharmacy Benefits
- Drug Pricing
- Specialty Medications
- Data Exchange
- Webhook
---
