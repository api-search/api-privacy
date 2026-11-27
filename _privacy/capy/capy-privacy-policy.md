---
api_specs:
- filename: capy-automations-api-openapi.yml
  format: yaml
  label: Capy Automations API
  slug: capy-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-automations-api-openapi.yml
- filename: capy-projects-api-openapi.yml
  format: yaml
  label: Capy Projects API
  slug: capy-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-projects-api-openapi.yml
- filename: capy-tasks-api-openapi.yml
  format: yaml
  label: Capy Tasks API
  slug: capy-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-tasks-api-openapi.yml
- filename: capy-threads-api-openapi.yml
  format: yaml
  label: Capy Threads API
  slug: capy-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-threads-api-openapi.yml
- filename: capy-usage-api-openapi.yml
  format: yaml
  label: Capy Usage API
  slug: capy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-usage-api-openapi.yml
- filename: capy-captains-api-openapi.yml
  format: yaml
  label: Capy Captains API
  slug: capy-captains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-captains-api-openapi.yml
- filename: capy-folders-api-openapi.yml
  format: yaml
  label: Capy Folders API
  slug: capy-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-folders-api-openapi.yml
- filename: capy-messages-api-openapi.yml
  format: yaml
  label: Capy Messages API
  slug: capy-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-messages-api-openapi.yml
- filename: capy-reviewfilters-api-openapi.yml
  format: yaml
  label: Capy Review Filters API
  slug: capy-reviewfilters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviewfilters-api-openapi.yml
- filename: capy-reviewrules-api-openapi.yml
  format: yaml
  label: Capy Review Rules API
  slug: capy-reviewrules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviewrules-api-openapi.yml
- filename: capy-reviews-api-openapi.yml
  format: yaml
  label: Capy Reviews API
  slug: capy-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-reviews-api-openapi.yml
- filename: capy-streams-api-openapi.yml
  format: yaml
  label: Capy Streams API
  slug: capy-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-streams-api-openapi.yml
- filename: capy-subagents-api-openapi.yml
  format: yaml
  label: Capy Subagents API
  slug: capy-subagents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-subagents-api-openapi.yml
