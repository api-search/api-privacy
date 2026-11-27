---
api_specs:
- filename: infranest-audit-log-api-openapi.yml
  format: yaml
  label: InfraNest Audit Log API
  slug: infranest-audit-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-audit-log-api-openapi.yml
- filename: infranest-authentication-api-openapi.yml
  format: yaml
  label: InfraNest Authentication API
  slug: infranest-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-authentication-api-openapi.yml
- filename: infranest-automations-api-openapi.yml
  format: yaml
  label: InfraNest Automations API
  slug: infranest-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-automations-api-openapi.yml
- filename: infranest-billing-api-openapi.yml
  format: yaml
  label: InfraNest Billing API
  slug: infranest-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-billing-api-openapi.yml
- filename: infranest-certificates-api-openapi.yml
  format: yaml
  label: InfraNest Certificates API
  slug: infranest-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-certificates-api-openapi.yml
- filename: infranest-cloud-api-openapi.yml
  format: yaml
  label: InfraNest Cloud API
  slug: infranest-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-cloud-api-openapi.yml
- filename: infranest-cost-api-openapi.yml
  format: yaml
  label: InfraNest Cost API
  slug: infranest-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-cost-api-openapi.yml
- filename: infranest-cost-reporting-api-openapi.yml
  format: yaml
  label: InfraNest Cost reporting API
  slug: infranest-cost-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-cost-reporting-api-openapi.yml
- filename: infranest-custom-fields-api-openapi.yml
  format: yaml
  label: InfraNest Custom fields API
  slug: infranest-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-custom-fields-api-openapi.yml
- filename: infranest-dns-api-openapi.yml
  format: yaml
  label: InfraNest DNS API
  slug: infranest-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-dns-api-openapi.yml
- filename: infranest-domains-api-openapi.yml
  format: yaml
  label: InfraNest Domains API
  slug: infranest-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-domains-api-openapi.yml
- filename: infranest-drop-catch-api-openapi.yml
  format: yaml
  label: InfraNest Drop Catch API
  slug: infranest-drop-catch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-drop-catch-api-openapi.yml
- filename: infranest-dynamic-ip-api-openapi.yml
  format: yaml
  label: InfraNest Dynamic IP API
  slug: infranest-dynamic-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-dynamic-ip-api-openapi.yml
- filename: infranest-endpoints-api-openapi.yml
  format: yaml
  label: InfraNest Endpoints API
  slug: infranest-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-endpoints-api-openapi.yml
- filename: infranest-integration-logs-api-openapi.yml
  format: yaml
  label: InfraNest Integration Logs API
  slug: infranest-integration-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-integration-logs-api-openapi.yml
- filename: infranest-integrations-api-openapi.yml
  format: yaml
  label: InfraNest Integrations API
  slug: infranest-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-integrations-api-openapi.yml
- filename: infranest-monitoring-api-openapi.yml
  format: yaml
  label: InfraNest Monitoring API
  slug: infranest-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-monitoring-api-openapi.yml
- filename: infranest-organizations-api-openapi.yml
  format: yaml
  label: InfraNest Organizations API
  slug: infranest-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-organizations-api-openapi.yml
- filename: infranest-webhooks-api-openapi.yml
  format: yaml
  label: InfraNest Webhooks API
  slug: infranest-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infranest/openapi/infranest-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details — your name, email, password (stored only as a secure hash) and organization.
  - category: contact
    text: The contact form — your name, email and message, so we can reply.
  - category: financial
    text: Billing — handled by Stripe . We never see or store your full card number.
  - category: location
    text: We work out an approximate country from your IP — locally, on our own servers — to flag unusual sign-ins.
  - category: behavioral
    text: 'With your consent — and only with it — we also record how pages are used on this website: mouse movement, clicks and scrolling'
  - category: device
    text: Technical data — IP address, browser/device information and server logs, which we need for security and reliability.
  - category: communication
    text: Support chat — if you message us, the conversation (handled by Intercom, in the US).
  deletion:
    route: Email privacy@infranest.io
    text: Email privacy@infranest.io and we'll respond within the timeframe the law sets.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide account and service
    text: Performing our contract with you — to provide your account, run the service and handle billing.
  - purpose: Security and fraud prevention
    text: Our legitimate interests — keeping the service secure, preventing fraud, understanding usage in aggregate, monitoring errors, improving InfraNest, and answering your messages.
  - purpose: Website analytics
    text: Analytics — we run Umami, self-hosted on our own servers and cookieless.
  - purpose: Legal record keeping
    text: Legal obligations — for example, keeping invoices for tax purposes.
  residency:
  - region: EU
    text: Hosted in the EU
  - region: Germany
    text: Most of our providers are based in the EU/EEA (Hetzner).
  retention:
  - period: null
    scope: Account data
    text: Account data is kept while your account is active; when you close it, we delete or anonymise your data
  - period: up to 10 years
    scope: Invoices
    text: invoices must be kept for up to 10 years under German tax law
  - period: 30 days
    scope: PostHog session replays
    text: PostHog session replays are deleted after 30 days
  - period: 7 days
    scope: Unconfirmed status-page email sign-ups
    text: Email sign-ups that are never confirmed are deleted after 7 days.
  rights:
  - right: access
    text: Under the GDPR you can ask us to access your data, correct it, delete it, restrict or object to how we use it, or provide it in a portable format
  - right: withdraw consent
    text: you can withdraw consent at any time
  - right: complain to authority
    text: You also have the right to complain to a data-protection authority; ours is the State Commissioner for Data Protection and Freedom of Information North Rhine-Westphalia (LDI NRW)
  role:
    text: We are the "data controller" for the personal data described here — meaning we decide how and why it's used.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data.
  subprocessors:
    text: Who else processes your data (sub-processors) We use a small set of trusted providers to run InfraNest
    url: null
  transfers:
  - mechanism: SCC
    text: Where they do, the transfer is protected by appropriate safeguards such as the EU Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: InfraNest
