---
api_specs:
- filename: ecosio-approval-request-status-api-openapi.yml
  format: yaml
  label: ecosio Approval Request Status API
  slug: ecosio-approval-request-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-approval-request-status-api-openapi.yml
- filename: ecosio-archive-messages-api-openapi.yml
  format: yaml
  label: ecosio Archive messages API
  slug: ecosio-archive-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-archive-messages-api-openapi.yml
- filename: ecosio-check-user-credentials-api-openapi.yml
  format: yaml
  label: ecosio Check user credentials API
  slug: ecosio-check-user-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-check-user-credentials-api-openapi.yml
- filename: ecosio-companies-api-openapi.yml
  format: yaml
  label: ecosio Companies API
  slug: ecosio-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-companies-api-openapi.yml
- filename: ecosio-connectors-api-openapi.yml
  format: yaml
  label: ecosio Connectors API
  slug: ecosio-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-connectors-api-openapi.yml
- filename: ecosio-deliver-messages-to-the-hub-api-openapi.yml
  format: yaml
  label: ecosio Deliver messages to the Hub API
  slug: ecosio-deliver-messages-to-the-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-deliver-messages-to-the-hub-api-openapi.yml
- filename: ecosio-fetch-messages-from-the-hub-api-openapi.yml
  format: yaml
  label: ecosio Fetch messages from the Hub API
  slug: ecosio-fetch-messages-from-the-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-fetch-messages-from-the-hub-api-openapi.yml
- filename: ecosio-message-controller-api-openapi.yml
  format: yaml
  label: ecosio Message Controller API
  slug: ecosio-message-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-message-controller-api-openapi.yml
- filename: ecosio-request-the-documents-for-an-e-invoice-api-openapi.yml
  format: yaml
  label: ecosio Request the documents for an e-invoice API
  slug: ecosio-request-the-documents-for-an-e-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-request-the-documents-for-an-e-invoice-api-openapi.yml
- filename: ecosio-scenarios-api-openapi.yml
  format: yaml
  label: ecosio Scenarios API
  slug: ecosio-scenarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecosio/openapi/ecosio-scenarios-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data is information that can be directly linked to you. This includes, for example, information such as your name, e-mail address or telephone number.
  - category: device
    text: information about the internet browser used (technical information)
  - category: contact
    text: Business phone number Business email address
  deletion:
    route: null
    text: Every user is free to change the personal data provided during registration at any time or to have it completely deleted from our database.
  dpa:
    available: true
    text: The transfer of data for processing within and outside ecosio for the purpose of commissioned processing is based exclusively on commissioned processing agreements.
    url: null
  purposes:
  - purpose: Providing services and operating website
    text: To provide our services and operate our website and other communication channels, we process personal data of the users with whom we interact.
  - purpose: Sales prospecting
    text: We use prospecting to target potential customers on our platform and services.
  residency:
  - region: EU (status page)
    text: To meet high data protection standards, the ecosio status page relies on EU-based servers.
  retention:
  - period: thirty days
    scope: Website log files
    text: This data is only needed to analyze any malfunctions and is deleted within thirty days at the latest.
  - period: three years
    scope: Events photographs
    text: we do not keep personal photos publicly accessible for longer than three years and do not store them for longer than that.
  - period: six months
    scope: Job application documents
    text: Your documents will be automatically deleted six months after a rejection has been sent.
  - period: null
    scope: ecosio Monitor raw transactional data
    text: raw transactional data is retained within the active Monitor environment for a standard period of three (3) months
  rights:
  - right: Object to processing
    text: You also have the option to object directly to the data processing by Cognism (opt-out)
  - right: Withdraw consent
    text: Consent can be withdrawn at any time.
  role:
    text: 'Depending on which of our companies you interact with, the controller within the meaning of the EU General Data Protection Regulation (“GDPR”) and other national data protection laws, as well as other data protection provisions, is:'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the forwarding of personal data to Greenhouse takes place based on standard data protection clauses of the European Commission in accordance with Art 46 (2) lit c) GDPR.
  - mechanism: adequacy
    text: Data processing is based on the GDPR and the European Commission’s adequacy decision for the United Kingdom under Article 45(3) GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ecosio
provenance_date: '2026-11-09'
provider_name: ecosio
provider_slug: ecosio
slug: ecosio-privacy-policy
source_date: '2026-11-09'
source_filename: ecosio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ecosio.com/en/data-protection/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ecosio\naid: ecosio\nurl: https://ecosio.com/en/data-protection/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'Depending on which of our companies you interact with, the controller within the meaning of the EU General\n    Data Protection Regulation (“GDPR”) and other national data protection laws, as well as other data protection\n    provisions, is:'\ndata_categories:\n- category: identifying\n  text: Personal data is information that can be directly linked to you. This includes, for example, information\n    such as your name, e-mail address or telephone number.\n-\
  \ category: device\n  text: information about the internet browser used (technical information)\n- category: contact\n  text: Business phone number Business email address\npurposes:\n- purpose: Providing services and operating website\n  text: To provide our services and operate our website and other communication channels, we process personal data\n    of the users with whom we interact.\n- purpose: Sales prospecting\n  text: We use prospecting to target potential customers on our platform and services.\nretention:\n- scope: Website log files\n  period: thirty days\n  text: This data is only needed to analyze any malfunctions and is deleted within thirty days at the latest.\n- scope: Events photographs\n  period: three years\n  text: we do not keep personal photos publicly accessible for longer than three years and do not store them for\n    longer than that.\n- scope: Job application documents\n  period: six months\n  text: Your documents will be automatically deleted six months after\
  \ a rejection has been sent.\n- scope: ecosio Monitor raw transactional data\n  period: null\n  text: raw transactional data is retained within the active Monitor environment for a standard period of three\n    (3) months\nresidency:\n- region: EU (status page)\n  text: To meet high data protection standards, the ecosio status page relies on EU-based servers.\ntransfers:\n- mechanism: SCC\n  text: the forwarding of personal data to Greenhouse takes place based on standard data protection clauses of the\n    European Commission in accordance with Art 46 (2) lit c) GDPR.\n- mechanism: adequacy\n  text: Data processing is based on the GDPR and the European Commission’s adequacy decision for the United Kingdom\n    under Article 45(3) GDPR.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: The transfer of data for processing within and outside ecosio for the purpose of commissioned processing\n    is based exclusively on commissioned processing agreements.\n\
  deletion:\n  route: null\n  text: Every user is free to change the personal data provided during registration at any time or to have it completely\n    deleted from our database.\nrights:\n- right: Object to processing\n  text: You also have the option to object directly to the data processing by Cognism (opt-out)\n- right: Withdraw consent\n  text: Consent can be withdrawn at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ecosio/privacy/ecosio-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 17 quoted statements, read from ecosio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EDI
- E-Invoicing
- B2B Integration
- VAT Compliance
- Peppol
- Supply Chain
- Messaging
---
