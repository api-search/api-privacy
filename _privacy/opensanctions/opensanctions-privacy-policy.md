---
api_specs:
- filename: opensanctions-data-access-api-openapi.yml
  format: yaml
  label: OpenSanctions Data access API
  slug: opensanctions-data-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-data-access-api-openapi.yml
- filename: opensanctions-matching-api-openapi.yml
  format: yaml
  label: OpenSanctions Matching API
  slug: opensanctions-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-matching-api-openapi.yml
- filename: opensanctions-reconciliation-api-openapi.yml
  format: yaml
  label: OpenSanctions Reconciliation API
  slug: opensanctions-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-reconciliation-api-openapi.yml
- filename: opensanctions-system-information-api-openapi.yml
  format: yaml
  label: OpenSanctions System information API
  slug: opensanctions-system-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opensanctions/openapi/opensanctions-system-information-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Company, address, bank details, as well as for our contact persons: salutation, first and last name, e-mail address, telephone number (landline and/or mobile).'
  - category: device
    text: IP address the subpages called up on the website, or the API URL requested
  - category: behavioral
    text: which sub-pages are called up and via which links or search terms visitors reach our website
  - category: location
    text: the country and location from which a user visited the website.
  - category: communication
    text: email address, selected newsletter(s), and the time of the subscription request and of the confirmation.
  - category: financial
    text: Company, address, bank details
  deletion:
    route: Contact us to have the information removed (authentication data) or unsubscribe for newsletters
    text: If you wish to end your use of the OpenSanctions API and other web site services that require the use of authentication, please contact us to have the information removed.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating website and ensuring stability and security
    text: The processing is carried out to enable the website to be called up and to ensure its stability and security.
  - purpose: Contract fulfilment and billing
    text: The data processing is carried out for the proper fulfillment and processing of the user contract.
  - purpose: Website analytics
    text: The processing takes place in order to be able to evaluate the use of our website.
  - purpose: Newsletters
    text: Newsletter subscription data is processed in order to send subscribed users information about product developments, data coverage, and technical changes to our services
  retention:
  - period: 90 days
    scope: Server log files
    text: Deletion of the log files takes place after 90 days.
  - period: 14 months
    scope: Google Analytics data
    text: The analysis data processed and stored with Google Analytics will be automatically deleted by us after 14 months.
  - period: three years
    scope: API usage records
    text: They are deleted after three years, corresponding to the regular limitation period for contractual claims.
  - period: up to seven days
    scope: Mailgun message content
    text: Mailgun retains message content for up to seven days and delivery metadata for up to 30 days.
  rights:
  - right: Information
    text: You have the right to request confirmation from us as to whether we are processing personal data relating to you.
  - right: Correction
    text: You have the right to request from us without undue delay the rectification of any inaccurate personal data concerning you
  - right: Deletion
    text: You have the right to request that we delete personal data concerning you without undue delay
  - right: Restriction
    text: You have the right to request us to restrict processing if one of the conditions listed in Art. 18 GDPR applies
  - right: Portability
    text: You have the right, under the conditions set out in Art. 20 GDPR, to request that we hand over the data concerning you in a structured, common and machine-readable format.
  - right: Withdraw consent
    text: You have the right to revoke your consent at any time in the case of processing based on consent.
  - right: Complaint
    text: you have the right to lodge a complaint with a supervisory authority.
  - right: Object
    text: you have the right to object to this under the conditions set out in Art. 21 GDPR.
  role:
    text: 'Responsible for data processing is: OpenSanctions Datenbanken GmbH .'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: User data is processed exclusively by us and is not sold, lent or passed on to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: both providers are certified under the EU-U.S. Data Privacy Framework, for which the European Commission has issued an adequacy decision (Art. 45 GDPR).
  - mechanism: SCC
    text: the data processing agreements incorporated into both providers' terms of service include the EU standard contractual clauses (Art. 46 para. 2 lit. c GDPR)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OpenSanctions
