---
api_specs:
- filename: tako-agent-api-openapi.yml
  format: yaml
  label: Tako Agent API
  slug: tako-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tako/openapi/tako-agent-api-openapi.yml
- filename: tako-tako-api-openapi.yml
  format: yaml
  label: Tako API
  slug: tako-tako-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tako/openapi/tako-tako-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: communication
    text: Communications that we exchange with you, including when you contact us with questions, feedback, or otherwise.
  deletion:
    route: Delete account at tako.com/account/general; privacy requests via privacy@tako.com
    text: You can delete your account at tako.com/account/general .
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Service inquiries
    text: Provide, operate, and improve the Services and our business.
  - purpose: Research and development
    text: We may create aggregated, de-identified, or anonymous data from personal information to analyze and improve the Services and promote our business.
  - purpose: Marketing and advertising
    text: Interest-based advertising. We and our advertising partners may use cookies and similar technologies to collect information over time across the web and serve you personalized ads.
  - purpose: Compliance and protection
    text: Complying with legal obligations and responding to lawful requests (e.g., subpoenas).
  - purpose: Training search models
    text: We use Queries to provide the Services and to evaluate and improve them, including by training the search and ranking models that power the Services.
  retention:
  - period: while your account is active
    scope: Account data
    text: 'Account data : while your account is active.'
  - period: until you ask us to delete them
    scope: Charts you create
    text: 'Charts you create : until you ask us to delete them.'
  - period: up to one year
    scope: Aggregate chart view counts
    text: Aggregate chart view counts, which don't include IP addresses, are kept for up to one year.
  rights:
  - right: access or deletion
    text: To request access to or deletion of your personal information, including Queries and charts, contact us using the details in "How to Contact Us."
  - right: opt out of marketing
    text: You may opt out of marketing-related communications by following the unsubscribe instructions in any marketing message we send you.
  role:
    text: we also process consumer personal information as a service provider on behalf of those customers
    value: both
  sale_or_sharing:
    stance: unstated
    text: To delete your personal information or stop Tako from selling or sharing it, submit a privacy request .
  subprocessors:
    text: We list our approved subprocessors at tako.com/legal/subprocessors .
    url: tako.com/legal/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tako
provenance_date: '2026-11-10'
provider_name: Tako
provider_slug: tako
slug: tako-privacy-policy
source_date: '2026-11-10'
source_filename: tako-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tako.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tako\naid: tako\nurl: https://tako.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we also process consumer personal information as a service provider on behalf of those customers\ndata_categories:\n- category: communication\n  text: Communications that we exchange with you, including when you contact us with questions, feedback, or otherwise.\npurposes:\n- purpose: Service inquiries\n  text: Provide, operate, and improve the Services and our business.\n- purpose: Research and development\n  text: We may create aggregated, de-identified, or anonymous data from personal information to\
  \ analyze and improve\n    the Services and promote our business.\n- purpose: Marketing and advertising\n  text: Interest-based advertising. We and our advertising partners may use cookies and similar technologies to\n    collect information over time across the web and serve you personalized ads.\n- purpose: Compliance and protection\n  text: Complying with legal obligations and responding to lawful requests (e.g., subpoenas).\n- purpose: Training search models\n  text: We use Queries to provide the Services and to evaluate and improve them, including by training the search\n    and ranking models that power the Services.\nretention:\n- scope: Account data\n  period: while your account is active\n  text: 'Account data : while your account is active.'\n- scope: Charts you create\n  period: until you ask us to delete them\n  text: 'Charts you create : until you ask us to delete them.'\n- scope: Aggregate chart view counts\n  period: up to one year\n  text: Aggregate chart view counts, which\
  \ don't include IP addresses, are kept for up to one year.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: tako.com/legal/subprocessors\n  text: We list our approved subprocessors at tako.com/legal/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: Delete account at tako.com/account/general; privacy requests via privacy@tako.com\n  text: You can delete your account at tako.com/account/general .\nrights:\n- right: access or deletion\n  text: To request access to or deletion of your personal information, including Queries and charts, contact us\n    using the details in \"How to Contact Us.\"\n- right: opt out of marketing\n  text: You may opt out of marketing-related communications by following the unsubscribe instructions in any marketing\n    message we send you.\nsale_or_sharing:\n  stance: unstated\n  text: To delete your personal information or stop Tako from selling or sharing it, submit a privacy request .\n"
source_yaml_url: https://artifacts.apis.io/tako/privacy/tako-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
summary_line: 15 quoted statements, read from Tako's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data
- Search
- Answer Engine
- Financial Data
- Knowledge Graph
- Agents
- MCP
- Data Visualization
---
