---
api_specs:
- filename: azurade-com-account-api-openapi.yml
  format: yaml
  label: Azurade AI Account API
  slug: azurade-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-account-api-openapi.yml
- filename: azurade-com-generations-api-openapi.yml
  format: yaml
  label: Azurade AI Generations API
  slug: azurade-com-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-generations-api-openapi.yml
- filename: azurade-com-models-api-openapi.yml
  format: yaml
  label: Azurade AI Models API
  slug: azurade-com-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-models-api-openapi.yml
- filename: azurade-com-prompts-api-openapi.yml
  format: yaml
  label: Azurade AI Prompts API
  slug: azurade-com-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-prompts-api-openapi.yml
- filename: azurade-com-uploads-api-openapi.yml
  format: yaml
  label: Azurade AI Uploads API
  slug: azurade-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azurade-com/openapi/azurade-com-uploads-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, and if you sign in with Google or Facebook, the name, email and profile picture that provider shares with us.
  - category: communication
    text: The prompts you write, the images and videos you upload as inputs, and the images and videos you generate.
  - category: financial
    text: the payment status, card brand and last four digits that our merchant of record, Dodo Payments, passes back to us.
  - category: device
    text: Server logs, with the IP address, browser and device details that arrive with every request.
  - category: behavioral
    text: Once you sign in, PostHog events are tied to your account id, email and name
  deletion:
    route: Email legal@azurade.com from the address you signed up with
    text: To close your account, email legal@azurade.com from the address you signed up with. We delete the account, its generation records and the generated files within 30 days.
  dpa:
    available: true
    text: or, if you use the Service through our API on behalf of a business, for a data-processing agreement (DPA).
    url: null
  purposes:
  - purpose: Create and run your account; provide the Service
    text: Create and run your account; provide the Service Performance of a contract
  - purpose: Turn prompts into images and videos
    text: Turn your prompts and inputs into images and videos, including the optional prompt-improvement step (section 4)
  - purpose: Sell subscriptions and process payments
    text: Sell subscriptions and credit packs; process payments and refunds
  - purpose: Keep the Service secure and prevent fraud
    text: Keep the Service secure; find and fix bugs; prevent fraud and abuse
  - purpose: Measure site and product use
    text: Measure how the site and the product are used
  residency:
  - region: European Union
    text: Our application, its database and every file you upload or generate are stored on servers in the European Union
  - region: Netherlands
    text: our Umami analytics instance runs on a server in the Netherlands
  retention:
  - period: as long as the account is open
    scope: Account, gallery and generation records
    text: Your account, gallery and generation records stay for as long as the account is open.
  - period: 5 days
    scope: Application logs
    text: Application logs are kept for 5 days, web-server access logs for up to 90 days.
  - period: up to 90 days
    scope: Web-server access logs
    text: Application logs are kept for 5 days, web-server access logs for up to 90 days.
  - period: six years
    scope: Purchase records
    text: Records of purchases stay for as long as Cyprus tax and accounting law requires, which is currently six years.
  rights:
  - right: access
    text: You can ask us for a copy of your personal data
  - right: correction or deletion
    text: ask us to correct or delete it
  - right: restriction or objection
    text: restrict or object to how we use it
  - right: portability
    text: receive it in a portable format
  - right: withdraw consent
    text: Where we rely on consent you can withdraw it at any time
  role:
    text: The data controller is Dubir Group LTD , a company registered in the Republic of Cyprus
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, and we do not “share” it in the sense used by US state privacy laws
  subprocessors:
    text: Write to legal@azurade.com for the current list of sub-processors
    url: null
  transfers:
  - mechanism: SCC
    text: For those transfers we rely on the European Commission's Standard Contractual Clauses or on an adequacy decision
  - mechanism: DPF
    text: which includes the EU-US Data Privacy Framework where the provider is certified under it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Azurade AI
provenance_date: '2026-11-09'
provider_name: Azurade AI
provider_slug: azurade-com
slug: azurade-com-privacy-policy
source_date: '2026-11-09'
source_filename: azurade-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://azurade.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Azurade AI\naid: azurade-com\nurl: https://azurade.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Dubir Group LTD , a company registered in the Republic of Cyprus\ndata_categories:\n- category: contact\n  text: Your email address, and if you sign in with Google or Facebook, the name, email and profile picture that\n    provider shares with us.\n- category: communication\n  text: The prompts you write, the images and videos you upload as inputs, and the images and videos you generate.\n- category: financial\n  text: the payment status, card brand and\
  \ last four digits that our merchant of record, Dodo Payments, passes back\n    to us.\n- category: device\n  text: Server logs, with the IP address, browser and device details that arrive with every request.\n- category: behavioral\n  text: Once you sign in, PostHog events are tied to your account id, email and name\npurposes:\n- purpose: Create and run your account; provide the Service\n  text: Create and run your account; provide the Service Performance of a contract\n- purpose: Turn prompts into images and videos\n  text: Turn your prompts and inputs into images and videos, including the optional prompt-improvement step (section\n    4)\n- purpose: Sell subscriptions and process payments\n  text: Sell subscriptions and credit packs; process payments and refunds\n- purpose: Keep the Service secure and prevent fraud\n  text: Keep the Service secure; find and fix bugs; prevent fraud and abuse\n- purpose: Measure site and product use\n  text: Measure how the site and the product are used\n\
  retention:\n- scope: Account, gallery and generation records\n  period: as long as the account is open\n  text: Your account, gallery and generation records stay for as long as the account is open.\n- scope: Application logs\n  period: 5 days\n  text: Application logs are kept for 5 days, web-server access logs for up to 90 days.\n- scope: Web-server access logs\n  period: up to 90 days\n  text: Application logs are kept for 5 days, web-server access logs for up to 90 days.\n- scope: Purchase records\n  period: six years\n  text: Records of purchases stay for as long as Cyprus tax and accounting law requires, which is currently six\n    years.\nresidency:\n- region: European Union\n  text: Our application, its database and every file you upload or generate are stored on servers in the European\n    Union\n- region: Netherlands\n  text: our Umami analytics instance runs on a server in the Netherlands\ntransfers:\n- mechanism: SCC\n  text: For those transfers we rely on the European Commission's\
  \ Standard Contractual Clauses or on an adequacy\n    decision\n- mechanism: DPF\n  text: which includes the EU-US Data Privacy Framework where the provider is certified under it.\nsubprocessors:\n  url: null\n  text: Write to legal@azurade.com for the current list of sub-processors\ndpa:\n  available: true\n  url: null\n  text: or, if you use the Service through our API on behalf of a business, for a data-processing agreement (DPA).\ndeletion:\n  route: Email legal@azurade.com from the address you signed up with\n  text: To close your account, email legal@azurade.com from the address you signed up with. We delete the account,\n    its generation records and the generated files within 30 days.\nrights:\n- right: access\n  text: You can ask us for a copy of your personal data\n- right: correction or deletion\n  text: ask us to correct or delete it\n- right: restriction or objection\n  text: restrict or object to how we use it\n- right: portability\n  text: receive it in a portable format\n\
  - right: withdraw consent\n  text: Where we rely on consent you can withdraw it at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, and we do not “share” it in the sense used by US state privacy laws\n"
source_yaml_url: https://artifacts.apis.io/azurade-com/privacy/azurade-com-privacy-policy.yml
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
- sale_or_sharing
summary_line: 28 quoted statements, read from Azurade AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Platform
- Creative
---
