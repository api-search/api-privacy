---
api_specs:
- filename: zayo-maintenance-cases-api-openapi.yml
  format: yaml
  label: Zayo Maintenance Cases API
  slug: zayo-maintenance-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-maintenance-cases-api-openapi.yml
- filename: zayo-network-discovery-api-openapi.yml
  format: yaml
  label: Zayo Network Discovery API
  slug: zayo-network-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-network-discovery-api-openapi.yml
- filename: zayo-order-api-openapi.yml
  format: yaml
  label: Zayo Order API
  slug: zayo-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-order-api-openapi.yml
- filename: zayo-product-catalog-api-openapi.yml
  format: yaml
  label: Zayo Product Catalog API
  slug: zayo-product-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-product-catalog-api-openapi.yml
- filename: zayo-quote-api-openapi.yml
  format: yaml
  label: Zayo Quote API
  slug: zayo-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-quote-api-openapi.yml
- filename: zayo-service-inventory-api-openapi.yml
  format: yaml
  label: Zayo Service Inventory API
  slug: zayo-service-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-service-inventory-api-openapi.yml
- filename: zayo-ticket-catalog-api-openapi.yml
  format: yaml
  label: Zayo Ticket Catalog API
  slug: zayo-ticket-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-ticket-catalog-api-openapi.yml
- filename: zayo-ticketing-api-openapi.yml
  format: yaml
  label: Zayo Ticketing API
  slug: zayo-ticketing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zayo/openapi/zayo-ticketing-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Information required by Zayo to enable communications with customers, administer customer accounts, and in accordance with contractual obligations is limited to name, business address, telephone number, job title, and email address.
  - category: biometric
    text: Zayo collects government issued identity information (e.g., drivers license, passport), palm or fingerprint biometric identifiers, and CCTV video image.
  - category: device
    text: collects website visitor information in the form of generic website statistics and cookies including device, operating system and browser type, country and time zone indicators and other system settings.
  - category: identifying
    text: Zayo collects data that is captured through system logging and data flow management systems including, but not limited to, source and destination Internet Protocol [IP] addresses and domain name
  deletion:
    route: contact privacy.office@zayo.com
    text: To update, correct, or remove personal data or to object to the processing of your information related to website visit or web application support, please contact us at privacy.office@zayo.com
  dpa:
    available: true
    text: Zayo has prepared a Data Processor Addendum (“DPA”) in accordance with GDPR Article 28.
    url: null
  purposes:
  - purpose: contract administration
    text: Zayo processes Personal Data contact information as necessary for the performance of Offerings pursuant to a contract between Zayo and its customer.
  - purpose: physical security controls
    text: Identity information is collected to authenticate individuals based on customer approvals.
  - purpose: network traffic monitoring
    text: Zayo monitors and processes network traffic data consistent with its legitimate interests to support the offerings provided pursuant to a contract between Zayo and its Customer, to ensure the integrity of services and to support security incident and event management functions.
  - purpose: website and marketing
    text: Zayo processes website visitor information and contact information with our legitimate interest to offer and provide products and services
  residency:
  - region: United States
    text: Personal Data transferred to Zayo subprocessors are stored on infrastructure located in the United States.
  retention:
  - period: 7 years after account termination
    scope: contact and website application information
    text: Zayo retains Personal Data contact information and website application information for as long as the Customer maintains an active account and for 7 years after account termination
  - period: 30 days
    scope: CCTV images
    text: CCTV images are kept up to 30 days after which they are deleted.
  - period: 90 days
    scope: network traffic data
    text: Zayo retains network traffic data for 90 days, then archived for 1 year before being deleted.
  - period: for the life of the website in an archive
    scope: generic website statistics
    text: Zayo retains website visitor information related to generic website statistics for the life of the website in an archive.
  rights:
  - right: access
    text: The right to access your personal information
  - right: erasure
    text: The right to the erasure of your personal information
  - right: data portability
    text: The right to data portability
  - right: opt out of sale (CCPA)
    text: The right to opt out of the sale of your personal information (under CCPA)
  role:
    text: Through the Cloud Services Offering, Zayo is acting in the role of a processor on behalf of the Customer (the controller).
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Zayo does provide Personal Data, limited to name, contact information, and title, to its subprocessors to fulfill its obligations to its customers, and for administrative purposes.
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses under GDPR where applicable
  - mechanism: other
    text: To the extent applicable, Zayo performs Offerings in compliance with Article 49(1) of the GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zayo
