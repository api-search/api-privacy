---
api_specs:
- filename: plausible-customprops-api-openapi.yml
  format: yaml
  label: Plausible CustomProps API
  slug: plausible-customprops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-customprops-api-openapi.yml
- filename: plausible-events-api-openapi.yml
  format: yaml
  label: Plausible Events API
  slug: plausible-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-events-api-openapi.yml
- filename: plausible-goals-api-openapi.yml
  format: yaml
  label: Plausible Goals API
  slug: plausible-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-goals-api-openapi.yml
- filename: plausible-guests-api-openapi.yml
  format: yaml
  label: Plausible Guests API
  slug: plausible-guests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-guests-api-openapi.yml
- filename: plausible-query-api-openapi.yml
  format: yaml
  label: Plausible Query API
  slug: plausible-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-query-api-openapi.yml
- filename: plausible-sites-api-openapi.yml
  format: yaml
  label: Plausible Sites API
  slug: plausible-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-sites-api-openapi.yml
- filename: plausible-teams-api-openapi.yml
  format: yaml
  label: Plausible Teams API
  slug: plausible-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-teams-api-openapi.yml
- filename: plausible-shared-links-api-openapi.yml
  format: yaml
  label: Plausible Shared Links API
  slug: plausible-shared-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plausible/openapi/plausible-shared-links-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: contact
    text: An email address is required to create an account.
  - category: financial
    text: 'Customer account data (you as a customer): This includes your email address, billing details and support communication.'
  - category: device
    text: information from the devices (device type, operating system, country and browser) used during the visit and more
  - category: behavioral
    text: Data collected includes referral sources, top pages, visit duration
  - category: communication
    text: support correspondence. Help Scout stores the emails
  - category: behavioral
    source: https://plausible.io/dpa
    text: Plausible Analytics will collect information about your visitors.
  - category: device
    source: https://plausible.io/dpa
    text: Every HTTP request includes the IP address and User-Agent.
  deletion:
    route: account deletion
    text: You can delete your Plausible Analytics account at any time.
  dpa:
    available: true
    text: For more details, see our Data Processing Agreement .
    url: null
  purposes:
  - purpose: provide the service
    text: 'Contract: to provide the Plausible Analytics service, including account access, billing and essential functionality such as maintaining logged-in sessions'
  - purpose: website statistics
    text: We use Plausible Analytics to collect some anonymous usage data for statistical purposes.
  - purpose: account communications
    text: so we can send you invoices, updates or other essential information
  - purpose: Measuring website usage
    source: https://plausible.io/dpa
    text: Even though the purpose of Plausible Analytics is to measure website usage
  - purpose: Calculating daily unique visitors
    source: https://plausible.io/dpa
    text: This generates a random string used to calculate daily unique visitors.
  residency:
  - region: European Union
    text: This data is processed entirely within the European Union and never leaves the EU.
  - region: Germany
    text: hosted on 100% renewable energy powered servers in Falkenstein, Germany.
  - region: Germany / European Union
    source: https://plausible.io/dpa
    text: Visitor data is processed and stored within the European Union on EU-owned infrastructure.
  retention:
  - period: null
    scope: account data
    text: We retain your information for as long as your account is active and as necessary to provide you with the service.
  - period: null
    scope: account deletion
    text: All your data will be permanently deleted without undue delay upon account deletion.
  - period: 24 hours
    scope: Old salts
    source: https://plausible.io/dpa
    text: Old salts are deleted every 24 hours to prevent linking visitor information across days
  - period: null
    scope: Raw IP and User-Agent
    source: https://plausible.io/dpa
    text: The raw IP address and User-Agent are never stored in logs, databases or on disk.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Object
    text: Object to processing where applicable
  - right: Audit rights
    source: https://plausible.io/dpa
    text: Plausible Analytics allows for and contributes to audits, including inspections, conducted by the customer or an independent auditor mandated by the customer.
  - right: Data subject requests forwarded
    source: https://plausible.io/dpa
    text: Plausible Analytics assists the customer with data protection obligations and forwards data subject requests to the customer.
  role:
    text: For website visitor data collected on behalf of your website, Plausible acts as a data processor. For customer account data (such as account details, billing and support communication), Plausible acts as a data controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: 'We promise we never sell your data: never have, never will.'
  subprocessors:
    text: 'Hetzner (European, Germany): server infrastructure and hosting'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Plausible
