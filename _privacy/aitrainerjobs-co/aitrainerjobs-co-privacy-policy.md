---
api_specs:
- filename: aitrainerjobs-co-categories-api-openapi.yml
  format: yaml
  label: AI Trainer Jobs Categories API
  slug: aitrainerjobs-co-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitrainerjobs-co/openapi/aitrainerjobs-co-categories-api-openapi.yml
- filename: aitrainerjobs-co-jobs-api-openapi.yml
  format: yaml
  label: AI Trainer Jobs Jobs API
  slug: aitrainerjobs-co-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitrainerjobs-co/openapi/aitrainerjobs-co-jobs-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: device
    text: For each click, I store the job, the time, your country, the address of the page you came from, and your browser's user agent (the browser and system name your browser sends).
  - category: behavioral
    text: Page views. When you open a page, the site adds 1 to that day's total of page views.
  - category: communication
    text: Tool inputs travel in the request body, not in the web address, and my code never logs the body.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Find requested jobs and companies
    text: 'Tool and API inputs: to find the jobs and companies you asked for.'
  - purpose: Rate limiting and service availability
    text: 'IP addresses: to apply rate limits and keep the service up for everyone.'
  - purpose: Usage and bot detection
    text: 'Page views and apply clicks: to see which pages and jobs people use, to spot bot traffic, and to show the public totals on the stats page.'
  - purpose: Job alerts
    text: 'Signup data: only to send the job alerts you asked for, once alerts start.'
  - purpose: Problem fixing
    text: 'Error and request logs: to find and fix problems.'
  residency:
  - region: Brazil
    text: I run the site from Brazil.
  retention:
  - period: null
    scope: MCP and API inputs
    text: 'MCP and API inputs: not kept. They exist only while the request runs.'
  - period: null
    scope: IP addresses for rate limits
    text: 'IP addresses for rate limits: used for a one-minute count in memory, never written to storage.'
  - period: 12 months
    scope: Apply click records
    text: 'Apply click records: 12 months. The site deletes older records automatically every day.'
  - period: 12 months
    scope: Daily page view and visit totals
    text: 'Daily page view and visit totals: 12 months.'
  - period: null
    scope: Signup data
    text: 'Signup data: until you ask me to delete it.'
  rights:
  - right: access, correction, deletion, objection
    text: You can ask to see, correct, or delete any data I hold about you, or ask me to stop using it.
  - right: complaint to authority
    text: If you're not happy with my answer, you can also complain to the data protection authority where you live. In Brazil, that's the ANPD.
  role:
    text: I decide how your data is used.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: I don't sell or rent personal data, and I don't share it with advertisers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Cloudflare serves it from data centers around the world, so your requests may be handled in another country, and the services above may process data in the United States and elsewhere.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Trainer Jobs
provenance_date: '2026-11-09'
provider_name: AI Trainer Jobs
provider_slug: aitrainerjobs-co
slug: aitrainerjobs-co-privacy-policy
source_date: '2026-11-09'
source_filename: aitrainerjobs-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aitrainerjobs.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Trainer Jobs\naid: aitrainerjobs-co\nurl: https://aitrainerjobs.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: I decide how your data is used.\ndata_categories:\n- category: device\n  text: For each click, I store the job, the time, your country, the address of the page you came from, and your\n    browser's user agent (the browser and system name your browser sends).\n- category: behavioral\n  text: Page views. When you open a page, the site adds 1 to that day's total of page views.\n- category: communication\n  text: Tool inputs travel in the request body, not in the web address,\
  \ and my code never logs the body.\npurposes:\n- purpose: Find requested jobs and companies\n  text: 'Tool and API inputs: to find the jobs and companies you asked for.'\n- purpose: Rate limiting and service availability\n  text: 'IP addresses: to apply rate limits and keep the service up for everyone.'\n- purpose: Usage and bot detection\n  text: 'Page views and apply clicks: to see which pages and jobs people use, to spot bot traffic, and to show the\n    public totals on the stats page.'\n- purpose: Job alerts\n  text: 'Signup data: only to send the job alerts you asked for, once alerts start.'\n- purpose: Problem fixing\n  text: 'Error and request logs: to find and fix problems.'\nretention:\n- scope: MCP and API inputs\n  period: null\n  text: 'MCP and API inputs: not kept. They exist only while the request runs.'\n- scope: IP addresses for rate limits\n  period: null\n  text: 'IP addresses for rate limits: used for a one-minute count in memory, never written to storage.'\n- scope:\
  \ Apply click records\n  period: 12 months\n  text: 'Apply click records: 12 months. The site deletes older records automatically every day.'\n- scope: Daily page view and visit totals\n  period: 12 months\n  text: 'Daily page view and visit totals: 12 months.'\n- scope: Signup data\n  period: null\n  text: 'Signup data: until you ask me to delete it.'\nresidency:\n- region: Brazil\n  text: I run the site from Brazil.\ntransfers:\n- mechanism: other\n  text: Cloudflare serves it from data centers around the world, so your requests may be handled in another country,\n    and the services above may process data in the United States and elsewhere.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correction, deletion, objection\n  text: You can ask to see, correct, or delete any data I hold about you, or ask me to stop using it.\n- right: complaint to authority\n  text: If you're\
  \ not happy with my answer, you can also complain to the data protection authority where you live.\n    In Brazil, that's the ANPD.\nsale_or_sharing:\n  stance: prohibited\n  text: I don't sell or rent personal data, and I don't share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/aitrainerjobs-co/privacy/aitrainerjobs-co-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AI Trainer Jobs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Training
- Job
- Remote
- Marketplace
---
