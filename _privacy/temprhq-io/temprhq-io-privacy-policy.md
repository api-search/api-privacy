---
api_specs:
- filename: temprhq-io-openapi-generated.yml
  format: yaml
  label: temprhq-io API
  slug: temprhq-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temprhq-io/openapi/_ae-authored/temprhq-io-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, an optional username, a hashed password
  - category: contact
    text: The contact form sends your name, email address, and message to us through Web3Forms.
  - category: financial
    text: Stripe processes payments. We store your Stripe customer and subscription IDs
  - category: location
    text: We work out the approximate location of that IP address on our own servers
  - category: behavioral
    text: for each AI request, the provider, model, token counts, estimated cost, and time
  - category: device
    text: the error and its stack trace, your IDE and extension versions
  - category: communication
    text: anything you email to us
  - category: other
    text: the keys you add in the portal for the AI providers you use
  deletion:
    route: Profile page in the portal, or email
    text: You can close your account on the Profile page in the portal, which deletes your data straight away (see section 7), or email us to have it deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'To provide the Service: signing you in, relaying your requests to the providers you choose, running the agent, and syncing your chats and settings.'
  - purpose: Improve the Service
    text: To improve the Service.
  - purpose: No AI training
    text: We don't use your prompts, code, or chats to train AI models.
  residency:
  - region: United States
    text: Tempr is based in the United States. We store and process information with Amazon Web Services in its US East (N. Virginia) region.
  retention:
  - period: until you close your account
    scope: Account and usage data
    text: 'Account, license, and usage data, and your sign-in history: until you close your account.'
  - period: 7, 30, or 90 days
    scope: Gateway logs
    text: 'Gateway logs: your plan''s retention period (7, 30, or 90 days, or what an Enterprise contract sets), or shorter if you set it.'
  - period: 72 hours after the run finishes
    scope: Agent runs
    text: 'Agent runs: deleted 72 hours after the run finishes.'
  - period: 14 days
    scope: Server logs
    text: 'Server logs, including access logs: 14 days.'
  rights:
  - right: access, correction, deletion
    text: You can request access to, correction of, or deletion of your personal data by contacting us.
  - right: GDPR rights
    text: If you're in the EEA, UK, or Switzerland, you have rights under the GDPR to access, correct, delete, restrict, or port your data, to object to processing, and to lodge a complaint with your local data protection authority.
  - right: CCPA/CPRA opt-out
    text: opt out of the sale or sharing of personal information (we don't sell it)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your personal information.
  subprocessors:
    text: 'Amazon Web Services: hosting, database, and email delivery (Amazon SES). Stripe: payments and subscriptions. WorkOS: single sign-on for Teams organizations'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: temprhq-io
provenance_date: '2026-11-10'
provider_name: temprhq-io
provider_slug: temprhq-io
slug: temprhq-io-privacy-policy
source_date: '2026-11-10'
source_filename: temprhq-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://temprhq.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: temprhq-io\naid: temprhq-io\nurl: https://temprhq.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your email address, an optional username, a hashed password\n- category: contact\n  text: The contact form sends your name, email address, and message to us through Web3Forms.\n- category: financial\n  text: Stripe processes payments. We store your Stripe customer and subscription IDs\n- category: location\n  text: We work out the approximate location of that IP address on our own servers\n- category: behavioral\n  text: for each\
  \ AI request, the provider, model, token counts, estimated cost, and time\n- category: device\n  text: the error and its stack trace, your IDE and extension versions\n- category: communication\n  text: anything you email to us\n- category: other\n  text: the keys you add in the portal for the AI providers you use\npurposes:\n- purpose: Provide the Service\n  text: 'To provide the Service: signing you in, relaying your requests to the providers you choose, running the\n    agent, and syncing your chats and settings.'\n- purpose: Improve the Service\n  text: To improve the Service.\n- purpose: No AI training\n  text: We don't use your prompts, code, or chats to train AI models.\nretention:\n- scope: Account and usage data\n  period: until you close your account\n  text: 'Account, license, and usage data, and your sign-in history: until you close your account.'\n- scope: Gateway logs\n  period: 7, 30, or 90 days\n  text: 'Gateway logs: your plan''s retention period (7, 30, or 90 days, or\
  \ what an Enterprise contract sets), or\n    shorter if you set it.'\n- scope: Agent runs\n  period: 72 hours after the run finishes\n  text: 'Agent runs: deleted 72 hours after the run finishes.'\n- scope: Server logs\n  period: 14 days\n  text: 'Server logs, including access logs: 14 days.'\nresidency:\n- region: United States\n  text: Tempr is based in the United States. We store and process information with Amazon Web Services in its US\n    East (N. Virginia) region.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Amazon Web Services: hosting, database, and email delivery (Amazon SES). Stripe: payments and subscriptions.\n    WorkOS: single sign-on for Teams organizations'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Profile page in the portal, or email\n  text: You can close your account on the Profile page in the portal, which deletes your data straight away (see\n    section 7), or email us to have it deleted.\nrights:\n- right: access, correction,\
  \ deletion\n  text: You can request access to, correction of, or deletion of your personal data by contacting us.\n- right: GDPR rights\n  text: If you're in the EEA, UK, or Switzerland, you have rights under the GDPR to access, correct, delete, restrict,\n    or port your data, to object to processing, and to lodge a complaint with your local data protection authority.\n- right: CCPA/CPRA opt-out\n  text: opt out of the sale or sharing of personal information (we don't sell it)\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/temprhq-io/privacy/temprhq-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from temprhq-io's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Automation
- Developer Tools
- Cloud
---
