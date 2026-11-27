---
api_specs:
- filename: penneo-case-file-creation-api-openapi.yml
  format: yaml
  label: Penneo Case File Creation API
  slug: penneo-case-file-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-case-file-creation-api-openapi.yml
- filename: penneo-oauth-api-openapi.yml
  format: yaml
  label: Penneo OAuth API
  slug: penneo-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-oauth-api-openapi.yml
- filename: penneo-penneo-collect-api-api-openapi.yml
  format: yaml
  label: Penneo Penneo Collect API
  slug: penneo-penneo-collect-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-penneo-collect-api-api-openapi.yml
- filename: penneo-queue-status-check-api-openapi.yml
  format: yaml
  label: Penneo Queue Status Check API
  slug: penneo-queue-status-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-queue-status-check-api-openapi.yml
- filename: penneo-version-api-openapi.yml
  format: yaml
  label: Penneo Version API
  slug: penneo-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-version-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: The types of data processed are the name, title, company and country.
  - category: identifying
    text: 'Types of personal data based on user type Penneo users and end-users: Name, email address, IP address'
  - category: financial
    text: We collect name and email address as essential billing information to process invoices and manage your account.
  - category: behavioral
    text: gather analytical data about website visitors’ behavior
  - category: identifying
    text: 'Penneo users and end-users- optional depending on the signing method selected: Job title, phone number, electronic ID information, national identification number'
  deletion:
    route: Request to Penneo or Customer; archive deletable by end-user within the archive
    text: End-users who have chosen to store their documents in a Penneo archive can request to have their archive and all documents stored therein deleted.
  dpa:
    available: true
    text: 'Data Processing Agreement can be found here: https://penneo.com/terms/ .'
    url: https://penneo.com/terms/
  purposes:
  - purpose: Website operation and analytics
    text: We use cookies to store website visitors’ preferences, keep our website operational, and gather analytical data about website visitors’ behavior.
  - purpose: Evaluating job applicants
    text: Penneo will process the personal data submitted by the job applicant for the purpose of evaluating the job applicant for a given position in Penneo.
  - purpose: Continuous product improvement
    text: for the purpose of continuously improving the user experience, the performance of the Platform as well as the product offering
  - purpose: Customer contact and product information
    text: Contact information is processed for the purpose of sharing relevant information about an active subscription, product offers and/or Platform features.
  residency:
  - region: EU
    text: Customer data processed in the Platform is stored in data centers in the EU.
  - region: EU
    text: All data is hosted within the EU.
  retention:
  - period: 6 months
    scope: Job applications
    text: Penneo will automatically delete job applications after 6 months unless the job applicant revokes consent earlier.
  - period: 2 years
    scope: User experience data
    text: The collected data is stored for 2 years.
  - period: 2 years
    scope: Support requests
    text: Penneo will automatically delete support requests after 2 years.
  - period: 90 days
    scope: Customer data after agreement
    text: Penneo will delete Customer’s data 90 days after the expiration of an Agreement with the Customer.
  rights:
  - right: access
    text: The right to access your data
  - right: rectification
    text: The right to rectification if any of your personal data is inaccurate or incomplete
  - right: erasure
    text: The right to erasure
  - right: restrict processing
    text: The right to restrict processing
  - right: portability
    text: The right to data portability, when technically feasible
  - right: object
    text: The right to object
  - right: withdraw consent
    text: The right to withdraw consent
  - right: lodge complaint
    text: The right to lodge a complaint
  role:
    text: 'The Customer assumes the role of data controller. Penneo assumes the role of data processor. Exception in the Penneo archive: Penneo will assume the role as data controller'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Penneo does not sell, trade, or otherwise attempt to monetise personal data that is processed through any of the processes mentioned in this privacy policy.
  subprocessors:
    text: 'Recipient: CRM systems, e.g. Hubspot, Salesforce, Aircall. Processing within the EU and US.'
    url: null
  transfers:
  - mechanism: DPF
    text: Data Privacy Framework applied to US vendors and thus covered by adequacy decision.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Penneo
