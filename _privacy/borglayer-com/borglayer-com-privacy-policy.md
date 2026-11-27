---
api_specs:
- filename: borglayer-com-balance-api-openapi.yml
  format: yaml
  label: BorgLayer Balance API
  slug: borglayer-com-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-balance-api-openapi.yml
- filename: borglayer-com-chains-api-openapi.yml
  format: yaml
  label: BorgLayer Chains API
  slug: borglayer-com-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-chains-api-openapi.yml
- filename: borglayer-com-domains-api-openapi.yml
  format: yaml
  label: BorgLayer Domains API
  slug: borglayer-com-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-domains-api-openapi.yml
- filename: borglayer-com-formation-api-openapi.yml
  format: yaml
  label: BorgLayer Formation API
  slug: borglayer-com-formation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-formation-api-openapi.yml
- filename: borglayer-com-marketplace-api-openapi.yml
  format: yaml
  label: BorgLayer Marketplace API
  slug: borglayer-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-marketplace-api-openapi.yml
- filename: borglayer-com-register-api-openapi.yml
  format: yaml
  label: BorgLayer Register API
  slug: borglayer-com-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-register-api-openapi.yml
- filename: borglayer-com-registrant-profiles-api-openapi.yml
  format: yaml
  label: BorgLayer Registrant Profiles API
  slug: borglayer-com-registrant-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-registrant-profiles-api-openapi.yml
- filename: borglayer-com-search-api-openapi.yml
  format: yaml
  label: BorgLayer Search API
  slug: borglayer-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-search-api-openapi.yml
- filename: borglayer-com-transfer-in-api-openapi.yml
  format: yaml
  label: BorgLayer Transfer In API
  slug: borglayer-com-transfer-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-transfer-in-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address, organization name, and account credentials (stored only as salted hashes
  - category: contact
    text: 'registrant (owner) contact details: name, organization, email, phone, and postal address.'
  - category: financial
    text: prepaid-balance top-ups, and on-chain escrow activity you perform through the platform
  - category: device
    text: IP address, user agent, and request metadata, used for security, abuse prevention, and service operation.
  deletion:
    route: Email request to privacy contact
    text: You can request access to, correction of, or deletion of your personal data by emailing [email protected] (subject to registry and legal retention rules).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested services
    text: 'To provide the services you request: registering and managing domains, editing DNS, forming companies, and processing payments.'
  - purpose: Security and fraud prevention
    text: To secure the platform, prevent abuse and fraud, and meet legal and registry compliance obligations.
  retention:
  - period: null
    scope: Account, registrant, and transaction records
    text: We retain account, registrant, and transaction records for as long as your account is active and as required to comply with registry rules, tax, and legal obligations
  rights:
  - right: Access
    text: You can request access to, correction of, or deletion of your personal data
  - right: Correction
    text: You can request access to, correction of, or deletion of your personal data
  - right: Deletion
    text: You can request access to, correction of, or deletion of your personal data
  role:
    text: 'BorgLayer LLC (“BorgLayer”, “we”, “us”), 99 Wall Street #2888, New York, NY 10005, United States, operates the BorgLayer domain and company-formation platform'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BorgLayer
provenance_date: '2026-11-09'
provider_name: BorgLayer
provider_slug: borglayer-com
slug: borglayer-com-privacy-policy
source_date: '2026-11-09'
source_filename: borglayer-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://borglayer.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BorgLayer\naid: borglayer-com\nurl: https://borglayer.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'BorgLayer LLC (“BorgLayer”, “we”, “us”), 99 Wall Street #2888, New York, NY 10005, United States, operates\n    the BorgLayer domain and company-formation platform'\ndata_categories:\n- category: identifying\n  text: name, email address, organization name, and account credentials (stored only as salted hashes\n- category: contact\n  text: 'registrant (owner) contact details: name, organization, email, phone, and postal address.'\n- category: financial\n  text: prepaid-balance\
  \ top-ups, and on-chain escrow activity you perform through the platform\n- category: device\n  text: IP address, user agent, and request metadata, used for security, abuse prevention, and service operation.\npurposes:\n- purpose: Provide requested services\n  text: 'To provide the services you request: registering and managing domains, editing DNS, forming companies,\n    and processing payments.'\n- purpose: Security and fraud prevention\n  text: To secure the platform, prevent abuse and fraud, and meet legal and registry compliance obligations.\nretention:\n- scope: Account, registrant, and transaction records\n  period: null\n  text: We retain account, registrant, and transaction records for as long as your account is active and as required\n    to comply with registry rules, tax, and legal obligations\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to privacy contact\n \
  \ text: You can request access to, correction of, or deletion of your personal data by emailing [email protected]\n    (subject to registry and legal retention rules).\nrights:\n- right: Access\n  text: You can request access to, correction of, or deletion of your personal data\n- right: Correction\n  text: You can request access to, correction of, or deletion of your personal data\n- right: Deletion\n  text: You can request access to, correction of, or deletion of your personal data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/borglayer-com/privacy/borglayer-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from BorgLayer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wallets
- Domains
- Hosting
- Email
---