- filename: capy-users-api-openapi.yml
  format: yaml
  label: Capy Users API
  slug: capy-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capy/openapi/capy-users-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and identity information: name, email address, avatar, organization, role, login identifiers, authentication state, workspace membership, preferences, and account settings.'
  - category: financial
    text: Full payment-card numbers are processed by our payment providers, not stored directly by Capy.
  - category: location
    text: approximate location inferred from IP address
  - category: behavioral
    text: 'Usage data: information about how you use the Services, such as pages viewed, features used, dates and times of access, models and compute used, errors, and performance.'
  - category: device
    text: 'Device and browser information: IP address, browser type, device type, operating system, language, time zone, referring page, and approximate location inferred from IP address.'
  - category: communication
    text: 'Communications: emails, support requests, sales requests, meeting information, feedback, survey responses, community messages, and other communications with us.'
  - category: professional
    text: 'Recruiting information: information submitted through careers pages or referral forms, such as name, email, resume, application materials, referral notes, job preferences, and interview communications.'
  deletion:
    route: Send a privacy request to support@capy.ai with subject line "Privacy Request"
    text: To make a privacy request, email support@capy.ai from the email address associated with your account and include "Privacy Request" in the subject line.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, maintain, secure and improve the Services
    text: provide, operate, maintain, secure, monitor, and improve the Services
  - purpose: Run agents and generate Output
    text: execute your instructions, run agents, generate Output, create branches and pull requests, analyze diffs, review code, and synchronize context from connected services
  - purpose: Fraud and abuse prevention
    text: detect, prevent, and investigate fraud, abuse, policy violations, security incidents, and illegal activity
  - purpose: Marketing and sales
    text: send product updates, marketing communications, events, and similar communications, where permitted by law
  - purpose: Process job applications
    text: process job applications and referrals
  residency:
  - region: United States
    text: We are based in the United States, and we and our service providers may process personal information in the United States and other countries.
  retention:
  - period: 400 days
    scope: Hashed device characteristics
    text: the hashed device characteristics we use to recognize a browser are kept for up to 400 days from the visit they came from
  - period: 180 days
    scope: Browser recognition index
    text: the index that matches a returning browser expires after 180 days without a visit
  - period: 30 days
    scope: Deleted data restoration
    text: On request, we permanently delete it within 30 days.
  - period: null
    scope: Account, billing and tax records
    text: account, billing, tax, and transaction records may be retained for legal and accounting purposes
  - period: null
    scope: Customer Content
    text: Customer Content may be deleted or returned after termination according to the applicable agreement and our standard deletion processes
  rights:
  - right: access
    text: access personal information we hold about you
  - right: correct
    text: correct inaccurate personal information
  - right: delete
    text: delete personal information
  - right: portability
    text: receive a portable copy of personal information
  - right: object or restrict
    text: object to or restrict certain processing
  - right: withdraw consent
    text: withdraw consent where processing is based on consent
  - right: opt out of marketing
    text: opt out of marketing communications
  - right: appeal
    text: appeal a denied privacy request
  - right: complain
    text: lodge a complaint with a privacy regulator
  role:
    text: This Policy applies when we act as a controller of personal information, such as for account administration, marketing, website analytics, billing, security, support, and recruiting.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information. We do not share personal information for cross-context behavioral advertising.
  subprocessors:
    text: See Subprocessors .
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on legally recognized transfer mechanisms, which may include Standard Contractual Clauses, the UK International Data Transfer Addendum, adequacy decisions, data processing agreements, or other lawful mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Capy
provenance_date: '2026-11-09'
provider_name: Capy
provider_slug: capy
slug: capy-privacy-policy
source_date: '2026-11-09'
source_filename: capy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://capy.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Capy\naid: capy\nurl: https://capy.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This Policy applies when we act as a controller of personal information, such as for account administration,\n    marketing, website analytics, billing, security, support, and recruiting.\ndata_categories:\n- category: identifying\n  text: 'Account and identity information: name, email address, avatar, organization, role, login identifiers, authentication\n    state, workspace membership, preferences, and account settings.'\n- category: financial\n  text: Full payment-card numbers are processed by\
  \ our payment providers, not stored directly by Capy.\n- category: location\n  text: approximate location inferred from IP address\n- category: behavioral\n  text: 'Usage data: information about how you use the Services, such as pages viewed, features used, dates and\n    times of access, models and compute used, errors, and performance.'\n- category: device\n  text: 'Device and browser information: IP address, browser type, device type, operating system, language, time\n    zone, referring page, and approximate location inferred from IP address.'\n- category: communication\n  text: 'Communications: emails, support requests, sales requests, meeting information, feedback, survey responses,\n    community messages, and other communications with us.'\n- category: professional\n  text: 'Recruiting information: information submitted through careers pages or referral forms, such as name, email,\n    resume, application materials, referral notes, job preferences, and interview communications.'\n\
  purposes:\n- purpose: Provide, operate, maintain, secure and improve the Services\n  text: provide, operate, maintain, secure, monitor, and improve the Services\n- purpose: Run agents and generate Output\n  text: execute your instructions, run agents, generate Output, create branches and pull requests, analyze diffs,\n    review code, and synchronize context from connected services\n- purpose: Fraud and abuse prevention\n  text: detect, prevent, and investigate fraud, abuse, policy violations, security incidents, and illegal activity\n- purpose: Marketing and sales\n  text: send product updates, marketing communications, events, and similar communications, where permitted by law\n- purpose: Process job applications\n  text: process job applications and referrals\nretention:\n- scope: Hashed device characteristics\n  period: 400 days\n  text: the hashed device characteristics we use to recognize a browser are kept for up to 400 days from the visit\n    they came from\n- scope: Browser recognition\
  \ index\n  period: 180 days\n  text: the index that matches a returning browser expires after 180 days without a visit\n- scope: Deleted data restoration\n  period: 30 days\n  text: On request, we permanently delete it within 30 days.\n- scope: Account, billing and tax records\n  period: null\n  text: account, billing, tax, and transaction records may be retained for legal and accounting purposes\n- scope: Customer Content\n  period: null\n  text: Customer Content may be deleted or returned after termination according to the applicable agreement and\n    our standard deletion processes\nresidency:\n- region: United States\n  text: We are based in the United States, and we and our service providers may process personal information in\n    the United States and other countries.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on legally recognized transfer mechanisms, which may include Standard Contractual\n    Clauses, the UK International Data Transfer Addendum, adequacy\
  \ decisions, data processing agreements, or other\n    lawful mechanisms.\nsubprocessors:\n  url: null\n  text: See Subprocessors .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Send a privacy request to support@capy.ai with subject line \"Privacy Request\"\n  text: To make a privacy request, email support@capy.ai from the email address associated with your account and\n    include \"Privacy Request\" in the subject line.\nrights:\n- right: access\n  text: access personal information we hold about you\n- right: correct\n  text: correct inaccurate personal information\n- right: delete\n  text: delete personal information\n- right: portability\n  text: receive a portable copy of personal information\n- right: object or restrict\n  text: object to or restrict certain processing\n- right: withdraw consent\n  text: withdraw consent where processing is based on consent\n- right: opt out of marketing\n  text: opt out of marketing communications\n- right: appeal\n  text:\
  \ appeal a denied privacy request\n- right: complain\n  text: lodge a complaint with a privacy regulator\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information. We do not share personal information for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/capy/privacy/capy-privacy-policy.yml
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
summary_line: 32 quoted statements, read from Capy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Coding Agents
- Software Engineering
- Developer Tools
- Automation
- Code Review
- DevOps
---
