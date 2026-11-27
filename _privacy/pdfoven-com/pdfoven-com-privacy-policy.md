---
api_specs:
- filename: pdfoven-com-render-api-openapi.yml
  format: yaml
  label: pdfoven-com Render API
  slug: pdfoven-com-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfoven-com/openapi/pdfoven-com-render-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email address and a salted hash of your password.'
  - category: contact
    text: Support emails may be processed by an AI assistant operated by PDFOven.
  - category: financial
    text: 'Billing data: handled by Stripe. We store your Stripe customer and subscription IDs, never your card details.'
  - category: device
    text: the device type (mobile, tablet or desktop)
  - category: behavioral
    text: render counts and per-request metadata (time, source type, output type, duration, size, error messages)
  deletion:
    route: Delete account from the billing page, or email support@pdfoven.com
    text: You can delete your account and its data at any time from the billing page, or request access, correction or deletion by emailing support@pdfoven.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure the Service
    text: To provide and secure the Service, enforce plan limits, process payments, and send account emails (welcome, password reset, billing).
  - purpose: Website visit counting
    text: We count page visits without cookies or third-party trackers
  retention:
  - period: 400 days
    scope: Visit counts
    text: Visit counts are deleted after 400 days.
  - period: null
    scope: Rendered files
    text: Rendered files are streamed back to you and not written to storage.
  rights:
  - right: Access, correction, deletion
    text: request access, correction or deletion by emailing support@pdfoven.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data and don't use your documents to train models.
  subprocessors:
    text: Processors Railway (hosting), Stripe (payments), Resend (transactional and support email).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pdfoven-com
provenance_date: '2026-11-10'
provider_name: pdfoven-com
provider_slug: pdfoven-com
slug: pdfoven-com-privacy-policy
source_date: '2026-11-10'
source_filename: pdfoven-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pdfoven.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pdfoven-com\naid: pdfoven-com\nurl: https://pdfoven.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your email address and a salted hash of your password.'\n- category: contact\n  text: Support emails may be processed by an AI assistant operated by PDFOven.\n- category: financial\n  text: 'Billing data: handled by Stripe. We store your Stripe customer and subscription IDs, never your card details.'\n- category: device\n  text: the device type (mobile, tablet or desktop)\n- category: behavioral\n  text: render\
  \ counts and per-request metadata (time, source type, output type, duration, size, error messages)\npurposes:\n- purpose: Provide and secure the Service\n  text: To provide and secure the Service, enforce plan limits, process payments, and send account emails (welcome,\n    password reset, billing).\n- purpose: Website visit counting\n  text: We count page visits without cookies or third-party trackers\nretention:\n- scope: Visit counts\n  period: 400 days\n  text: Visit counts are deleted after 400 days.\n- scope: Rendered files\n  period: null\n  text: Rendered files are streamed back to you and not written to storage.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors Railway (hosting), Stripe (payments), Resend (transactional and support email).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account from the billing page, or email support@pdfoven.com\n  text: You can delete your account and its data at any time from the billing\
  \ page, or request access, correction\n    or deletion by emailing support@pdfoven.com .\nrights:\n- right: Access, correction, deletion\n  text: request access, correction or deletion by emailing support@pdfoven.com\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data and don't use your documents to train models.\n"
source_yaml_url: https://artifacts.apis.io/pdfoven-com/privacy/pdfoven-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from pdfoven-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Conversion
- Developers
---
