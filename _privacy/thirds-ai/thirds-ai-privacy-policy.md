---
api_specs:
- filename: thirds-ai-batches-api-openapi.yml
  format: yaml
  label: thirds.ai Batches API
  slug: thirds-ai-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-batches-api-openapi.yml
- filename: thirds-ai-brand-kits-api-openapi.yml
  format: yaml
  label: thirds.ai Brand Kits API
  slug: thirds-ai-brand-kits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-brand-kits-api-openapi.yml
- filename: thirds-ai-carousels-api-openapi.yml
  format: yaml
  label: thirds.ai Carousels API
  slug: thirds-ai-carousels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-carousels-api-openapi.yml
- filename: thirds-ai-downloads-api-openapi.yml
  format: yaml
  label: thirds.ai Downloads API
  slug: thirds-ai-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-downloads-api-openapi.yml
- filename: thirds-ai-image-api-openapi.yml
  format: yaml
  label: thirds.ai Image API
  slug: thirds-ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-image-api-openapi.yml
- filename: thirds-ai-image-assets-api-openapi.yml
  format: yaml
  label: thirds.ai Image Assets API
  slug: thirds-ai-image-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-image-assets-api-openapi.yml
- filename: thirds-ai-image-packs-api-openapi.yml
  format: yaml
  label: thirds.ai Image Packs API
  slug: thirds-ai-image-packs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-image-packs-api-openapi.yml
- filename: thirds-ai-keys-api-openapi.yml
  format: yaml
  label: thirds.ai Keys API
  slug: thirds-ai-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-keys-api-openapi.yml
- filename: thirds-ai-me-api-openapi.yml
  format: yaml
  label: thirds.ai Me API
  slug: thirds-ai-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-me-api-openapi.yml
- filename: thirds-ai-openapi-json-api-openapi.yml
  format: yaml
  label: thirds.ai Openapi.json API
  slug: thirds-ai-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-openapi-json-api-openapi.yml
- filename: thirds-ai-pdf-api-openapi.yml
  format: yaml
  label: thirds.ai PDF API
  slug: thirds-ai-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-pdf-api-openapi.yml
- filename: thirds-ai-public-stats-api-openapi.yml
  format: yaml
  label: thirds.ai Public Stats API
  slug: thirds-ai-public-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-public-stats-api-openapi.yml
- filename: thirds-ai-template-builds-api-openapi.yml
  format: yaml
  label: thirds.ai Template Builds API
  slug: thirds-ai-template-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-template-builds-api-openapi.yml
- filename: thirds-ai-templates-api-openapi.yml
  format: yaml
  label: thirds.ai Templates API
  slug: thirds-ai-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-templates-api-openapi.yml
- filename: thirds-ai-testimonials-api-openapi.yml
  format: yaml
  label: thirds.ai Testimonials API
  slug: thirds-ai-testimonials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-testimonials-api-openapi.yml
- filename: thirds-ai-webhooks-api-openapi.yml
  format: yaml
  label: thirds.ai Webhooks API
  slug: thirds-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirds-ai/openapi/thirds-ai-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Your account holds your email address, a display name if you choose to set one, and the sign-in methods you have connected.
  - category: behavioral
    text: It also records your visits and shows us where people click and scroll
  - category: device
    text: Your browser connects to PostHog directly, so PostHog also sees your network address and your browser and device type.
  - category: communication
    text: When you write to support@thirds.ai, we keep your message in the support mailbox until your request is closed.
  - category: other
    text: The HTML, templates, and assets you send exist on our servers only to make your PDFs and images.
  deletion:
    route: Delete files in the app, or write to support@thirds.ai to delete your account
    text: You can choose a shorter period, and you can delete a file earlier at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Product analytics
    text: We use PostHog Cloud to see how people find thirds.ai and use it, so we can fix what's confusing.
  - purpose: Account and billing records
    text: We also keep a record of your plan, your credit use, and your renders, because that record is how we know what to show you and what to charge.
  - purpose: Sign-in email
    text: When you sign in with an email link, Resend delivers that one mail for us.
  residency:
  - region: Finland
    text: Hetzner Online GmbH hosts the live application, database, and file storage in Finland.
  - region: EU
    text: PostHog Cloud in the EU stores our product analytics
  retention:
  - period: 90 days
    scope: Event details and visit source tags
    text: We keep event details and visit source tags on our servers for 90 days.
  - period: 365 days
    scope: Finished PDF or static image, paid plan
    text: The longest period is 365 days on a paid plan and 30 days on the free plan
  - period: 30 days
    scope: Finished PDF or static image, free plan
    text: 30 days on the free plan
  - period: when the job ends
    scope: Job input
    text: We delete the input of a job when the job ends.
  - period: one-hour grace period
    scope: Failed standalone AI prompts
    text: Failed standalone prompts are removed by cleanup after a one-hour grace period.
  - period: null
    scope: Successful AI image prompts and saved versions
    text: We keep successful image prompts and their saved versions in your private account until you close it.
  rights:
  - right: access
    text: You can ask us for a copy of the data we hold about you
  - right: correction
    text: ask us to correct it
  - right: deletion of account
    text: ask us to delete your account and everything in it
  - right: disconnect AI app
    text: You can disconnect an app at any time under Connected apps in Settings.
  - right: change analytics choice
    text: You can change your choice at any time.
  role:
    text: The operator uses thirds.ai as a trading name and is the controller for the personal data described on this page.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: PostHog is our sub-processor for this work, and it stores the data in the EU.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: thirds.ai
