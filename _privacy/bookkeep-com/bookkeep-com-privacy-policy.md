---
api_specs:
- filename: bookkeep-com-entities-api-openapi.yml
  format: yaml
  label: Bookkeep.com Entities API
  slug: bookkeep-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bookkeep-com/openapi/bookkeep-com-entities-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact and account data ,such as your first and last name, email address, business role, phone number, and plan tier.
  - category: financial
    text: Payment and transaction data . This information is collected and processed by our payment service provider, Stripe, in accordance with its privacy policy
  - category: device
    text: Device data ,such as your computer’s or mobile device’s operating system type and version, manufacturer and model, browser type
  - category: location
    text: general location information such as city, state or geographic area.
  - category: behavioral
    text: Online activity data ,such as pages or screens you viewed, how long you spent on a page or screen
  - category: communication
    text: Feedback or correspondence , such as information you provide when you contact us with questions, feedback, or otherwise correspond with us
  deletion:
    route: email privacy@bookkeep.com or contact us
    text: You may also request that we access, update or delete your information by contacting us at the information provided below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: Provide, operate, maintain, secure and improve our Services; Fulfill transactions initiated by you;
  - purpose: Research and development
    text: we may create and use aggregated, de-identified or other anonymous data from personal information we process.
  - purpose: Marketing and advertising
    text: 'We may use personal information for marketing and advertising purposes, including:'
  - purpose: Compliance and protection
    text: Comply with applicable laws, lawful requests, and legal process
  residency:
  - region: United States
    text: We have personnel and use service providers located in the United States. To provide our Services and operate our website, it is necessary for us to process personal information in the United States.
  retention:
  - period: null
    scope: personal information
    text: We retain personal information for as long as necessary to fulfill the purposes for which we collected it
  rights:
  - right: access
    text: Provide you with information about our processing of your personal information and give you access to your personal information.
  - right: deletion
    text: Delete your personal information.
  - right: portability
    text: Transfer a machine-readable copy of your personal information to you or a third party of your choice.
  - right: restriction
    text: Restrict the processing of your personal information.
  - right: objection
    text: Object to our reliance on legitimate interests as the basis of our processing of your personal data
  role:
    text: Where Bookkeep processes this personal information on behalf of our business customers, as a service provider and / or data processor, the terms of our agreement with those business customers will govern.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: such as standard contractual clauses, the individual’s consent, or in other circumstances permitted by European data protection law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bookkeep.com
provenance_date: '2026-11-09'
provider_name: Bookkeep.com
provider_slug: bookkeep-com
slug: bookkeep-com-privacy-policy
source_date: '2026-11-09'
source_filename: bookkeep-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bookkeep.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bookkeep.com\naid: bookkeep-com\nurl: https://www.bookkeep.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where Bookkeep processes this personal information on behalf of our business customers, as a service provider\n    and / or data processor, the terms of our agreement with those business customers will govern.\ndata_categories:\n- category: contact\n  text: Contact and account data ,such as your first and last name, email address, business role, phone number,\n    and plan tier.\n- category: financial\n  text: Payment and transaction data . This information is collected and\
  \ processed by our payment service provider,\n    Stripe, in accordance with its privacy policy\n- category: device\n  text: Device data ,such as your computer’s or mobile device’s operating system type and version, manufacturer\n    and model, browser type\n- category: location\n  text: general location information such as city, state or geographic area.\n- category: behavioral\n  text: Online activity data ,such as pages or screens you viewed, how long you spent on a page or screen\n- category: communication\n  text: Feedback or correspondence , such as information you provide when you contact us with questions, feedback,\n    or otherwise correspond with us\npurposes:\n- purpose: Service delivery\n  text: Provide, operate, maintain, secure and improve our Services; Fulfill transactions initiated by you;\n- purpose: Research and development\n  text: we may create and use aggregated, de-identified or other anonymous data from personal information we process.\n- purpose: Marketing and\
  \ advertising\n  text: 'We may use personal information for marketing and advertising purposes, including:'\n- purpose: Compliance and protection\n  text: Comply with applicable laws, lawful requests, and legal process\nretention:\n- scope: personal information\n  period: null\n  text: We retain personal information for as long as necessary to fulfill the purposes for which we collected it\nresidency:\n- region: United States\n  text: We have personnel and use service providers located in the United States. To provide our Services and operate\n    our website, it is necessary for us to process personal information in the United States.\ntransfers:\n- mechanism: SCC\n  text: such as standard contractual clauses, the individual’s consent, or in other circumstances permitted by European\n    data protection law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@bookkeep.com or contact us\n  text: You may also\
  \ request that we access, update or delete your information by contacting us at the information\n    provided below.\nrights:\n- right: access\n  text: Provide you with information about our processing of your personal information and give you access to your\n    personal information.\n- right: deletion\n  text: Delete your personal information.\n- right: portability\n  text: Transfer a machine-readable copy of your personal information to you or a third party of your choice.\n- right: restriction\n  text: Restrict the processing of your personal information.\n- right: objection\n  text: Object to our reliance on legitimate interests as the basis of our processing of your personal data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bookkeep-com/privacy/bookkeep-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Bookkeep.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Automation
- Shopify
- E-Commerce
- Integration
---
