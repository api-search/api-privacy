---
api_specs:
- filename: surfingdog-ai-census-api-openapi.yml
  format: yaml
  label: surfingdog-ai Census API
  slug: surfingdog-ai-census-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-census-api-openapi.yml
- filename: surfingdog-ai-directory-api-openapi.yml
  format: yaml
  label: surfingdog-ai Directory API
  slug: surfingdog-ai-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-directory-api-openapi.yml
- filename: surfingdog-ai-integrations-api-openapi.yml
  format: yaml
  label: surfingdog-ai Integrations API
  slug: surfingdog-ai-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-integrations-api-openapi.yml
- filename: surfingdog-ai-keys-api-openapi.yml
  format: yaml
  label: surfingdog-ai Keys API
  slug: surfingdog-ai-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-keys-api-openapi.yml
- filename: surfingdog-ai-owner-api-openapi.yml
  format: yaml
  label: surfingdog-ai Owner API
  slug: surfingdog-ai-owner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-owner-api-openapi.yml
- filename: surfingdog-ai-owners-api-openapi.yml
  format: yaml
  label: surfingdog-ai Owners API
  slug: surfingdog-ai-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-owners-api-openapi.yml
- filename: surfingdog-ai-products-api-openapi.yml
  format: yaml
  label: surfingdog-ai Products API
  slug: surfingdog-ai-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-products-api-openapi.yml
- filename: surfingdog-ai-public-api-openapi.yml
  format: yaml
  label: surfingdog-ai Public API
  slug: surfingdog-ai-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-public-api-openapi.yml
- filename: surfingdog-ai-reports-api-openapi.yml
  format: yaml
  label: surfingdog-ai Reports API
  slug: surfingdog-ai-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-reports-api-openapi.yml
- filename: surfingdog-ai-rules-api-openapi.yml
  format: yaml
  label: surfingdog-ai Rules API
  slug: surfingdog-ai-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-rules-api-openapi.yml
- filename: surfingdog-ai-score-api-openapi.yml
  format: yaml
  label: surfingdog-ai Score API
  slug: surfingdog-ai-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-score-api-openapi.yml
- filename: surfingdog-ai-setup-api-openapi.yml
  format: yaml
  label: surfingdog-ai Setup API
  slug: surfingdog-ai-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-setup-api-openapi.yml
