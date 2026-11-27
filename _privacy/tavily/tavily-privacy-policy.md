---
api_specs:
- filename: tavily-crawl-api-openapi.yml
  format: yaml
  label: Tavily Crawl API
  slug: tavily-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-crawl-api-openapi.yml
- filename: tavily-extract-api-openapi.yml
  format: yaml
  label: Tavily Extract API
  slug: tavily-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-extract-api-openapi.yml
- filename: tavily-map-api-openapi.yml
  format: yaml
  label: Tavily Map API
  slug: tavily-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-map-api-openapi.yml
- filename: tavily-research-api-openapi.yml
  format: yaml
  label: Tavily Research API
  slug: tavily-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-research-api-openapi.yml
- filename: tavily-search-api-openapi.yml
  format: yaml
  label: Tavily Search API
  slug: tavily-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tavily/openapi/tavily-search-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect, from you, your personal identifiers (such as name, email address) and a selected password
  - category: financial
    text: your sensitive financial information (such as credit/debit card number, security code, expiration date)
  - category: device
    text: your online identifiers (IP address, browser type, operating system)
  - category: behavioral
    text: your internet or other electronic network activity information (usage data (e.g., timestamps, interactions with the Platform))
  - category: communication
    text: your query data and any documents you upload to the Platform
  - category: professional
    text: For enterprise subscriptions we also collect from the client your professional or employment-related information (such as job title, company name, industry, phone number, location)
  deletion:
    route: email request to support@tavily.com
    text: If at any point you wish to withdraw your consent, you can do so by contacting us at support@tavily.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management and access
    text: We use this information to create and maintain your account, communicate with you, and facilitate your access to the Services.
  - purpose: retrieve content for queries
    text: We use this information to retrieve relevant content from the Internet in response to your query.
  - purpose: improve query responses
    text: we may use certain portions of your query data to improve our responses to future queries.
  residency:
  - region: United States
    text: Some of the service providers that we engage for the provision of our Services (as described above) are located in the United States
  retention:
  - period: null
    scope: general personal information
    text: we retain your personal information (i) for as long as you maintain an account with us, (ii) until we receive a valid request to delete the information
  rights:
  - right: access
    text: Right to access. For any of the processing described above, you have the right to ask us for copies of your personal information.
  - right: rectification
    text: Right to rectification. For any of the processing described above, you have the right to ask us to rectify personal information you think is inaccurate or incomplete.
  - right: erasure
    text: Right to erasure. When we use cookies and other trackers or send you marketing emails, you have the right to request erasure of your personal information
  - right: restrict processing
    text: Right to restrict processing. For any of the processing described above
  - right: object to processing
    text: Right to object to processing. You have the right to object to our processing of your personal information when the legal basis for the processing is pursuant to our legitimate interests
  - right: portability
    text: Right to data portability. You have the right to ask that we transfer the personal information you gave us from one organization to another or give it to you.
  - right: opt out of targeted advertising and sale/sharing
    text: 'Right to Opt Out. You have the right to opt out of the processing of your personal information for the purposes of: (i) targeted advertising; (ii) profiling through solely automated decision making; and (iii) the sale or sharing of your personal information to third parties.'
  role:
    text: the entity responsible for the collection and use (processing) of your personal information is AlphaAI Technologies Inc., the data controller.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Such sharing may be deemed a sale or sharing (i.e. disclosure for targeted advertising purposes) under state data privacy laws.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: These include implementing the European Commission’s Standard Contractual Clauses (and UK Addendum) for transfers of personal information with our service providers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tavily
provenance_date: '2026-11-10'
provider_name: Tavily
provider_slug: tavily
slug: tavily-privacy-policy
source_date: '2026-11-10'
source_filename: tavily-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tavily.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tavily\naid: tavily\nurl: https://www.tavily.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: the entity responsible for the collection and use (processing) of your personal information is AlphaAI Technologies\n    Inc., the data controller.\ndata_categories:\n- category: identifying\n  text: we collect, from you, your personal identifiers (such as name, email address) and a selected password\n- category: financial\n  text: your sensitive financial information (such as credit/debit card number, security code, expiration date)\n- category: device\n  text: your online identifiers (IP address,\
  \ browser type, operating system)\n- category: behavioral\n  text: your internet or other electronic network activity information (usage data (e.g., timestamps, interactions\n    with the Platform))\n- category: communication\n  text: your query data and any documents you upload to the Platform\n- category: professional\n  text: For enterprise subscriptions we also collect from the client your professional or employment-related information\n    (such as job title, company name, industry, phone number, location)\npurposes:\n- purpose: account management and access\n  text: We use this information to create and maintain your account, communicate with you, and facilitate your access\n    to the Services.\n- purpose: retrieve content for queries\n  text: We use this information to retrieve relevant content from the Internet in response to your query.\n- purpose: improve query responses\n  text: we may use certain portions of your query data to improve our responses to future queries.\nretention:\n\
  - scope: general personal information\n  period: null\n  text: we retain your personal information (i) for as long as you maintain an account with us, (ii) until we receive\n    a valid request to delete the information\nresidency:\n- region: United States\n  text: Some of the service providers that we engage for the provision of our Services (as described above) are\n    located in the United States\ntransfers:\n- mechanism: SCC\n  text: These include implementing the European Commission’s Standard Contractual Clauses (and UK Addendum) for\n    transfers of personal information with our service providers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to support@tavily.com\n  text: If at any point you wish to withdraw your consent, you can do so by contacting us at support@tavily.com.\nrights:\n- right: access\n  text: Right to access. For any of the processing described above, you have the right to ask\
  \ us for copies of your\n    personal information.\n- right: rectification\n  text: Right to rectification. For any of the processing described above, you have the right to ask us to rectify\n    personal information you think is inaccurate or incomplete.\n- right: erasure\n  text: Right to erasure. When we use cookies and other trackers or send you marketing emails, you have the right\n    to request erasure of your personal information\n- right: restrict processing\n  text: Right to restrict processing. For any of the processing described above\n- right: object to processing\n  text: Right to object to processing. You have the right to object to our processing of your personal information\n    when the legal basis for the processing is pursuant to our legitimate interests\n- right: portability\n  text: Right to data portability. You have the right to ask that we transfer the personal information you gave\n    us from one organization to another or give it to you.\n- right: opt out of\
  \ targeted advertising and sale/sharing\n  text: 'Right to Opt Out. You have the right to opt out of the processing of your personal information for the\n    purposes of: (i) targeted advertising; (ii) profiling through solely automated decision making; and (iii) the\n    sale or sharing of your personal information to third parties.'\nsale_or_sharing:\n  stance: conditional\n  text: Such sharing may be deemed a sale or sharing (i.e. disclosure for targeted advertising purposes) under state\n    data privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/tavily/privacy/tavily-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Tavily's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Web Search
- AI Agents
- LLM
- Extract
- Crawl
- Sitemap
- Research
- REST
- LangChain
- LlamaIndex
- Real-Time
- A2A
---
