---
api_specs:
- filename: crispy-sh-openapi-generated.yml
  format: yaml
  label: crispy-sh API
  slug: crispy-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crispy-sh/openapi/_ae-authored/crispy-sh-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email, display name, authentication identifiers, and account or organization membership.'
  - category: contact
    text: 'Managed storage for contacts and messages: names, profile URLs, roles, employers, locations, contact details, identifiers, tags, notes, enrichment, conversation metadata, message text, sender, timestamps, attachment metadata, labels, and classifications.'
  - category: financial
    text: 'Billing data: Stripe customer and subscription identifiers, plan, invoices, payment status, and transaction metadata.'
  - category: device
    text: 'Usage and device data: tool calls, timestamps, account identifiers, request metadata, quotas, audit events, IP address, browser or device attributes, page URLs, referrer, UTM parameters, cookies, and similar identifiers.'
  - category: behavioral
    text: 'Campaign and content data: lists, imports, campaign settings, drafts, schedules, sent content, and activity history.'
  - category: communication
    text: 'Support and security data: support requests and replies, delivery identifiers, and error, performance, access, fraud, abuse, and security-event data.'
  deletion:
    route: Account deletion flow where available, or contact us; Data Rights page for non-account prospects
    text: To request hard deletion, use the account deletion flow where available or contact us.
  dpa:
    available: true
    text: DPA Request
    url: https://crispy.sh/dpa
  purposes:
  - purpose: Provide and secure the service
    text: create accounts, authenticate users, manage organizations, and provide the service
  - purpose: Billing and accounting
    text: operate subscriptions, invoices, refunds, accounting, and fraud controls
  - purpose: Marketing email
    text: deliver transactional, lifecycle, support, and permitted marketing email
  - purpose: Advertising measurement
    text: measure advertising or build retargeting audiences only when the relevant feature is enabled and marketing consent has been granted
  residency:
  - region: United States
    text: Crispy is based in the United States, and vendors may process data in the United States or other countries.
  retention:
  - period: 90 days
    scope: Message cache
    text: 'Message cache: 90 days from cache write, using an expiry field and daily retention sweep.'
  - period: 60 days
    scope: Raw campaign imports
    text: 'Raw campaign imports: 60 days.'
  - period: 180 days after the paid term ends
    scope: Contacts, activity, and campaign data
    text: the current churn-sweep target is 180 days after the paid term ends
  rights:
  - right: access, correction, deletion, portability, restriction, objection
    text: you may request access, correction, deletion, portability, restriction, or objection
  - right: withdraw consent
    text: withdraw consent
  - right: opt out of sale, sharing, or targeted advertising
    text: opt out of sale, sharing, or targeted advertising
  - right: appeal
    text: appeal a denied request
  role:
    text: We generally act as a controller for account, website, billing, security, analytics, and communications data.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: See our Subprocessor List for named vendors and our current contract, region, and transfer-status disclosures.
    url: https://crispy.sh/subprocessors
  transfers:
  - mechanism: other
    text: We do not currently claim that Standard Contractual Clauses, the UK Addendum, or another safeguard has been executed with every vendor.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crispy-sh
provenance_date: '2026-11-09'
provider_name: crispy-sh
provider_slug: crispy-sh
slug: crispy-sh-privacy-policy
source_date: '2026-11-09'
source_filename: crispy-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crispy.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crispy-sh\naid: crispy-sh\nurl: https://crispy.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We generally act as a controller for account, website, billing, security, analytics, and communications\n    data.\ndata_categories:\n- category: identifying\n  text: 'Account data: email, display name, authentication identifiers, and account or organization membership.'\n- category: contact\n  text: 'Managed storage for contacts and messages: names, profile URLs, roles, employers, locations, contact details,\n    identifiers, tags, notes, enrichment, conversation metadata, message text, sender,\
  \ timestamps, attachment metadata,\n    labels, and classifications.'\n- category: financial\n  text: 'Billing data: Stripe customer and subscription identifiers, plan, invoices, payment status, and transaction\n    metadata.'\n- category: device\n  text: 'Usage and device data: tool calls, timestamps, account identifiers, request metadata, quotas, audit events,\n    IP address, browser or device attributes, page URLs, referrer, UTM parameters, cookies, and similar identifiers.'\n- category: behavioral\n  text: 'Campaign and content data: lists, imports, campaign settings, drafts, schedules, sent content, and activity\n    history.'\n- category: communication\n  text: 'Support and security data: support requests and replies, delivery identifiers, and error, performance,\n    access, fraud, abuse, and security-event data.'\npurposes:\n- purpose: Provide and secure the service\n  text: create accounts, authenticate users, manage organizations, and provide the service\n- purpose: Billing\
  \ and accounting\n  text: operate subscriptions, invoices, refunds, accounting, and fraud controls\n- purpose: Marketing email\n  text: deliver transactional, lifecycle, support, and permitted marketing email\n- purpose: Advertising measurement\n  text: measure advertising or build retargeting audiences only when the relevant feature is enabled and marketing\n    consent has been granted\nretention:\n- scope: Message cache\n  period: 90 days\n  text: 'Message cache: 90 days from cache write, using an expiry field and daily retention sweep.'\n- scope: Raw campaign imports\n  period: 60 days\n  text: 'Raw campaign imports: 60 days.'\n- scope: Contacts, activity, and campaign data\n  period: 180 days after the paid term ends\n  text: the current churn-sweep target is 180 days after the paid term ends\nresidency:\n- region: United States\n  text: Crispy is based in the United States, and vendors may process data in the United States or other countries.\ntransfers:\n- mechanism: other\n  text:\
  \ We do not currently claim that Standard Contractual Clauses, the UK Addendum, or another safeguard has been\n    executed with every vendor.\nsubprocessors:\n  url: https://crispy.sh/subprocessors\n  text: See our Subprocessor List for named vendors and our current contract, region, and transfer-status disclosures.\ndpa:\n  available: true\n  url: https://crispy.sh/dpa\n  text: DPA Request\ndeletion:\n  route: Account deletion flow where available, or contact us; Data Rights page for non-account prospects\n  text: To request hard deletion, use the account deletion flow where available or contact us.\nrights:\n- right: access, correction, deletion, portability, restriction, objection\n  text: you may request access, correction, deletion, portability, restriction, or objection\n- right: withdraw consent\n  text: withdraw consent\n- right: opt out of sale, sharing, or targeted advertising\n  text: opt out of sale, sharing, or targeted advertising\n- right: appeal\n  text: appeal a denied\
  \ request\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crispy-sh/privacy/crispy-sh-privacy-policy.yml
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
summary_line: 23 quoted statements, read from crispy-sh's own page on 2026-11-09.
synthetic: false
tags:
- LinkedIn
- Founders
- Outreach
- Automation
- Software-as-a-Service
---
