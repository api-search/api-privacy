---
api_specs:
- filename: candid-lookup-api-openapi.yml
  format: yaml
  label: Candid Lookup API
  slug: candid-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/candid/openapi/candid-lookup-api-openapi.yml
- filename: candid-essentials-api-openapi.yml
  format: yaml
  label: Candid Essentials API
  slug: candid-essentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/candid/openapi/candid-essentials-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: we will ask you to provide certain personally identifying information, including your name and email address.
  - category: financial
    text: as well as your credit card billing information, in order to process the donation.
  - category: device
    text: Stripe also collects identifying information about the devices that connect to its services
  - category: behavioral
    text: The information collected may include usage information, such as the numbers and frequency of users to the Websites, pages visited, web browsing histories, your location and device, social networking activities and similar data.
  deletion:
    route: email request
    text: You may access, correct, or request deletion of your Personal Information – or request that we stop any processing of your Personal Information – by contacting us at customersuccess@candid.org .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate services
    text: To provide and operate the Websites and services (including, e.g., any services or functionality enabled by artificial intelligence or “AI”).
  - purpose: marketing
    text: To send you marketing and promotional communications, including suggestions for additional products or services.
  - purpose: AI model improvement
    text: By interacting with the services described herein that are powered by AI, you agree and acknowledge that your Personal Information, and data generated through your use of these services, may be used to train and improve Candid’s AI functionality.
  residency:
  - region: United States
    text: our Websites are hosted in the United States and are governed by United States law.
  retention:
  - period: null
    scope: account and relationship data
    text: We will retain your Personal Information for as long as your account is active or as needed to provide you services, or otherwise as is reasonable and customary given the nature of the relationship you have with Candid.
  rights:
  - right: access
    text: 'Access: You may have the right to know what Personal Information we have collected about you and to receive a copy of such data.'
  - right: deletion
    text: 'Deletion: You may have the right to delete your Personal Information that we have obtained, subject to certain exceptions.'
  - right: correction
    text: 'Correction: You may have the right to correct inaccuracies in your Personal Information.'
  - right: data portability
    text: 'Data portability: You may have the right to receive a copy of your information in a portable and readily usable format.'
  - right: opt out of certain processing
    text: 'Opt out of certain processing: You may have the right to opt out of the processing of your Personal Information for purposes of (a) targeted advertising, (b), the sale of your Personal Information; or (c) profiling in furtherance of decisions that produce legal or similarly significant effect concerning you.'
  role:
    text: null
    value: unstated
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
name: Candid
provenance_date: '2026-11-09'
provider_name: Candid
provider_slug: candid
slug: candid-privacy-policy
source_date: '2026-11-09'
source_filename: candid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://candid.org/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Candid\naid: candid\nurl: https://candid.org/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we will ask you to provide certain personally identifying information, including your name and email address.\n- category: financial\n  text: as well as your credit card billing information, in order to process the donation.\n- category: device\n  text: Stripe also collects identifying information about the devices that connect to its services\n- category: behavioral\n  text: The information collected may include usage information, such\
  \ as the numbers and frequency of users to the\n    Websites, pages visited, web browsing histories, your location and device, social networking activities and\n    similar data.\npurposes:\n- purpose: provide and operate services\n  text: To provide and operate the Websites and services (including, e.g., any services or functionality enabled\n    by artificial intelligence or “AI”).\n- purpose: marketing\n  text: To send you marketing and promotional communications, including suggestions for additional products or services.\n- purpose: AI model improvement\n  text: By interacting with the services described herein that are powered by AI, you agree and acknowledge that\n    your Personal Information, and data generated through your use of these services, may be used to train and improve\n    Candid’s AI functionality.\nretention:\n- scope: account and relationship data\n  period: null\n  text: We will retain your Personal Information for as long as your account is active or as needed to\
  \ provide you\n    services, or otherwise as is reasonable and customary given the nature of the relationship you have with Candid.\nresidency:\n- region: United States\n  text: our Websites are hosted in the United States and are governed by United States law.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: You may access, correct, or request deletion of your Personal Information – or request that we stop any\n    processing of your Personal Information – by contacting us at customersuccess@candid.org .\nrights:\n- right: access\n  text: 'Access: You may have the right to know what Personal Information we have collected about you and to receive\n    a copy of such data.'\n- right: deletion\n  text: 'Deletion: You may have the right to delete your Personal Information that we have obtained, subject to\n    certain exceptions.'\n- right: correction\n  text: 'Correction: You may have\
  \ the right to correct inaccuracies in your Personal Information.'\n- right: data portability\n  text: 'Data portability: You may have the right to receive a copy of your information in a portable and readily\n    usable format.'\n- right: opt out of certain processing\n  text: 'Opt out of certain processing: You may have the right to opt out of the processing of your Personal Information\n    for purposes of (a) targeted advertising, (b), the sale of your Personal Information; or (c) profiling in furtherance\n    of decisions that produce legal or similarly significant effect concerning you.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/candid/privacy/candid-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 15 quoted statements, read from Candid's own page on 2026-11-09.
synthetic: false
tags:
- Charities
- Donations
- Non-Profit
- Philanthropy
- Foundations
- Grants
- 990s
- Demographics
---
