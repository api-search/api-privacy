---
api_specs:
- filename: crimescore-io-geocode-api-openapi.yml
  format: yaml
  label: crimescore-io Geocode API
  slug: crimescore-io-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-geocode-api-openapi.yml
- filename: crimescore-io-incidents-api-openapi.yml
  format: yaml
  label: crimescore-io Incidents API
  slug: crimescore-io-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-incidents-api-openapi.yml
- filename: crimescore-io-score-api-openapi.yml
  format: yaml
  label: crimescore-io Score API
  slug: crimescore-io-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crimescore-io/openapi/crimescore-io-score-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register, we collect your email address, hashed password (via AWS Cognito), the organization name you create, and any team-member email addresses you invite.
  - category: contact
    text: We process your email address, marketing subscription status, optional first name, account activation stage, and email delivery or engagement events
  - category: financial
    text: We store the Stripe customer ID, subscription status, plan tier, billing-cycle dates, and the email address associated with the Stripe customer record.
  - category: location
    text: Exact-address watches are verified again through Amazon Location Service and may store the matched address and its coordinates and ZIP;
  - category: behavioral
    text: For signed-in users, we record dashboard page visits and selected map areas, including the geographic identifier, score component, time, and interaction count
  - category: device
    text: When the CrimeScore embed widget is loaded on a third-party site, we record the publishable key used, the origin domain, the timestamp, and an aggregate load count.
  - category: communication
    text: Signed-in dashboard users can provide survey answers and optional written feedback linked to their account.
  deletion:
    route: dashboard, or support@crimescore.io for Stripe and accountless watch data
    text: you can access, correct, export, or delete your account data at any time via the dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate API and dashboard
    text: To operate the CrimeScore API and dashboard, send transactional emails (invitations, billing notifications, security alerts)
  - purpose: save Area Watch areas
    text: We use explicitly submitted Area Watch details to save the areas you choose, understand demand and optional feedback, and support future area updates.
  - purpose: attribute advertising outcomes
    text: attribute advertising outcomes, measure acquisition and product activation, improve product performance
  retention:
  - period: 90 days
    scope: dashboard activity records
    text: We schedule these activity records to expire after 90 days.
  - period: 30 days
    scope: operational logs
    text: Operational logs are retained for up to 30 days.
  - period: 7 years
    scope: billing records
    text: Billing records are retained for 7 years to satisfy tax-record obligations.
  - period: 120 days
    scope: Google Ads conversion rows
    text: Limited Google Ads conversion rows expire after 120 days
  - period: 15 minutes
    scope: short-lived feedback tokens
    text: Short-lived feedback tokens expire after 15 minutes.
  - period: while the watch is active
    scope: Area Watch records
    text: Area Watch records are retained while the watch is active or until you delete the linked account or ask support to remove an accountless watch.
  - period: up to 90 days
    scope: advertising click identifiers in browser
    text: we may retain the first valid identifier for up to 90 days in your browser
  rights:
  - right: access, correct, export, delete
    text: you can access, correct, export, or delete your account data at any time via the dashboard.
  - right: lodge complaint (GDPR/UK-GDPR)
    text: the right to lodge a complaint with your supervisory authority
  - right: CCPA/CPRA rights
    text: If you are a California resident, you have rights under the CCPA/CPRA.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Advertising on our public website may involve sharing that is considered a “sale,” “sharing,” or “targeted advertising” under applicable state privacy laws
  subprocessors:
    text: 'We use the following third-party services to operate the product:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crimescore-io
provenance_date: '2026-11-09'
provider_name: crimescore-io
provider_slug: crimescore-io
slug: crimescore-io-privacy-policy
source_date: '2026-11-09'
source_filename: crimescore-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crimescore.io/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crimescore-io\naid: crimescore-io\nurl: https://crimescore.io/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you register, we collect your email address, hashed password (via AWS Cognito), the organization name\n    you create, and any team-member email addresses you invite.\n- category: contact\n  text: We process your email address, marketing subscription status, optional first name, account activation stage,\n    and email delivery or engagement events\n- category: financial\n  text: We store the Stripe customer\
  \ ID, subscription status, plan tier, billing-cycle dates, and the email address\n    associated with the Stripe customer record.\n- category: location\n  text: Exact-address watches are verified again through Amazon Location Service and may store the matched address\n    and its coordinates and ZIP;\n- category: behavioral\n  text: For signed-in users, we record dashboard page visits and selected map areas, including the geographic identifier,\n    score component, time, and interaction count\n- category: device\n  text: When the CrimeScore embed widget is loaded on a third-party site, we record the publishable key used, the\n    origin domain, the timestamp, and an aggregate load count.\n- category: communication\n  text: Signed-in dashboard users can provide survey answers and optional written feedback linked to their account.\npurposes:\n- purpose: operate API and dashboard\n  text: To operate the CrimeScore API and dashboard, send transactional emails (invitations, billing notifications,\n\
  \    security alerts)\n- purpose: save Area Watch areas\n  text: We use explicitly submitted Area Watch details to save the areas you choose, understand demand and optional\n    feedback, and support future area updates.\n- purpose: attribute advertising outcomes\n  text: attribute advertising outcomes, measure acquisition and product activation, improve product performance\nretention:\n- scope: dashboard activity records\n  period: 90 days\n  text: We schedule these activity records to expire after 90 days.\n- scope: operational logs\n  period: 30 days\n  text: Operational logs are retained for up to 30 days.\n- scope: billing records\n  period: 7 years\n  text: Billing records are retained for 7 years to satisfy tax-record obligations.\n- scope: Google Ads conversion rows\n  period: 120 days\n  text: Limited Google Ads conversion rows expire after 120 days\n- scope: short-lived feedback tokens\n  period: 15 minutes\n  text: Short-lived feedback tokens expire after 15 minutes.\n- scope:\
  \ Area Watch records\n  period: while the watch is active\n  text: Area Watch records are retained while the watch is active or until you delete the linked account or ask\n    support to remove an accountless watch.\n- scope: advertising click identifiers in browser\n  period: up to 90 days\n  text: we may retain the first valid identifier for up to 90 days in your browser\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use the following third-party services to operate the product:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard, or support@crimescore.io for Stripe and accountless watch data\n  text: you can access, correct, export, or delete your account data at any time via the dashboard.\nrights:\n- right: access, correct, export, delete\n  text: you can access, correct, export, or delete your account data at any time via the dashboard.\n- right: lodge complaint (GDPR/UK-GDPR)\n  text: the right to lodge a complaint with your\
  \ supervisory authority\n- right: CCPA/CPRA rights\n  text: If you are a California resident, you have rights under the CCPA/CPRA.\nsale_or_sharing:\n  stance: conditional\n  text: Advertising on our public website may involve sharing that is considered a “sale,” “sharing,” or “targeted\n    advertising” under applicable state privacy laws\n"
source_yaml_url: https://artifacts.apis.io/crimescore-io/privacy/crimescore-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from crimescore-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Safety
- Real Estate
- Data
- Mapping
---
