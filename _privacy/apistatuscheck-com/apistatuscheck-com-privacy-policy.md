---
api_specs:
- filename: apistatuscheck-com-openapi-generated.yml
  format: yaml
  label: apistatuscheck-com API
  slug: apistatuscheck-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apistatuscheck-com/openapi/_ae-authored/apistatuscheck-com-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: When you sign up for alerts or a paid plan, we collect your email address.
  - category: behavioral
    text: Page views and referrer URLs
  - category: location
    text: Country (from IP, not stored)
  - category: device
    text: Device type and browser
  - category: financial
    text: We never see or store your full credit card number.
  - category: identifying
    text: a pseudonymous caller ID (a salted one-way hash, never your IP address)
  deletion:
    route: email hello@apistatuscheck.com
    text: To exercise any of these rights, email hello@apistatuscheck.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: analytics
    text: We use Vercel Web Analytics to understand how people use the site.
  - purpose: outage alerts
    text: Send outage alerts for APIs you selected
  - purpose: subscription processing
    text: Process your subscription
  - purpose: usage counting
    text: so we can count usage
  retention:
  - period: null
    scope: Analytics
    text: Aggregated, no personal data retained.
  - period: within 30 days of account cancellation
    scope: Email and account data
    text: Deleted within 30 days of account cancellation or upon request.
  - period: up to 30 days per API
    scope: API status data
    text: Historical uptime data is retained for up to 30 days per API.
  rights:
  - right: access
    text: Request a copy of any data we hold about you
  - right: deletion
    text: Request deletion of your data
  - right: unsubscribe
    text: Unsubscribe from all emails at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell, rent, or share your personal data with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: apistatuscheck-com
provenance_date: '2026-11-09'
provider_name: apistatuscheck-com
provider_slug: apistatuscheck-com
slug: apistatuscheck-com-privacy-policy
source_date: '2026-11-09'
source_filename: apistatuscheck-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apistatuscheck.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apistatuscheck-com\naid: apistatuscheck-com\nurl: https://apistatuscheck.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you sign up for alerts or a paid plan, we collect your email address.\n- category: behavioral\n  text: Page views and referrer URLs\n- category: location\n  text: Country (from IP, not stored)\n- category: device\n  text: Device type and browser\n- category: financial\n  text: We never see or store your full credit card number.\n- category: identifying\n  text: a pseudonymous caller ID (a salted one-way hash,\
  \ never your IP address)\npurposes:\n- purpose: analytics\n  text: We use Vercel Web Analytics to understand how people use the site.\n- purpose: outage alerts\n  text: Send outage alerts for APIs you selected\n- purpose: subscription processing\n  text: Process your subscription\n- purpose: usage counting\n  text: so we can count usage\nretention:\n- scope: Analytics\n  period: null\n  text: Aggregated, no personal data retained.\n- scope: Email and account data\n  period: within 30 days of account cancellation\n  text: Deleted within 30 days of account cancellation or upon request.\n- scope: API status data\n  period: up to 30 days per API\n  text: Historical uptime data is retained for up to 30 days per API.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@apistatuscheck.com\n  text: To exercise any of these rights, email hello@apistatuscheck.com .\nrights:\n- right: access\n\
  \  text: Request a copy of any data we hold about you\n- right: deletion\n  text: Request deletion of your data\n- right: unsubscribe\n  text: Unsubscribe from all emails at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell, rent, or share your personal data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/apistatuscheck-com/privacy/apistatuscheck-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from apistatuscheck-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Monitoring
- Outage Detection
- Developer Tools
---