- filename: surfingdog-ai-stays-api-openapi.yml
  format: yaml
  label: surfingdog-ai Stays API
  slug: surfingdog-ai-stays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfingdog-ai/openapi/surfingdog-ai-stays-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: A new customer's email address , when a customer books or orders with an email and their assistant carries no pass.
  - category: identifying
    text: Which Google account it is (Google's own id for it, and its email address)
  - category: location
    text: when you are busy on your main calendar, as start and end times only, never what an event is called, who is in it or where
  - category: device
    text: the kind of assistant or software that sent it (such as Claude or ChatGPT) and its version
  - category: behavioral
    text: how many businesses it found, in which order, and whether on its first page
  deletion:
    route: Write to privacy@surfingdog.ai
    text: Write to privacy@surfingdog.ai and we will answer within a month.
  dpa:
    available: true
    text: under the processing agreement
    url: null
  purposes:
  - purpose: Operating the inbox and calendar sync
    text: Your inbox adds it to your calendar (the service, the customer's name, the time, and a link to the booking in your inbox)
  - purpose: Improving search
    text: we keep a record of the call, to improve search
  - purpose: Keeping the service up and stopping abuse
    text: Our servers keep technical logs to keep the site up and stop abuse
  - purpose: Website visit counting
    text: We count visits to this website with Cloudflare Web Analytics
  residency:
  - region: European Union
    text: On an inbox we host, this database and its backups are in the European Union.
  retention:
  - period: no time limit
    scope: Searches by AI agents
    text: we keep a record of the call, to improve search, with no time limit
  - period: 90 days
    scope: Check records of a new read of a site
    text: The record of each new read of a site is deleted after 90 days.
  - period: 90 days
    scope: Network hourly messages
    text: The hourly messages, with the internet address they came from, for 90 days.
  - period: 90 days
    scope: Phone relay records
    text: deletes a phone nothing reached for 90 days
  - period: 400 days
    scope: Delivered business requests record
    text: 'We keep a record that it was delivered: when, to which business, which kind of request and how it went, never who sent it or what it said, for 400 days.'
  - period: 24 hours
    scope: Sign-in sessions
    text: Sign-in sessions for 24 hours, and emailed codes for ten minutes.
  rights:
  - right: Access
    text: ask for a copy of what we hold about you
  - right: Correction or deletion
    text: ask us to correct or delete it
  - right: Objection
    text: object to what we do with it
  role:
    text: You are the controller of the data your customers send your hosted inbox, and we are your processor, under the processing agreement . For your own account we are the controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell it, use it for advertising, or use it to train AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: surfingdog-ai
provenance_date: '2026-11-10'
provider_name: surfingdog-ai
provider_slug: surfingdog-ai
slug: surfingdog-ai-privacy-policy
source_date: '2026-11-10'
source_filename: surfingdog-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://surfingdog.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: surfingdog-ai\naid: surfingdog-ai\nurl: https://surfingdog.ai/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: You are the controller of the data your customers send your hosted inbox, and we are your processor, under\n    the processing agreement . For your own account we are the controller\ndata_categories:\n- category: contact\n  text: A new customer's email address , when a customer books or orders with an email and their assistant carries\n    no pass.\n- category: identifying\n  text: Which Google account it is (Google's own id for it, and its email address)\n- category: location\n\
  \  text: when you are busy on your main calendar, as start and end times only, never what an event is called, who\n    is in it or where\n- category: device\n  text: the kind of assistant or software that sent it (such as Claude or ChatGPT) and its version\n- category: behavioral\n  text: how many businesses it found, in which order, and whether on its first page\npurposes:\n- purpose: Operating the inbox and calendar sync\n  text: Your inbox adds it to your calendar (the service, the customer's name, the time, and a link to the booking\n    in your inbox)\n- purpose: Improving search\n  text: we keep a record of the call, to improve search\n- purpose: Keeping the service up and stopping abuse\n  text: Our servers keep technical logs to keep the site up and stop abuse\n- purpose: Website visit counting\n  text: We count visits to this website with Cloudflare Web Analytics\nretention:\n- scope: Searches by AI agents\n  period: no time limit\n  text: we keep a record of the call, to improve\
  \ search, with no time limit\n- scope: Check records of a new read of a site\n  period: 90 days\n  text: The record of each new read of a site is deleted after 90 days.\n- scope: Network hourly messages\n  period: 90 days\n  text: The hourly messages, with the internet address they came from, for 90 days.\n- scope: Phone relay records\n  period: 90 days\n  text: deletes a phone nothing reached for 90 days\n- scope: Delivered business requests record\n  period: 400 days\n  text: 'We keep a record that it was delivered: when, to which business, which kind of request and how it went,\n    never who sent it or what it said, for 400 days.'\n- scope: Sign-in sessions\n  period: 24 hours\n  text: Sign-in sessions for 24 hours, and emailed codes for ten minutes.\nresidency:\n- region: European Union\n  text: On an inbox we host, this database and its backups are in the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: under\
  \ the processing agreement\ndeletion:\n  route: Write to privacy@surfingdog.ai\n  text: Write to privacy@surfingdog.ai and we will answer within a month.\nrights:\n- right: Access\n  text: ask for a copy of what we hold about you\n- right: Correction or deletion\n  text: ask us to correct or delete it\n- right: Objection\n  text: object to what we do with it\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell it, use it for advertising, or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/surfingdog-ai/privacy/surfingdog-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from surfingdog-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Directory
- Inbox
---
