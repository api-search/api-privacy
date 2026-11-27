---
api_specs:
- filename: gitcoin-bounties-api-openapi.yml
  format: yaml
  label: Gitcoin Bounties API
  slug: gitcoin-bounties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-bounties-api-openapi.yml
- filename: gitcoin-contributors-api-openapi.yml
  format: yaml
  label: Gitcoin Contributors API
  slug: gitcoin-contributors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-contributors-api-openapi.yml
- filename: gitcoin-grants-api-openapi.yml
  format: yaml
  label: Gitcoin Grants API
  slug: gitcoin-grants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-grants-api-openapi.yml
- filename: gitcoin-model-analysis-api-openapi.yml
  format: yaml
  label: Gitcoin Model Analysis API
  slug: gitcoin-model-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-model-analysis-api-openapi.yml
- filename: gitcoin-stamp-api-api-openapi.yml
  format: yaml
  label: Gitcoin Stamp API
  slug: gitcoin-stamp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gitcoin/openapi/gitcoin-stamp-api-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: device
    text: limited off-chain data like device type, browser version, etc.
  - category: identifying
    text: we will record any biographical information you directly provide to us (for example, your name, email, and job title)
  - category: contact
    text: If you specifically sign up to receive emails from us, we will store your email address to allow us to send you those emails.
  - category: financial
    text: Publicly-available blockchain data. When you connect your non-custodial blockchain wallet to the Services, we collect and log your publicly-available blockchain address
  - category: behavioral
    text: Information from localStorage and other tracking technologies.
  deletion:
    route: email privacy@gitcoin.co
    text: You can submit a request for information, access, or deletion to privacy@gitcoin.co .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Services
    text: We use the data we collect to provide, maintain, customize and improve our Services and features of our Services.
  - purpose: Safety and security
    text: We may use data to protect against, investigate, and stop fraudulent, unauthorized, or illegal activity.
  - purpose: Legal compliance
    text: We may use the information we collect as needed or requested by regulators, government entities, and law enforcement to comply with applicable laws and regulations.
  - purpose: Customer support
    text: We may use information to provide customer support for and answer inquiries about the Services.
  retention:
  - period: null
    scope: Information collected
    text: we may retain information as necessary to fulfill the purpose for which it was collected
  rights:
  - right: access
    text: request access and obtain a copy of your personal data
  - right: rectification or erasure
    text: request rectification or erasure of your personal data
  - right: object or restrict processing
    text: object to or restrict the processing of your personal data
  - right: portability
    text: request portability of your personal data
  - right: withdraw consent
    text: you may withdraw your consent to our collection at any time
  role:
    text: This privacy policy (“Policy”) describes how Gitcoin Limited, a British Virgin Islands Company
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not share or sell your information with any third parties for any marketing purposes whatsoever.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Gitcoin
provenance_date: '2026-11-09'
provider_name: Gitcoin
provider_slug: gitcoin
slug: gitcoin-privacy-policy
source_date: '2026-11-09'
source_filename: gitcoin-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gitcoin.co/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Gitcoin\naid: gitcoin\nurl: https://gitcoin.co/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This privacy policy (“Policy”) describes how Gitcoin Limited, a British Virgin Islands Company\ndata_categories:\n- category: device\n  text: limited off-chain data like device type, browser version, etc.\n- category: identifying\n  text: we will record any biographical information you directly provide to us (for example, your name, email, and\n    job title)\n- category: contact\n  text: If you specifically sign up to receive emails from us, we will store your email address to allow\
  \ us to send\n    you those emails.\n- category: financial\n  text: Publicly-available blockchain data. When you connect your non-custodial blockchain wallet to the Services,\n    we collect and log your publicly-available blockchain address\n- category: behavioral\n  text: Information from localStorage and other tracking technologies.\npurposes:\n- purpose: Providing the Services\n  text: We use the data we collect to provide, maintain, customize and improve our Services and features of our\n    Services.\n- purpose: Safety and security\n  text: We may use data to protect against, investigate, and stop fraudulent, unauthorized, or illegal activity.\n- purpose: Legal compliance\n  text: We may use the information we collect as needed or requested by regulators, government entities, and law\n    enforcement to comply with applicable laws and regulations.\n- purpose: Customer support\n  text: We may use information to provide customer support for and answer inquiries about the Services.\n\
  retention:\n- scope: Information collected\n  period: null\n  text: we may retain information as necessary to fulfill the purpose for which it was collected\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@gitcoin.co\n  text: You can submit a request for information, access, or deletion to privacy@gitcoin.co .\nrights:\n- right: access\n  text: request access and obtain a copy of your personal data\n- right: rectification or erasure\n  text: request rectification or erasure of your personal data\n- right: object or restrict processing\n  text: object to or restrict the processing of your personal data\n- right: portability\n  text: request portability of your personal data\n- right: withdraw consent\n  text: you may withdraw your consent to our collection at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not share or sell your information with any third parties\
  \ for any marketing purposes whatsoever.\n"
source_yaml_url: https://artifacts.apis.io/gitcoin/privacy/gitcoin-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Gitcoin's own page on 2026-11-09.
synthetic: false
tags:
- Public Goods
- Grants
- Bounties
- Quadratic Funding
- Web3
- Verifiable Credentials
- Identity
- Open Source
---
