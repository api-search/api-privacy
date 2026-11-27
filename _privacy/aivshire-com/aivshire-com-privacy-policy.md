---
api_specs:
- filename: aivshire-com-calculator-api-openapi.yml
  format: yaml
  label: AI vs Hire Calculator API
  slug: aivshire-com-calculator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivshire-com/openapi/aivshire-com-calculator-api-openapi.yml
- filename: aivshire-com-enquiry-api-openapi.yml
  format: yaml
  label: AI vs Hire Enquiry API
  slug: aivshire-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivshire-com/openapi/aivshire-com-enquiry-api-openapi.yml
- filename: aivshire-com-mcp-api-openapi.yml
  format: yaml
  label: AI vs Hire MCP API
  slug: aivshire-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivshire-com/openapi/aivshire-com-mcp-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: we store the details you enter (with a timestamp and the page you sent it from) to answer it
  - category: contact
    text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when
  - category: behavioral
    text: We measure pages, referrers, device class and tool usage server-side
  - category: communication
    text: 'Raw inbound email: 12 months, then deleted.'
  deletion:
    route: email enquiries@aivshire.com with the address you used
    text: email enquiries@aivshire.com with the address you used
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer enquiries
    text: to answer it and, where you ask us to, to pass it to a relevant provider
  - purpose: email updates
    text: We email you only about what that sentence names.
  - purpose: emailing a result
    text: If you ask us to email you a result from a calculator or a checker, we send it to you once.
  - purpose: aggregate analytics
    text: 'Analytics : first-party, cookieless and aggregate.'
  residency:
  - region: EU
    text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).
  retention:
  - period: 24 months
    scope: enquiries
    text: 'Enquiries: 24 months from when you send them, then deleted.'
  - period: 12 months
    scope: raw inbound email
    text: 'Raw inbound email: 12 months, then deleted.'
  - period: kept while you are subscribed
    scope: email updates
    text: 'Email updates: kept while you are subscribed.'
  - period: 6 years after the enquiry is deleted
    scope: consent records
    text: kept for 6 years after the enquiry is deleted
  - period: indefinitely
    scope: aggregate analytics
    text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'
  rights:
  - right: access, correction, erasure
    text: You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time
  - right: complaint to ICO
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell data, run third-party advertising, or load third-party scripts on this site.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI vs Hire
provenance_date: '2026-11-09'
provider_name: AI vs Hire
provider_slug: aivshire-com
slug: aivshire-com-privacy-policy
source_date: '2026-11-09'
source_filename: aivshire-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aivshire.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI vs Hire\naid: aivshire-com\nurl: https://aivshire.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.\ndata_categories:\n- category: contact\n  text: we store the details you enter (with a timestamp and the page you sent it from) to answer it\n- category: contact\n  text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when\n\
  - category: behavioral\n  text: We measure pages, referrers, device class and tool usage server-side\n- category: communication\n  text: 'Raw inbound email: 12 months, then deleted.'\npurposes:\n- purpose: answer enquiries\n  text: to answer it and, where you ask us to, to pass it to a relevant provider\n- purpose: email updates\n  text: We email you only about what that sentence names.\n- purpose: emailing a result\n  text: If you ask us to email you a result from a calculator or a checker, we send it to you once.\n- purpose: aggregate analytics\n  text: 'Analytics : first-party, cookieless and aggregate.'\nretention:\n- scope: enquiries\n  period: 24 months\n  text: 'Enquiries: 24 months from when you send them, then deleted.'\n- scope: raw inbound email\n  period: 12 months\n  text: 'Raw inbound email: 12 months, then deleted.'\n- scope: email updates\n  period: kept while you are subscribed\n  text: 'Email updates: kept while you are subscribed.'\n- scope: consent records\n  period:\
  \ 6 years after the enquiry is deleted\n  text: kept for 6 years after the enquiry is deleted\n- scope: aggregate analytics\n  period: indefinitely\n  text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'\nresidency:\n- region: EU\n  text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email enquiries@aivshire.com with the address you used\n  text: email enquiries@aivshire.com with the address you used\nrights:\n- right: access, correction, erasure\n  text: You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time\n- right: complaint to ICO\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell data, run third-party advertising, or load third-party scripts on this site.\n"
source_yaml_url: https://artifacts.apis.io/aivshire-com/privacy/aivshire-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AI vs Hire's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Hiring
- Cost Comparison
- Finance
- Automation
---
