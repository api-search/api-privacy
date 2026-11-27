---
api_specs:
- filename: letagentsin-com-c-api-openapi.yml
  format: yaml
  label: letagentsin-com C API
  slug: letagentsin-com-c-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-c-api-openapi.yml
- filename: letagentsin-com-corpus-csv-api-openapi.yml
  format: yaml
  label: letagentsin-com Corpus.csv API
  slug: letagentsin-com-corpus-csv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-corpus-csv-api-openapi.yml
- filename: letagentsin-com-corpus-json-api-openapi.yml
  format: yaml
  label: letagentsin-com Corpus.json API
  slug: letagentsin-com-corpus-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-corpus-json-api-openapi.yml
- filename: letagentsin-com-mcp-api-openapi.yml
  format: yaml
  label: letagentsin-com MCP API
  slug: letagentsin-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-mcp-api-openapi.yml
- filename: letagentsin-com-scan-api-openapi.yml
  format: yaml
  label: letagentsin-com Scan API
  slug: letagentsin-com-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-scan-api-openapi.yml
- filename: letagentsin-com-visibility-api-openapi.yml
  format: yaml
  label: letagentsin-com Visibility API
  slug: letagentsin-com-visibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-visibility-api-openapi.yml
- filename: letagentsin-com-watch-api-openapi.yml
  format: yaml
  label: letagentsin-com Watch API
  slug: letagentsin-com-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/letagentsin-com/openapi/letagentsin-com-watch-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact details , when you give them: an email address to send a scan result, to confirm a domain you asked us to watch, or to deliver something you bought.'
  - category: identifying
    text: An inquiry submission also includes your name, company or product, selected interest and message.
  - category: behavioral
    text: A page counter. A date, a path or the name of a button that was pressed, and whether the request looked like a browser, an unnamed client, or one of a short list of search and AI crawlers
  - category: device
    text: 'one word from a fixed list naming the family of client that asked: chrome , firefox , curl , python and a dozen others, or other when it is none of them.'
  deletion:
    route: Email hello@letagentsin.com
    text: Write to hello@letagentsin.com about anything on this page, including deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: scan and monitoring delivery
    text: 'An address given for monitoring is kept until you stop it: every email we send carries a stop link'
  - purpose: web analytics
    text: Cookieless web analytics. For browsers that run JavaScript, PostHog counts page views, approximate unique visitors
  - purpose: AI visibility audit
    text: When you run the beta, the brand, domain, product category, selected depth, prompts, answers and cited sources are saved with a random audit identifier in MongoDB.
  residency:
  - region: EU
    text: PostHog processes the request IP address and user-agent transiently to make a privacy-preserving identifier on its EU servers
  - region: EU
    text: Heroku (hosting, EU region)
  retention:
  - period: as long as they are published
    scope: Scan results
    text: Scan results are kept as long as they are published, because a permanent link that stops working is worse than one that ages.
  - period: until you stop it
    scope: Monitoring address
    text: An address given for monitoring is kept until you stop it
  - period: while the beta is being evaluated
    scope: Visibility audit jobs
    text: Visibility audit jobs and their answers are kept while the beta is being evaluated
  rights:
  - right: access, correction, deletion, portability, objection
    text: Access, correction, deletion, portability and objection, under the GDPR.
  - right: complain to authority
    text: You can also complain to your data protection authority.
  role:
    text: Krystian Gwizdała , a private individual in Poland , is the controller of the data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it to train anything.
  subprocessors:
    text: Who processes it for us Heroku (hosting, EU region), MongoDB Atlas (storage), Resend (scorecard and monitoring email delivery), Formspree (contact-form delivery), PostHog Cloud EU (cookieless aggregate web analytics), and, only when you run the visibility beta, the configured model providers Anthropic, OpenAI, Google and Perplexity.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: letagentsin-com
provenance_date: '2026-11-09'
provider_name: letagentsin-com
provider_slug: letagentsin-com
slug: letagentsin-com-privacy-policy
source_date: '2026-11-09'
source_filename: letagentsin-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://letagentsin.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: letagentsin-com\naid: letagentsin-com\nurl: https://letagentsin.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Krystian Gwizdała , a private individual in Poland , is the controller of the data described here.\ndata_categories:\n- category: contact\n  text: 'Contact details , when you give them: an email address to send a scan result, to confirm a domain you asked\n    us to watch, or to deliver something you bought.'\n- category: identifying\n  text: An inquiry submission also includes your name, company or product, selected interest and message.\n- category: behavioral\n  text:\
  \ A page counter. A date, a path or the name of a button that was pressed, and whether the request looked\n    like a browser, an unnamed client, or one of a short list of search and AI crawlers\n- category: device\n  text: 'one word from a fixed list naming the family of client that asked: chrome , firefox , curl , python and\n    a dozen others, or other when it is none of them.'\npurposes:\n- purpose: scan and monitoring delivery\n  text: 'An address given for monitoring is kept until you stop it: every email we send carries a stop link'\n- purpose: web analytics\n  text: Cookieless web analytics. For browsers that run JavaScript, PostHog counts page views, approximate unique\n    visitors\n- purpose: AI visibility audit\n  text: When you run the beta, the brand, domain, product category, selected depth, prompts, answers and cited sources\n    are saved with a random audit identifier in MongoDB.\nretention:\n- scope: Scan results\n  period: as long as they are published\n  text: Scan\
  \ results are kept as long as they are published, because a permanent link that stops working is worse\n    than one that ages.\n- scope: Monitoring address\n  period: until you stop it\n  text: An address given for monitoring is kept until you stop it\n- scope: Visibility audit jobs\n  period: while the beta is being evaluated\n  text: Visibility audit jobs and their answers are kept while the beta is being evaluated\nresidency:\n- region: EU\n  text: PostHog processes the request IP address and user-agent transiently to make a privacy-preserving identifier\n    on its EU servers\n- region: EU\n  text: Heroku (hosting, EU region)\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who processes it for us Heroku (hosting, EU region), MongoDB Atlas (storage), Resend (scorecard and monitoring\n    email delivery), Formspree (contact-form delivery), PostHog Cloud EU (cookieless aggregate web analytics), and,\n    only when you run the visibility beta, the configured model providers Anthropic,\
  \ OpenAI, Google and Perplexity.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@letagentsin.com\n  text: Write to hello@letagentsin.com about anything on this page, including deletion.\nrights:\n- right: access, correction, deletion, portability, objection\n  text: Access, correction, deletion, portability and objection, under the GDPR.\n- right: complain to authority\n  text: You can also complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it to train anything.\n"
source_yaml_url: https://artifacts.apis.io/letagentsin-com/privacy/letagentsin-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from letagentsin-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agent Audits
- Developer Tools
- API Testing
- Integration
---
