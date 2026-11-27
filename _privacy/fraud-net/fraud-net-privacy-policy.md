---
api_specs:
- filename: fraud-net-banking-fintech-api-openapi.yml
  format: yaml
  label: Fraud.net Banking / Fintech API
  slug: fraud-net-banking-fintech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fraud-net/openapi/fraud-net-banking-fintech-api-openapi.yml
- filename: fraud-net-commerce-api-openapi.yml
  format: yaml
  label: Fraud.net Commerce API
  slug: fraud-net-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fraud-net/openapi/fraud-net-commerce-api-openapi.yml
- filename: fraud-net-identity-api-openapi.yml
  format: yaml
  label: Fraud.net Identity API
  slug: fraud-net-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fraud-net/openapi/fraud-net-identity-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: We also collect personal information of those individuals that represent the Member in connection with the use of the Services such as name, job title, email address and phone number.
  - category: financial
    text: payment information (does not include full credit card information)
  - category: behavioral
    text: User behavior, transaction information and transaction history
  - category: device
    text: collect unique device identifiers, including device metadata, from Users automatically
  - category: location
    text: The SDKs provide Fraud.net more precise information about the Users’ locations such as GPS (if the location settings allow it) and IP address.
  - category: contact
    text: email addresses, billing and shipping addresses, usernames, telephone numbers
  deletion:
    route: 'Request correction in writing to Fraud.net Inc. Attn: Legal Department; erasure available for consent or legitimate interest processing'
    text: If we are processing your personal data for reasons of consent or legitimate interest, you can request that your data be erased.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Services and billing
    text: provide Members with the Services and for billing and collections
  - purpose: Internal analysis and business analytics
    text: create internal analysis and business analytics to improve the Services
  - purpose: Marketing communications
    text: send Members marketing information, including product updates, industry news and reports, if it is in accordance with their newsletter and marketing preferences
  - purpose: Data enrichment
    text: We may share minimal User information (e.g., email addresses) with select third-party vendors for data enrichment purposes.
  residency:
  - region: Customer-selected region
    text: Information collected through our Services is primarily hosted on servers located closest to the customer or in a specific region selected by the customer.
  retention:
  - period: null
    scope: Following termination or deactivation of an account
    text: Following termination or deactivation of an account, we may retain personal information and content for backup, archival, audit, disaster recovery, or otherwise in accordance with the Terms of Service and applicable law.
  rights:
  - right: Access
    text: you can ask us what information we hold about you, and you can ask us to correct it if it is inaccurate
  - right: Withdraw consent
    text: If we have asked for your consent to process your personal data, you may withdraw that consent at any time.
  - right: Data portability
    text: you can ask us to give you a copy of the information in a machine-readable format so that you can transfer it to another provider
  - right: Erasure
    text: you can request that your data be erased
  - right: Restriction
    text: You have the right to ask us to stop using your information for a period of time if you believe we are not doing so lawfully.
  - right: Object to automated decisions
    text: you can ask us not to reach decisions affecting you using automated processing or profiling
  - right: Complain
    text: If you have a complaint about our use of your information, we would prefer you to contact us directly in the first instance
  role:
    text: Fraud.net generates analysis and results using the Service Data, whether alone or in combination with other sources, and creates risk profiles for Users
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Fraud.net does not (i) share User information with third party marketers or advertisers
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: in the event of a major outage or service disruption in that region, data may temporarily be transferred to and processed on servers located in another region (such as the United States, Europe, Canada, Australia, Middle East or Asia)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fraud.net
provenance_date: '2026-11-09'
provider_name: Fraud.net
provider_slug: fraud-net
slug: fraud-net-privacy-policy
source_date: '2026-11-09'
source_filename: fraud-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fraud.net/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fraud.net\naid: fraud-net\nurl: https://www.fraud.net/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Fraud.net generates analysis and results using the Service Data, whether alone or in combination with other\n    sources, and creates risk profiles for Users\ndata_categories:\n- category: identifying\n  text: We also collect personal information of those individuals that represent the Member in connection with the\n    use of the Services such as name, job title, email address and phone number.\n- category: financial\n  text: payment information (does not include full credit card\
  \ information)\n- category: behavioral\n  text: User behavior, transaction information and transaction history\n- category: device\n  text: collect unique device identifiers, including device metadata, from Users automatically\n- category: location\n  text: The SDKs provide Fraud.net more precise information about the Users’ locations such as GPS (if the location\n    settings allow it) and IP address.\n- category: contact\n  text: email addresses, billing and shipping addresses, usernames, telephone numbers\npurposes:\n- purpose: Provide Services and billing\n  text: provide Members with the Services and for billing and collections\n- purpose: Internal analysis and business analytics\n  text: create internal analysis and business analytics to improve the Services\n- purpose: Marketing communications\n  text: send Members marketing information, including product updates, industry news and reports, if it is in accordance\n    with their newsletter and marketing preferences\n- purpose: Data\
  \ enrichment\n  text: We may share minimal User information (e.g., email addresses) with select third-party vendors for data enrichment\n    purposes.\nretention:\n- scope: Following termination or deactivation of an account\n  period: null\n  text: Following termination or deactivation of an account, we may retain personal information and content for\n    backup, archival, audit, disaster recovery, or otherwise in accordance with the Terms of Service and applicable\n    law.\nresidency:\n- region: Customer-selected region\n  text: Information collected through our Services is primarily hosted on servers located closest to the customer\n    or in a specific region selected by the customer.\ntransfers:\n- mechanism: other\n  text: in the event of a major outage or service disruption in that region, data may temporarily be transferred\n    to and processed on servers located in another region (such as the United States, Europe, Canada, Australia,\n    Middle East or Asia)\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Request correction in writing to Fraud.net Inc. Attn: Legal Department; erasure available for consent\n    or legitimate interest processing'\n  text: If we are processing your personal data for reasons of consent or legitimate interest, you can request that\n    your data be erased.\nrights:\n- right: Access\n  text: you can ask us what information we hold about you, and you can ask us to correct it if it is inaccurate\n- right: Withdraw consent\n  text: If we have asked for your consent to process your personal data, you may withdraw that consent at any time.\n- right: Data portability\n  text: you can ask us to give you a copy of the information in a machine-readable format so that you can transfer\n    it to another provider\n- right: Erasure\n  text: you can request that your data be erased\n- right: Restriction\n  text: You have the right to ask us to stop using your information for\
  \ a period of time if you believe we are not\n    doing so lawfully.\n- right: Object to automated decisions\n  text: you can ask us not to reach decisions affecting you using automated processing or profiling\n- right: Complain\n  text: If you have a complaint about our use of your information, we would prefer you to contact us directly in\n    the first instance\nsale_or_sharing:\n  stance: prohibited\n  text: Fraud.net does not (i) share User information with third party marketers or advertisers\n"
source_yaml_url: https://artifacts.apis.io/fraud-net/privacy/fraud-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Fraud.net's own page on 2026-11-09.
synthetic: false
tags:
- Fraud Prevention
- Risk Management
- Commerce
- Payments
- Security
- Compliance
- Identity
- Banking
- Machine Learning
---
