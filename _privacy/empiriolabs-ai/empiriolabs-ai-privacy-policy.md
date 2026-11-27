---
api_specs:
- filename: empiriolabs-ai-chatcompletions-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Chat Completions API
  slug: empiriolabs-ai-chatcompletions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-chatcompletions-api-openapi.yml
- filename: empiriolabs-ai-completions-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Completions API
  slug: empiriolabs-ai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-completions-api-openapi.yml
- filename: empiriolabs-ai-gemini-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Gemini API
  slug: empiriolabs-ai-gemini-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-gemini-api-openapi.yml
- filename: empiriolabs-ai-messages-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Messages API
  slug: empiriolabs-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-messages-api-openapi.yml
- filename: empiriolabs-ai-models-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Models API
  slug: empiriolabs-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-models-api-openapi.yml
- filename: empiriolabs-ai-responses-api-openapi.yml
  format: yaml
  label: EmpirioLabs AI Responses API
  slug: empiriolabs-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empiriolabs-ai/openapi/empiriolabs-ai-responses-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: account details, authentication data, billing and payment records, API usage records, support messages
  - category: device
    text: technical information such as timestamps, request metadata, usage metrics, latency, error codes, IP address, user agent, and diagnostic data
  - category: behavioral
    text: the pages you view, the site or source that referred you, and any marketing or campaign identifiers included in the links you follow
  - category: communication
    text: content you submit, files you upload, generated outputs
  - category: biometric
    text: Images and video of your face captured during verification, the photos of yourself you add, and facial features extracted from them.
  deletion:
    route: Email support@empiriolabs.ai to request deletion of your account and associated information
    text: You can request deletion of your account and associated information at any time by contacting support@empiriolabs.ai .
  dpa:
    available: true
    text: A data processing agreement (DPA) incorporating these safeguards is available to business customers on request at support@empiriolabs.ai .
    url: null
  purposes:
  - purpose: service operation and billing
    text: We use information to route requests, return outputs, provide accounts and API access, meter usage, process billing
  - purpose: security and abuse prevention
    text: prevent fraud and abuse, maintain security, investigate issues
  - purpose: marketing measurement
    text: understand how visitors find and use our services and measure the performance of our marketing
  - purpose: face verification
    text: We use them only to confirm that you are a real person and the person in your photos, and to generate videos from those photos on your account.
  residency:
  - region: United States
    text: We are based in the United States and process information there and in the locations of the service providers described in this policy.
  retention:
  - period: indefinitely
    scope: Usage records
    text: is retained indefinitely so you can review historical usage in your dashboard
  - period: null
    scope: Content of requests and responses
    text: We do not retain the content of your requests or responses once a response is delivered, for any model, and we never use it to train any model.
  - period: approximately 30 days
    scope: Generated files
    text: the underlying files are retained on our storage for approximately 30 days before being deleted by our automated cleanup processes
  - period: approximately 48 hours
    scope: Uploaded files
    text: are retained for a shorter window, approximately 48 hours, before being deleted by our automated cleanup processes
  - period: null
    scope: Face verification data
    text: Until you remove it, withdraw your consent, or your account is deleted; it is deleted then.
  - period: 30 days
    scope: YouTube data after access revoked
    text: When access is revoked, we delete the data obtained through it within 30 days, unless the law requires us to keep it longer.
  rights:
  - right: access, correction, deletion, export, restriction, objection, opt-out
    text: you may have rights to access, correct, delete, export, restrict, object to, or opt out of certain processing of personal information
  role:
    text: This Privacy Policy explains how EmpirioLabs.ai LLC, a New Mexico limited liability company ("Empirio Labs", "we", "us", or "our") handles information when you use our services
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on recognized transfer safeguards, including the European Commission's Standard Contractual Clauses and the UK Addendum where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EmpirioLabs AI
provenance_date: '2026-11-09'
provider_name: EmpirioLabs AI
provider_slug: empiriolabs-ai
slug: empiriolabs-ai-privacy-policy
source_date: '2026-11-09'
source_filename: empiriolabs-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://empiriolabs.ai/policy/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EmpirioLabs AI\naid: empiriolabs-ai\nurl: https://empiriolabs.ai/policy/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy explains how EmpirioLabs.ai LLC, a New Mexico limited liability company (\"Empirio Labs\",\n    \"we\", \"us\", or \"our\") handles information when you use our services\ndata_categories:\n- category: identifying\n  text: account details, authentication data, billing and payment records, API usage records, support messages\n- category: device\n  text: technical information such as timestamps, request metadata, usage metrics, latency, error\
  \ codes, IP address,\n    user agent, and diagnostic data\n- category: behavioral\n  text: the pages you view, the site or source that referred you, and any marketing or campaign identifiers included\n    in the links you follow\n- category: communication\n  text: content you submit, files you upload, generated outputs\n- category: biometric\n  text: Images and video of your face captured during verification, the photos of yourself you add, and facial features\n    extracted from them.\npurposes:\n- purpose: service operation and billing\n  text: We use information to route requests, return outputs, provide accounts and API access, meter usage, process\n    billing\n- purpose: security and abuse prevention\n  text: prevent fraud and abuse, maintain security, investigate issues\n- purpose: marketing measurement\n  text: understand how visitors find and use our services and measure the performance of our marketing\n- purpose: face verification\n  text: We use them only to confirm that you\
  \ are a real person and the person in your photos, and to generate videos\n    from those photos on your account.\nretention:\n- scope: Usage records\n  period: indefinitely\n  text: is retained indefinitely so you can review historical usage in your dashboard\n- scope: Content of requests and responses\n  period: null\n  text: We do not retain the content of your requests or responses once a response is delivered, for any model,\n    and we never use it to train any model.\n- scope: Generated files\n  period: approximately 30 days\n  text: the underlying files are retained on our storage for approximately 30 days before being deleted by our automated\n    cleanup processes\n- scope: Uploaded files\n  period: approximately 48 hours\n  text: are retained for a shorter window, approximately 48 hours, before being deleted by our automated cleanup\n    processes\n- scope: Face verification data\n  period: null\n  text: Until you remove it, withdraw your consent, or your account is deleted;\
  \ it is deleted then.\n- scope: YouTube data after access revoked\n  period: 30 days\n  text: When access is revoked, we delete the data obtained through it within 30 days, unless the law requires us\n    to keep it longer.\nresidency:\n- region: United States\n  text: We are based in the United States and process information there and in the locations of the service providers\n    described in this policy.\ntransfers:\n- mechanism: SCC\n  text: we rely on recognized transfer safeguards, including the European Commission's Standard Contractual Clauses\n    and the UK Addendum where applicable\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement (DPA) incorporating these safeguards is available to business customers on request\n    at support@empiriolabs.ai .\ndeletion:\n  route: Email support@empiriolabs.ai to request deletion of your account and associated information\n  text: You can request deletion of your account and\
  \ associated information at any time by contacting support@empiriolabs.ai\n    .\nrights:\n- right: access, correction, deletion, export, restriction, objection, opt-out\n  text: you may have rights to access, correct, delete, export, restrict, object to, or opt out of certain processing\n    of personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/empiriolabs-ai/privacy/empiriolabs-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from EmpirioLabs AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Inference
- Cloud
- Platform
---
