---
api_specs:
- filename: agenthost-eu-openapi-generated.yml
  format: yaml
  label: agenthost API
  slug: agenthost-eu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenthost-eu/openapi/_ae-authored/agenthost-eu-openapi-generated.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: contact
    text: an email address to sign you in, a name for your organization
  - category: identifying
    text: Email address, your name, organization name
  - category: financial
    text: Billing details and invoices
  - category: device
    text: 'Server logs: IP address, timestamps, requested URLs, error detail'
  - category: behavioral
    text: Which pages of this website and the docs were visited, and roughly from where
  - category: communication
    text: Support correspondence
  deletion:
    route: Account closure, then deletion after 30 days
    text: Account, projects, and deployed content — while your account is open, then deleted 30 days after it closes.
  dpa:
    available: true
    text: Under our Data Processing Agreement
    url: null
  purposes:
  - purpose: Create and run account
    text: To create and run your account, and to identify you when you sign in
  - purpose: Provide hosting
    text: To provide the hosting you asked for
  - purpose: Operate and secure service
    text: To operate the service, investigate faults, and prevent abuse
  - purpose: Site understanding
    text: To see which pages are read and which are not, so we know what to write next
  residency:
  - region: EU
    text: Your account, your projects, and everything you deploy are stored on servers in the EU, and they stay there.
  retention:
  - period: minutes
    scope: Sign-in codes
    text: Sign-in codes — minutes. They expire in ten and are deleted within a day.
  - period: 30 days
    scope: Browser sessions
    text: Browser sessions — 30 days, or until you sign out.
  - period: 30 days
    scope: Account, projects, and deployed content
    text: Account, projects, and deployed content — while your account is open, then deleted 30 days after it closes.
  - period: 90 days
    scope: Server logs
    text: Server logs — 90 days.
  - period: five years
    scope: Record of actions on account
    text: The record of what is done on your account — five years.
  - period: seven years
    scope: Accounting records
    text: Accounting records — seven years, as the Swedish Accounting Act (bokföringslagen) requires.
  rights:
  - right: Access
    text: tell you what we hold about you, and give you a copy
  - right: Correction
    text: correct anything inaccurate
  - right: Erasure
    text: delete your data — we will, unless we must keep it (accounting records, for example)
  - right: Restriction or objection
    text: restrict or object to processing we base on legitimate interests
  - right: Portability
    text: hand your data over in a portable, machine-readable form
  - right: Withdraw consent
    text: withdraw consent, where we relied on it, without affecting what came before
  role:
    text: For your account we are the controller — this policy covers that. For personal data inside the applications you deploy, you are the controller and we are only your processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not buy personal data, we do not run advertising, and we do not profile you.
  subprocessors:
    text: Provider What for Where Postmark (ActiveCampaign, Inc.) Sending sign-in codes and account email USA — see section 4 OVH SAS (OVHcloud) Servers, databases, and backups France, EU company Stripe Payments Europe, Limited Card payments, subscriptions, and invoices Ireland
    url: null
  transfers:
  - mechanism: SCC
    text: Both rest on the European Commission's standard contractual clauses, together with a transfer impact assessment
  - mechanism: DPF
    text: and on the EU–US Data Privacy Framework where the provider is certified under it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agenthost
provenance_date: '2026-11-09'
provider_name: agenthost
provider_slug: agenthost-eu
slug: agenthost-eu-privacy-policy
source_date: '2026-11-09'
source_filename: agenthost-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenthost.eu/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agenthost\naid: agenthost-eu\nurl: https://agenthost.eu/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your account we are the controller — this policy covers that. For personal data inside the applications\n    you deploy, you are the controller and we are only your processor\ndata_categories:\n- category: contact\n  text: an email address to sign you in, a name for your organization\n- category: identifying\n  text: Email address, your name, organization name\n- category: financial\n  text: Billing details and invoices\n- category: device\n  text: 'Server logs: IP address, timestamps,\
  \ requested URLs, error detail'\n- category: behavioral\n  text: Which pages of this website and the docs were visited, and roughly from where\n- category: communication\n  text: Support correspondence\npurposes:\n- purpose: Create and run account\n  text: To create and run your account, and to identify you when you sign in\n- purpose: Provide hosting\n  text: To provide the hosting you asked for\n- purpose: Operate and secure service\n  text: To operate the service, investigate faults, and prevent abuse\n- purpose: Site understanding\n  text: To see which pages are read and which are not, so we know what to write next\nretention:\n- scope: Sign-in codes\n  period: minutes\n  text: Sign-in codes — minutes. They expire in ten and are deleted within a day.\n- scope: Browser sessions\n  period: 30 days\n  text: Browser sessions — 30 days, or until you sign out.\n- scope: Account, projects, and deployed content\n  period: 30 days\n  text: Account, projects, and deployed content — while your\
  \ account is open, then deleted 30 days after it closes.\n- scope: Server logs\n  period: 90 days\n  text: Server logs — 90 days.\n- scope: Record of actions on account\n  period: five years\n  text: The record of what is done on your account — five years.\n- scope: Accounting records\n  period: seven years\n  text: Accounting records — seven years, as the Swedish Accounting Act (bokföringslagen) requires.\nresidency:\n- region: EU\n  text: Your account, your projects, and everything you deploy are stored on servers in the EU, and they stay there.\ntransfers:\n- mechanism: SCC\n  text: Both rest on the European Commission's standard contractual clauses, together with a transfer impact assessment\n- mechanism: DPF\n  text: and on the EU–US Data Privacy Framework where the provider is certified under it.\nsubprocessors:\n  url: null\n  text: Provider What for Where Postmark (ActiveCampaign, Inc.) Sending sign-in codes and account email USA — see\n    section 4 OVH SAS (OVHcloud) Servers,\
  \ databases, and backups France, EU company Stripe Payments Europe, Limited\n    Card payments, subscriptions, and invoices Ireland\ndpa:\n  available: true\n  url: null\n  text: Under our Data Processing Agreement\ndeletion:\n  route: Account closure, then deletion after 30 days\n  text: Account, projects, and deployed content — while your account is open, then deleted 30 days after it closes.\nrights:\n- right: Access\n  text: tell you what we hold about you, and give you a copy\n- right: Correction\n  text: correct anything inaccurate\n- right: Erasure\n  text: delete your data — we will, unless we must keep it (accounting records, for example)\n- right: Restriction or objection\n  text: restrict or object to processing we base on legitimate interests\n- right: Portability\n  text: hand your data over in a portable, machine-readable form\n- right: Withdraw consent\n  text: withdraw consent, where we relied on it, without affecting what came before\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not buy personal data, we do not run advertising, and we do not profile you.\n"
source_yaml_url: https://artifacts.apis.io/agenthost-eu/privacy/agenthost-eu-privacy-policy.yml
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
summary_line: 30 quoted statements, read from agenthost's own page on 2026-11-09.
synthetic: false
tags:
- Web Hosting
- Artificial Intelligence
- MCP
- Cloud
- EU
---
