---
api_specs:
- filename: peoplesearch-im-credits-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Credits API
  slug: peoplesearch-im-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-credits-api-openapi.yml
- filename: peoplesearch-im-deliver-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Deliver API
  slug: peoplesearch-im-deliver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-deliver-api-openapi.yml
- filename: peoplesearch-im-email-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Email API
  slug: peoplesearch-im-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-email-api-openapi.yml
- filename: peoplesearch-im-reveal-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Reveal API
  slug: peoplesearch-im-reveal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-reveal-api-openapi.yml
- filename: peoplesearch-im-search-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Search API
  slug: peoplesearch-im-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-search-api-openapi.yml
- filename: peoplesearch-im-tools-api-openapi.yml
  format: yaml
  label: PeopleSearch.im Tools API
  slug: peoplesearch-im-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/peoplesearch-im/openapi/peoplesearch-im-tools-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name and email address, and your password, which our sign-in system stores only in hashed form.
  - category: contact
    text: a work email address with its verification status when one can be found
  - category: professional
    text: name, job title, headline and profile summary, current role and employer with details about that company
  - category: location
    text: general location (such as the city)
  - category: device
    text: the IP address and browser it came from
  - category: financial
    text: Your credit balance and a ledger of the credits granted, bought, spent and refunded.
  - category: behavioral
    text: the searches you run (the text you type and the filters we understood), the profiles you unlock
  deletion:
    route: email hello@peoplesearch.im or close account
    text: When you ask us to close your account, we delete or anonymize its data within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: 'provide the service: searches, profile unlocks, email lookups, credits, the API and the MCP server'
  - purpose: process payments
    text: process payments and keep an accurate credit ledger
  - purpose: security and abuse prevention
    text: keep the service secure and prevent abuse, for example with rate limits on free searches and on opt-out requests
  - purpose: account and service emails
    text: send account and service emails
  - purpose: aggregate analytics
    text: understand, in aggregate, how the service is used so we can improve it
  residency:
  - region: United States and European Union
    text: Our service providers process information in the United States and the European Union
  retention:
  - period: as long as your account is open
    scope: account data
    text: 'Account, search history, contacts, credit ledger and email logs: for as long as your account is open.'
  - period: 7 days
    scope: sign-in sessions
    text: 'Sign-in sessions: 7 days, deleted within a day after they expire.'
  - period: 90 days
    scope: API and MCP call records
    text: 'Record of API and MCP calls: 90 days, including the daily counts of calls made without an account.'
  - period: 180 days
    scope: analytics events
    text: 'Analytics events: 180 days.'
  - period: 30 days
    scope: rate-limit IP addresses
    text: 'IP addresses used for rate limits: 30 days on the website'
  - period: most recent 1,000 entries
    scope: error logs
    text: 'Error logs: only the most recent 1,000 entries.'
  rights:
  - right: access
    text: tell you whether we hold information about you and give you a copy
  - right: correction
    text: correct information that is wrong
  - right: deletion
    text: delete your information, or close your account
  - right: portability
    text: give you your information in a portable format
  - right: restriction or objection
    text: restrict or object to how we use it, including use based on legitimate interests
  - right: withdraw consent
    text: withdraw any consent you gave
  role:
    text: which is the controller of the personal information described here
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell customer information or share it for cross-context behavioral advertising.
  subprocessors:
    text: 'Icypeas (business data provider): receives the search filters and lookup inputs needed to answer a request'
    url: null
  transfers:
  - mechanism: SCC
    text: such as the European Commission's standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PeopleSearch.im
provenance_date: '2026-11-10'
provider_name: PeopleSearch.im
provider_slug: peoplesearch-im
slug: peoplesearch-im-privacy-policy
source_date: '2026-11-10'
source_filename: peoplesearch-im-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://peoplesearch.im/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PeopleSearch.im\naid: peoplesearch-im\nurl: https://peoplesearch.im/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: which is the controller of the personal information described here\ndata_categories:\n- category: identifying\n  text: Your name and email address, and your password, which our sign-in system stores only in hashed form.\n- category: contact\n  text: a work email address with its verification status when one can be found\n- category: professional\n  text: name, job title, headline and profile summary, current role and employer with details about that company\n- category:\
  \ location\n  text: general location (such as the city)\n- category: device\n  text: the IP address and browser it came from\n- category: financial\n  text: Your credit balance and a ledger of the credits granted, bought, spent and refunded.\n- category: behavioral\n  text: the searches you run (the text you type and the filters we understood), the profiles you unlock\npurposes:\n- purpose: provide the service\n  text: 'provide the service: searches, profile unlocks, email lookups, credits, the API and the MCP server'\n- purpose: process payments\n  text: process payments and keep an accurate credit ledger\n- purpose: security and abuse prevention\n  text: keep the service secure and prevent abuse, for example with rate limits on free searches and on opt-out\n    requests\n- purpose: account and service emails\n  text: send account and service emails\n- purpose: aggregate analytics\n  text: understand, in aggregate, how the service is used so we can improve it\nretention:\n- scope: account\
  \ data\n  period: as long as your account is open\n  text: 'Account, search history, contacts, credit ledger and email logs: for as long as your account is open.'\n- scope: sign-in sessions\n  period: 7 days\n  text: 'Sign-in sessions: 7 days, deleted within a day after they expire.'\n- scope: API and MCP call records\n  period: 90 days\n  text: 'Record of API and MCP calls: 90 days, including the daily counts of calls made without an account.'\n- scope: analytics events\n  period: 180 days\n  text: 'Analytics events: 180 days.'\n- scope: rate-limit IP addresses\n  period: 30 days\n  text: 'IP addresses used for rate limits: 30 days on the website'\n- scope: error logs\n  period: most recent 1,000 entries\n  text: 'Error logs: only the most recent 1,000 entries.'\nresidency:\n- region: United States and European Union\n  text: Our service providers process information in the United States and the European Union\ntransfers:\n- mechanism: SCC\n  text: such as the European Commission's standard\
  \ contractual clauses\nsubprocessors:\n  url: null\n  text: 'Icypeas (business data provider): receives the search filters and lookup inputs needed to answer a request'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@peoplesearch.im or close account\n  text: When you ask us to close your account, we delete or anonymize its data within 30 days.\nrights:\n- right: access\n  text: tell you whether we hold information about you and give you a copy\n- right: correction\n  text: correct information that is wrong\n- right: deletion\n  text: delete your information, or close your account\n- right: portability\n  text: give you your information in a portable format\n- right: restriction or objection\n  text: restrict or object to how we use it, including use based on legitimate interests\n- right: withdraw consent\n  text: withdraw any consent you gave\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell customer information or share it for cross-context\
  \ behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/peoplesearch-im/privacy/peoplesearch-im-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from PeopleSearch.im's own page on 2026-11-10.
synthetic: false
tags:
- Company
- People Search
- Email Lookup
- Artificial Intelligence
- Software-as-a-Service
---
