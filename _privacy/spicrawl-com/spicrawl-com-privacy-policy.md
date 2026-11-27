---
api_specs:
- filename: spicrawl-com-batch-api-openapi.yml
  format: yaml
  label: spicrawl-com Batch API
  slug: spicrawl-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-batch-api-openapi.yml
- filename: spicrawl-com-browser-api-openapi.yml
  format: yaml
  label: spicrawl-com Browser API
  slug: spicrawl-com-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-browser-api-openapi.yml
- filename: spicrawl-com-fleet-api-openapi.yml
  format: yaml
  label: spicrawl-com Fleet API
  slug: spicrawl-com-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-fleet-api-openapi.yml
- filename: spicrawl-com-health-api-openapi.yml
  format: yaml
  label: spicrawl-com Health API
  slug: spicrawl-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-health-api-openapi.yml
- filename: spicrawl-com-requests-api-openapi.yml
  format: yaml
  label: spicrawl-com Requests API
  slug: spicrawl-com-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-requests-api-openapi.yml
- filename: spicrawl-com-scrape-api-openapi.yml
  format: yaml
  label: spicrawl-com Scrape API
  slug: spicrawl-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-scrape-api-openapi.yml
- filename: spicrawl-com-sessions-api-openapi.yml
  format: yaml
  label: spicrawl-com Sessions API
  slug: spicrawl-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-sessions-api-openapi.yml
- filename: spicrawl-com-usage-api-openapi.yml
  format: yaml
  label: spicrawl-com Usage API
  slug: spicrawl-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicrawl-com/openapi/spicrawl-com-usage-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: your email address and, if you give it, your name.'
  - category: contact
    text: 'Messages: what you send us through the contact form or by email.'
  - category: device
    text: 'Sign-in information: when you sign up or sign in, we record the time, how you signed in, and your IP address and browser details.'
  - category: behavioral
    text: 'Request information: the requests you make, including the URLs you ask us to fetch, the result status, timing, credits used and which API key was used.'
  - category: professional
    text: 'Optional answers: your role, company and intended use, if you choose to give them when you start.'
  - category: financial
    text: We do not collect payment card details.
  deletion:
    route: Email support@spicrawl.com
    text: To ask about your data, or to have it corrected or deleted, email support@spicrawl.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run and secure the service
    text: To run and secure the service, show you your usage, answer your questions and improve Spicrawl.
  - purpose: Website analytics
    text: We use this information to improve the website.
  retention:
  - period: 48 hours
    scope: Cached pages
    text: cached pages are kept for up to 48 hours
  - period: 72 hours (3 days)
    scope: Batch job results
    text: batch job results expire after 72 hours (3 days)
  - period: null
    scope: Request logs
    text: Request logs are kept for a limited period, shown in your dashboard.
  - period: null
    scope: Other data
    text: Other data is kept while it is needed to run your account.
  rights:
  - right: Access, correction or deletion
    text: To ask about your data, or to have it corrected or deleted, email support@spicrawl.com .
  - right: Revoke API keys and remove team members
    text: You can revoke API keys and remove team members in the dashboard.
  - right: Disconnect connected apps
    text: You can disconnect an app at any time under Settings → Connected apps.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: spicrawl-com
provenance_date: '2026-11-10'
provider_name: spicrawl-com
provider_slug: spicrawl-com
slug: spicrawl-com-privacy-policy
source_date: '2026-11-10'
source_filename: spicrawl-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://spicrawl.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: spicrawl-com\naid: spicrawl-com\nurl: https://spicrawl.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account details: your email address and, if you give it, your name.'\n- category: contact\n  text: 'Messages: what you send us through the contact form or by email.'\n- category: device\n  text: 'Sign-in information: when you sign up or sign in, we record the time, how you signed in, and your IP address\n    and browser details.'\n- category: behavioral\n  text: 'Request information: the requests you make, including the URLs\
  \ you ask us to fetch, the result status,\n    timing, credits used and which API key was used.'\n- category: professional\n  text: 'Optional answers: your role, company and intended use, if you choose to give them when you start.'\n- category: financial\n  text: We do not collect payment card details.\npurposes:\n- purpose: Run and secure the service\n  text: To run and secure the service, show you your usage, answer your questions and improve Spicrawl.\n- purpose: Website analytics\n  text: We use this information to improve the website.\nretention:\n- scope: Cached pages\n  period: 48 hours\n  text: cached pages are kept for up to 48 hours\n- scope: Batch job results\n  period: 72 hours (3 days)\n  text: batch job results expire after 72 hours (3 days)\n- scope: Request logs\n  period: null\n  text: Request logs are kept for a limited period, shown in your dashboard.\n- scope: Other data\n  period: null\n  text: Other data is kept while it is needed to run your account.\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@spicrawl.com\n  text: To ask about your data, or to have it corrected or deleted, email support@spicrawl.com .\nrights:\n- right: Access, correction or deletion\n  text: To ask about your data, or to have it corrected or deleted, email support@spicrawl.com .\n- right: Revoke API keys and remove team members\n  text: You can revoke API keys and remove team members in the dashboard.\n- right: Disconnect connected apps\n  text: You can disconnect an app at any time under Settings → Connected apps.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/spicrawl-com/privacy/spicrawl-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from spicrawl-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- Automation
- Artificial Intelligence
---
