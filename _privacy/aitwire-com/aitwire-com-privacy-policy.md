---
api_specs:
- filename: aitwire-com-api-keys-api-openapi.yml
  format: yaml
  label: aitwire-com API Keys API
  slug: aitwire-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-api-keys-api-openapi.yml
- filename: aitwire-com-attribution-api-openapi.yml
  format: yaml
  label: aitwire-com Attribution API
  slug: aitwire-com-attribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-attribution-api-openapi.yml
- filename: aitwire-com-authority-api-openapi.yml
  format: yaml
  label: aitwire-com Authority API
  slug: aitwire-com-authority-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-authority-api-openapi.yml
- filename: aitwire-com-billing-api-openapi.yml
  format: yaml
  label: aitwire-com Billing API
  slug: aitwire-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-billing-api-openapi.yml
- filename: aitwire-com-drift-api-openapi.yml
  format: yaml
  label: aitwire-com Drift API
  slug: aitwire-com-drift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-drift-api-openapi.yml
- filename: aitwire-com-entities-api-openapi.yml
  format: yaml
  label: aitwire-com Entities API
  slug: aitwire-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-entities-api-openapi.yml
- filename: aitwire-com-scans-api-openapi.yml
  format: yaml
  label: aitwire-com Scans API
  slug: aitwire-com-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-scans-api-openapi.yml
- filename: aitwire-com-webhooks-api-openapi.yml
  format: yaml
  label: aitwire-com Webhooks API
  slug: aitwire-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aitwire-com/openapi/aitwire-com-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, organization name, job title, login credentials, authentication data, billing contact information, and workspace or account settings.
  - category: financial
    text: Subscription details, invoices, payment status, plan selection, and limited payment metadata.
  - category: device
    text: Log data, device and browser information, IP address, authentication events, diagnostic data, API usage, widget configuration, domain configuration, usage metrics, and interaction history with the Service.
  - category: communication
    text: Messages sent to support, sales, or us generally, and records of those communications.
  - category: behavioral
    text: Consent status, subscription preferences, and engagement with our communications.
  deletion:
    route: null
    text: Customer Data is retained during the subscription and for thirty (30) days following termination to support data export, after which it may be deleted.
  dpa:
    available: true
    text: Enterprise customers requiring processor-style commitments should refer to the AITWIRE Enterprise Data Processing Addendum .
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: provide, operate, secure, and support the Service
  - purpose: Process payments and manage subscriptions
    text: process payments and manage subscriptions
  - purpose: AI monitoring
    text: conduct AI monitoring, including sending Monitoring Probes to third-party Automated Agents to assess accuracy
  - purpose: Analytics and product improvement
    text: perform drift detection, analytics, scoring, and product improvement
  - purpose: Fraud and security
    text: detect, investigate, and prevent fraud, misuse, or security incidents
  residency:
  - region: Canada
    text: AITWIRE is based in Ontario, Canada.
  retention:
  - period: null
    scope: Account Data
    text: Account Data is retained for the duration of the account relationship and for a reasonable period thereafter for legal and administrative purposes.
  - period: thirty (30) days
    scope: Customer Data
    text: Customer Data is retained during the subscription and for thirty (30) days following termination to support data export, after which it may be deleted.
  - period: null
    scope: Billing and transaction records
    text: Billing and transaction records are retained for the period required by applicable tax and accounting laws.
  rights:
  - right: access
    text: request access to their personal information held by AITWIRE
  - right: correction
    text: request correction of inaccurate personal information
  - right: withdraw consent
    text: withdraw consent to certain processing activities
  - right: complaint
    text: file a complaint with the Office of the Privacy Commissioner of Canada or the applicable provincial privacy authority
  - right: deletion, portability, restriction, or objection
    text: individuals may also have rights regarding deletion, portability, restriction, or objection
  role:
    text: AITWIRE collects, uses, discloses, stores, and otherwise processes personal information through the AITWIRE website, dashboard, APIs
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: AITWIRE does not sell personal information as that term is commonly understood in consumer privacy laws.
  subprocessors:
    text: Service providers and subprocessors assisting with hosting, identity, analytics, support, payment processing, communications, or infrastructure
    url: null
  transfers:
  - mechanism: other
    text: Personal information may also be processed by our service providers in other jurisdictions, including through Cloudflare's global edge network.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: aitwire-com
