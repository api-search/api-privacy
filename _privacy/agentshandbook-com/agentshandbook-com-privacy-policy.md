---
api_specs:
- filename: agentshandbook-com-agents-api-openapi.yml
  format: yaml
  label: Agents Handbook Agents API
  slug: agentshandbook-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-agents-api-openapi.yml
- filename: agentshandbook-com-contributors-api-openapi.yml
  format: yaml
  label: Agents Handbook Contributors API
  slug: agentshandbook-com-contributors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-contributors-api-openapi.yml
- filename: agentshandbook-com-lessons-api-openapi.yml
  format: yaml
  label: Agents Handbook Lessons API
  slug: agentshandbook-com-lessons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-lessons-api-openapi.yml
- filename: agentshandbook-com-playbooks-api-openapi.yml
  format: yaml
  label: Agents Handbook Playbooks API
  slug: agentshandbook-com-playbooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-playbooks-api-openapi.yml
- filename: agentshandbook-com-runs-api-openapi.yml
  format: yaml
  label: Agents Handbook Runs API
  slug: agentshandbook-com-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-runs-api-openapi.yml
- filename: agentshandbook-com-search-api-openapi.yml
  format: yaml
  label: Agents Handbook Search API
  slug: agentshandbook-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-search-api-openapi.yml
- filename: agentshandbook-com-stats-api-openapi.yml
  format: yaml
  label: Agents Handbook Stats API
  slug: agentshandbook-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-stats-api-openapi.yml
- filename: agentshandbook-com-tasks-api-openapi.yml
  format: yaml
  label: Agents Handbook Tasks API
  slug: agentshandbook-com-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-tasks-api-openapi.yml
- filename: agentshandbook-com-votes-api-openapi.yml
  format: yaml
  label: Agents Handbook Votes API
  slug: agentshandbook-com-votes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentshandbook-com/openapi/agentshandbook-com-votes-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: contact
    text: 'we store what you send: the playbook, agent, outcome, the text you wrote, links, and an optional public handle and email.'
  - category: device
    text: Our host (Vercel) keeps standard server logs, such as IP address, user agent and the URL requested, for security and operations.
  - category: behavioral
    text: We count page visits with PostHog in cookieless mode, so nothing is stored on your device.
  deletion:
    route: email to hello@agentshandbook.com
    text: You can ask us to delete your reports, submissions, or contributor record
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the site and related operations
    text: To run the site, review and publish contributions, compute success rates, credit contributors by handle, prevent abuse, and contact you about your submission if you gave an email.
  retention:
  - period: while the site runs
    scope: submissions and reports
    text: We keep submissions and reports while the site runs.
  rights:
  - right: deletion
    text: You can ask us to delete your reports, submissions, or contributor record
  - right: access
    text: ask what we hold about you
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agents Handbook
provenance_date: '2026-11-09'
provider_name: Agents Handbook
provider_slug: agentshandbook-com
slug: agentshandbook-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentshandbook-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentshandbook.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agents Handbook\naid: agentshandbook-com\nurl: https://agentshandbook.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'we store what you send: the playbook, agent, outcome, the text you wrote, links, and an optional public\n    handle and email.'\n- category: device\n  text: Our host (Vercel) keeps standard server logs, such as IP address, user agent and the URL requested, for\n    security and operations.\n- category: behavioral\n  text: We count page visits with PostHog in cookieless mode, so nothing is stored on your device.\n\
  purposes:\n- purpose: run the site and related operations\n  text: To run the site, review and publish contributions, compute success rates, credit contributors by handle,\n    prevent abuse, and contact you about your submission if you gave an email.\nretention:\n- scope: submissions and reports\n  period: while the site runs\n  text: We keep submissions and reports while the site runs.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to hello@agentshandbook.com\n  text: You can ask us to delete your reports, submissions, or contributor record\nrights:\n- right: deletion\n  text: You can ask us to delete your reports, submissions, or contributor record\n- right: access\n  text: ask what we hold about you\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentshandbook-com/privacy/agentshandbook-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from Agents Handbook's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Playbooks
- Automation
- Community
---
