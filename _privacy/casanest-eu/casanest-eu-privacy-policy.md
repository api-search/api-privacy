---
api_specs:
- filename: casanest-eu-public-api-openapi.yml
  format: yaml
  label: CasaNest Public API
  slug: casanest-eu-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casanest-eu/openapi/casanest-eu-public-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect the name, email, telephone number (if you give it) and the message you write.
  - category: identifying
    text: We collect email, name, telephone number and, for agencies, the company details (company name, AMI licence, address, contact details).
  - category: device
    text: Our servers automatically log IP addresses, the date and time of requests and browser type.
  - category: location
    text: the approximate country you are writing from — worked out from the IP address by the network that serves the site (Cloudflare); we keep only the country, never the address
  deletion:
    route: Write to the controller's privacy address to exercise erasure rights
    text: To exercise any of these rights, write to [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Passing enquiries to advertisers
    text: 'This data serves a single purpose: passing your enquiry on to the advertiser of the property or business concerned, so that they can reply to you.'
  - purpose: Replying to contact page messages
    text: 'This data stays with us and serves a single purpose: replying to you.'
  - purpose: Sending valuation requests to chosen agency
    text: 'They serve a single purpose: sending the request to the agency you chose'
  - purpose: Newsletter
    text: We use your email to send periodic CasaNest news and updates, on the basis of the explicit consent you confirm by email.
  - purpose: Security and abuse protection
    text: 'This is used to keep the service secure and running, and to detect abuse. Legal basis: our legitimate interest in protecting the portal.'
  residency:
  - region: European Union
    text: Hosting provider (Hetzner Online GmbH, servers in the European Union), where the portal and the database reside.
  retention:
  - period: 24 months
    scope: Enquiries sent to advertisers
    text: Enquiries sent to advertisers — 24 months after sending, so that complaints can be resolved and consent can be proven.
  - period: 30 days
    scope: Technical server logs
    text: Technical server logs — 30 days.
  - period: 12 months
    scope: Account data
    text: Account data — for as long as the account exists, and 12 months after it is closed.
  - period: 90 days
    scope: WhatsApp support conversations
    text: WhatsApp support conversations — 90 days
  rights:
  - right: access
    text: find out what data we hold about you and obtain a copy ( access )
  - right: rectification
    text: correct anything that is wrong or incomplete ( rectification )
  - right: erasure
    text: ask for it to be deleted ( erasure )
  - right: restriction
    text: ask us to stop using it while you contest it ( restriction )
  - right: objection
    text: object to processing based on legitimate interest
  - right: portability
    text: receive the data you gave us in an open format, or ask us to send it to another provider ( portability )
  - right: withdraw consent
    text: withdraw your consent where that was the basis for the processing
  role:
    text: 'Data controller: Joviano Miguel Ascenso Silva NIF (Portuguese tax number) 209167254'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data , nor do we pass it on for third-party advertising.
  subprocessors:
    text: Hosting provider (Hetzner Online GmbH, servers in the European Union)
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers outside the European Union are covered by the Standard Contractual Clauses approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CasaNest
provenance_date: '2026-11-09'
provider_name: CasaNest
provider_slug: casanest-eu
slug: casanest-eu-privacy-policy
source_date: '2026-11-09'
source_filename: casanest-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://casanest.eu/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CasaNest\naid: casanest-eu\nurl: https://casanest.eu/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data controller: Joviano Miguel Ascenso Silva NIF (Portuguese tax number) 209167254'\ndata_categories:\n- category: contact\n  text: We collect the name, email, telephone number (if you give it) and the message you write.\n- category: identifying\n  text: We collect email, name, telephone number and, for agencies, the company details (company name, AMI licence,\n    address, contact details).\n- category: device\n  text: Our servers automatically log IP addresses, the date and time\
  \ of requests and browser type.\n- category: location\n  text: the approximate country you are writing from — worked out from the IP address by the network that serves\n    the site (Cloudflare); we keep only the country, never the address\npurposes:\n- purpose: Passing enquiries to advertisers\n  text: 'This data serves a single purpose: passing your enquiry on to the advertiser of the property or business\n    concerned, so that they can reply to you.'\n- purpose: Replying to contact page messages\n  text: 'This data stays with us and serves a single purpose: replying to you.'\n- purpose: Sending valuation requests to chosen agency\n  text: 'They serve a single purpose: sending the request to the agency you chose'\n- purpose: Newsletter\n  text: We use your email to send periodic CasaNest news and updates, on the basis of the explicit consent you confirm\n    by email.\n- purpose: Security and abuse protection\n  text: 'This is used to keep the service secure and running, and to detect\
  \ abuse. Legal basis: our legitimate interest\n    in protecting the portal.'\nretention:\n- scope: Enquiries sent to advertisers\n  period: 24 months\n  text: Enquiries sent to advertisers — 24 months after sending, so that complaints can be resolved and consent\n    can be proven.\n- scope: Technical server logs\n  period: 30 days\n  text: Technical server logs — 30 days.\n- scope: Account data\n  period: 12 months\n  text: Account data — for as long as the account exists, and 12 months after it is closed.\n- scope: WhatsApp support conversations\n  period: 90 days\n  text: WhatsApp support conversations — 90 days\nresidency:\n- region: European Union\n  text: Hosting provider (Hetzner Online GmbH, servers in the European Union), where the portal and the database\n    reside.\ntransfers:\n- mechanism: SCC\n  text: Transfers outside the European Union are covered by the Standard Contractual Clauses approved by the European\n    Commission.\nsubprocessors:\n  url: null\n  text: Hosting\
  \ provider (Hetzner Online GmbH, servers in the European Union)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to the controller's privacy address to exercise erasure rights\n  text: To exercise any of these rights, write to [email protected] .\nrights:\n- right: access\n  text: find out what data we hold about you and obtain a copy ( access )\n- right: rectification\n  text: correct anything that is wrong or incomplete ( rectification )\n- right: erasure\n  text: ask for it to be deleted ( erasure )\n- right: restriction\n  text: ask us to stop using it while you contest it ( restriction )\n- right: objection\n  text: object to processing based on legitimate interest\n- right: portability\n  text: receive the data you gave us in an open format, or ask us to send it to another provider ( portability )\n- right: withdraw consent\n  text: withdraw your consent where that was the basis for the processing\nsale_or_sharing:\n  stance: prohibited\n  text: We never\
  \ sell your data , nor do we pass it on for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/casanest-eu/privacy/casanest-eu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from CasaNest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Property Listings
- Portugal
- PropTech
- CRM Integration
- MCP
- Housing Statistics
---
