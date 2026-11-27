---
api_specs:
- filename: friendbuy-analytics-api-openapi.yml
  format: yaml
  label: Friendbuy Analytics API
  slug: friendbuy-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-analytics-api-openapi.yml
- filename: friendbuy-authorization-api-openapi.yml
  format: yaml
  label: Friendbuy Authorization API
  slug: friendbuy-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-authorization-api-openapi.yml
- filename: friendbuy-customers-api-openapi.yml
  format: yaml
  label: Friendbuy Customers API
  slug: friendbuy-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-customers-api-openapi.yml
- filename: friendbuy-events-api-openapi.yml
  format: yaml
  label: Friendbuy Events API
  slug: friendbuy-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-events-api-openapi.yml
- filename: friendbuy-management-api-openapi.yml
  format: yaml
  label: Friendbuy Management API
  slug: friendbuy-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-management-api-openapi.yml
- filename: friendbuy-referrals-api-openapi.yml
  format: yaml
  label: Friendbuy Referrals API
  slug: friendbuy-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-referrals-api-openapi.yml
- filename: friendbuy-rewards-loyalty-api-openapi.yml
  format: yaml
  label: Friendbuy Rewards & Loyalty API
  slug: friendbuy-rewards-loyalty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-rewards-loyalty-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: we will collect your email address, full name and any other information you submit to us (“Merchant Information”)
  - category: financial
    text: a third-party payment processor that collects your credit card information, mailing address, and other billing information
  - category: device
    text: your mobile device’s advertising identifier or other device identifiers, a cookie identifier, your computer’s IP address
  - category: behavioral
    text: information about how you use our Site and the Services
  - category: demographic
    text: such as your date of birth or friend’s name and e-mail address
  - category: contact
    text: (i) your e-mail address
  deletion:
    route: Merchant contact
    text: the End User must reach out to that Merchant directly to exercise any rights under local data protection laws
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate services for merchants
    text: We use End User Information to operate the Services we provide to Merchants.
  - purpose: billing and payment
    text: to facilitate billing and payment, to authenticate a Merchant’s identity
  - purpose: merchant advertising and offers
    text: We also use and share this information to provide Merchants with useful advertising and offers.
  residency:
  - region: United States and other countries
    text: We may process and store information in the United States and other countries
  retention:
  - period: null
    scope: End User Information and Automated Information
    text: We may retain End User Information and Automated Information according to our internal data retention policy, including after the associated Merchant account is closed.
  rights:
  - right: access
    text: To request access to your Merchant Information;
  - right: rectify or erase
    text: To request that we rectify or erase your Merchant Information;
  - right: restrict or block processing
    text: To request that we restrict or block the processing of your Merchant Information;
  - right: data portability
    text: a right to data portability
  - right: withdraw consent
    text: to withdraw consent to our processing of your Merchant Information
  role:
    text: We act as a processor for those Merchants
    value: both
  sale_or_sharing:
    stance: conditional
    text: Friendbuy does not share or sell End User Information to any other non-affiliated organizations for those third parties’ marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Friendbuy enters into Standard Contractual Clauses for the transfer of personal information outside of the EEA, UK, and Switzerland
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Friendbuy
provenance_date: '2026-11-09'
provider_name: Friendbuy
provider_slug: friendbuy
slug: friendbuy-privacy-policy
source_date: '2026-11-09'
source_filename: friendbuy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.friendbuy.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Friendbuy\naid: friendbuy\nurl: https://www.friendbuy.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as a processor for those Merchants\ndata_categories:\n- category: identifying\n  text: we will collect your email address, full name and any other information you submit to us (“Merchant Information”)\n- category: financial\n  text: a third-party payment processor that collects your credit card information, mailing address, and other billing\n    information\n- category: device\n  text: your mobile device’s advertising identifier or other device identifiers, a cookie identifier,\
  \ your computer’s\n    IP address\n- category: behavioral\n  text: information about how you use our Site and the Services\n- category: demographic\n  text: such as your date of birth or friend’s name and e-mail address\n- category: contact\n  text: (i) your e-mail address\npurposes:\n- purpose: operate services for merchants\n  text: We use End User Information to operate the Services we provide to Merchants.\n- purpose: billing and payment\n  text: to facilitate billing and payment, to authenticate a Merchant’s identity\n- purpose: merchant advertising and offers\n  text: We also use and share this information to provide Merchants with useful advertising and offers.\nretention:\n- scope: End User Information and Automated Information\n  period: null\n  text: We may retain End User Information and Automated Information according to our internal data retention policy,\n    including after the associated Merchant account is closed.\nresidency:\n- region: United States and other countries\n\
  \  text: We may process and store information in the United States and other countries\ntransfers:\n- mechanism: SCC\n  text: Friendbuy enters into Standard Contractual Clauses for the transfer of personal information outside of the\n    EEA, UK, and Switzerland\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Merchant contact\n  text: the End User must reach out to that Merchant directly to exercise any rights under local data protection\n    laws\nrights:\n- right: access\n  text: To request access to your Merchant Information;\n- right: rectify or erase\n  text: To request that we rectify or erase your Merchant Information;\n- right: restrict or block processing\n  text: To request that we restrict or block the processing of your Merchant Information;\n- right: data portability\n  text: a right to data portability\n- right: withdraw consent\n  text: to withdraw consent to our processing of your Merchant Information\n\
  sale_or_sharing:\n  stance: conditional\n  text: Friendbuy does not share or sell End User Information to any other non-affiliated organizations for those\n    third parties’ marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/friendbuy/privacy/friendbuy-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Friendbuy's own page on 2026-11-09.
synthetic: false
tags:
- Referral Marketing
- Loyalty
- Rewards
- E-Commerce
- Marketing
- Advocacy
- Loyalty & Incentives
---