provenance_date: '2026-11-10'
provider_name: Zayo
provider_slug: zayo
slug: zayo-privacy-policy
source_date: '2026-11-10'
source_filename: zayo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zayo.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zayo\naid: zayo\nurl: https://www.zayo.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Through the Cloud Services Offering, Zayo is acting in the role of a processor on behalf of the Customer\n    (the controller).\ndata_categories:\n- category: contact\n  text: Information required by Zayo to enable communications with customers, administer customer accounts, and\n    in accordance with contractual obligations is limited to name, business address, telephone number, job title,\n    and email address.\n- category: biometric\n  text: Zayo collects government issued identity information\
  \ (e.g., drivers license, passport), palm or fingerprint\n    biometric identifiers, and CCTV video image.\n- category: device\n  text: collects website visitor information in the form of generic website statistics and cookies including device,\n    operating system and browser type, country and time zone indicators and other system settings.\n- category: identifying\n  text: Zayo collects data that is captured through system logging and data flow management systems including, but\n    not limited to, source and destination Internet Protocol [IP] addresses and domain name\npurposes:\n- purpose: contract administration\n  text: Zayo processes Personal Data contact information as necessary for the performance of Offerings pursuant\n    to a contract between Zayo and its customer.\n- purpose: physical security controls\n  text: Identity information is collected to authenticate individuals based on customer approvals.\n- purpose: network traffic monitoring\n  text: Zayo monitors and processes\
  \ network traffic data consistent with its legitimate interests to support the\n    offerings provided pursuant to a contract between Zayo and its Customer, to ensure the integrity of services\n    and to support security incident and event management functions.\n- purpose: website and marketing\n  text: Zayo processes website visitor information and contact information with our legitimate interest to offer\n    and provide products and services\nretention:\n- scope: contact and website application information\n  period: 7 years after account termination\n  text: Zayo retains Personal Data contact information and website application information for as long as the Customer\n    maintains an active account and for 7 years after account termination\n- scope: CCTV images\n  period: 30 days\n  text: CCTV images are kept up to 30 days after which they are deleted.\n- scope: network traffic data\n  period: 90 days\n  text: Zayo retains network traffic data for 90 days, then archived for 1 year\
  \ before being deleted.\n- scope: generic website statistics\n  period: for the life of the website in an archive\n  text: Zayo retains website visitor information related to generic website statistics for the life of the website\n    in an archive.\nresidency:\n- region: United States\n  text: Personal Data transferred to Zayo subprocessors are stored on infrastructure located in the United States.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses under GDPR where applicable\n- mechanism: other\n  text: To the extent applicable, Zayo performs Offerings in compliance with Article 49(1) of the GDPR.\nsubprocessors:\n  url: null\n  text: Zayo does provide Personal Data, limited to name, contact information, and title, to its subprocessors to\n    fulfill its obligations to its customers, and for administrative purposes.\ndpa:\n  available: true\n  url: null\n  text: Zayo has prepared a Data Processor Addendum (“DPA”) in accordance with GDPR Article 28.\ndeletion:\n  route:\
  \ contact privacy.office@zayo.com\n  text: To update, correct, or remove personal data or to object to the processing of your information related to\n    website visit or web application support, please contact us at privacy.office@zayo.com\nrights:\n- right: access\n  text: The right to access your personal information\n- right: erasure\n  text: The right to the erasure of your personal information\n- right: data portability\n  text: The right to data portability\n- right: opt out of sale (CCPA)\n  text: The right to opt out of the sale of your personal information (under CCPA)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zayo/privacy/zayo-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Zayo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telecommunications
- Networking
- Connectivity
- Fiber
- Infrastructure
- Bandwidth
- Cloud Connectivity
- Ordering
- Ticketing
---
