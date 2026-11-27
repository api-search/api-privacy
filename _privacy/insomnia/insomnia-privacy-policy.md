---
api_specs:
- filename: insomnia-mock-logs-api-openapi.yml
  format: yaml
  label: Insomnia Mock Logs API
  slug: insomnia-mock-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insomnia/openapi/insomnia-mock-logs-api-openapi.yml
- filename: insomnia-mock-routes-api-openapi.yml
  format: yaml
  label: Insomnia Mock Routes API
  slug: insomnia-mock-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insomnia/openapi/insomnia-mock-routes-api-openapi.yml
- filename: insomnia-mock-servers-api-openapi.yml
  format: yaml
  label: Insomnia Mock Servers API
  slug: insomnia-mock-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insomnia/openapi/insomnia-mock-servers-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: When creating an Insomnia account, you will be asked to enter an email address and password.
  - category: identifying
    text: Service Data is kept confidential. It is visible to our staff and includes, but is not limited to, email address, full name, billing information, server logs, client IP address, and stats on application usage.
  - category: behavioral
    text: Analytics Data Insomnia’s website and applications collect information to operate and improve our Services.
  - category: device
    text: Cookies are files with small amounts of data which may include an anonymous unique identifier.
  deletion:
    route: Delete account through an authenticated session; erasure requests remove data permanently, except backups
    text: Account owners have the right to instruct us to remove data permanently from our systems. To ensure that no one’s data is deleted without their consent, you must first delete your account through an authenticated session.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and improve services
    text: We use the information we collect to operate and improve our website, applications, and provide customer support.
  - purpose: Account sign-in and notifications
    text: Email addresses are used during sign-in and for receiving occasional updates initiated by you or your team members.
  - purpose: Session and preference cookies
    text: 'Examples of Cookies we use: session cookies (we use these cookies to operate our Service) and preference cookies (we use these cookies to remember your preferences and various settings).'
  retention:
  - period: null
    scope: Service Data
    text: We retain the minimum amount of Service Data to operate and improve our Services.
  rights:
  - right: Right to know
    text: You have the right to know what we know about you and to see how that data is handled.
  - right: Erasure
    text: Account owners have the right to instruct us to remove data permanently from our systems.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Your Service Data are held by third party data processors, who provide us with hosting and other infrastructure services.
    url: null
  transfers:
  - mechanism: other
    text: By using our Service and providing your information, you authorize us to collect, use, and store your information outside of the European Union.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Insomnia
provenance_date: '2026-11-09'
provider_name: Insomnia
provider_slug: insomnia
slug: insomnia-privacy-policy
source_date: '2026-11-09'
source_filename: insomnia-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://insomnia.rest/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Insomnia\naid: insomnia\nurl: https://insomnia.rest/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When creating an Insomnia account, you will be asked to enter an email address and password.\n- category: identifying\n  text: Service Data is kept confidential. It is visible to our staff and includes, but is not limited to, email\n    address, full name, billing information, server logs, client IP address, and stats on application usage.\n- category: behavioral\n  text: Analytics Data Insomnia’s website and applications collect\
  \ information to operate and improve our Services.\n- category: device\n  text: Cookies are files with small amounts of data which may include an anonymous unique identifier.\npurposes:\n- purpose: Operate and improve services\n  text: We use the information we collect to operate and improve our website, applications, and provide customer\n    support.\n- purpose: Account sign-in and notifications\n  text: Email addresses are used during sign-in and for receiving occasional updates initiated by you or your team\n    members.\n- purpose: Session and preference cookies\n  text: 'Examples of Cookies we use: session cookies (we use these cookies to operate our Service) and preference\n    cookies (we use these cookies to remember your preferences and various settings).'\nretention:\n- scope: Service Data\n  period: null\n  text: We retain the minimum amount of Service Data to operate and improve our Services.\nresidency: []\ntransfers:\n- mechanism: other\n  text: By using our Service and\
  \ providing your information, you authorize us to collect, use, and store your information\n    outside of the European Union.\nsubprocessors:\n  url: null\n  text: Your Service Data are held by third party data processors, who provide us with hosting and other infrastructure\n    services.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account through an authenticated session; erasure requests remove data permanently, except backups\n  text: Account owners have the right to instruct us to remove data permanently from our systems. To ensure that\n    no one’s data is deleted without their consent, you must first delete your account through an authenticated\n    session.\nrights:\n- right: Right to know\n  text: You have the right to know what we know about you and to see how that data is handled.\n- right: Erasure\n  text: Account owners have the right to instruct us to remove data permanently from our systems.\nsale_or_sharing:\n  stance: unstated\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/insomnia/privacy/insomnia-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 13 quoted statements, read from Insomnia's own page on 2026-11-09.
synthetic: false
tags:
- API Design
- CLI
- Clients
- Developer Tools
- Mocking
- Platform
- Testing
- OpenAPI
---