provenance_date: '2026-11-09'
provider_name: InfraNest
provider_slug: infranest
slug: infranest-privacy-policy
source_date: '2026-11-09'
source_filename: infranest-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://infranest.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: InfraNest\naid: infranest\nurl: https://infranest.io/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the \"data controller\" for the personal data described here — meaning we decide how and why it's used.\ndata_categories:\n- category: identifying\n  text: Account details — your name, email, password (stored only as a secure hash) and organization.\n- category: contact\n  text: The contact form — your name, email and message, so we can reply.\n- category: financial\n  text: Billing — handled by Stripe . We never see or store your full card number.\n- category: location\n  text:\
  \ We work out an approximate country from your IP — locally, on our own servers — to flag unusual sign-ins.\n- category: behavioral\n  text: 'With your consent — and only with it — we also record how pages are used on this website: mouse movement,\n    clicks and scrolling'\n- category: device\n  text: Technical data — IP address, browser/device information and server logs, which we need for security and\n    reliability.\n- category: communication\n  text: Support chat — if you message us, the conversation (handled by Intercom, in the US).\npurposes:\n- purpose: Provide account and service\n  text: Performing our contract with you — to provide your account, run the service and handle billing.\n- purpose: Security and fraud prevention\n  text: Our legitimate interests — keeping the service secure, preventing fraud, understanding usage in aggregate,\n    monitoring errors, improving InfraNest, and answering your messages.\n- purpose: Website analytics\n  text: Analytics — we run Umami,\
  \ self-hosted on our own servers and cookieless.\n- purpose: Legal record keeping\n  text: Legal obligations — for example, keeping invoices for tax purposes.\nretention:\n- scope: Account data\n  period: null\n  text: Account data is kept while your account is active; when you close it, we delete or anonymise your data\n- scope: Invoices\n  period: up to 10 years\n  text: invoices must be kept for up to 10 years under German tax law\n- scope: PostHog session replays\n  period: 30 days\n  text: PostHog session replays are deleted after 30 days\n- scope: Unconfirmed status-page email sign-ups\n  period: 7 days\n  text: Email sign-ups that are never confirmed are deleted after 7 days.\nresidency:\n- region: EU\n  text: Hosted in the EU\n- region: Germany\n  text: Most of our providers are based in the EU/EEA (Hetzner).\ntransfers:\n- mechanism: SCC\n  text: Where they do, the transfer is protected by appropriate safeguards such as the EU Standard Contractual Clauses.\nsubprocessors:\n  url:\
  \ null\n  text: Who else processes your data (sub-processors) We use a small set of trusted providers to run InfraNest\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@infranest.io\n  text: Email privacy@infranest.io and we'll respond within the timeframe the law sets.\nrights:\n- right: access\n  text: Under the GDPR you can ask us to access your data, correct it, delete it, restrict or object to how we use\n    it, or provide it in a portable format\n- right: withdraw consent\n  text: you can withdraw consent at any time\n- right: complain to authority\n  text: You also have the right to complain to a data-protection authority; ours is the State Commissioner for Data\n    Protection and Freedom of Information North Rhine-Westphalia (LDI NRW)\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data.\n"
source_yaml_url: https://artifacts.apis.io/infranest/privacy/infranest-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from InfraNest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- DNS
- Monitoring
- SSL
- Cloud
---
