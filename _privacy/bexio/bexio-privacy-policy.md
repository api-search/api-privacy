---
api_specs:
- filename: bexio-accounting-api-openapi.yml
  format: yaml
  label: bexio Accounting API
  slug: bexio-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-accounting-api-openapi.yml
- filename: bexio-banking-api-openapi.yml
  format: yaml
  label: bexio Banking API
  slug: bexio-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-banking-api-openapi.yml
- filename: bexio-contacts-api-openapi.yml
  format: yaml
  label: bexio Contacts API
  slug: bexio-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-contacts-api-openapi.yml
- filename: bexio-files-api-openapi.yml
  format: yaml
  label: bexio Files API
  slug: bexio-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-files-api-openapi.yml
- filename: bexio-items-api-openapi.yml
  format: yaml
  label: bexio Items API
  slug: bexio-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-items-api-openapi.yml
- filename: bexio-payroll-api-openapi.yml
  format: yaml
  label: bexio Payroll API
  slug: bexio-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-payroll-api-openapi.yml
- filename: bexio-projects-api-openapi.yml
  format: yaml
  label: bexio Projects API
  slug: bexio-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-projects-api-openapi.yml
- filename: bexio-purchase-api-openapi.yml
  format: yaml
  label: bexio Purchase API
  slug: bexio-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-purchase-api-openapi.yml
- filename: bexio-sales-orders-api-openapi.yml
  format: yaml
  label: bexio Sales Orders API
  slug: bexio-sales-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bexio/openapi/bexio-sales-orders-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: the personal master data (name, address, email address) and the settings required for the service in question are usually collected
  - category: device
    text: IP address, MAC address of the smartphone or computer, information about your device and settings, cookies
  - category: financial
    text: The processed data also includes payment- and bank-specific information, such as IBAN, account information, etc.
  - category: behavioral
    text: pages and content accessed, functions used, referring website, location information
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract conclusion and processing
    text: We primarily use the personal data we collect to conclude and process our contracts with our customers and business partners
  - purpose: Offer and develop services
    text: To offer and further develop our offers, services and websites, apps and other platforms on which we are present
  - purpose: Advertising and marketing
    text: Advertising and marketing (including the organisation of events), insofar as you have not objected to the use of your data
  - purpose: Newsletter statistics
    text: The Provider evaluates this data for statistical purposes in order to better tailor the content of the newsletters to the interests of its customers.
  residency:
  - region: Switzerland
    text: All personal data of our customers that is stored in the bexio software will be stored and processed exclusively in Switzerland.
  retention:
  - period: null
    scope: Business relationship data
    text: We process and store your personal data for as long as it is necessary to fulfil our contractual and legal obligations
  - period: one month
    scope: Banking log data
    text: the Provider stores the following log data for a duration of one month when the banking features are used
  - period: twelve months or less
    scope: Operational data
    text: For operational data (e.g., system logs, other logs), generally shorter retention periods of twelve months or less apply.
  - period: null
    scope: Newsletter data
    text: The Provider stores the personal data deposited by customers for the purpose of receiving the newsletter until the customer unsubscribes from the newsletter.
  rights:
  - right: Access
    text: The right of access
  - right: Rectification
    text: The right to rectification;
  - right: Erasure
    text: The right to erasure;
  - right: Restriction of processing
    text: The right to restriction of processing;
  - right: Portability
    text: The right to data portability
  - right: Objection
    text: The right to object.
  role:
    text: 'The data controller responsible for data processing is: bexio AG Alte Jonastrasse 24 8640 Rapperswil Switzerland'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we contractually oblige the recipient to comply with the applicable data protection standards (for this, we use the revised standard contractual clauses of the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bexio
provenance_date: '2026-11-09'
provider_name: bexio
provider_slug: bexio
slug: bexio-privacy-policy
source_date: '2026-11-09'
source_filename: bexio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bexio.com/en-CH/policies/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bexio\naid: bexio\nurl: https://www.bexio.com/en-CH/policies/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller responsible for data processing is: bexio AG Alte Jonastrasse 24 8640 Rapperswil Switzerland'\ndata_categories:\n- category: identifying\n  text: the personal master data (name, address, email address) and the settings required for the service in question\n    are usually collected\n- category: device\n  text: IP address, MAC address of the smartphone or computer, information about your device and settings, cookies\n- category: financial\n  text: The\
  \ processed data also includes payment- and bank-specific information, such as IBAN, account information,\n    etc.\n- category: behavioral\n  text: pages and content accessed, functions used, referring website, location information\npurposes:\n- purpose: Contract conclusion and processing\n  text: We primarily use the personal data we collect to conclude and process our contracts with our customers and\n    business partners\n- purpose: Offer and develop services\n  text: To offer and further develop our offers, services and websites, apps and other platforms on which we are\n    present\n- purpose: Advertising and marketing\n  text: Advertising and marketing (including the organisation of events), insofar as you have not objected to the\n    use of your data\n- purpose: Newsletter statistics\n  text: The Provider evaluates this data for statistical purposes in order to better tailor the content of the newsletters\n    to the interests of its customers.\nretention:\n- scope: Business\
  \ relationship data\n  period: null\n  text: We process and store your personal data for as long as it is necessary to fulfil our contractual and legal\n    obligations\n- scope: Banking log data\n  period: one month\n  text: the Provider stores the following log data for a duration of one month when the banking features are used\n- scope: Operational data\n  period: twelve months or less\n  text: For operational data (e.g., system logs, other logs), generally shorter retention periods of twelve months\n    or less apply.\n- scope: Newsletter data\n  period: null\n  text: The Provider stores the personal data deposited by customers for the purpose of receiving the newsletter\n    until the customer unsubscribes from the newsletter.\nresidency:\n- region: Switzerland\n  text: All personal data of our customers that is stored in the bexio software will be stored and processed exclusively\n    in Switzerland.\ntransfers:\n- mechanism: SCC\n  text: we contractually oblige the recipient to\
  \ comply with the applicable data protection standards (for this,\n    we use the revised standard contractual clauses of the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: The right of access\n- right: Rectification\n  text: The right to rectification;\n- right: Erasure\n  text: The right to erasure;\n- right: Restriction of processing\n  text: The right to restriction of processing;\n- right: Portability\n  text: The right to data portability\n- right: Objection\n  text: The right to object.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bexio/privacy/bexio-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
summary_line: 21 quoted statements, read from bexio's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- ERP
- Invoicing
- Small Business
- Switzerland
---
