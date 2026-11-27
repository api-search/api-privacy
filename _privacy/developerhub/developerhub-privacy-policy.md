---
api_specs:
- filename: developerhub-documentation-api-openapi.yml
  format: yaml
  label: DeveloperHub Documentation API
  slug: developerhub-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-documentation-api-openapi.yml
- filename: developerhub-project-api-openapi.yml
  format: yaml
  label: DeveloperHub Project API
  slug: developerhub-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-project-api-openapi.yml
- filename: developerhub-reader-access-api-openapi.yml
  format: yaml
  label: DeveloperHub Reader Access API
  slug: developerhub-reader-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-reader-access-api-openapi.yml
- filename: developerhub-changelog-api-openapi.yml
  format: yaml
  label: DeveloperHub Changelog API
  slug: developerhub-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-changelog-api-openapi.yml
- filename: developerhub-page-api-openapi.yml
  format: yaml
  label: DeveloperHub Page API
  slug: developerhub-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-page-api-openapi.yml
- filename: developerhub-reference-api-openapi.yml
  format: yaml
  label: DeveloperHub Reference API
  slug: developerhub-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-reference-api-openapi.yml
- filename: developerhub-version-api-openapi.yml
  format: yaml
  label: DeveloperHub Version API
  slug: developerhub-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/developerhub/openapi/developerhub-version-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Email address
  - category: financial
    text: Credit/debit card information
  - category: device
    text: Device identifiers
  - category: behavioral
    text: Browsing history
  - category: location
    text: Location information (e.g. IP address, zip code)
  - category: communication
    text: User content, for example, information or content you upload (which can include Personal Data if you include Personal Data in such content)
  deletion:
    route: Contact security@developerhub.io or legal@developerhub.io; delete project or disconnect repository
    text: Deleting the project deletes them.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate, improve and personalize services
    text: We process Personal Data to operate, improve, understand and personalize our Services.
  - purpose: Process orders
    text: Process orders
  - purpose: Provide AI features
    text: To provide these features we send the content they need to third party AI providers, who act as our sub-processors and appear on the list linked above.
  - purpose: Fraud protection
    text: Protect against or deter fraudulent, illegal or harmful actions
  retention:
  - period: 12 months
    scope: Account data
    text: We retain Personal Data about you for as long as you have an open account with us and for 12 months after you close your account.
  - period: for as long as the project they belong to exists
    scope: AI conversations
    text: We also keep the conversations you have with the AI features, and the changes they propose, for as long as the project they belong to exists, so that you can review and return to them.
  rights:
  - right: Access
    text: 'Access: You can request more information about the Personal Data we hold about you and request a copy of such Personal Data.'
  - right: Rectification
    text: 'Rectification: If you believe that any Personal Data we are holding about you is incorrect or incomplete, you can request that we correct or supplement such data.'
  - right: Erasure
    text: 'Erasure: You can request that we erase some or all of your Personal Data from our systems.'
  - right: Portability
    text: 'Portability: You can ask for a copy of your Personal Data in a machine-readable format.'
  - right: Objection
    text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal Data for certain purposes, such as for direct marketing purposes.'
  - right: Restriction of Processing
    text: 'Restriction of Processing: You can ask us to restrict further processing of your Personal Data.'
  - right: Withdraw consent
    text: 'Withdrawal of Consent: If we are processing your Personal Data based on your consent (as indicated at the time of collection of such data), you have the right to withdraw your consent at any time.'
  - right: Complaint
    text: 'Right to File Complaint: You have the right to lodge a complaint about Company’s practices with respect to your Personal Data with the supervisory authority of your country or EU Member State.'
  role:
    text: Company will be the controller of your Personal Data processed in connection with the Services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent Users personal identification information to others.
  subprocessors:
    text: 'An up-to-date list of sub-processors that we use to provide the service is available here: https://developerhub.io/sub-processors'
    url: https://developerhub.io/sub-processors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DeveloperHub
provenance_date: '2026-11-09'
provider_name: DeveloperHub
provider_slug: developerhub
slug: developerhub-privacy-policy
source_date: '2026-11-09'
source_filename: developerhub-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://developerhub.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DeveloperHub\naid: developerhub\nurl: https://developerhub.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Company will be the controller of your Personal Data processed in connection with the Services.\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Email address\n- category: financial\n  text: Credit/debit card information\n- category: device\n  text: Device identifiers\n- category: behavioral\n  text: Browsing history\n- category: location\n  text: Location information (e.g. IP address, zip code)\n- category: communication\n  text: User content,\
  \ for example, information or content you upload (which can include Personal Data if you include\n    Personal Data in such content)\npurposes:\n- purpose: Operate, improve and personalize services\n  text: We process Personal Data to operate, improve, understand and personalize our Services.\n- purpose: Process orders\n  text: Process orders\n- purpose: Provide AI features\n  text: To provide these features we send the content they need to third party AI providers, who act as our sub-processors\n    and appear on the list linked above.\n- purpose: Fraud protection\n  text: Protect against or deter fraudulent, illegal or harmful actions\nretention:\n- scope: Account data\n  period: 12 months\n  text: We retain Personal Data about you for as long as you have an open account with us and for 12 months after\n    you close your account.\n- scope: AI conversations\n  period: for as long as the project they belong to exists\n  text: We also keep the conversations you have with the AI features,\
  \ and the changes they propose, for as long\n    as the project they belong to exists, so that you can review and return to them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: https://developerhub.io/sub-processors\n  text: 'An up-to-date list of sub-processors that we use to provide the service is available here: https://developerhub.io/sub-processors'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact security@developerhub.io or legal@developerhub.io; delete project or disconnect repository\n  text: Deleting the project deletes them.\nrights:\n- right: Access\n  text: 'Access: You can request more information about the Personal Data we hold about you and request a copy of\n    such Personal Data.'\n- right: Rectification\n  text: 'Rectification: If you believe that any Personal Data we are holding about you is incorrect or incomplete,\n    you can request that we correct or supplement such data.'\n- right: Erasure\n  text: 'Erasure: You can request\
  \ that we erase some or all of your Personal Data from our systems.'\n- right: Portability\n  text: 'Portability: You can ask for a copy of your Personal Data in a machine-readable format.'\n- right: Objection\n  text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal\n    Data for certain purposes, such as for direct marketing purposes.'\n- right: Restriction of Processing\n  text: 'Restriction of Processing: You can ask us to restrict further processing of your Personal Data.'\n- right: Withdraw consent\n  text: 'Withdrawal of Consent: If we are processing your Personal Data based on your consent (as indicated at the\n    time of collection of such data), you have the right to withdraw your consent at any time.'\n- right: Complaint\n  text: 'Right to File Complaint: You have the right to lodge a complaint about Company’s practices with respect\n    to your Personal Data with the supervisory authority of your country or EU\
  \ Member State.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent Users personal identification information to others.\n"
source_yaml_url: https://artifacts.apis.io/developerhub/privacy/developerhub-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from DeveloperHub's own page on 2026-11-09.
synthetic: false
tags:
- API Reference
- Developer Portal
- Documentation
- Knowledge Base
- OpenAPI
- Docs as Code
- MCP
- Agent Skills
---
