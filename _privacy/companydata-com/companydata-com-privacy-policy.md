---
api_specs:
- filename: companydata-com-company-api-openapi.yml
  format: yaml
  label: CompanyData Company API
  slug: companydata-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-company-api-openapi.yml
- filename: companydata-com-corporate-structure-api-openapi.yml
  format: yaml
  label: CompanyData Corporate Structure API
  slug: companydata-com-corporate-structure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-corporate-structure-api-openapi.yml
- filename: companydata-com-domain-enrichment-api-openapi.yml
  format: yaml
  label: CompanyData Domain Enrichment API
  slug: companydata-com-domain-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-domain-enrichment-api-openapi.yml
- filename: companydata-com-lookup-api-openapi.yml
  format: yaml
  label: CompanyData Lookup API
  slug: companydata-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/companydata-com/openapi/companydata-com-lookup-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: company name, address, country, phone number, mobile number, fax number, email address, website, first and last name of contact person
  - category: professional
    text: job title of contact person, trade register data, contact history and content of messages
  - category: demographic
    text: gender of contact person
  - category: identifying
    text: first and last name of director
  deletion:
    route: Deletion request to CompanyData.com
    text: Deletion of personal data, whereby CompanyData.com may still be required to process such data for specific (legal) purposes (such as tax administration)
  dpa:
    available: true
    text: With such parties, CompanyData.com concludes a data processing agreement.
    url: null
  purposes:
  - purpose: Compliance with legal obligations
    text: Compliance with legal obligations, including tax and administrative legislation
  - purpose: Marketing and communication
    text: Marketing and communication, such as (when consent has been given) newsletters to provide information about new and existing services of CompanyData.com
  - purpose: Market research and data analysis
    text: Market research and data analysis to improve its services
  - purpose: Updating customer data for CRM
    text: Updating and managing (mainly B2B) customer data on behalf of companies, in order to ensure accurate and up-to-date information in CRM systems.
  retention:
  - period: null
    scope: personal data generally
    text: CompanyData.com does not retain personal data longer than necessary for the purposes for which CompanyData.com processes personal data.
  rights:
  - right: access and correction
    text: To access which personal data CompanyData.com processes and correct it if it is incorrect
  - right: deletion
    text: Deletion of personal data, whereby CompanyData.com may still be required to process such data for specific (legal) purposes (such as tax administration)
  - right: restriction
    text: Restriction of the processing of personal data
  - right: objection
    text: Object to a particular processing of personal data
  - right: portability
    text: Transfer of personal data to a carrier in a commonly readable format
  role:
    text: CompanyData.com processes personal data in accordance with the applicable relevant privacy legislation
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share this data with third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where data is transferred outside the EEA, we ensure appropriate safeguards to protect the privacy of data subjects in accordance with the GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CompanyData
provenance_date: '2026-11-09'
provider_name: CompanyData
provider_slug: companydata-com
slug: companydata-com-privacy-policy
source_date: '2026-11-09'
source_filename: companydata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://companydata.com/privacy-statement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CompanyData\naid: companydata-com\nurl: https://companydata.com/privacy-statement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CompanyData.com processes personal data in accordance with the applicable relevant privacy legislation\ndata_categories:\n- category: contact\n  text: company name, address, country, phone number, mobile number, fax number, email address, website, first and\n    last name of contact person\n- category: professional\n  text: job title of contact person, trade register data, contact history and content of messages\n- category: demographic\n  text: gender of contact\
  \ person\n- category: identifying\n  text: first and last name of director\npurposes:\n- purpose: Compliance with legal obligations\n  text: Compliance with legal obligations, including tax and administrative legislation\n- purpose: Marketing and communication\n  text: Marketing and communication, such as (when consent has been given) newsletters to provide information about\n    new and existing services of CompanyData.com\n- purpose: Market research and data analysis\n  text: Market research and data analysis to improve its services\n- purpose: Updating customer data for CRM\n  text: Updating and managing (mainly B2B) customer data on behalf of companies, in order to ensure accurate and\n    up-to-date information in CRM systems.\nretention:\n- scope: personal data generally\n  period: null\n  text: CompanyData.com does not retain personal data longer than necessary for the purposes for which CompanyData.com\n    processes personal data.\nresidency: []\ntransfers:\n- mechanism: other\n\
  \  text: Where data is transferred outside the EEA, we ensure appropriate safeguards to protect the privacy of data\n    subjects in accordance with the GDPR.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: With such parties, CompanyData.com concludes a data processing agreement.\ndeletion:\n  route: Deletion request to CompanyData.com\n  text: Deletion of personal data, whereby CompanyData.com may still be required to process such data for specific\n    (legal) purposes (such as tax administration)\nrights:\n- right: access and correction\n  text: To access which personal data CompanyData.com processes and correct it if it is incorrect\n- right: deletion\n  text: Deletion of personal data, whereby CompanyData.com may still be required to process such data for specific\n    (legal) purposes (such as tax administration)\n- right: restriction\n  text: Restriction of the processing of personal data\n- right: objection\n  text: Object to a particular\
  \ processing of personal data\n- right: portability\n  text: Transfer of personal data to a carrier in a commonly readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share this data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/companydata-com/privacy/companydata-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from CompanyData's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Company Data
- Business Registry
- B2B Data
- Data Enrichment
- KYC
- KYB
- Lead Generation
- MCP
---
