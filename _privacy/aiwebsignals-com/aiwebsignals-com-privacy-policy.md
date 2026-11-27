---
api_specs:
- filename: aiwebsignals-com-agent-experience-api-openapi.yml
  format: yaml
  label: AIWebSignals Agent Experience API
  slug: aiwebsignals-com-agent-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-agent-experience-api-openapi.yml
- filename: aiwebsignals-com-agent-reflective-api-openapi.yml
  format: yaml
  label: AIWebSignals Agent Reflective API
  slug: aiwebsignals-com-agent-reflective-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-agent-reflective-api-openapi.yml
- filename: aiwebsignals-com-discovery-api-openapi.yml
  format: yaml
  label: AIWebSignals Discovery API
  slug: aiwebsignals-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-discovery-api-openapi.yml
- filename: aiwebsignals-com-network-api-openapi.yml
  format: yaml
  label: AIWebSignals Network API
  slug: aiwebsignals-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-network-api-openapi.yml
- filename: aiwebsignals-com-readiness-api-openapi.yml
  format: yaml
  label: AIWebSignals Readiness API
  slug: aiwebsignals-com-readiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-readiness-api-openapi.yml
- filename: aiwebsignals-com-research-api-openapi.yml
  format: yaml
  label: AIWebSignals Research API
  slug: aiwebsignals-com-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-research-api-openapi.yml
- filename: aiwebsignals-com-self-observation-api-openapi.yml
  format: yaml
  label: AIWebSignals Self Observation API
  slug: aiwebsignals-com-self-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-self-observation-api-openapi.yml
- filename: aiwebsignals-com-well-known-api-openapi.yml
  format: yaml
  label: AIWebSignals .well Known API
  slug: aiwebsignals-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiwebsignals-com/openapi/aiwebsignals-com-well-known-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: The contact form stores the category, reply email, message, request reference, permission to reply, and timestamps in an operator-only database queue.
  - category: financial
    text: Square processes payment-card information; AIWebSignals receives only the identifiers and subscription state needed to provide paid access.
  - category: device
    text: Google Analytics may use cookies or similar identifiers depending on browser, regional, and consent settings.
  - category: other
    text: AIWebSignals stores normalized observations, findings, report identifiers, timestamps, monitoring configurations, execution state, and change history needed to provide the product.
  deletion:
    route: management key or private contact form
    text: A valid management key can pause or delete the connection and its retained normalized events.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide service
    text: Provide scans, reports, monitoring, history, and the in-app alerts currently available to you.
  - purpose: Measure usage
    text: Measure aggregate product usage and improve navigation, content, and conversion flows.
  - purpose: Security and abuse
    text: Protect the service, enforce rate and capacity limits, investigate abuse, and maintain reliability.
  - purpose: Legal compliance
    text: Meet legal obligations and enforce the Terms of Use.
  retention:
  - period: 90 days
    scope: Private support inquiries
    text: Private inquiry records expire after 90 days and are removed during scheduled cleanup.
  - period: between 7 and 90 days, with 30 days as the default
    scope: Connected traffic normalized events
    text: The selected normalized-event retention period is between 7 and 90 days, with 30 days as the default.
  - period: 30 days
    scope: Journey records and operational request aggregates
    text: Journey records and operational request aggregates are retained for 30 days
  - period: 30 days
    scope: Access Watch audit entries
    text: Audit entries are kept for 30 days.
  - period: null
    scope: Normalized reports and monitoring records
    text: A fixed automatic deletion period is not currently promised.
  rights:
  - right: Correction or deletion of inquiry
    text: To request correction or deletion of an inquiry, use the private contact form and provide its reference
  - right: Withdraw measurement consent
    text: can be withdrawn from Measurement preferences
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: AIWebSignals does not sell scanned domains or management credentials.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIWebSignals
provenance_date: '2026-11-09'
provider_name: AIWebSignals
provider_slug: aiwebsignals-com
slug: aiwebsignals-com-privacy-policy
source_date: '2026-11-09'
source_filename: aiwebsignals-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aiwebsignals.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIWebSignals\naid: aiwebsignals-com\nurl: https://aiwebsignals.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: The contact form stores the category, reply email, message, request reference, permission to reply, and\n    timestamps in an operator-only database queue.\n- category: financial\n  text: Square processes payment-card information; AIWebSignals receives only the identifiers and subscription state\n    needed to provide paid access.\n- category: device\n  text: Google Analytics may use cookies or similar identifiers depending\
  \ on browser, regional, and consent settings.\n- category: other\n  text: AIWebSignals stores normalized observations, findings, report identifiers, timestamps, monitoring configurations,\n    execution state, and change history needed to provide the product.\npurposes:\n- purpose: Provide service\n  text: Provide scans, reports, monitoring, history, and the in-app alerts currently available to you.\n- purpose: Measure usage\n  text: Measure aggregate product usage and improve navigation, content, and conversion flows.\n- purpose: Security and abuse\n  text: Protect the service, enforce rate and capacity limits, investigate abuse, and maintain reliability.\n- purpose: Legal compliance\n  text: Meet legal obligations and enforce the Terms of Use.\nretention:\n- scope: Private support inquiries\n  period: 90 days\n  text: Private inquiry records expire after 90 days and are removed during scheduled cleanup.\n- scope: Connected traffic normalized events\n  period: between 7 and 90 days, with\
  \ 30 days as the default\n  text: The selected normalized-event retention period is between 7 and 90 days, with 30 days as the default.\n- scope: Journey records and operational request aggregates\n  period: 30 days\n  text: Journey records and operational request aggregates are retained for 30 days\n- scope: Access Watch audit entries\n  period: 30 days\n  text: Audit entries are kept for 30 days.\n- scope: Normalized reports and monitoring records\n  period: null\n  text: A fixed automatic deletion period is not currently promised.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: management key or private contact form\n  text: A valid management key can pause or delete the connection and its retained normalized events.\nrights:\n- right: Correction or deletion of inquiry\n  text: To request correction or deletion of an inquiry, use the private contact form and provide its reference\n- right:\
  \ Withdraw measurement consent\n  text: can be withdrawn from Measurement preferences\nsale_or_sharing:\n  stance: prohibited\n  text: AIWebSignals does not sell scanned domains or management credentials.\n"
source_yaml_url: https://artifacts.apis.io/aiwebsignals-com/privacy/aiwebsignals-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AIWebSignals's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Web
- Signals
- Analytics
- Machine Access
- CrawlerReadiness
---
