---
api_specs:
- filename: sendmux-ai-billing-api-openapi.yml
  format: yaml
  label: sendmux-ai Billing API
  slug: sendmux-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-billing-api-openapi.yml
- filename: sendmux-ai-connection-api-openapi.yml
  format: yaml
  label: sendmux-ai Connection API
  slug: sendmux-ai-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-connection-api-openapi.yml
- filename: sendmux-ai-domain-filters-api-openapi.yml
  format: yaml
  label: sendmux-ai Domain Filters API
  slug: sendmux-ai-domain-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-domain-filters-api-openapi.yml
- filename: sendmux-ai-domains-api-openapi.yml
  format: yaml
  label: sendmux-ai Domains API
  slug: sendmux-ai-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-domains-api-openapi.yml
- filename: sendmux-ai-emails-api-openapi.yml
  format: yaml
  label: sendmux-ai Emails API
  slug: sendmux-ai-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-emails-api-openapi.yml
- filename: sendmux-ai-inboxes-api-openapi.yml
  format: yaml
  label: sendmux-ai Inboxes API
  slug: sendmux-ai-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-inboxes-api-openapi.yml
- filename: sendmux-ai-mailbox-api-api-openapi.yml
  format: yaml
  label: sendmux-ai Mailbox API
  slug: sendmux-ai-mailbox-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-mailbox-api-api-openapi.yml
- filename: sendmux-ai-mailbox-filters-api-openapi.yml
  format: yaml
  label: sendmux-ai Mailbox Filters API
  slug: sendmux-ai-mailbox-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-mailbox-filters-api-openapi.yml
- filename: sendmux-ai-mailboxes-api-openapi.yml
  format: yaml
  label: sendmux-ai Mailboxes API
  slug: sendmux-ai-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-mailboxes-api-openapi.yml
- filename: sendmux-ai-sending-accounts-api-openapi.yml
  format: yaml
  label: sendmux-ai Sending accounts API
  slug: sendmux-ai-sending-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-sending-accounts-api-openapi.yml
- filename: sendmux-ai-webhooks-api-openapi.yml
  format: yaml
  label: sendmux-ai Webhooks API
  slug: sendmux-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendmux-ai/openapi/sendmux-ai-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: communication
    text: Sender and recipient email addresses
  - category: financial
    text: Billing information (processed and stored by Stripe — we do not store full payment card details)
  - category: device
    text: browser and device information
  - category: behavioral
    text: Feature usage patterns
  deletion:
    route: Contact us
    text: Delete your account and associated data by contacting us
  dpa:
    available: true
    text: Our Data Processing Agreement, available at sendmux.ai/legal/dpa or upon request at contact@sendmux.ai
    url: sendmux.ai/legal/dpa
  purposes:
  - purpose: Provide, operate, and maintain the Service
    text: Provide, operate, and maintain the Service
  - purpose: Process payments and manage billing
    text: Process payments and manage billing
  - purpose: Detect and prevent abuse, fraud and security issues
    text: Detect, prevent, and address abuse, fraud, and security issues
  residency:
  - region: European Union
    text: Your data is primarily stored within the European Union.
  - region: United States
    text: We do not store data on Amazon Web Services or in the United States, except where Cloudflare's global edge network may temporarily cache non-sensitive data at edge nodes.
  retention:
  - period: Duration of account plus 30 days after termination
    scope: Account information
    text: Duration of account plus 30 days after termination
  - period: 90 days
    scope: Email metadata and delivery logs
    text: 90 days (configurable by customer)
  - period: minutes to hours
    scope: Outbound email body content
    text: Deleted after delivery or retry exhaustion (typically minutes to hours)
  - period: 7 years
    scope: Payment and billing records
    text: 7 years (as required by Australian tax law)
  rights:
  - right: Access
    text: Access your personal information through your account dashboard
  - right: Correct
    text: Correct inaccurate information through your account settings
  - right: Export
    text: Export your data (delivery logs, provider configurations) through the API or dashboard
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Data portability
    text: Data portability (receive your data in a structured, machine-readable format)
  - right: Restriction
    text: Request restriction of processing
  - right: Withdraw consent
    text: Withdraw consent at any time where processing is based on consent
  role:
    text: Qubrics a data processor under GDPR
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: See Section 5.1 for the sub-processor table identifying the EU hosting provider.
    url: null
  transfers:
  - mechanism: SCC
    text: Cloudflare maintains appropriate safeguards including Standard Contractual Clauses for international transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: sendmux-ai
provenance_date: '2026-11-10'
provider_name: sendmux-ai
provider_slug: sendmux-ai
slug: sendmux-ai-privacy-policy
source_date: '2026-11-10'
source_filename: sendmux-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sendmux.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sendmux-ai\naid: sendmux-ai\nurl: https://sendmux.ai/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Qubrics a data processor under GDPR\ndata_categories:\n- category: contact\n  text: Email address\n- category: communication\n  text: Sender and recipient email addresses\n- category: financial\n  text: Billing information (processed and stored by Stripe — we do not store full payment card details)\n- category: device\n  text: browser and device information\n- category: behavioral\n  text: Feature usage patterns\npurposes:\n- purpose: Provide, operate, and maintain the Service\n  text:\
  \ Provide, operate, and maintain the Service\n- purpose: Process payments and manage billing\n  text: Process payments and manage billing\n- purpose: Detect and prevent abuse, fraud and security issues\n  text: Detect, prevent, and address abuse, fraud, and security issues\nretention:\n- scope: Account information\n  period: Duration of account plus 30 days after termination\n  text: Duration of account plus 30 days after termination\n- scope: Email metadata and delivery logs\n  period: 90 days\n  text: 90 days (configurable by customer)\n- scope: Outbound email body content\n  period: minutes to hours\n  text: Deleted after delivery or retry exhaustion (typically minutes to hours)\n- scope: Payment and billing records\n  period: 7 years\n  text: 7 years (as required by Australian tax law)\nresidency:\n- region: European Union\n  text: Your data is primarily stored within the European Union.\n- region: United States\n  text: We do not store data on Amazon Web Services or in the United\
  \ States, except where Cloudflare's global edge\n    network may temporarily cache non-sensitive data at edge nodes.\ntransfers:\n- mechanism: SCC\n  text: Cloudflare maintains appropriate safeguards including Standard Contractual Clauses for international transfers.\nsubprocessors:\n  url: null\n  text: See Section 5.1 for the sub-processor table identifying the EU hosting provider.\ndpa:\n  available: true\n  url: sendmux.ai/legal/dpa\n  text: Our Data Processing Agreement, available at sendmux.ai/legal/dpa or upon request at contact@sendmux.ai\ndeletion:\n  route: Contact us\n  text: Delete your account and associated data by contacting us\nrights:\n- right: Access\n  text: Access your personal information through your account dashboard\n- right: Correct\n  text: Correct inaccurate information through your account settings\n- right: Export\n  text: Export your data (delivery logs, provider configurations) through the API or dashboard\n- right: Object\n  text: Object to processing based\
  \ on legitimate interests\n- right: Data portability\n  text: Data portability (receive your data in a structured, machine-readable format)\n- right: Restriction\n  text: Request restriction of processing\n- right: Withdraw consent\n  text: Withdraw consent at any time where processing is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/sendmux-ai/privacy/sendmux-ai-privacy-policy.yml
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
summary_line: 27 quoted statements, read from sendmux-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Artificial Intelligence
- Agents
- Integration
---
