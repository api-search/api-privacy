---
api_specs:
- filename: cledara-applications-api-openapi.yml
  format: yaml
  label: Cledara Applications API
  slug: cledara-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cledara/openapi/cledara-applications-api-openapi.yml
- filename: cledara-transactions-api-openapi.yml
  format: yaml
  label: Cledara Transactions API
  slug: cledara-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cledara/openapi/cledara-transactions-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact Data , including your first name, last name, email address, phone number, Social Security Number and date of birth.
  - category: financial
    text: Financial Data , including your or your company's bank balance, routing and account numbers, transaction history, tax identification number, and related information.
  - category: location
    text: Location Data , including imprecise location information (such as location derived from an IP address or information that indicates a city or postal code level).
  - category: behavioral
    text: Service Use Data , including information about how much time you spend on particular pages you visit, the features you use, your preferences or selections, the services you view, the SaaS products you use, the time of day your browse, and your referring and exiting pages
  - category: device
    text: Device Data , including information about the type of device or browser you use, your device's operating software, your internet service provider, your device's regional and language settings, and device identifiers such as IP address and Ad Id.
  - category: communication
    text: Content, including content within any messages you send to us (such as when contacting sales or asking a question).
  - category: professional
    text: Job Applicant Data , including your employment and education history, transcripts, writing samples, and references as necessary to consider your job application for open positions.
  deletion:
    route: Email dpo@cledara.com with "CCPA Request" in the subject line to request deletion
    text: In addition, you have the right to delete the personal information we have collected from you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing services
    text: We use the information we collect to operate and manage our Service and Product, including to provide the Website, determine eligibility for the Product, allow you to use the Card and access the Platform
  - purpose: Security and fraud detection
    text: We use the information we collect to prevent and detect potentially fraudulent or unauthorized transactions, breach of policies or terms, and threats of harm.
  - purpose: Marketing and advertising
    text: We use the information we collect through the Service to develop and send advertising, direct marketing, and communications about our and other entities' products, offers, promotions, rewards, events, and services.
  - purpose: Understanding usage and improving services
    text: We use the information we collect to understand how our business customers use the Service and Product, and improve our services and products.
  residency:
  - region: UK or EEA (UK and Europe notice)
    text: The personal data that we hold will be stored in the UK or the European Economic Area (EEA), but may also be transferred to, and stored at, a destination outside the UK or EEA
  - region: United States, United Kingdom, European Union and other jurisdictions (US notice)
    text: Any information we collect may be transferred to, processed, used, handled, and stored in the United States, the United Kingdom, European Union and other jurisdictions.
  retention:
  - period: up to 10 years
    scope: Customer personal information (UK and Europe notice)
    text: We may keep your personal information for up to 10 years after you stop being a customer.
  rights:
  - right: Right to know
    text: You have the right to know certain details about our data practices in the past 12 months.
  - right: Right to delete
    text: In addition, you have the right to delete the personal information we have collected from you.
  - right: Right to non-discrimination
    text: You have the right not to receive discriminatory treatment by us for the exercise of any your rights.
  role:
    text: We are responsible as ‘controller’ of that personal information for the purposes of those laws.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For personal data transferred from Europe or the United Kingdom, we will provide appropriate safeguards, such as through the use of standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cledara
provenance_date: '2026-11-09'
provider_name: Cledara
provider_slug: cledara
slug: cledara-privacy-policy
source_date: '2026-11-09'
source_filename: cledara-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cledara.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cledara\naid: cledara\nurl: https://www.cledara.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible as ‘controller’ of that personal information for the purposes of those laws.\ndata_categories:\n- category: identifying\n  text: Contact Data , including your first name, last name, email address, phone number, Social Security Number\n    and date of birth.\n- category: financial\n  text: Financial Data , including your or your company's bank balance, routing and account numbers, transaction\n    history, tax identification number, and related information.\n\
  - category: location\n  text: Location Data , including imprecise location information (such as location derived from an IP address or\n    information that indicates a city or postal code level).\n- category: behavioral\n  text: Service Use Data , including information about how much time you spend on particular pages you visit, the\n    features you use, your preferences or selections, the services you view, the SaaS products you use, the time\n    of day your browse, and your referring and exiting pages\n- category: device\n  text: Device Data , including information about the type of device or browser you use, your device's operating\n    software, your internet service provider, your device's regional and language settings, and device identifiers\n    such as IP address and Ad Id.\n- category: communication\n  text: Content, including content within any messages you send to us (such as when contacting sales or asking a\n    question).\n- category: professional\n  text: Job Applicant\
  \ Data , including your employment and education history, transcripts, writing samples, and\n    references as necessary to consider your job application for open positions.\npurposes:\n- purpose: Providing services\n  text: We use the information we collect to operate and manage our Service and Product, including to provide the\n    Website, determine eligibility for the Product, allow you to use the Card and access the Platform\n- purpose: Security and fraud detection\n  text: We use the information we collect to prevent and detect potentially fraudulent or unauthorized transactions,\n    breach of policies or terms, and threats of harm.\n- purpose: Marketing and advertising\n  text: We use the information we collect through the Service to develop and send advertising, direct marketing,\n    and communications about our and other entities' products, offers, promotions, rewards, events, and services.\n- purpose: Understanding usage and improving services\n  text: We use the information\
  \ we collect to understand how our business customers use the Service and Product,\n    and improve our services and products.\nretention:\n- scope: Customer personal information (UK and Europe notice)\n  period: up to 10 years\n  text: We may keep your personal information for up to 10 years after you stop being a customer.\nresidency:\n- region: UK or EEA (UK and Europe notice)\n  text: The personal data that we hold will be stored in the UK or the European Economic Area (EEA), but may also\n    be transferred to, and stored at, a destination outside the UK or EEA\n- region: United States, United Kingdom, European Union and other jurisdictions (US notice)\n  text: Any information we collect may be transferred to, processed, used, handled, and stored in the United States,\n    the United Kingdom, European Union and other jurisdictions.\ntransfers:\n- mechanism: SCC\n  text: For personal data transferred from Europe or the United Kingdom, we will provide appropriate safeguards,\n    such\
  \ as through the use of standard contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email dpo@cledara.com with \"CCPA Request\" in the subject line to request deletion\n  text: In addition, you have the right to delete the personal information we have collected from you.\nrights:\n- right: Right to know\n  text: You have the right to know certain details about our data practices in the past 12 months.\n- right: Right to delete\n  text: In addition, you have the right to delete the personal information we have collected from you.\n- right: Right to non-discrimination\n  text: You have the right not to receive discriminatory treatment by us for the exercise of any your rights.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cledara/privacy/cledara-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Cledara's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- SaaS Management
- Software Spending
- Spend Management
- Subscription Management
- Virtual Cards
- Expense Management
- FinOps
- MCP
- Market Data
---