provenance_date: '2026-11-10'
provider_name: thirds.ai
provider_slug: thirds-ai
slug: thirds-ai-privacy-policy
source_date: '2026-11-10'
source_filename: thirds-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thirds.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: thirds.ai\naid: thirds-ai\nurl: https://thirds.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The operator uses thirds.ai as a trading name and is the controller for the personal data described on this\n    page.\ndata_categories:\n- category: contact\n  text: Your account holds your email address, a display name if you choose to set one, and the sign-in methods\n    you have connected.\n- category: behavioral\n  text: It also records your visits and shows us where people click and scroll\n- category: device\n  text: Your browser connects to PostHog directly, so PostHog also sees\
  \ your network address and your browser and\n    device type.\n- category: communication\n  text: When you write to support@thirds.ai, we keep your message in the support mailbox until your request is closed.\n- category: other\n  text: The HTML, templates, and assets you send exist on our servers only to make your PDFs and images.\npurposes:\n- purpose: Product analytics\n  text: We use PostHog Cloud to see how people find thirds.ai and use it, so we can fix what's confusing.\n- purpose: Account and billing records\n  text: We also keep a record of your plan, your credit use, and your renders, because that record is how we know\n    what to show you and what to charge.\n- purpose: Sign-in email\n  text: When you sign in with an email link, Resend delivers that one mail for us.\nretention:\n- scope: Event details and visit source tags\n  period: 90 days\n  text: We keep event details and visit source tags on our servers for 90 days.\n- scope: Finished PDF or static image, paid plan\n \
  \ period: 365 days\n  text: The longest period is 365 days on a paid plan and 30 days on the free plan\n- scope: Finished PDF or static image, free plan\n  period: 30 days\n  text: 30 days on the free plan\n- scope: Job input\n  period: when the job ends\n  text: We delete the input of a job when the job ends.\n- scope: Failed standalone AI prompts\n  period: one-hour grace period\n  text: Failed standalone prompts are removed by cleanup after a one-hour grace period.\n- scope: Successful AI image prompts and saved versions\n  period: null\n  text: We keep successful image prompts and their saved versions in your private account until you close it.\nresidency:\n- region: Finland\n  text: Hetzner Online GmbH hosts the live application, database, and file storage in Finland.\n- region: EU\n  text: PostHog Cloud in the EU stores our product analytics\ntransfers: []\nsubprocessors:\n  url: null\n  text: PostHog is our sub-processor for this work, and it stores the data in the EU.\ndpa:\n \
  \ available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete files in the app, or write to support@thirds.ai to delete your account\n  text: You can choose a shorter period, and you can delete a file earlier at any time.\nrights:\n- right: access\n  text: You can ask us for a copy of the data we hold about you\n- right: correction\n  text: ask us to correct it\n- right: deletion of account\n  text: ask us to delete your account and everything in it\n- right: disconnect AI app\n  text: You can disconnect an app at any time under Connected apps in Settings.\n- right: change analytics choice\n  text: You can change your choice at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/thirds-ai/privacy/thirds-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from thirds.ai's own page on 2026-11-10.
synthetic: false
tags:
- pdf-automation
- image-automation
- Document Generation
- HTML to PDF
- HTML to Image
- template-rendering
- Branded Content
- Developer Tools
- MCP Server
- Agent-Native
- marketing-ops
---
