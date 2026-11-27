---
api_specs:
- filename: airouter-ai-router-api-api-openapi.yml
  format: yaml
  label: AI Router AI Router API
  slug: airouter-ai-router-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airouter/openapi/airouter-ai-router-api-api-openapi.yml
- filename: airouter-chat-completions-api-openapi.yml
  format: yaml
  label: AI Router Chat Completions API
  slug: airouter-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airouter/openapi/airouter-chat-completions-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: When you register, we collect your email and authentication details using Supabase (EU, Frankfurt).'
  - category: financial
    text: 'Billing Information: Stripe securely handles your payment details when you make a purchase.'
  - category: communication
    text: 'Support and Communications: Information you provide via support or onboarding (handled by kit.com).'
  - category: behavioral
    text: 'Event Data: We log specific in-app events (such as LLM completion with request settings) to Posthog (EU, Frankfurt) and associate them with user records from Supabase.'
  - category: device
    text: 'Technical Data: IP address, browser, and device information may be processed by our hosting providers (Vercel and Google Cloud Platform, EU, Frankfurt) for service operations and security.'
  - category: behavioral
    text: 'Web Analytics: We use Vercel Analytics to capture aggregated usage information such as visits and page views.'
  deletion:
    route: Contact hello@airouter.io or the contact in section 13
    text: If you wish to delete your account and data, contact us using the information in section 13.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and improve service
    text: We use your information to operate and improve AI Router, authenticate users, process payments, provide support, fulfill legal obligations, protect platform security, monitor service usage and reliability, and improve features through in-app event metrics and aggregate web analytics.
  - purpose: no advertising or profiling
    text: We do not use your data for advertising, profiling, or cross-site tracking.
  residency:
  - region: EU (Frankfurt)
    text: Supabase (EU, Frankfurt)
  - region: EU
    text: Sentry for error logging (EU)
  retention:
  - period: null
    scope: LLM input data (paid packages)
    text: For paid packages, input data to LLMs is never retained or stored by AI Router.
  - period: null
    scope: Account and billing records
    text: Other personal data, such as account or billing records, is kept as necessary for regulatory and operational reasons.
  rights:
  - right: access, correct, delete, restrict, object
    text: you may have the right to access, correct, delete, restrict, or object to processing of your personal data
  - right: data portability
    text: as well as data portability and right to withdraw consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Any query sent to an LLM provider is processed under their privacy policies and may be transferred outside the EU/EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Router
provenance_date: '2026-11-09'
provider_name: AI Router
provider_slug: airouter
slug: airouter-privacy-policy
source_date: '2026-11-09'
source_filename: airouter-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://airouter.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Router\naid: airouter\nurl: https://airouter.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: When you register, we collect your email and authentication details using Supabase\n    (EU, Frankfurt).'\n- category: financial\n  text: 'Billing Information: Stripe securely handles your payment details when you make a purchase.'\n- category: communication\n  text: 'Support and Communications: Information you provide via support or onboarding (handled by kit.com).'\n- category: behavioral\n  text: 'Event\
  \ Data: We log specific in-app events (such as LLM completion with request settings) to Posthog (EU,\n    Frankfurt) and associate them with user records from Supabase.'\n- category: device\n  text: 'Technical Data: IP address, browser, and device information may be processed by our hosting providers (Vercel\n    and Google Cloud Platform, EU, Frankfurt) for service operations and security.'\n- category: behavioral\n  text: 'Web Analytics: We use Vercel Analytics to capture aggregated usage information such as visits and page\n    views.'\npurposes:\n- purpose: operate and improve service\n  text: We use your information to operate and improve AI Router, authenticate users, process payments, provide\n    support, fulfill legal obligations, protect platform security, monitor service usage and reliability, and improve\n    features through in-app event metrics and aggregate web analytics.\n- purpose: no advertising or profiling\n  text: We do not use your data for advertising, profiling,\
  \ or cross-site tracking.\nretention:\n- scope: LLM input data (paid packages)\n  period: null\n  text: For paid packages, input data to LLMs is never retained or stored by AI Router.\n- scope: Account and billing records\n  period: null\n  text: Other personal data, such as account or billing records, is kept as necessary for regulatory and operational\n    reasons.\nresidency:\n- region: EU (Frankfurt)\n  text: Supabase (EU, Frankfurt)\n- region: EU\n  text: Sentry for error logging (EU)\ntransfers:\n- mechanism: other\n  text: Any query sent to an LLM provider is processed under their privacy policies and may be transferred outside\n    the EU/EEA.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact hello@airouter.io or the contact in section 13\n  text: If you wish to delete your account and data, contact us using the information in section 13.\nrights:\n- right: access, correct, delete, restrict, object\n  text:\
  \ you may have the right to access, correct, delete, restrict, or object to processing of your personal data\n- right: data portability\n  text: as well as data portability and right to withdraw consent\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airouter/privacy/airouter-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from AI Router's own page on 2026-11-09.
synthetic: false
tags:
- LLM Cost Optimization
- Model Routing
- Enterprise AI
- Privacy
---