provenance_date: '2026-11-10'
provider_name: OpenSanctions
provider_slug: opensanctions
slug: opensanctions-privacy-policy
source_date: '2026-11-10'
source_filename: opensanctions-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.opensanctions.org/docs/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OpenSanctions\naid: opensanctions\nurl: https://www.opensanctions.org/docs/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Responsible for data processing is: OpenSanctions Datenbanken GmbH .'\ndata_categories:\n- category: contact\n  text: 'Company, address, bank details, as well as for our contact persons: salutation, first and last name, e-mail\n    address, telephone number (landline and/or mobile).'\n- category: device\n  text: IP address the subpages called up on the website, or the API URL requested\n- category: behavioral\n  text: which sub-pages are called up and via which\
  \ links or search terms visitors reach our website\n- category: location\n  text: the country and location from which a user visited the website.\n- category: communication\n  text: email address, selected newsletter(s), and the time of the subscription request and of the confirmation.\n- category: financial\n  text: Company, address, bank details\npurposes:\n- purpose: Operating website and ensuring stability and security\n  text: The processing is carried out to enable the website to be called up and to ensure its stability and security.\n- purpose: Contract fulfilment and billing\n  text: The data processing is carried out for the proper fulfillment and processing of the user contract.\n- purpose: Website analytics\n  text: The processing takes place in order to be able to evaluate the use of our website.\n- purpose: Newsletters\n  text: Newsletter subscription data is processed in order to send subscribed users information about product developments,\n    data coverage, and technical\
  \ changes to our services\nretention:\n- scope: Server log files\n  period: 90 days\n  text: Deletion of the log files takes place after 90 days.\n- scope: Google Analytics data\n  period: 14 months\n  text: The analysis data processed and stored with Google Analytics will be automatically deleted by us after 14\n    months.\n- scope: API usage records\n  period: three years\n  text: They are deleted after three years, corresponding to the regular limitation period for contractual claims.\n- scope: Mailgun message content\n  period: up to seven days\n  text: Mailgun retains message content for up to seven days and delivery metadata for up to 30 days.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: both providers are certified under the EU-U.S. Data Privacy Framework, for which the European Commission\n    has issued an adequacy decision (Art. 45 GDPR).\n- mechanism: SCC\n  text: the data processing agreements incorporated into both providers' terms of service include the EU standard\n\
  \    contractual clauses (Art. 46 para. 2 lit. c GDPR)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us to have the information removed (authentication data) or unsubscribe for newsletters\n  text: If you wish to end your use of the OpenSanctions API and other web site services that require the use of\n    authentication, please contact us to have the information removed.\nrights:\n- right: Information\n  text: You have the right to request confirmation from us as to whether we are processing personal data relating\n    to you.\n- right: Correction\n  text: You have the right to request from us without undue delay the rectification of any inaccurate personal data\n    concerning you\n- right: Deletion\n  text: You have the right to request that we delete personal data concerning you without undue delay\n- right: Restriction\n  text: You have the right to request us to restrict processing if one of the conditions\
  \ listed in Art. 18 GDPR\n    applies\n- right: Portability\n  text: You have the right, under the conditions set out in Art. 20 GDPR, to request that we hand over the data\n    concerning you in a structured, common and machine-readable format.\n- right: Withdraw consent\n  text: You have the right to revoke your consent at any time in the case of processing based on consent.\n- right: Complaint\n  text: you have the right to lodge a complaint with a supervisory authority.\n- right: Object\n  text: you have the right to object to this under the conditions set out in Art. 21 GDPR.\nsale_or_sharing:\n  stance: prohibited\n  text: User data is processed exclusively by us and is not sold, lent or passed on to third parties.\n"
source_yaml_url: https://artifacts.apis.io/opensanctions/privacy/opensanctions-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from OpenSanctions's own page on 2026-11-10.
synthetic: false
tags:
- Sanctions Screening
- AML
- Politically Exposed Persons
- Compliance
- Financial Crime
- KYC
- Entity Resolution
- Open Data
- Risk Data
- Due Diligence
- Public APIs
- Agent-Native
---
