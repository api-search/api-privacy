---
api_specs:
- filename: agentcat-com-openapi-generated.yml
  format: yaml
  label: AgentCat API
  slug: agentcat-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcat-com/openapi/_ae-authored/agentcat-com-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect your IP address, browser and device information, the pages you visit, and identifiers collected through cookies and similar technologies
  - category: contact
    text: We collect your email address (used for authentication), your name and avatar if you choose to provide them
  - category: financial
    text: billing information (payments are processed by Stripe; we do not store card numbers)
  - category: behavioral
    text: information about how you use it, including session replays
  deletion:
    route: Email privacy@agentcat.com
    text: Customers can request deletion of account information by emailing privacy@agentcat.com
  dpa:
    available: true
    text: Terms of Service and Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide the service
    text: 'Provide the service: authenticate you with one-time email codes and, for our MCP endpoint, OAuth; operate your dashboard; meter usage; and bill you through Stripe.'
  - purpose: Advertising measurement
    text: to measure and improve our advertising
  - purpose: Secure and improve the service
    text: 'Secure and improve the service: monitoring for abuse, debugging, and producing de-identified, aggregated statistics.'
  residency:
  - region: United States
    text: AgentCat is hosted on Amazon Web Services in the United States, where Customer Data and End User Data are stored
  retention:
  - period: null
    scope: Customer account information
    text: customer account information is retained while your account is active
  - period: 30 days
    scope: Deleted project data
    text: the data remains available for export for 30 days and is then irreversibly deleted
  rights:
  - right: Access
    text: the right to access a copy of it, correct it, delete it, receive it in a portable format
  - right: Object or restrict
    text: object to or restrict certain processing, and withdraw consent you have given
  role:
    text: we process it as a service provider on behalf of our customers
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information in exchange for money, and we do not sell or share customer account information or End User Data.
  subprocessors:
    text: The providers that process End User Data on our customers' behalf are listed, with change notifications available, at trust.agentcat.com
    url: https://trust.agentcat.com
  transfers:
  - mechanism: SCC
    text: we transfer it under the European Commission's Standard Contractual Clauses, together with the UK Addendum and Swiss adaptations where they apply
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentCat
provenance_date: '2026-11-09'
provider_name: AgentCat
provider_slug: agentcat-com
slug: agentcat-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentcat-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentcat.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentCat\naid: agentcat-com\nurl: https://agentcat.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we process it as a service provider on behalf of our customers\ndata_categories:\n- category: identifying\n  text: We collect your IP address, browser and device information, the pages you visit, and identifiers collected\n    through cookies and similar technologies\n- category: contact\n  text: We collect your email address (used for authentication), your name and avatar if you choose to provide them\n- category: financial\n  text: billing information (payments are processed by Stripe;\
  \ we do not store card numbers)\n- category: behavioral\n  text: information about how you use it, including session replays\npurposes:\n- purpose: Provide the service\n  text: 'Provide the service: authenticate you with one-time email codes and, for our MCP endpoint, OAuth; operate\n    your dashboard; meter usage; and bill you through Stripe.'\n- purpose: Advertising measurement\n  text: to measure and improve our advertising\n- purpose: Secure and improve the service\n  text: 'Secure and improve the service: monitoring for abuse, debugging, and producing de-identified, aggregated\n    statistics.'\nretention:\n- scope: Customer account information\n  period: null\n  text: customer account information is retained while your account is active\n- scope: Deleted project data\n  period: 30 days\n  text: the data remains available for export for 30 days and is then irreversibly deleted\nresidency:\n- region: United States\n  text: AgentCat is hosted on Amazon Web Services in the United States,\
  \ where Customer Data and End User Data are\n    stored\ntransfers:\n- mechanism: SCC\n  text: we transfer it under the European Commission's Standard Contractual Clauses, together with the UK Addendum\n    and Swiss adaptations where they apply\nsubprocessors:\n  url: https://trust.agentcat.com\n  text: The providers that process End User Data on our customers' behalf are listed, with change notifications\n    available, at trust.agentcat.com\ndpa:\n  available: true\n  url: null\n  text: Terms of Service and Data Processing Addendum\ndeletion:\n  route: Email privacy@agentcat.com\n  text: Customers can request deletion of account information by emailing privacy@agentcat.com\nrights:\n- right: Access\n  text: the right to access a copy of it, correct it, delete it, receive it in a portable format\n- right: Object or restrict\n  text: object to or restrict certain processing, and withdraw consent you have given\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information\
  \ in exchange for money, and we do not sell or share customer account\n    information or End User Data.\n"
source_yaml_url: https://artifacts.apis.io/agentcat-com/privacy/agentcat-com-privacy-policy.yml
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
summary_line: 18 quoted statements, read from AgentCat's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- Observability
- Agent Experience
- Company
---
