---
api_specs:
- filename: ariba-sourcing-approval-tasks-api-openapi.yml
  format: yaml
  label: Ariba Sourcing Approval Tasks API
  slug: ariba-sourcing-approval-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba-sourcing/openapi/ariba-sourcing-approval-tasks-api-openapi.yml
- filename: ariba-sourcing-documents-api-openapi.yml
  format: yaml
  label: Ariba Sourcing Documents API
  slug: ariba-sourcing-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba-sourcing/openapi/ariba-sourcing-documents-api-openapi.yml
- filename: ariba-sourcing-groups-api-openapi.yml
  format: yaml
  label: Ariba Sourcing Groups API
  slug: ariba-sourcing-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba-sourcing/openapi/ariba-sourcing-groups-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: 'SAP processes the following categories of personal data as contact data: first name, last name, email addresses, postal address/location (country, state/province, city), telephone numbers, and your relationship history with SAP.'
  - category: financial
    text: If you provide a credit card number or bank details to order products or services, SAP will collect this information to process your payment for the requested products or services.
  - category: device
    text: SAP processes certain user-related information, e.g., info regarding your browser, operating system, or your IP address when you visit SAP’s web properties.
  - category: behavioral
    text: We also process information regarding your use of our web offerings, like the pages you visit, the amount of time you spend on a page, the page which has referred you to our page and the links on our sites you select.
  - category: health
    text: In connection with the registration for an event, SAP may ask for your dietary preferences or information about possible disabilities for purposes of consideration for the health and well-being of our guests.
  deletion:
    route: DSR Intake Request form
    text: If you want to exercise your data subject rights under applicable data protection law, then please fill out and submit the DSR Intake Request form .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: business relationships
    text: pursue its business relationships with you, your employer, or your employer’s customers
  - purpose: web services operation
    text: SAP processes personal data for the purpose of operating, providing to you and administering your use of SAP’s internet pages, web offerings, or other online events.
  - purpose: security and compliance
    text: ensure compliance with statutory laws and regulations applicable to SAP
  retention:
  - period: null
    scope: general
    text: SAP stores your personal data only for as long as it is required
  rights:
  - right: access
    text: Access your personal data that we have on you, or have it updated.
  - right: deletion
    text: Delete your personal data we hold about you.
  - right: restriction
    text: 'Request from SAP to restrict your Personal Data from further processing in any of the following events:'
  - right: objection
    text: Object to SAP further processing your personal data , if and to the extent SAP is processing your personal data based on its legitimate interest.
  - right: consent withdrawal
    text: Revoke consent , wherever SAP is processing your personal data based on your consent, you may at any time withdraw your consent by unsubscribing or giving us respective notice of withdrawal.
  - right: complaint
    text: Lodge a complaint to the competent supervisory authority if you are not satisfied with how SAP is processing your personal data.
  role:
    text: Who is the Data Protection Officer of the Controller?
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: SAP uses the EU standard contractual clauses to contractually require the data importer to ensure a level of data protection consistent with the one in the EEA to protect your personal data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ariba Sourcing
provenance_date: '2026-11-09'
provider_name: Ariba Sourcing
provider_slug: ariba-sourcing
slug: ariba-sourcing-privacy-policy
source_date: '2026-11-09'
source_filename: ariba-sourcing-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sap.com/about/legal/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ariba Sourcing\naid: ariba-sourcing\nurl: https://www.sap.com/about/legal/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Who is the Data Protection Officer of the Controller?\ndata_categories:\n- category: contact\n  text: 'SAP processes the following categories of personal data as contact data: first name, last name, email addresses,\n    postal address/location (country, state/province, city), telephone numbers, and your relationship history with\n    SAP.'\n- category: financial\n  text: If you provide a credit card number or bank details to order products\
  \ or services, SAP will collect this\n    information to process your payment for the requested products or services.\n- category: device\n  text: SAP processes certain user-related information, e.g., info regarding your browser, operating system, or\n    your IP address when you visit SAP’s web properties.\n- category: behavioral\n  text: We also process information regarding your use of our web offerings, like the pages you visit, the amount\n    of time you spend on a page, the page which has referred you to our page and the links on our sites you select.\n- category: health\n  text: In connection with the registration for an event, SAP may ask for your dietary preferences or information\n    about possible disabilities for purposes of consideration for the health and well-being of our guests.\npurposes:\n- purpose: business relationships\n  text: pursue its business relationships with you, your employer, or your employer’s customers\n- purpose: web services operation\n  text: SAP processes\
  \ personal data for the purpose of operating, providing to you and administering your use of\n    SAP’s internet pages, web offerings, or other online events.\n- purpose: security and compliance\n  text: ensure compliance with statutory laws and regulations applicable to SAP\nretention:\n- scope: general\n  period: null\n  text: SAP stores your personal data only for as long as it is required\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: SAP uses the EU standard contractual clauses to contractually require the data importer to ensure a level\n    of data protection consistent with the one in the EEA to protect your personal data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DSR Intake Request form\n  text: If you want to exercise your data subject rights under applicable data protection law, then please fill\n    out and submit the DSR Intake Request form .\nrights:\n- right: access\n  text: Access your personal\
  \ data that we have on you, or have it updated.\n- right: deletion\n  text: Delete your personal data we hold about you.\n- right: restriction\n  text: 'Request from SAP to restrict your Personal Data from further processing in any of the following events:'\n- right: objection\n  text: Object to SAP further processing your personal data , if and to the extent SAP is processing your personal\n    data based on its legitimate interest.\n- right: consent withdrawal\n  text: Revoke consent , wherever SAP is processing your personal data based on your consent, you may at any time\n    withdraw your consent by unsubscribing or giving us respective notice of withdrawal.\n- right: complaint\n  text: Lodge a complaint to the competent supervisory authority if you are not satisfied with how SAP is processing\n    your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ariba-sourcing/privacy/ariba-sourcing-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from Ariba Sourcing's own page on 2026-11-09.
synthetic: false
tags:
- Approvals
- Auctions
- B2B
- Contracts
- Procurement
- RFx
- SAP
- Sourcing
- Supplier Management
- Supply Chain
---
