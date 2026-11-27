---
api_specs:
- filename: evaboot-com-account-api-openapi.yml
  format: yaml
  label: Evaboot Account API
  slug: evaboot-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-account-api-openapi.yml
- filename: evaboot-com-email-finder-api-openapi.yml
  format: yaml
  label: Evaboot Email Finder API
  slug: evaboot-com-email-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-email-finder-api-openapi.yml
- filename: evaboot-com-email-verifier-api-openapi.yml
  format: yaml
  label: Evaboot Email Verifier API
  slug: evaboot-com-email-verifier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-email-verifier-api-openapi.yml
- filename: evaboot-com-linkedin-extraction-api-openapi.yml
  format: yaml
  label: Evaboot LinkedIn Extraction API
  slug: evaboot-com-linkedin-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-linkedin-extraction-api-openapi.yml
- filename: evaboot-com-search-builder-api-openapi.yml
  format: yaml
  label: Evaboot Search Builder API
  slug: evaboot-com-search-builder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evaboot-com/openapi/evaboot-com-search-builder-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, electronic identification data (incl. when you sign up through Google or Outlook) and LinkedIn account usage data
  - category: device
    text: IP address, browser user agent and device identifier recorded when you sign up, log in, subscribe, are charged or cancel
  - category: behavioral
    text: We may also collect information about how your device has interacted with our Website, including the pages accessed and links clicked.
  - category: location
    text: broad geographic location (e.g. country or city-level location)
  - category: identifying
    text: Name and surname, email address
  deletion:
    route: Contact privacy@evaboot.com to request deletion
    text: If you wish to access, correct, update or request deletion of your Personal Data, you can do so at any time by contacting us at privacy@evaboot.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing services to clients
    text: Providing our services to our clients (including free-trial users), including managing the access to our services and enabling the pooling feature
  - purpose: Marketing updates
    text: Sending you marketing updates and messages regarding our services
  - purpose: Fraud prevention and payment disputes
    text: Preventing fraud and answering payment disputes (chargebacks) raised with our payment provider
  - purpose: Internal analytics
    text: We use this information for our internal analytics purposes and to improve the quality and relevance of our Website to our visitors.
  residency:
  - region: United States
    text: our servers are located in the United States
  - region: EU and United States
    text: our third party service providers operate in the EU and the United States
  retention:
  - period: 2 years
    scope: Customer data
    text: We retain customer data for no longer than 2 years following the end of our contractual relationship.
  - period: 10 years
    scope: Accounting data
    text: we will retain the personal data related to accounting for no longer than 10 years
  - period: at least 18 months
    scope: Fraud and payment dispute identifiers
    text: We keep the IP addresses, user agents and device identifiers recorded for fraud prevention and payment disputes for at least 18 months
  rights:
  - right: Access, correction, deletion
    text: If you wish to access, correct, update or request deletion of your Personal Data, you can do so at any time by contacting us at privacy@evaboot.com .
  - right: Object, restriction, portability
    text: you can object to processing of your Personal Data, ask us to restrict processing of your Personal Data or request portability of your Personal Data
  - right: Withdraw consent
    text: If we have collected and process your Personal Data with your consent, then you can withdraw your consent at any time.
  - right: Opt-out of marketing
    text: You have the right to opt-out of marketing communications we send you at any time.
  - right: Complain to authority
    text: you have the right to complain to a data protection authority about our collection and use of your Personal Data
  role:
    text: acts as the data controller for the Personal Data collected via the Website and the Extension
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: These include implementing the European Commission's Standard Contractual Clauses for transfers of Personal Data with our third party service providers and partners.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Evaboot
provenance_date: '2026-11-09'
provider_name: Evaboot
provider_slug: evaboot-com
slug: evaboot-com-privacy-policy
source_date: '2026-11-09'
source_filename: evaboot-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://evaboot.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Evaboot\naid: evaboot-com\nurl: https://evaboot.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: acts as the data controller for the Personal Data collected via the Website and the Extension\ndata_categories:\n- category: contact\n  text: Email address, electronic identification data (incl. when you sign up through Google or Outlook) and LinkedIn\n    account usage data\n- category: device\n  text: IP address, browser user agent and device identifier recorded when you sign up, log in, subscribe, are charged\n    or cancel\n- category: behavioral\n  text: We may also collect\
  \ information about how your device has interacted with our Website, including the pages\n    accessed and links clicked.\n- category: location\n  text: broad geographic location (e.g. country or city-level location)\n- category: identifying\n  text: Name and surname, email address\npurposes:\n- purpose: Providing services to clients\n  text: Providing our services to our clients (including free-trial users), including managing the access to our\n    services and enabling the pooling feature\n- purpose: Marketing updates\n  text: Sending you marketing updates and messages regarding our services\n- purpose: Fraud prevention and payment disputes\n  text: Preventing fraud and answering payment disputes (chargebacks) raised with our payment provider\n- purpose: Internal analytics\n  text: We use this information for our internal analytics purposes and to improve the quality and relevance of\n    our Website to our visitors.\nretention:\n- scope: Customer data\n  period: 2 years\n  text: We\
  \ retain customer data for no longer than 2 years following the end of our contractual relationship.\n- scope: Accounting data\n  period: 10 years\n  text: we will retain the personal data related to accounting for no longer than 10 years\n- scope: Fraud and payment dispute identifiers\n  period: at least 18 months\n  text: We keep the IP addresses, user agents and device identifiers recorded for fraud prevention and payment disputes\n    for at least 18 months\nresidency:\n- region: United States\n  text: our servers are located in the United States\n- region: EU and United States\n  text: our third party service providers operate in the EU and the United States\ntransfers:\n- mechanism: SCC\n  text: These include implementing the European Commission's Standard Contractual Clauses for transfers of Personal\n    Data with our third party service providers and partners.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact\
  \ privacy@evaboot.com to request deletion\n  text: If you wish to access, correct, update or request deletion of your Personal Data, you can do so at any time\n    by contacting us at privacy@evaboot.com .\nrights:\n- right: Access, correction, deletion\n  text: If you wish to access, correct, update or request deletion of your Personal Data, you can do so at any time\n    by contacting us at privacy@evaboot.com .\n- right: Object, restriction, portability\n  text: you can object to processing of your Personal Data, ask us to restrict processing of your Personal Data\n    or request portability of your Personal Data\n- right: Withdraw consent\n  text: If we have collected and process your Personal Data with your consent, then you can withdraw your consent\n    at any time.\n- right: Opt-out of marketing\n  text: You have the right to opt-out of marketing communications we send you at any time.\n- right: Complain to authority\n  text: you have the right to complain to a data protection\
  \ authority about our collection and use of your Personal\n    Data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/evaboot-com/privacy/evaboot-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from Evaboot's own page on 2026-11-09.
synthetic: false
tags:
- Lead Generation
- Sales
- Data Cleaning
- Email Verification
- Chrome Extension
---
