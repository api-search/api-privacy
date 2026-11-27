---
api_specs:
- filename: firstrade-plaid-api-openapi.yml
  format: yaml
  label: Firstrade Plaid API
  slug: firstrade-plaid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firstrade/openapi/firstrade-plaid-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity data, such as your full name, Social Security number/Tax Identification number, date of birth
  - category: contact
    text: Contact data, such as residential/mailing address, telephone numbers, and email address.
  - category: financial
    text: Financial data, such as such as your bank account and payment card details, and information about your employment, income, account balances, financial transaction history, credit history, tax information, and credit scores.
  - category: device
    text: device identifiers (like IP address or mobile device identifiers)
  - category: behavioral
    text: pages or features you use, time and date of access, and other similar usage information
  - category: communication
    text: Advertising Data. We collect information in connection with our ad campaigns that surface on other platforms, such as the ads you click on and other interactions with our ads.
  deletion:
    route: Right to Request Deletion for California residents
    text: You can ask us to delete the personal information we have collected from you. To submit a request, contact us via email or phone.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain services
    text: Provide and maintain our services, which encompasses processing account applications, verifying your identity, ensuring the functionality of our platform, offering support, recording transactional details, and managing billing and accounts.
  - purpose: Targeted advertising
    text: delivering targeted ads based on your interests both on our platforms and others
  - purpose: Legal and regulatory compliance
    text: Adhere to relevant laws and regulatory obligations, including those applicable to regulated broker-dealers and money services businesses.
  retention:
  - period: null
    scope: personal information generally
    text: Personal data is kept for as long as necessary to fulfill the purposes for which it was collected, as well as for other business purposes outlined in this Privacy Policy.
  rights:
  - right: Right to know (California)
    text: 'Right to Know: You can request details about the personal data we collect, use, disclose, and sell.'
  - right: Right to delete (California)
    text: 'Right to Request Deletion: You can ask us to delete the personal information we have collected from you.'
  - right: Opt out of sale (California)
    text: 'Right to Opt-Out of Selling Personal Information: We do not sell your personal information.'
  - right: Nondiscrimination (California)
    text: 'Nondiscrimination: We will not discriminate against California residents who exercise their privacy rights.'
  - right: Opt out of data sharing
    text: 'Opt Out of Data Sharing: To stop sharing your data with marketing partners, contact us at service@firstrade.com or 1-800-869-8800, and we will cease sharing your information for these purposes.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not sell your personal information. However, we allow third parties to collect information for advertising and marketing purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Firstrade
provenance_date: '2026-11-09'
provider_name: Firstrade
provider_slug: firstrade
slug: firstrade-privacy-policy
source_date: '2026-11-09'
source_filename: firstrade-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.firstrade.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Firstrade\naid: firstrade\nurl: https://www.firstrade.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identity data, such as your full name, Social Security number/Tax Identification number, date of birth\n- category: contact\n  text: Contact data, such as residential/mailing address, telephone numbers, and email address.\n- category: financial\n  text: Financial data, such as such as your bank account and payment card details, and information about your employment,\n    income, account balances, financial transaction\
  \ history, credit history, tax information, and credit scores.\n- category: device\n  text: device identifiers (like IP address or mobile device identifiers)\n- category: behavioral\n  text: pages or features you use, time and date of access, and other similar usage information\n- category: communication\n  text: Advertising Data. We collect information in connection with our ad campaigns that surface on other platforms,\n    such as the ads you click on and other interactions with our ads.\npurposes:\n- purpose: Provide and maintain services\n  text: Provide and maintain our services, which encompasses processing account applications, verifying your identity,\n    ensuring the functionality of our platform, offering support, recording transactional details, and managing\n    billing and accounts.\n- purpose: Targeted advertising\n  text: delivering targeted ads based on your interests both on our platforms and others\n- purpose: Legal and regulatory compliance\n  text: Adhere to relevant\
  \ laws and regulatory obligations, including those applicable to regulated broker-dealers\n    and money services businesses.\nretention:\n- scope: personal information generally\n  period: null\n  text: Personal data is kept for as long as necessary to fulfill the purposes for which it was collected, as well\n    as for other business purposes outlined in this Privacy Policy.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Right to Request Deletion for California residents\n  text: You can ask us to delete the personal information we have collected from you. To submit a request, contact\n    us via email or phone.\nrights:\n- right: Right to know (California)\n  text: 'Right to Know: You can request details about the personal data we collect, use, disclose, and sell.'\n- right: Right to delete (California)\n  text: 'Right to Request Deletion: You can ask us to delete the personal information\
  \ we have collected from you.'\n- right: Opt out of sale (California)\n  text: 'Right to Opt-Out of Selling Personal Information: We do not sell your personal information.'\n- right: Nondiscrimination (California)\n  text: 'Nondiscrimination: We will not discriminate against California residents who exercise their privacy rights.'\n- right: Opt out of data sharing\n  text: 'Opt Out of Data Sharing: To stop sharing your data with marketing partners, contact us at service@firstrade.com\n    or 1-800-869-8800, and we will cease sharing your information for these purposes.'\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell your personal information. However, we allow third parties to collect information for advertising\n    and marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/firstrade/privacy/firstrade-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from Firstrade's own page on 2026-11-09.
synthetic: false
tags:
- Brokerage
- Commission-Free Trading
- Stocks
- ETFs
- Options
- Mutual Funds
- Fixed Income
- Retirement
- IRA
- Investing
- Finance
- Open Banking
- Financial Services
---
