---
api_specs:
- filename: relmcrm-com-activities-api-openapi.yml
  format: yaml
  label: Relm Activities API
  slug: relmcrm-com-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-activities-api-openapi.yml
- filename: relmcrm-com-automations-api-openapi.yml
  format: yaml
  label: Relm Automations API
  slug: relmcrm-com-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-automations-api-openapi.yml
- filename: relmcrm-com-batch-api-openapi.yml
  format: yaml
  label: Relm Batch API
  slug: relmcrm-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-batch-api-openapi.yml
- filename: relmcrm-com-companies-api-openapi.yml
  format: yaml
  label: Relm Companies API
  slug: relmcrm-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-companies-api-openapi.yml
- filename: relmcrm-com-connections-api-openapi.yml
  format: yaml
  label: Relm Connections API
  slug: relmcrm-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-connections-api-openapi.yml
- filename: relmcrm-com-contacts-api-openapi.yml
  format: yaml
  label: Relm Contacts API
  slug: relmcrm-com-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-contacts-api-openapi.yml
- filename: relmcrm-com-deals-api-openapi.yml
  format: yaml
  label: Relm Deals API
  slug: relmcrm-com-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-deals-api-openapi.yml
- filename: relmcrm-com-discovery-api-openapi.yml
  format: yaml
  label: Relm Discovery API
  slug: relmcrm-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-discovery-api-openapi.yml
- filename: relmcrm-com-pipelines-api-openapi.yml
  format: yaml
  label: Relm Pipelines API
  slug: relmcrm-com-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-pipelines-api-openapi.yml
- filename: relmcrm-com-registry-api-openapi.yml
  format: yaml
  label: Relm Registry API
  slug: relmcrm-com-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-registry-api-openapi.yml
- filename: relmcrm-com-search-api-openapi.yml
  format: yaml
  label: Relm Search API
  slug: relmcrm-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-search-api-openapi.yml
- filename: relmcrm-com-sequences-api-openapi.yml
  format: yaml
  label: Relm Sequences API
  slug: relmcrm-com-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-sequences-api-openapi.yml
- filename: relmcrm-com-templates-api-openapi.yml
  format: yaml
  label: Relm Templates API
  slug: relmcrm-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-templates-api-openapi.yml
- filename: relmcrm-com-webhooks-api-openapi.yml
  format: yaml
  label: Relm Webhooks API
  slug: relmcrm-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relmcrm-com/openapi/relmcrm-com-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: the email address and password you sign up with, your workspace name, your API keys, and your billing record
  - category: behavioral
    text: That covers page views, clicks, and product events such as signing up or minting an API key.
  - category: financial
    text: Held by Stripe, never by us - we do not see your card
  - category: communication
    text: Sending email you asked us to send
  deletion:
    route: Email to the provider to erase the entire account, including from backups on the stated schedule
    text: To erase your entire account and everything in it, email [email protected] and we will delete it - including from backups, as those roll off on the schedule above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign-in and account recovery
    text: Sign-in and account recovery
  - purpose: Running the CRM product
    text: The product itself
  - purpose: Quota and billing
    text: Quota and billing
  - purpose: Product and site analytics
    text: Knowing what to improve
  residency:
  - region: Finland (EU)
    text: Your CRM database runs on our own servers in Helsinki, Finland (EU) , hosted by Hetzner.
  retention:
  - period: Until you delete the account
    scope: Account data
    text: Until you delete the account
  - period: Until revoked
    scope: API keys
    text: Until revoked - stored only as a SHA-256 hash, never in plain text
  - period: 7 days
    scope: Test-mode CRM records
    text: test-mode records auto-delete after 7 days
  - period: 14 days locally and 30 days offsite
    scope: Encrypted backups
    text: Backups are kept 14 days locally and 30 days offsite.
  rights:
  - right: access
    text: you may have the right to access, correct, export, or delete your personal data
  - right: object or restrict processing
    text: to object to or restrict how we process it
  - right: complain to authority
    text: to complain to your data protection authority
  - right: export CRM content
    text: Your CRM content is exportable at any time through the same API you put it in with.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data , and we do not share it for advertising.
  subprocessors:
    text: 'These are our subprocessors - the only third parties that can hold or process your data:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Relm
provenance_date: '2026-11-10'
provider_name: Relm
provider_slug: relmcrm-com
slug: relmcrm-com-privacy-policy
source_date: '2026-11-10'
source_filename: relmcrm-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://relmcrm.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Relm\naid: relmcrm-com\nurl: https://relmcrm.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the email address and password you sign up with, your workspace name, your API keys, and your billing record\n- category: behavioral\n  text: That covers page views, clicks, and product events such as signing up or minting an API key.\n- category: financial\n  text: Held by Stripe, never by us - we do not see your card\n- category: communication\n  text: Sending email you asked us to send\npurposes:\n- purpose: Sign-in and account recovery\n\
  \  text: Sign-in and account recovery\n- purpose: Running the CRM product\n  text: The product itself\n- purpose: Quota and billing\n  text: Quota and billing\n- purpose: Product and site analytics\n  text: Knowing what to improve\nretention:\n- scope: Account data\n  period: Until you delete the account\n  text: Until you delete the account\n- scope: API keys\n  period: Until revoked\n  text: Until revoked - stored only as a SHA-256 hash, never in plain text\n- scope: Test-mode CRM records\n  period: 7 days\n  text: test-mode records auto-delete after 7 days\n- scope: Encrypted backups\n  period: 14 days locally and 30 days offsite\n  text: Backups are kept 14 days locally and 30 days offsite.\nresidency:\n- region: Finland (EU)\n  text: Your CRM database runs on our own servers in Helsinki, Finland (EU) , hosted by Hetzner.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'These are our subprocessors - the only third parties that can hold or process your data:'\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email to the provider to erase the entire account, including from backups on the stated schedule\n  text: To erase your entire account and everything in it, email [email protected] and we will delete it - including\n    from backups, as those roll off on the schedule above.\nrights:\n- right: access\n  text: you may have the right to access, correct, export, or delete your personal data\n- right: object or restrict processing\n  text: to object to or restrict how we process it\n- right: complain to authority\n  text: to complain to your data protection authority\n- right: export CRM content\n  text: Your CRM content is exportable at any time through the same API you put it in with.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data , and we do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/relmcrm-com/privacy/relmcrm-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Relm's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Contacts
- Deals
- Sales Pipeline
- Automation
- Webhook
- MCP
- A2A
- AI Agents
- Agent-Native
- United Arab Emirates
---
