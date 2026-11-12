---
api_specs:
- filename: commontape-com-book-api-openapi.yml
  format: yaml
  label: CommonTape Book API
  slug: commontape-com-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-book-api-openapi.yml
- filename: commontape-com-cancel-api-openapi.yml
  format: yaml
  label: CommonTape Cancel API
  slug: commontape-com-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-cancel-api-openapi.yml
- filename: commontape-com-discover-api-openapi.yml
  format: yaml
  label: CommonTape Discover API
  slug: commontape-com-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-discover-api-openapi.yml
- filename: commontape-com-hold-api-openapi.yml
  format: yaml
  label: CommonTape Hold API
  slug: commontape-com-hold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-hold-api-openapi.yml
- filename: commontape-com-keys-api-openapi.yml
  format: yaml
  label: CommonTape Keys API
  slug: commontape-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-keys-api-openapi.yml
- filename: commontape-com-modify-api-openapi.yml
  format: yaml
  label: CommonTape Modify API
  slug: commontape-com-modify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-modify-api-openapi.yml
- filename: commontape-com-quote-api-openapi.yml
  format: yaml
  label: CommonTape Quote API
  slug: commontape-com-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-quote-api-openapi.yml
- filename: commontape-com-search-api-openapi.yml
  format: yaml
  label: CommonTape Search API
  slug: commontape-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-search-api-openapi.yml
- filename: commontape-com-status-api-openapi.yml
  format: yaml
  label: CommonTape Status API
  slug: commontape-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-status-api-openapi.yml
- filename: commontape-com-taxonomy-api-openapi.yml
  format: yaml
  label: CommonTape Taxonomy API
  slug: commontape-com-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-taxonomy-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: business name, trade, service area and email address
  - category: contact
    text: we keep your business name, trade, ZIP code, phone number and the email you signed in with
  - category: contact
    text: the agent sends us the customer’s name, phone number, service address and, optionally, email address
  - category: communication
    text: If you write to hello@commontape.com, we keep your message and address so we can reply.
  - category: device
    text: the kind of agent it came from as read from the user-agent the software sends
  deletion:
    route: email hello@commontape.com
    text: Email hello@commontape.com to see, correct or delete the information you gave us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: contact about sign-up or waiting list
    text: To contact you about your sign-up or your trade’s waiting list, to send the monthly note to those who confirmed it, to reply to your emails, and to keep the site secure (for example, filtering bot submissions).
  - purpose: booking completion
    text: 'We use this only to complete the booking: we share it with the business that will do the job (by email) so they can show up'
  residency:
  - region: United States and other countries
    text: These providers may process data in the United States and other countries where they operate.
  retention:
  - period: 24 months
    scope: waitlist entries
    text: kept until you ask us to delete them or 24 months after you first submitted them, whichever comes first
  - period: 90 days
    scope: agent and search requests
    text: The record of agent and search requests is deleted after 90 days.
  - period: null
    scope: sign-in requests
    text: The code kept for a sign-in request is deleted within 25 hours.
  - period: 24 months
    scope: completed job contact details
    text: For completed jobs we keep them for 24 months after the booking, then delete them.
  - period: null
    scope: declined or cancelled job contact details
    text: If a job is declined, expires or is cancelled, the customer’s contact details are deleted automatically.
  rights:
  - right: access, correction and deletion
    text: Email hello@commontape.com to see, correct or delete the information you gave us.
  - right: statutory privacy rights
    text: If you live somewhere with a statutory privacy right (for example, California), those rights apply and we will honor them through the same address.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal information or share it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CommonTape
provenance_date: '2026-11-09'
provider_name: CommonTape
provider_slug: commontape-com
slug: commontape-com-privacy-policy
source_date: '2026-11-09'
source_filename: commontape-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://commontape.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CommonTape\naid: commontape-com\nurl: https://commontape.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: business name, trade, service area and email address\n- category: contact\n  text: we keep your business name, trade, ZIP code, phone number and the email you signed in with\n- category: contact\n  text: the agent sends us the customer’s name, phone number, service address and, optionally, email address\n- category: communication\n  text: If you write to hello@commontape.com, we keep your message and address so we can reply.\n\
  - category: device\n  text: the kind of agent it came from as read from the user-agent the software sends\npurposes:\n- purpose: contact about sign-up or waiting list\n  text: To contact you about your sign-up or your trade’s waiting list, to send the monthly note to those who confirmed\n    it, to reply to your emails, and to keep the site secure (for example, filtering bot submissions).\n- purpose: booking completion\n  text: 'We use this only to complete the booking: we share it with the business that will do the job (by email)\n    so they can show up'\nretention:\n- scope: waitlist entries\n  period: 24 months\n  text: kept until you ask us to delete them or 24 months after you first submitted them, whichever comes first\n- scope: agent and search requests\n  period: 90 days\n  text: The record of agent and search requests is deleted after 90 days.\n- scope: sign-in requests\n  period: null\n  text: The code kept for a sign-in request is deleted within 25 hours.\n- scope: completed\
  \ job contact details\n  period: 24 months\n  text: For completed jobs we keep them for 24 months after the booking, then delete them.\n- scope: declined or cancelled job contact details\n  period: null\n  text: If a job is declined, expires or is cancelled, the customer’s contact details are deleted automatically.\nresidency:\n- region: United States and other countries\n  text: These providers may process data in the United States and other countries where they operate.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@commontape.com\n  text: Email hello@commontape.com to see, correct or delete the information you gave us.\nrights:\n- right: access, correction and deletion\n  text: Email hello@commontape.com to see, correct or delete the information you gave us.\n- right: statutory privacy rights\n  text: If you live somewhere with a statutory privacy right (for example, California), those rights\
  \ apply and we\n    will honor them through the same address.\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell personal information or share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/commontape-com/privacy/commontape-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from CommonTape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Booking
- Home Services
- House Cleaning
- MCP
- Marketplace
- Scheduling
---
