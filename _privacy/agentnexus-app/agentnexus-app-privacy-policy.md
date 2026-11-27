---
api_specs:
- filename: agentnexus-app-discovery-api-openapi.yml
  format: yaml
  label: Agent Nexus Discovery API
  slug: agentnexus-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-discovery-api-openapi.yml
- filename: agentnexus-app-keys-api-openapi.yml
  format: yaml
  label: Agent Nexus Keys API
  slug: agentnexus-app-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-keys-api-openapi.yml
- filename: agentnexus-app-registry-api-openapi.yml
  format: yaml
  label: Agent Nexus Registry API
  slug: agentnexus-app-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-registry-api-openapi.yml
- filename: agentnexus-app-reliability-api-openapi.yml
  format: yaml
  label: Agent Nexus Reliability API
  slug: agentnexus-app-reliability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentnexus-app/openapi/agentnexus-app-reliability-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — email address, login credentials (stored hashed), display name, role.
  - category: device
    text: Access logs — which machine endpoint was called, timestamp, a hashed (non-reversible) form of the caller's IP address, user-agent string and country.
  - category: communication
    text: Support messages — the content of emails you send us.
  - category: financial
    text: Subscription records — plan, status and subscription identifier received from Paddle.
  - category: behavioral
    text: API keys and usage counters — key prefix, hashed key, per-day call counts, last-used timestamp.
  deletion:
    route: Email support@agentnexus.app
    text: Data is deleted or anonymised once no longer needed.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: Used to create and secure your account and provide the Service.
  - purpose: Quotas and abuse prevention
    text: Used to enforce quotas and prevent abuse.
  - purpose: Security and aggregate product analytics
    text: Used for security, abuse prevention and aggregate product analytics.
  - purpose: Operating and moderating public registry
    text: Used to operate and moderate the public registry.
  - purpose: Answering support requests
    text: Used to answer you.
  - purpose: Unlocking paid features
    text: Used to unlock paid features.
  retention:
  - period: up to 12 months afterwards
    scope: Account data
    text: Account data is kept while your account is active and for up to 12 months afterwards.
  - period: 60 days
    scope: Access logs
    text: Access logs are retained for 60 days and then deleted automatically.
  - period: 7 days
    scope: API usage counters
    text: API usage counters are pruned after 7 days.
  - period: null
    scope: Billing records
    text: Billing records are kept as long as tax law requires.
  rights:
  - right: access
    text: you may request access to your data
  - right: correction
    text: correction of inaccurate data
  - right: erasure
    text: erasure
  - right: restriction
    text: restriction of processing
  - right: portability
    text: portability
  - right: objection
    text: you may object to processing based on legitimate interests
  - right: withdraw consent
    text: withdraw consent where consent was the basis
  - right: complain to supervisory authority
    text: you also have the right to complain to your data protection supervisory authority
  role:
    text: For the personal data described here, BrainPath.io acts as the data controller
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use it to train AI models.
  subprocessors:
    text: Service providers / subprocessors — our hosting, database and authentication providers, and the email provider used for account messages.
    url: null
  transfers:
  - mechanism: SCC
    text: Where that happens we rely on appropriate safeguards, such as European Commission adequacy decisions or Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Nexus
provenance_date: '2026-11-09'
provider_name: Agent Nexus
provider_slug: agentnexus-app
slug: agentnexus-app-privacy-policy
source_date: '2026-11-09'
source_filename: agentnexus-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentnexus.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Nexus\naid: agentnexus-app\nurl: https://agentnexus.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the personal data described here, BrainPath.io acts as the data controller\ndata_categories:\n- category: identifying\n  text: Account data — email address, login credentials (stored hashed), display name, role.\n- category: device\n  text: Access logs — which machine endpoint was called, timestamp, a hashed (non-reversible) form of the caller's\n    IP address, user-agent string and country.\n- category: communication\n  text: Support messages — the content of emails you\
  \ send us.\n- category: financial\n  text: Subscription records — plan, status and subscription identifier received from Paddle.\n- category: behavioral\n  text: API keys and usage counters — key prefix, hashed key, per-day call counts, last-used timestamp.\npurposes:\n- purpose: Account creation and security\n  text: Used to create and secure your account and provide the Service.\n- purpose: Quotas and abuse prevention\n  text: Used to enforce quotas and prevent abuse.\n- purpose: Security and aggregate product analytics\n  text: Used for security, abuse prevention and aggregate product analytics.\n- purpose: Operating and moderating public registry\n  text: Used to operate and moderate the public registry.\n- purpose: Answering support requests\n  text: Used to answer you.\n- purpose: Unlocking paid features\n  text: Used to unlock paid features.\nretention:\n- scope: Account data\n  period: up to 12 months afterwards\n  text: Account data is kept while your account is active and for\
  \ up to 12 months afterwards.\n- scope: Access logs\n  period: 60 days\n  text: Access logs are retained for 60 days and then deleted automatically.\n- scope: API usage counters\n  period: 7 days\n  text: API usage counters are pruned after 7 days.\n- scope: Billing records\n  period: null\n  text: Billing records are kept as long as tax law requires.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where that happens we rely on appropriate safeguards, such as European Commission adequacy decisions or\n    Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: Service providers / subprocessors — our hosting, database and authentication providers, and the email provider\n    used for account messages.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@agentnexus.app\n  text: Data is deleted or anonymised once no longer needed.\nrights:\n- right: access\n  text: you may request access to your data\n- right: correction\n  text: correction\
  \ of inaccurate data\n- right: erasure\n  text: erasure\n- right: restriction\n  text: restriction of processing\n- right: portability\n  text: portability\n- right: objection\n  text: you may object to processing based on legitimate interests\n- right: withdraw consent\n  text: withdraw consent where consent was the basis\n- right: complain to supervisory authority\n  text: you also have the right to complain to your data protection supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/agentnexus-app/privacy/agentnexus-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Agent Nexus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Infrastructure
- Registry
- Agents
- Platform
---
