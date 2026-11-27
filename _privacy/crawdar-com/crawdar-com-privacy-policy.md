---
api_specs:
- filename: crawdar-com-account-api-openapi.yml
  format: yaml
  label: Crawdar Account API
  slug: crawdar-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-account-api-openapi.yml
- filename: crawdar-com-graph-api-openapi.yml
  format: yaml
  label: Crawdar Graph API
  slug: crawdar-com-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-graph-api-openapi.yml
- filename: crawdar-com-keys-api-openapi.yml
  format: yaml
  label: Crawdar Keys API
  slug: crawdar-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-keys-api-openapi.yml
- filename: crawdar-com-learning-api-openapi.yml
  format: yaml
  label: Crawdar Learning API
  slug: crawdar-com-learning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-learning-api-openapi.yml
- filename: crawdar-com-lists-api-openapi.yml
  format: yaml
  label: Crawdar Lists API
  slug: crawdar-com-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-lists-api-openapi.yml
- filename: crawdar-com-network-api-openapi.yml
  format: yaml
  label: Crawdar Network API
  slug: crawdar-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-network-api-openapi.yml
- filename: crawdar-com-pain-points-api-openapi.yml
  format: yaml
  label: Crawdar Pain Points API
  slug: crawdar-com-pain-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-pain-points-api-openapi.yml
- filename: crawdar-com-quality-benchmark-api-openapi.yml
  format: yaml
  label: Crawdar Quality Benchmark API
  slug: crawdar-com-quality-benchmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-quality-benchmark-api-openapi.yml
- filename: crawdar-com-sandbox-api-openapi.yml
  format: yaml
  label: Crawdar Sandbox API
  slug: crawdar-com-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-sandbox-api-openapi.yml
- filename: crawdar-com-search-api-openapi.yml
  format: yaml
  label: Crawdar Search API
  slug: crawdar-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-search-api-openapi.yml
- filename: crawdar-com-searches-api-openapi.yml
  format: yaml
  label: Crawdar Searches API
  slug: crawdar-com-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-searches-api-openapi.yml
- filename: crawdar-com-status-api-openapi.yml
  format: yaml
  label: Crawdar Status API
  slug: crawdar-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-status-api-openapi.yml
- filename: crawdar-com-workspaces-api-openapi.yml
  format: yaml
  label: Crawdar Workspaces API
  slug: crawdar-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawdar-com/openapi/crawdar-com-workspaces-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your name, email, signup source, and status
  - category: contact
    text: If you request email delivery, save a private search, or activate monitoring, we store your email address, delivery status, saved query and results, and monitoring schedule.
  - category: device
    text: We process your search query, a keyed hash derived from your network address, source URLs, and basic usage information.
  - category: financial
    text: We use the order amount, payment status, payment email address, and transaction reference to match your payment to the agreed work
  - category: professional
    text: we store your name, work email, company, workflow description, source, and request status so we can confirm fit and deliver the service
  - category: communication
    text: we store your useful or not useful response, optional message and email
  deletion:
    route: email privacy@crawdar.com
    text: You may ask us to stop a monitor, remove a result, correct a record, or delete associated search metadata by emailing privacy@crawdar.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run searches and deliver results
    text: We use this information to run searches, restore saved lists, deliver requested results and monitoring updates
  - purpose: product analytics
    text: Search metadata may be retained for product analytics.
  - purpose: advertising measurement
    text: If you allow measurement, Crawdar loads Google and Reddit advertising tags to measure visits, completed searches, shared searches, referral-link copies, and activated referrals.
  - purpose: prevent abuse and security
    text: prevent abuse, improve result quality, manage the beta waitlist, and maintain service security
  - purpose: payment processing
    text: to match your payment to the agreed work, deliver the service, handle support and refunds, and maintain business records
  rights:
  - right: removal or stop beta emails
    text: You can request removal or stop beta emails at any time by contacting privacy@crawdar.com.
  - right: correction
    text: You may ask us to stop a monitor, remove a result, correct a record, or delete associated search metadata by emailing privacy@crawdar.com.
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
name: Crawdar
provenance_date: '2026-11-09'
provider_name: Crawdar
provider_slug: crawdar-com
slug: crawdar-com-privacy-policy
source_date: '2026-11-09'
source_filename: crawdar-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crawdar.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Crawdar\naid: crawdar-com\nurl: https://crawdar.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we store your name, email, signup source, and status\n- category: contact\n  text: If you request email delivery, save a private search, or activate monitoring, we store your email address,\n    delivery status, saved query and results, and monitoring schedule.\n- category: device\n  text: We process your search query, a keyed hash derived from your network address, source URLs, and basic usage\n    information.\n- category: financial\n\
  \  text: We use the order amount, payment status, payment email address, and transaction reference to match your\n    payment to the agreed work\n- category: professional\n  text: we store your name, work email, company, workflow description, source, and request status so we can confirm\n    fit and deliver the service\n- category: communication\n  text: we store your useful or not useful response, optional message and email\npurposes:\n- purpose: run searches and deliver results\n  text: We use this information to run searches, restore saved lists, deliver requested results and monitoring updates\n- purpose: product analytics\n  text: Search metadata may be retained for product analytics.\n- purpose: advertising measurement\n  text: If you allow measurement, Crawdar loads Google and Reddit advertising tags to measure visits, completed\n    searches, shared searches, referral-link copies, and activated referrals.\n- purpose: prevent abuse and security\n  text: prevent abuse, improve result\
  \ quality, manage the beta waitlist, and maintain service security\n- purpose: payment processing\n  text: to match your payment to the agreed work, deliver the service, handle support and refunds, and maintain\n    business records\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@crawdar.com\n  text: You may ask us to stop a monitor, remove a result, correct a record, or delete associated search metadata\n    by emailing privacy@crawdar.com.\nrights:\n- right: removal or stop beta emails\n  text: You can request removal or stop beta emails at any time by contacting privacy@crawdar.com.\n- right: correction\n  text: You may ask us to stop a monitor, remove a result, correct a record, or delete associated search metadata\n    by emailing privacy@crawdar.com.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crawdar-com/privacy/crawdar-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
summary_line: 14 quoted statements, read from Crawdar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business Research
- Lead Generation
- CustomerReviews
- Sales Prospecting
- MCP
- AI Agents
---
