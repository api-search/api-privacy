---
api_specs:
- filename: actablesite-com-ai-crawler-check-api-openapi.yml
  format: yaml
  label: actablesite-com Ai Crawler Check API
  slug: actablesite-com-ai-crawler-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actablesite-com/openapi/actablesite-com-ai-crawler-check-api-openapi.yml
- filename: actablesite-com-audit-api-openapi.yml
  format: yaml
  label: actablesite-com Audit API
  slug: actablesite-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actablesite-com/openapi/actablesite-com-audit-api-openapi.yml
- filename: actablesite-com-health-api-openapi.yml
  format: yaml
  label: actablesite-com Health API
  slug: actablesite-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actablesite-com/openapi/actablesite-com-health-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: Crawler Watch receives the public website and checkout email collected by Stripe.
  - category: behavioral
    text: the service records an anonymous engaged-visit count for the homepage, guide, or crawler tool
  - category: device
    text: It records an aggregate action-event time and a one-way digest derived from standard request information
  - category: identifying
    text: it does not retain the raw caller address or a ChatGPT user identity
  - category: financial
    text: ActableSite does not receive or store full card numbers.
  deletion:
    route: Remove access from browser
    text: Use “Remove access from browser” on a data-product access panel to delete its stored access ID from that browser.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: aggregate funnel measurement
    text: This supports aggregate funnel measurement without retaining the submitted URL, page content, raw referrer, or a visitor profile.
  - purpose: payment processing
    text: Stripe hosts checkout and processes payment information.
  - purpose: email delivery
    text: Resend processes the recipient address and message content to deliver activation, change, recovery, or configuration-error email.
  - purpose: operate and protect the service
    text: Hosting, source-control, and security providers may temporarily process standard request information such as IP address, user agent, requested path, and error details to operate and protect the service.
  retention:
  - period: null
    scope: public scan content
    text: Public content is processed to create the response and is not deliberately stored in the product database.
  - period: null
    scope: operational records
    text: Operational records are removed or minimized after the subscription becomes inactive and any necessary support, refund, security, or accounting period ends.
  rights:
  - right: questions and contact
    text: Email support@actablesite.com with questions about public-data processing, anonymous funnel telemetry, or a purchase.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: actablesite-com
provenance_date: '2026-11-09'
provider_name: actablesite-com
provider_slug: actablesite-com
slug: actablesite-com-privacy-policy
source_date: '2026-11-09'
source_filename: actablesite-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://actablesite.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: actablesite-com\naid: actablesite-com\nurl: https://actablesite.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Crawler Watch receives the public website and checkout email collected by Stripe.\n- category: behavioral\n  text: the service records an anonymous engaged-visit count for the homepage, guide, or crawler tool\n- category: device\n  text: It records an aggregate action-event time and a one-way digest derived from standard request information\n- category: identifying\n  text: it does not retain the raw caller address or\
  \ a ChatGPT user identity\n- category: financial\n  text: ActableSite does not receive or store full card numbers.\npurposes:\n- purpose: aggregate funnel measurement\n  text: This supports aggregate funnel measurement without retaining the submitted URL, page content, raw referrer,\n    or a visitor profile.\n- purpose: payment processing\n  text: Stripe hosts checkout and processes payment information.\n- purpose: email delivery\n  text: Resend processes the recipient address and message content to deliver activation, change, recovery, or configuration-error\n    email.\n- purpose: operate and protect the service\n  text: Hosting, source-control, and security providers may temporarily process standard request information such\n    as IP address, user agent, requested path, and error details to operate and protect the service.\nretention:\n- scope: public scan content\n  period: null\n  text: Public content is processed to create the response and is not deliberately stored in the product\
  \ database.\n- scope: operational records\n  period: null\n  text: Operational records are removed or minimized after the subscription becomes inactive and any necessary support,\n    refund, security, or accounting period ends.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Remove access from browser\n  text: Use “Remove access from browser” on a data-product access panel to delete its stored access ID from that\n    browser.\nrights:\n- right: questions and contact\n  text: Email support@actablesite.com with questions about public-data processing, anonymous funnel telemetry, or\n    a purchase.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/actablesite-com/privacy/actablesite-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from actablesite-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Platform
- Low-Code
- Analytics
- SEO
---
