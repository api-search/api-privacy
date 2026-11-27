---
api_specs:
- filename: orkas-audio-api-openapi.yml
  format: yaml
  label: Orkas Audio API
  slug: orkas-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-audio-api-openapi.yml
- filename: orkas-images-api-openapi.yml
  format: yaml
  label: Orkas Images API
  slug: orkas-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-images-api-openapi.yml
- filename: orkas-openapi-json-api-openapi.yml
  format: yaml
  label: Orkas Openapi.json API
  slug: orkas-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-openapi-json-api-openapi.yml
- filename: orkas-search-api-openapi.yml
  format: yaml
  label: Orkas Search API
  slug: orkas-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-search-api-openapi.yml
- filename: orkas-videos-api-openapi.yml
  format: yaml
  label: Orkas Videos API
  slug: orkas-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-videos-api-openapi.yml
- filename: orkas-chat-completions-api-openapi.yml
  format: yaml
  label: Orkas Chat Completions API
  slug: orkas-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orkas/openapi/orkas-chat-completions-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Depending on the method, we may receive and store your user ID, email address, display name, profile picture, phone number, provider identity, device ID, and session records to operate your account.
  - category: financial
    text: Payment-card details are handled by our payment processor; Orkas does not store full card numbers.
  - category: behavioral
    text: We collect page views and a small set of in-product UI events, and use them in aggregate to understand which features are used.
  - category: communication
    text: Messages you send us by email, including any attachments and contact details you choose to include.
  - category: other
    text: Sync content. When you enable multi-device sync, data related to tasks, projects, agents, skills, connectors, data libraries, saved apps, and similar product data is uploaded to our cloud storage
  deletion:
    route: Email request or in-product actions
    text: For requests that we need to handle — access, export, correction, or deletion of server-held information, or closing your account — email us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: Provide the Service — authenticate you, deliver sync and relay, host the marketplace, route in-product communications, operate managed AI and tool features, process billing and credits, and operate the website.
  - purpose: Maintain and secure the Service
    text: Maintain and secure the Service — detect abuse, defend against attacks, debug failures.
  - purpose: Improve the product
    text: Improve the product — understand how the Service is used through anonymous, aggregated statistics.
  residency:
  - region: mainland China
    text: Your account data and sync data are stored on infrastructure located within mainland China.
  retention:
  - period: within 30 days
    scope: Account and billing records
    text: After you close your account, we delete or anonymize account records within 30 days, except where longer retention is required by law
  - period: up to 90 days
    scope: Service activity records
    text: Service activity records — retained for a limited period (typically up to 90 days), then deleted or aggregated.
  - period: up to 180 days
    scope: Download-link requests
    text: Download-link requests — recipient and delivery records are retained for up to 180 days, then deleted.
  - period: 7 days
    scope: Sync data
    text: if your paid membership ends, cloud copies remain available for 7 days and are then deleted unless you renew.
  rights:
  - right: access
    text: Depending on where you live, you may have rights to access, correct, export, delete, or restrict the processing of your personal information, and to withdraw consent or object to processing.
  - right: complain to authority
    text: You also have the right to lodge a complaint with your local data-protection authority.
  role:
    text: Orkas is a local-first AI agent client.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you choose managed features or third-party integrations, the content needed for those requests may be sent to the selected or configured upstream providers as described in this policy, including providers outside mainland China where applicable and permitted by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Orkas
provenance_date: '2026-11-10'
provider_name: Orkas
provider_slug: orkas
slug: orkas-privacy-policy
source_date: '2026-11-10'
source_filename: orkas-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://orkas.ai/views/legal/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Orkas\naid: orkas\nurl: https://orkas.ai/views/legal/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Orkas is a local-first AI agent client.\ndata_categories:\n- category: identifying\n  text: Depending on the method, we may receive and store your user ID, email address, display name, profile picture,\n    phone number, provider identity, device ID, and session records to operate your account.\n- category: financial\n  text: Payment-card details are handled by our payment processor; Orkas does not store full card numbers.\n- category: behavioral\n  text: We collect page views and\
  \ a small set of in-product UI events, and use them in aggregate to understand which\n    features are used.\n- category: communication\n  text: Messages you send us by email, including any attachments and contact details you choose to include.\n- category: other\n  text: Sync content. When you enable multi-device sync, data related to tasks, projects, agents, skills, connectors,\n    data libraries, saved apps, and similar product data is uploaded to our cloud storage\npurposes:\n- purpose: Provide the Service\n  text: Provide the Service — authenticate you, deliver sync and relay, host the marketplace, route in-product communications,\n    operate managed AI and tool features, process billing and credits, and operate the website.\n- purpose: Maintain and secure the Service\n  text: Maintain and secure the Service — detect abuse, defend against attacks, debug failures.\n- purpose: Improve the product\n  text: Improve the product — understand how the Service is used through anonymous,\
  \ aggregated statistics.\nretention:\n- scope: Account and billing records\n  period: within 30 days\n  text: After you close your account, we delete or anonymize account records within 30 days, except where longer\n    retention is required by law\n- scope: Service activity records\n  period: up to 90 days\n  text: Service activity records — retained for a limited period (typically up to 90 days), then deleted or aggregated.\n- scope: Download-link requests\n  period: up to 180 days\n  text: Download-link requests — recipient and delivery records are retained for up to 180 days, then deleted.\n- scope: Sync data\n  period: 7 days\n  text: if your paid membership ends, cloud copies remain available for 7 days and are then deleted unless you renew.\nresidency:\n- region: mainland China\n  text: Your account data and sync data are stored on infrastructure located within mainland China.\ntransfers:\n- mechanism: other\n  text: If you choose managed features or third-party integrations, the\
  \ content needed for those requests may be\n    sent to the selected or configured upstream providers as described in this policy, including providers outside\n    mainland China where applicable and permitted by law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request or in-product actions\n  text: For requests that we need to handle — access, export, correction, or deletion of server-held information,\n    or closing your account — email us at [email protected] .\nrights:\n- right: access\n  text: Depending on where you live, you may have rights to access, correct, export, delete, or restrict the processing\n    of your personal information, and to withdraw consent or object to processing.\n- right: complain to authority\n  text: You also have the right to lodge a complaint with your local data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/orkas/privacy/orkas-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Orkas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Chatbots
- Media
---
