---
api_specs:
- filename: hydrafetch-com-brand-api-openapi.yml
  format: yaml
  label: hydrafetch-com Brand API
  slug: hydrafetch-com-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-brand-api-openapi.yml
- filename: hydrafetch-com-crawl-batch-api-openapi.yml
  format: yaml
  label: hydrafetch-com Crawl & batch API
  slug: hydrafetch-com-crawl-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-crawl-batch-api-openapi.yml
- filename: hydrafetch-com-extract-api-openapi.yml
  format: yaml
  label: hydrafetch-com Extract API
  slug: hydrafetch-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-extract-api-openapi.yml
- filename: hydrafetch-com-feedback-api-openapi.yml
  format: yaml
  label: hydrafetch-com Feedback API
  slug: hydrafetch-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-feedback-api-openapi.yml
- filename: hydrafetch-com-logo-api-openapi.yml
  format: yaml
  label: hydrafetch-com Logo API
  slug: hydrafetch-com-logo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-logo-api-openapi.yml
- filename: hydrafetch-com-media-api-openapi.yml
  format: yaml
  label: hydrafetch-com Media API
  slug: hydrafetch-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-media-api-openapi.yml
- filename: hydrafetch-com-scrape-api-openapi.yml
  format: yaml
  label: hydrafetch-com Scrape API
  slug: hydrafetch-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-scrape-api-openapi.yml
- filename: hydrafetch-com-search-api-openapi.yml
  format: yaml
  label: hydrafetch-com Search API
  slug: hydrafetch-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydrafetch-com/openapi/hydrafetch-com-search-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account we collect your name, email address, and the workspace details you provide.
  - category: financial
    text: We receive and store records of your plan, credit balance, and invoices. We do not store full payment card numbers on our systems.
  - category: behavioral
    text: When you call the API we record the request you made (including the URLs or queries you submitted), the outcome, the credits consumed, and operational metadata such as timestamps, your API key identifier, and originating IP address.
  - category: identifying
    text: Between them these give us your name, email address, Google account identifier, and profile picture.
  - category: other
    text: We store the fetched raw content, including the page’s HTML, together with the outputs derived from it (Markdown, structured data, extractions).
  deletion:
    route: Account deletion or written request to the privacy contact
    text: When your account is deleted, we delete or de-identify the personal data associated with it within a reasonable period, except where we are legally required to keep it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the service and meter credits
    text: We use this to operate the service, meter credits, show you your own activity, enforce rate limits, and debug problems.
  - purpose: Google sign-in account creation
    text: We use them to create your account, identify you when you return, and contact you about the service.
  - purpose: Run and bill AI-assistant requests
    text: We store these requests and their results in your usage history, and use them to run the request, bill it to your workspace, show it to you in the dashboard, and keep the service secure
  retention:
  - period: 6 months
    scope: Request history
    text: Request history (each call, its status, cost and timing) 6 months
  - period: 180 days
    scope: Responses returned to you
    text: The responses we returned to you 180 days
  - period: 30 days
    scope: Fetched page content
    text: Fetched page content 30 days
  - period: 90 days after the job last changes
    scope: Crawl and batch results
    text: Crawl and batch results 90 days after the job last changes
  - period: 2 years
    scope: Credit usage records
    text: Credit usage records 2 years
  rights:
  - right: Access and update account information
    text: You can access and update your account information from the dashboard.
  - right: Request provision, correction or deletion
    text: You can ask us to provide, correct, or delete personal data we hold about you by writing to [email protected] .
  - right: Statutory rights
    text: Depending on where you live, you may have additional statutory rights; we will honour valid requests under applicable law.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use a small number of third-party providers: Provider Purpose Data involved Amazon Web Services (SES) Transactional and account email delivery Email address, email content Kelviq Subscription billing and payment processing Name, email address, billing details Cloudflare Content delivery, DNS, and network security IP address, request metadata'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: hydrafetch-com
provenance_date: '2026-11-09'
provider_name: hydrafetch-com
provider_slug: hydrafetch-com
slug: hydrafetch-com-privacy-policy
source_date: '2026-11-09'
source_filename: hydrafetch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hydrafetch.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: hydrafetch-com\naid: hydrafetch-com\nurl: https://hydrafetch.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account we collect your name, email address, and the workspace details you provide.\n- category: financial\n  text: We receive and store records of your plan, credit balance, and invoices. We do not store full payment card\n    numbers on our systems.\n- category: behavioral\n  text: When you call the API we record the request you made (including the URLs or queries you submitted), the\n    outcome,\
  \ the credits consumed, and operational metadata such as timestamps, your API key identifier, and originating\n    IP address.\n- category: identifying\n  text: Between them these give us your name, email address, Google account identifier, and profile picture.\n- category: other\n  text: We store the fetched raw content, including the page’s HTML, together with the outputs derived from it (Markdown,\n    structured data, extractions).\npurposes:\n- purpose: Operate the service and meter credits\n  text: We use this to operate the service, meter credits, show you your own activity, enforce rate limits, and\n    debug problems.\n- purpose: Google sign-in account creation\n  text: We use them to create your account, identify you when you return, and contact you about the service.\n- purpose: Run and bill AI-assistant requests\n  text: We store these requests and their results in your usage history, and use them to run the request, bill it\n    to your workspace, show it to you in the dashboard,\
  \ and keep the service secure\nretention:\n- scope: Request history\n  period: 6 months\n  text: Request history (each call, its status, cost and timing) 6 months\n- scope: Responses returned to you\n  period: 180 days\n  text: The responses we returned to you 180 days\n- scope: Fetched page content\n  period: 30 days\n  text: Fetched page content 30 days\n- scope: Crawl and batch results\n  period: 90 days after the job last changes\n  text: Crawl and batch results 90 days after the job last changes\n- scope: Credit usage records\n  period: 2 years\n  text: Credit usage records 2 years\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use a small number of third-party providers: Provider Purpose Data involved Amazon Web Services (SES)\n    Transactional and account email delivery Email address, email content Kelviq Subscription billing and payment\n    processing Name, email address, billing details Cloudflare Content delivery, DNS, and network security IP address,\n\
  \    request metadata'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or written request to the privacy contact\n  text: When your account is deleted, we delete or de-identify the personal data associated with it within a reasonable\n    period, except where we are legally required to keep it.\nrights:\n- right: Access and update account information\n  text: You can access and update your account information from the dashboard.\n- right: Request provision, correction or deletion\n  text: You can ask us to provide, correct, or delete personal data we hold about you by writing to [email protected]\n    .\n- right: Statutory rights\n  text: Depending on where you live, you may have additional statutory rights; we will honour valid requests under\n    applicable law.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hydrafetch-com/privacy/hydrafetch-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from hydrafetch-com's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- Automation
- Markdown
---
