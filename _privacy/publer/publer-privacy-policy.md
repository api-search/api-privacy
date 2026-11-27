---
api_specs:
- filename: publer-accounts-api-openapi.yml
  format: yaml
  label: Publer Accounts API
  slug: publer-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-accounts-api-openapi.yml
- filename: publer-analytics-api-openapi.yml
  format: yaml
  label: Publer Analytics API
  slug: publer-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-analytics-api-openapi.yml
- filename: publer-competitors-api-openapi.yml
  format: yaml
  label: Publer Competitors API
  slug: publer-competitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-competitors-api-openapi.yml
- filename: publer-jobs-api-openapi.yml
  format: yaml
  label: Publer Jobs API
  slug: publer-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-jobs-api-openapi.yml
- filename: publer-media-api-openapi.yml
  format: yaml
  label: Publer Media API
  slug: publer-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-media-api-openapi.yml
- filename: publer-posts-api-openapi.yml
  format: yaml
  label: Publer Posts API
  slug: publer-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-posts-api-openapi.yml
- filename: publer-users-api-openapi.yml
  format: yaml
  label: Publer Users API
  slug: publer-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-users-api-openapi.yml
- filename: publer-workspaces-api-openapi.yml
  format: yaml
  label: Publer Workspaces API
  slug: publer-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publer/openapi/publer-workspaces-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name (encrypted)
  - category: contact
    text: Email address (encrypted)
  - category: identifying
    text: IP address (encrypted)
  - category: device
    text: browser type, device details, pages visited, and how you interact with the Site
  - category: financial
    text: payment transaction records (processed by Paddle and PayPro Global)
  - category: location
    text: Time zone (precise location is not collected)
  deletion:
    route: Delete account in settings or contact support
    text: You may also delete your account directly by following these instructions.
  dpa:
    available: true
    text: If you require a Data Processing Agreement for GDPR compliance, you may obtain one here.
    url: null
  purposes:
  - purpose: Providing the Service
    text: To operate Publer, publish your content to connected social networks, and manage your account.
  - purpose: Communication
    text: To send you service-related communications, respond to inquiries, and provide customer support.
  - purpose: Marketing
    text: To inform you about Publer and other Kalemi Code products and services, including Linkie and Kibo.
  - purpose: Improvement and Analytics
    text: To analyze usage patterns, improve our Site and Service, and develop new features.
  - purpose: Legal Compliance
    text: To comply with applicable laws, regulations, and legal processes.
  residency:
  - region: Germany
    text: Publer is operated from servers located in Frankfurt, Germany.
  retention:
  - period: 7 days
    scope: Deleted account data
    text: When you delete your account, we retain your data for 7 days to allow for recovery.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal information we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete information.'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal information, subject to legal exceptions.'
  - right: Restriction
    text: 'Restriction: Request that we restrict processing of your information in certain circumstances.'
  - right: Portability
    text: 'Portability: Request your information in a structured, commonly used, machine-readable format.'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests or for direct marketing purposes.'
  - right: Withdrawal of Consent
    text: 'Withdrawal of Consent: Where processing is based on consent, withdraw your consent at any time.'
  role:
    text: Kalemi Code is the parent company and data controller for Publer, as well as our other products, including Linkie and Kibo.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Kalemi Code does not "sell" personal information in exchange for monetary compensation. However, under the CCPA/CPRA, sharing personal information for cross-context behavioral advertising may be considered a "sale" or "share."
  subprocessors:
    text: For a complete list of our sub-processors, please visit our Sub-processors List.
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Publer
provenance_date: '2026-11-10'
provider_name: Publer
provider_slug: publer
slug: publer-privacy-policy
source_date: '2026-11-10'
source_filename: publer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://publer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Publer\naid: publer\nurl: https://publer.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Kalemi Code is the parent company and data controller for Publer, as well as our other products, including\n    Linkie and Kibo.\ndata_categories:\n- category: identifying\n  text: Full name (encrypted)\n- category: contact\n  text: Email address (encrypted)\n- category: identifying\n  text: IP address (encrypted)\n- category: device\n  text: browser type, device details, pages visited, and how you interact with the Site\n- category: financial\n  text: payment transaction records (processed\
  \ by Paddle and PayPro Global)\n- category: location\n  text: Time zone (precise location is not collected)\npurposes:\n- purpose: Providing the Service\n  text: To operate Publer, publish your content to connected social networks, and manage your account.\n- purpose: Communication\n  text: To send you service-related communications, respond to inquiries, and provide customer support.\n- purpose: Marketing\n  text: To inform you about Publer and other Kalemi Code products and services, including Linkie and Kibo.\n- purpose: Improvement and Analytics\n  text: To analyze usage patterns, improve our Site and Service, and develop new features.\n- purpose: Legal Compliance\n  text: To comply with applicable laws, regulations, and legal processes.\nretention:\n- scope: Deleted account data\n  period: 7 days\n  text: When you delete your account, we retain your data for 7 days to allow for recovery.\nresidency:\n- region: Germany\n  text: Publer is operated from servers located in Frankfurt,\
  \ Germany.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses where applicable\nsubprocessors:\n  url: null\n  text: For a complete list of our sub-processors, please visit our Sub-processors List.\ndpa:\n  available: true\n  url: null\n  text: If you require a Data Processing Agreement for GDPR compliance, you may obtain one here.\ndeletion:\n  route: Delete account in settings or contact support\n  text: You may also delete your account directly by following these instructions.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal information we hold about you.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete information.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal information, subject to legal exceptions.'\n- right: Restriction\n  text: 'Restriction: Request that we restrict processing of your information in certain circumstances.'\n- right: Portability\n  text: 'Portability:\
  \ Request your information in a structured, commonly used, machine-readable format.'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests or for direct marketing purposes.'\n- right: Withdrawal of Consent\n  text: 'Withdrawal of Consent: Where processing is based on consent, withdraw your consent at any time.'\nsale_or_sharing:\n  stance: conditional\n  text: Kalemi Code does not \"sell\" personal information in exchange for monetary compensation. However, under the\n    CCPA/CPRA, sharing personal information for cross-context behavioral advertising may be considered a \"sale\"\n    or \"share.\"\n"
source_yaml_url: https://artifacts.apis.io/publer/privacy/publer-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Publer's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Scheduling
- Publishing
- Content Management
- Marketing
- Social Media Management
- Analytics
- Agents
- MCP
- Automation
---