provenance_date: '2026-11-10'
provider_name: Plausible
provider_slug: plausible
slug: plausible-privacy-policy
source_date: '2026-11-10'
source_filename: plausible-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://plausible.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Plausible\naid: plausible\nurl: https://plausible.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://plausible.io/dpa\n  - https://plausible.io/privacy\nrole:\n  value: both\n  text: For website visitor data collected on behalf of your website, Plausible acts as a data processor. For customer\n    account data (such as account details, billing and support communication), Plausible acts as a data controller.\ndata_categories:\n- category: contact\n  text: An email address is required to create an account.\n- category: financial\n  text: 'Customer account data (you as a customer): This includes your\
  \ email address, billing details and support\n    communication.'\n- category: device\n  text: information from the devices (device type, operating system, country and browser) used during the visit\n    and more\n- category: behavioral\n  text: Data collected includes referral sources, top pages, visit duration\n- category: communication\n  text: support correspondence. Help Scout stores the emails\n- category: behavioral\n  text: Plausible Analytics will collect information about your visitors.\n  source: https://plausible.io/dpa\n- category: device\n  text: Every HTTP request includes the IP address and User-Agent.\n  source: https://plausible.io/dpa\npurposes:\n- purpose: provide the service\n  text: 'Contract: to provide the Plausible Analytics service, including account access, billing and essential functionality\n    such as maintaining logged-in sessions'\n- purpose: website statistics\n  text: We use Plausible Analytics to collect some anonymous usage data for statistical purposes.\n\
  - purpose: account communications\n  text: so we can send you invoices, updates or other essential information\n- purpose: Measuring website usage\n  text: Even though the purpose of Plausible Analytics is to measure website usage\n  source: https://plausible.io/dpa\n- purpose: Calculating daily unique visitors\n  text: This generates a random string used to calculate daily unique visitors.\n  source: https://plausible.io/dpa\nretention:\n- scope: account data\n  period: null\n  text: We retain your information for as long as your account is active and as necessary to provide you with the\n    service.\n- scope: account deletion\n  period: null\n  text: All your data will be permanently deleted without undue delay upon account deletion.\n- scope: Old salts\n  period: 24 hours\n  text: Old salts are deleted every 24 hours to prevent linking visitor information across days\n  source: https://plausible.io/dpa\n- scope: Raw IP and User-Agent\n  period: null\n  text: The raw IP address and\
  \ User-Agent are never stored in logs, databases or on disk.\n  source: https://plausible.io/dpa\nresidency:\n- region: European Union\n  text: This data is processed entirely within the European Union and never leaves the EU.\n- region: Germany\n  text: hosted on 100% renewable energy powered servers in Falkenstein, Germany.\n- region: Germany / European Union\n  text: Visitor data is processed and stored within the European Union on EU-owned infrastructure.\n  source: https://plausible.io/dpa\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission.\nsubprocessors:\n  url: null\n  text: 'Hetzner (European, Germany): server infrastructure and hosting'\ndpa:\n  available: true\n  url: null\n  text: For more details, see our Data Processing Agreement .\ndeletion:\n  route: account deletion\n  text: You can delete your Plausible Analytics account at any time.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text:\
  \ Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Object\n  text: Object to processing where applicable\n- right: Audit rights\n  text: Plausible Analytics allows for and contributes to audits, including inspections, conducted by the customer\n    or an independent auditor mandated by the customer.\n  source: https://plausible.io/dpa\n- right: Data subject requests forwarded\n  text: Plausible Analytics assists the customer with data protection obligations and forwards data subject requests\n    to the customer.\n  source: https://plausible.io/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: 'We promise we never sell your data: never have, never will.'\n"
source_yaml_url: https://artifacts.apis.io/plausible/privacy/plausible-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Plausible's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Cookie-Free
- Event Tracking
- GDPR
- Goal Conversions
- Open Source
- Privacy
- Self-Hosted
- Site Management
- Web Analytics
---
