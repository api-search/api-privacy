---
api_specs:
- filename: serpapi-account-api-openapi.yml
  format: yaml
  label: SerpApi Account API
  slug: serpapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpapi/openapi/serpapi-account-api-openapi.yml
- filename: serpapi-search-api-openapi.yml
  format: yaml
  label: SerpApi Search API
  slug: serpapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpapi/openapi/serpapi-search-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect the personal information you give us such as your name, address and email address
  - category: device
    text: we also automatically receive your computer's internet protocol (IP) address in order to provide us with information that helps us learn about your browser and operating system
  - category: behavioral
    text: 'Google Analytics : analytics cookies that help us measure website usage and improve our service.'
  deletion:
    route: email privacy@serpapi.com
    text: To submit a data-deletion request, contact us at privacy@serpapi.com.
  dpa:
    available: true
    text: customers may request our current DPA by contacting privacy@serpapi.com.
    url: null
  purposes:
  - purpose: transaction processing
    text: we imply that you consent to our collecting it and using it for that specific reason only
  - purpose: email marketing
    text: With your permission, we may send you emails about our website, new products and other updates.
  - purpose: customer data processing on behalf of customers
    text: Customer PII processed by SerpApi on behalf of customers is used only for the purpose of providing the contracted services and is not used by SerpApi for unrelated marketing or advertising purposes.
  residency:
  - region: United States
    text: SerpApi is located in the United States.
  retention:
  - period: 31 days
    scope: search data
    text: Search data is retained for 31 days after the search is completed, after which it expires and is deleted automatically.
  rights:
  - right: access, correction, and deletion
    text: 'Access, correction, and deletion requests : email privacy@serpapi.com with the subject "Privacy Request".'
  - right: withdraw consent
    text: you may withdraw your consent for us to contact you, for the continued collection, use or disclosure of your information, at anytime
  - right: complaint to data protection authority
    text: you may lodge a complaint with your local data protection authority.
  role:
    text: When you purchase something from our website, as part of the buying and selling process, we collect the personal information you give us such as your name, address and email address.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use the following subprocessors that may process customer personal information: Amazon Web Services : cloud infrastructure and website hosting'
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses, or equivalent transfer mechanisms
  - mechanism: adequacy
    text: such as adequacy decisions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SerpApi
provenance_date: '2026-11-10'
provider_name: SerpApi
provider_slug: serpapi
slug: serpapi-privacy-policy
source_date: '2026-11-10'
source_filename: serpapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://serpapi.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SerpApi\naid: serpapi\nurl: https://serpapi.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When you purchase something from our website, as part of the buying and selling process, we collect the\n    personal information you give us such as your name, address and email address.\ndata_categories:\n- category: contact\n  text: we collect the personal information you give us such as your name, address and email address\n- category: device\n  text: we also automatically receive your computer's internet protocol (IP) address in order to provide us with\n    information that helps us learn about\
  \ your browser and operating system\n- category: behavioral\n  text: 'Google Analytics : analytics cookies that help us measure website usage and improve our service.'\npurposes:\n- purpose: transaction processing\n  text: we imply that you consent to our collecting it and using it for that specific reason only\n- purpose: email marketing\n  text: With your permission, we may send you emails about our website, new products and other updates.\n- purpose: customer data processing on behalf of customers\n  text: Customer PII processed by SerpApi on behalf of customers is used only for the purpose of providing the contracted\n    services and is not used by SerpApi for unrelated marketing or advertising purposes.\nretention:\n- scope: search data\n  period: 31 days\n  text: Search data is retained for 31 days after the search is completed, after which it expires and is deleted\n    automatically.\nresidency:\n- region: United States\n  text: SerpApi is located in the United States.\ntransfers:\n\
  - mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses, or equivalent transfer mechanisms\n- mechanism: adequacy\n  text: such as adequacy decisions\nsubprocessors:\n  url: null\n  text: 'We use the following subprocessors that may process customer personal information: Amazon Web Services\n    : cloud infrastructure and website hosting'\ndpa:\n  available: true\n  url: null\n  text: customers may request our current DPA by contacting privacy@serpapi.com.\ndeletion:\n  route: email privacy@serpapi.com\n  text: To submit a data-deletion request, contact us at privacy@serpapi.com.\nrights:\n- right: access, correction, and deletion\n  text: 'Access, correction, and deletion requests : email privacy@serpapi.com with the subject \"Privacy Request\".'\n- right: withdraw consent\n  text: you may withdraw your consent for us to contact you, for the continued collection, use or disclosure of\n    your information, at anytime\n- right: complaint to data protection authority\n\
  \  text: you may lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/serpapi/privacy/serpapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 17 quoted statements, read from SerpApi's own page on 2026-11-10.
synthetic: false
tags:
- Bing
- Google
- Search
- Search Engines
- SERP
- Web Scraping
- AI Agents
- MCP
- Markdown
- Baidu
- DuckDuckGo
- YouTube
- Amazon
---
