---
api_specs:
- filename: npm-registry-api-openapi.yml
  format: yaml
  label: npm Registry API
  slug: registry
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-registry-api-openapi.yml
- filename: npm-hooks-api-openapi.yml
  format: yaml
  label: npm Hooks API
  slug: hooks
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-hooks-api-openapi.yml
- filename: npm-downloads-api-openapi.yml
  format: yaml
  label: npm Downloads API
  slug: npm-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-downloads-api-openapi.yml
- filename: npm-packages-api-openapi.yml
  format: yaml
  label: npm Packages API
  slug: npm-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-packages-api-openapi.yml
- filename: npm-search-api-openapi.yml
  format: yaml
  label: npm Search API
  slug: npm-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-search-api-openapi.yml
- filename: npm-trusted-publishers-api-openapi.yml
  format: yaml
  label: npm Trusted Publishers API
  slug: npm-trusted-publishers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-trusted-publishers-api-openapi.yml
- filename: npm-access-api-openapi.yml
  format: yaml
  label: npm Access API
  slug: npm-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-access-api-openapi.yml
- filename: npm-audit-api-openapi.yml
  format: yaml
  label: npm Audit API
  slug: npm-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-audit-api-openapi.yml
- filename: npm-org-api-openapi.yml
  format: yaml
  label: npm Org API
  slug: npm-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-org-api-openapi.yml
- filename: npm-publish-api-openapi.yml
  format: yaml
  label: npm Publish API
  slug: npm-publish-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-publish-api-openapi.yml
- filename: npm-stage-api-openapi.yml
  format: yaml
  label: npm Stage API
  slug: npm-stage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-stage-api-openapi.yml
- filename: npm-team-api-openapi.yml
  format: yaml
  label: npm Team API
  slug: npm-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-team-api-openapi.yml
- filename: npm-trust-api-openapi.yml
  format: yaml
  label: npm Trust API
  slug: npm-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-trust-api-openapi.yml
- filename: npm-oidc-api-openapi.yml
  format: yaml
  label: npm OIDC API
  slug: npm-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-oidc-api-openapi.yml
- filename: npm-tokens-api-openapi.yml
  format: yaml
  label: npm Tokens API
  slug: npm-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npm/openapi/npm-tokens-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: To create an npm account, npm requires a working email address and an available user name.
  - category: contact
    text: Those data usually include your name and email address, and may include your company or other affiliation.
  - category: financial
    text: To sign up for paid services, npm requires your payment card data.
  - category: device
    text: network request data, such as the date and time, your IP address, and the URL
  - category: behavioral
    text: npm uses cookies, server logs, and other methods to collect data about what pages you visit, and when.
  - category: location
    text: However, we do collect imprecise location (e.g., your IP address).
  deletion:
    route: Support ticket or account closure request via support
    text: You can close your npm account at any time by e-mailing contacting support . Closing your account removes the profile from the public registry but does not automatically erase packages published under your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: fulfill requests and send security alerts
    text: send you alerts about security vulnerabilities that may affect the software you're building, when you run npm install or npm audit
  - purpose: provide account access and identification
    text: npm uses this data to provide you access to features and identify you across npm services, publicly and within npm.
  - purpose: charge for npm services
    text: npm uses your payment card data only to charge for npm services.
  - purpose: optimize and secure website
    text: optimize the website, so that it's quick and easy to use
  residency:
  - region: United States
    text: npm stores account data, data about website use, data about registry use, and private packages on servers in the United States of America.
  - region: Enterprise registries
    text: npm stores package data published to Enterprise registries that npm hosts, plus metadata about them, in cloud computing zones of customers' choosing.
  retention:
  - period: null
    scope: payment card data
    text: npm instructs Stripe to store your payment card data only as long as you use paid npm services.
  rights:
  - right: Access
    text: access to information held about you.
  - right: Correction
    text: ask us to correct or amend inaccurate or incomplete information we have about you.
  - right: Erasure
    text: ask us to erase data that under certain circumstances
  - right: Restriction
    text: request that we restrict our processing if we are processing your data based on legitimate interests
  - right: Opt-out of sale (California)
    text: California residents have the right to request that we stop "selling" their personal information.
  - right: Complaint to supervisory authority
    text: complain about our data collection or processing actions with the supervisor authority concerned.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: npm does not sell information about you to others.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Information we collect may be transferred to, and stored and processed in, the United States or any other country in which we or our affiliates or subcontractors maintain facilities, as described above.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: npm
provenance_date: '2026-11-10'
provider_name: npm
provider_slug: npm
slug: npm-privacy-policy
source_date: '2026-11-10'
source_filename: npm-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.npmjs.com/policies/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: npm\naid: npm\nurl: https://docs.npmjs.com/policies/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: To create an npm account, npm requires a working email address and an available user name.\n- category: contact\n  text: Those data usually include your name and email address, and may include your company or other affiliation.\n- category: financial\n  text: To sign up for paid services, npm requires your payment card data.\n- category: device\n  text: network request data, such as the date and time, your IP address, and the URL\n\
  - category: behavioral\n  text: npm uses cookies, server logs, and other methods to collect data about what pages you visit, and when.\n- category: location\n  text: However, we do collect imprecise location (e.g., your IP address).\npurposes:\n- purpose: fulfill requests and send security alerts\n  text: send you alerts about security vulnerabilities that may affect the software you're building, when you run\n    npm install or npm audit\n- purpose: provide account access and identification\n  text: npm uses this data to provide you access to features and identify you across npm services, publicly and\n    within npm.\n- purpose: charge for npm services\n  text: npm uses your payment card data only to charge for npm services.\n- purpose: optimize and secure website\n  text: optimize the website, so that it's quick and easy to use\nretention:\n- scope: payment card data\n  period: null\n  text: npm instructs Stripe to store your payment card data only as long as you use paid npm services.\n\
  residency:\n- region: United States\n  text: npm stores account data, data about website use, data about registry use, and private packages on servers\n    in the United States of America.\n- region: Enterprise registries\n  text: npm stores package data published to Enterprise registries that npm hosts, plus metadata about them, in\n    cloud computing zones of customers' choosing.\ntransfers:\n- mechanism: other\n  text: Information we collect may be transferred to, and stored and processed in, the United States or any other\n    country in which we or our affiliates or subcontractors maintain facilities, as described above.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Support ticket or account closure request via support\n  text: You can close your npm account at any time by e-mailing contacting support . Closing your account removes\n    the profile from the public registry but does not automatically erase packages\
  \ published under your account.\nrights:\n- right: Access\n  text: access to information held about you.\n- right: Correction\n  text: ask us to correct or amend inaccurate or incomplete information we have about you.\n- right: Erasure\n  text: ask us to erase data that under certain circumstances\n- right: Restriction\n  text: request that we restrict our processing if we are processing your data based on legitimate interests\n- right: Opt-out of sale (California)\n  text: California residents have the right to request that we stop \"selling\" their personal information.\n- right: Complaint to supervisory authority\n  text: complain about our data collection or processing actions with the supervisor authority concerned.\nsale_or_sharing:\n  stance: prohibited\n  text: npm does not sell information about you to others.\n"
source_yaml_url: https://artifacts.apis.io/npm/privacy/npm-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from npm's own page on 2026-11-10.
synthetic: false
tags:
- Packages
- JavaScript
- Node.js
- Package Management
- Registry
- Security
- Developer Tools
- npm
---
