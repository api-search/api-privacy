---
api_specs:
- filename: coupondroid-com-a2a-api-openapi.yml
  format: yaml
  label: Coupondroid A2a API
  slug: coupondroid-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-a2a-api-openapi.yml
- filename: coupondroid-com-auth-md-api-openapi.yml
  format: yaml
  label: Coupondroid Auth.md API
  slug: coupondroid-com-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-auth-md-api-openapi.yml
- filename: coupondroid-com-llms-txt-api-openapi.yml
  format: yaml
  label: Coupondroid Llms.txt API
  slug: coupondroid-com-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-llms-txt-api-openapi.yml
- filename: coupondroid-com-mcp-api-openapi.yml
  format: yaml
  label: Coupondroid MCP API
  slug: coupondroid-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-mcp-api-openapi.yml
- filename: coupondroid-com-well-known-api-openapi.yml
  format: yaml
  label: Coupondroid .well Known API
  slug: coupondroid-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coupondroid-com/openapi/coupondroid-com-well-known-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address , if you subscribe to the newsletter. That is the only field we ask for.
  - category: identifying
    text: 'Whatever is in a message you send us: your address, your name if you sign it, and what you wrote.'
  - category: device
    text: 'Server logs: IP address, browser and operating system, referring page, and which pages you opened and when.'
  - category: behavioral
    text: 'Usage measurement: which pages and coupons get clicked, roughly which region you are in, and whether you use a phone or a desktop.'
  deletion:
    route: email privacy contact
    text: Email [email protected] from the address you want us to look up and say what you want.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the site
    text: 'To run the site: serve pages, keep the coupon list current, remember your cookie choice, block abuse.'
  - purpose: understand what works
    text: 'To understand what works: aggregated numbers show which stores and pages people need.'
  - purpose: affiliate commission
    text: 'To pay for it: when you click a deal, an affiliate network records the referral so the store can pay us a commission.'
  - purpose: newsletter and replies
    text: To send the newsletter, if and only if you asked, and to answer you when you write in.
  residency:
  - region: outside the United States
    text: Coupondroid is operated from outside the United States and uses providers here and in Europe
  retention:
  - period: 12 months
    scope: server logs
    text: 'Server logs: up to 12 months, then deleted or stripped of identifiers'
  - period: until you unsubscribe
    scope: newsletter addresses
    text: 'Newsletter addresses: until you unsubscribe, plus a suppression record'
  - period: 24 months
    scope: emails you send us
    text: 'Emails you send us: up to 24 months, longer only while an issue is open.'
  rights:
  - right: know what was collected
    text: California residents can know what we collected and who we disclosed it to
  - right: delete
    text: delete it subject to the statutory exceptions
  - right: correct
    text: correct what is inaccurate
  - right: opt out of sale or sharing
    text: opt out of the sale or sharing of personal information
  - right: appeal
    text: California, Virginia, Colorado and Connecticut residents can appeal by replying with “Appeal” in the subject
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information for money.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coupondroid
provenance_date: '2026-11-09'
provider_name: Coupondroid
provider_slug: coupondroid-com
slug: coupondroid-com-privacy-policy
source_date: '2026-11-09'
source_filename: coupondroid-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coupondroid.com/corp/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coupondroid\naid: coupondroid-com\nurl: https://coupondroid.com/corp/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address , if you subscribe to the newsletter. That is the only field we ask for.\n- category: identifying\n  text: 'Whatever is in a message you send us: your address, your name if you sign it, and what you wrote.'\n- category: device\n  text: 'Server logs: IP address, browser and operating system, referring page, and which pages you opened and when.'\n- category: behavioral\n  text: 'Usage measurement:\
  \ which pages and coupons get clicked, roughly which region you are in, and whether you\n    use a phone or a desktop.'\npurposes:\n- purpose: run the site\n  text: 'To run the site: serve pages, keep the coupon list current, remember your cookie choice, block abuse.'\n- purpose: understand what works\n  text: 'To understand what works: aggregated numbers show which stores and pages people need.'\n- purpose: affiliate commission\n  text: 'To pay for it: when you click a deal, an affiliate network records the referral so the store can pay us\n    a commission.'\n- purpose: newsletter and replies\n  text: To send the newsletter, if and only if you asked, and to answer you when you write in.\nretention:\n- scope: server logs\n  period: 12 months\n  text: 'Server logs: up to 12 months, then deleted or stripped of identifiers'\n- scope: newsletter addresses\n  period: until you unsubscribe\n  text: 'Newsletter addresses: until you unsubscribe, plus a suppression record'\n- scope: emails you\
  \ send us\n  period: 24 months\n  text: 'Emails you send us: up to 24 months, longer only while an issue is open.'\nresidency:\n- region: outside the United States\n  text: Coupondroid is operated from outside the United States and uses providers here and in Europe\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy contact\n  text: Email [email protected] from the address you want us to look up and say what you want.\nrights:\n- right: know what was collected\n  text: California residents can know what we collected and who we disclosed it to\n- right: delete\n  text: delete it subject to the statutory exceptions\n- right: correct\n  text: correct what is inaccurate\n- right: opt out of sale or sharing\n  text: opt out of the sale or sharing of personal information\n- right: appeal\n  text: California, Virginia, Colorado and Connecticut residents can appeal by replying with “Appeal” in the subject\n\
  sale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information for money.\n"
source_yaml_url: https://artifacts.apis.io/coupondroid-com/privacy/coupondroid-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Coupondroid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coupons
- Deals
- E-Commerce
- Shopping
- Affiliate Marketing
- MCP
- AI Agents
---