provenance_date: '2026-11-09'
provider_name: aitwire-com
provider_slug: aitwire-com
slug: aitwire-com-privacy-policy
source_date: '2026-11-09'
source_filename: aitwire-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aitwire.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: aitwire-com\naid: aitwire-com\nurl: https://aitwire.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AITWIRE collects, uses, discloses, stores, and otherwise processes personal information through the AITWIRE\n    website, dashboard, APIs\ndata_categories:\n- category: identifying\n  text: Name, email address, organization name, job title, login credentials, authentication data, billing contact\n    information, and workspace or account settings.\n- category: financial\n  text: Subscription details, invoices, payment status, plan selection, and limited payment metadata.\n- category:\
  \ device\n  text: Log data, device and browser information, IP address, authentication events, diagnostic data, API usage,\n    widget configuration, domain configuration, usage metrics, and interaction history with the Service.\n- category: communication\n  text: Messages sent to support, sales, or us generally, and records of those communications.\n- category: behavioral\n  text: Consent status, subscription preferences, and engagement with our communications.\npurposes:\n- purpose: Provide and operate the Service\n  text: provide, operate, secure, and support the Service\n- purpose: Process payments and manage subscriptions\n  text: process payments and manage subscriptions\n- purpose: AI monitoring\n  text: conduct AI monitoring, including sending Monitoring Probes to third-party Automated Agents to assess accuracy\n- purpose: Analytics and product improvement\n  text: perform drift detection, analytics, scoring, and product improvement\n- purpose: Fraud and security\n  text: detect,\
  \ investigate, and prevent fraud, misuse, or security incidents\nretention:\n- scope: Account Data\n  period: null\n  text: Account Data is retained for the duration of the account relationship and for a reasonable period thereafter\n    for legal and administrative purposes.\n- scope: Customer Data\n  period: thirty (30) days\n  text: Customer Data is retained during the subscription and for thirty (30) days following termination to support\n    data export, after which it may be deleted.\n- scope: Billing and transaction records\n  period: null\n  text: Billing and transaction records are retained for the period required by applicable tax and accounting laws.\nresidency:\n- region: Canada\n  text: AITWIRE is based in Ontario, Canada.\ntransfers:\n- mechanism: other\n  text: Personal information may also be processed by our service providers in other jurisdictions, including through\n    Cloudflare's global edge network.\nsubprocessors:\n  url: null\n  text: Service providers and subprocessors\
  \ assisting with hosting, identity, analytics, support, payment processing,\n    communications, or infrastructure\ndpa:\n  available: true\n  url: null\n  text: Enterprise customers requiring processor-style commitments should refer to the AITWIRE Enterprise Data Processing\n    Addendum .\ndeletion:\n  route: null\n  text: Customer Data is retained during the subscription and for thirty (30) days following termination to support\n    data export, after which it may be deleted.\nrights:\n- right: access\n  text: request access to their personal information held by AITWIRE\n- right: correction\n  text: request correction of inaccurate personal information\n- right: withdraw consent\n  text: withdraw consent to certain processing activities\n- right: complaint\n  text: file a complaint with the Office of the Privacy Commissioner of Canada or the applicable provincial privacy\n    authority\n- right: deletion, portability, restriction, or objection\n  text: individuals may also have rights\
  \ regarding deletion, portability, restriction, or objection\nsale_or_sharing:\n  stance: prohibited\n  text: AITWIRE does not sell personal information as that term is commonly understood in consumer privacy laws.\n"
source_yaml_url: https://artifacts.apis.io/aitwire-com/privacy/aitwire-com-privacy-policy.yml
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
- sale_or_sharing
summary_line: 25 quoted statements, read from aitwire-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- Connectivity
- Industrial
---
