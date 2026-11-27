---
api_specs:
- filename: agentickeychain-com-capabilities-api-openapi.yml
  format: yaml
  label: Agentic Keychain Capabilities API
  slug: agentickeychain-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-capabilities-api-openapi.yml
- filename: agentickeychain-com-compare-api-openapi.yml
  format: yaml
  label: Agentic Keychain Compare API
  slug: agentickeychain-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-compare-api-openapi.yml
- filename: agentickeychain-com-evaluate-api-openapi.yml
  format: yaml
  label: Agentic Keychain Evaluate API
  slug: agentickeychain-com-evaluate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-evaluate-api-openapi.yml
- filename: agentickeychain-com-outcome-api-openapi.yml
  format: yaml
  label: Agentic Keychain Outcome API
  slug: agentickeychain-com-outcome-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-outcome-api-openapi.yml
- filename: agentickeychain-com-quote-api-openapi.yml
  format: yaml
  label: Agentic Keychain Quote API
  slug: agentickeychain-com-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-quote-api-openapi.yml
- filename: agentickeychain-com-resolve-api-openapi.yml
  format: yaml
  label: Agentic Keychain Resolve API
  slug: agentickeychain-com-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-resolve-api-openapi.yml
- filename: agentickeychain-com-roi-api-openapi.yml
  format: yaml
  label: Agentic Keychain Roi API
  slug: agentickeychain-com-roi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-roi-api-openapi.yml
- filename: agentickeychain-com-unlock-api-openapi.yml
  format: yaml
  label: Agentic Keychain Unlock API
  slug: agentickeychain-com-unlock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentickeychain-com/openapi/agentickeychain-com-unlock-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: the operator processes your e-mail address, your name if you give it, the content of your message
  - category: financial
    text: the price of the linked quote
  - category: device
    text: a client family taken from the User-Agent (a fixed list)
  - category: behavioral
    text: for searches and evaluations only the words that are in a fixed vocabulary
  deletion:
    route: email request to operator
    text: You can ask for access to your personal data, its rectification or erasure, restriction of its processing and data portability.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: license check and purchase records
    text: 'Checking a license key, recording the purchase it unlocks and issuing download links: to perform the contract with the buyer (GDPR article 6(1)(b)).'
  - purpose: security and abuse prevention
    text: 'Rate limits and the access log: to keep the service secure and available and to stop abuse (article 6(1)(f)).'
  - purpose: registry improvement
    text: 'Usage events and counts: to keep the service secure, to see how agents find, evaluate and buy capabilities, and to improve the registry (article 6(1)(f)).'
  residency:
  - region: Netherlands
    text: TransIP B.V. hosts the server in the Netherlands and processes the data above on the operator's behalf, as processor.
  retention:
  - period: 14 days
    scope: usage events
    text: Kept 14 days.
  - period: 90 days
    scope: quote, unlock, download and outcome-report events
    text: 'Quote, unlock, download and outcome-report events, with the same fields plus the quote, evaluation and purchase references and the list price: kept 90 days.'
  - period: 2557 days
    scope: purchase records
    text: Kept 2557 days after the first unlock (about 7 years); the retention job then deletes them.
  - period: 730 days
    scope: e-mail to the operator
    text: keeps them 730 days (about 2 years) after the request is handled
  - period: 14 days
    scope: rotated access log files
    text: a rotated file is deleted at a later rotation once it is more than 14 days old
  rights:
  - right: access
    text: You can ask for access to your personal data
  - right: rectification or erasure
    text: its rectification or erasure
  - right: objection
    text: You can object at any time, on grounds relating to your situation
  - right: complaint
    text: You can also lodge a complaint with the Dutch data protection authority, the Autoriteit Persoonsgegevens
  role:
    text: Vayu Solutions, van Pijkerenlaan 28, 8096 VE Oldebroek, the Netherlands, Chamber of Commerce (KvK) number 67490395, is the controller of the personal data described on this page.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: applies the European Commission's standard contractual clauses (Implementing Decision (EU) 2021/914) to it
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentic Keychain
provenance_date: '2026-11-09'
provider_name: Agentic Keychain
provider_slug: agentickeychain-com
slug: agentickeychain-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentickeychain-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentickeychain.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentic Keychain\naid: agentickeychain-com\nurl: https://agentickeychain.com/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Vayu Solutions, van Pijkerenlaan 28, 8096 VE Oldebroek, the Netherlands, Chamber of Commerce (KvK) number\n    67490395, is the controller of the personal data described on this page.\ndata_categories:\n- category: contact\n  text: the operator processes your e-mail address, your name if you give it, the content of your message\n- category: financial\n  text: the price of the linked quote\n- category: device\n  text: a client family taken from the User-Agent\
  \ (a fixed list)\n- category: behavioral\n  text: for searches and evaluations only the words that are in a fixed vocabulary\npurposes:\n- purpose: license check and purchase records\n  text: 'Checking a license key, recording the purchase it unlocks and issuing download links: to perform the contract\n    with the buyer (GDPR article 6(1)(b)).'\n- purpose: security and abuse prevention\n  text: 'Rate limits and the access log: to keep the service secure and available and to stop abuse (article 6(1)(f)).'\n- purpose: registry improvement\n  text: 'Usage events and counts: to keep the service secure, to see how agents find, evaluate and buy capabilities,\n    and to improve the registry (article 6(1)(f)).'\nretention:\n- scope: usage events\n  period: 14 days\n  text: Kept 14 days.\n- scope: quote, unlock, download and outcome-report events\n  period: 90 days\n  text: 'Quote, unlock, download and outcome-report events, with the same fields plus the quote, evaluation and\n    purchase references\
  \ and the list price: kept 90 days.'\n- scope: purchase records\n  period: 2557 days\n  text: Kept 2557 days after the first unlock (about 7 years); the retention job then deletes them.\n- scope: e-mail to the operator\n  period: 730 days\n  text: keeps them 730 days (about 2 years) after the request is handled\n- scope: rotated access log files\n  period: 14 days\n  text: a rotated file is deleted at a later rotation once it is more than 14 days old\nresidency:\n- region: Netherlands\n  text: TransIP B.V. hosts the server in the Netherlands and processes the data above on the operator's behalf,\n    as processor.\ntransfers:\n- mechanism: SCC\n  text: applies the European Commission's standard contractual clauses (Implementing Decision (EU) 2021/914) to\n    it\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to operator\n  text: You can ask for access to your personal data, its rectification or erasure,\
  \ restriction of its processing\n    and data portability.\nrights:\n- right: access\n  text: You can ask for access to your personal data\n- right: rectification or erasure\n  text: its rectification or erasure\n- right: objection\n  text: You can object at any time, on grounds relating to your situation\n- right: complaint\n  text: You can also lodge a complaint with the Dutch data protection authority, the Autoriteit Persoonsgegevens\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentickeychain-com/privacy/agentickeychain-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Agentic Keychain's own page on 2026-11-09.
synthetic: false
tags:
- Autonomous Trading
- Blockchain
- Finance
- Solana
- Base
---