provenance_date: '2026-11-10'
provider_name: Penneo
provider_slug: penneo
slug: penneo-privacy-policy
source_date: '2026-11-10'
source_filename: penneo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://penneo.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Penneo\naid: penneo\nurl: https://penneo.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'The Customer assumes the role of data controller. Penneo assumes the role of data processor. Exception\n    in the Penneo archive: Penneo will assume the role as data controller'\ndata_categories:\n- category: contact\n  text: The types of data processed are the name, title, company and country.\n- category: identifying\n  text: 'Types of personal data based on user type Penneo users and end-users: Name, email address, IP address'\n- category: financial\n  text: We collect name and email\
  \ address as essential billing information to process invoices and manage your account.\n- category: behavioral\n  text: gather analytical data about website visitors’ behavior\n- category: identifying\n  text: 'Penneo users and end-users- optional depending on the signing method selected: Job title, phone number,\n    electronic ID information, national identification number'\npurposes:\n- purpose: Website operation and analytics\n  text: We use cookies to store website visitors’ preferences, keep our website operational, and gather analytical\n    data about website visitors’ behavior.\n- purpose: Evaluating job applicants\n  text: Penneo will process the personal data submitted by the job applicant for the purpose of evaluating the job\n    applicant for a given position in Penneo.\n- purpose: Continuous product improvement\n  text: for the purpose of continuously improving the user experience, the performance of the Platform as well as\n    the product offering\n- purpose: Customer\
  \ contact and product information\n  text: Contact information is processed for the purpose of sharing relevant information about an active subscription,\n    product offers and/or Platform features.\nretention:\n- scope: Job applications\n  period: 6 months\n  text: Penneo will automatically delete job applications after 6 months unless the job applicant revokes consent\n    earlier.\n- scope: User experience data\n  period: 2 years\n  text: The collected data is stored for 2 years.\n- scope: Support requests\n  period: 2 years\n  text: Penneo will automatically delete support requests after 2 years.\n- scope: Customer data after agreement\n  period: 90 days\n  text: Penneo will delete Customer’s data 90 days after the expiration of an Agreement with the Customer.\nresidency:\n- region: EU\n  text: Customer data processed in the Platform is stored in data centers in the EU.\n- region: EU\n  text: All data is hosted within the EU.\ntransfers:\n- mechanism: DPF\n  text: Data Privacy Framework\
  \ applied to US vendors and thus covered by adequacy decision.\nsubprocessors:\n  url: null\n  text: 'Recipient: CRM systems, e.g. Hubspot, Salesforce, Aircall. Processing within the EU and US.'\ndpa:\n  available: true\n  url: https://penneo.com/terms/\n  text: 'Data Processing Agreement can be found here: https://penneo.com/terms/ .'\ndeletion:\n  route: Request to Penneo or Customer; archive deletable by end-user within the archive\n  text: End-users who have chosen to store their documents in a Penneo archive can request to have their archive\n    and all documents stored therein deleted.\nrights:\n- right: access\n  text: The right to access your data\n- right: rectification\n  text: The right to rectification if any of your personal data is inaccurate or incomplete\n- right: erasure\n  text: The right to erasure\n- right: restrict processing\n  text: The right to restrict processing\n- right: portability\n  text: The right to data portability, when technically feasible\n- right:\
  \ object\n  text: The right to object\n- right: withdraw consent\n  text: The right to withdraw consent\n- right: lodge complaint\n  text: The right to lodge a complaint\nsale_or_sharing:\n  stance: prohibited\n  text: Penneo does not sell, trade, or otherwise attempt to monetise personal data that is processed through any\n    of the processes mentioned in this privacy policy.\n"
source_yaml_url: https://artifacts.apis.io/penneo/privacy/penneo-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Penneo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Signing
- eIDAS
- Compliance
---
