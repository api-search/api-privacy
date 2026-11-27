---
api_specs:
- filename: mcpbundles-local-runtime-api-openapi.yml
  format: yaml
  label: MCPBundles Local Runtime API
  slug: mcpbundles-local-runtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpbundles/openapi/mcpbundles-local-runtime-api-openapi.yml
- filename: mcpbundles-tunnel-api-openapi.yml
  format: yaml
  label: MCPBundles Tunnel API
  slug: mcpbundles-tunnel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpbundles/openapi/mcpbundles-tunnel-api-openapi.yml
- filename: mcpbundles-graph-ql-api-openapi.yml
  format: yaml
  label: MCPBundles Graph QL API
  slug: mcpbundles-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpbundles/openapi/mcpbundles-graph-ql-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Full name (optional) Password hash (never stored in plaintext)
  - category: contact
    text: Contact-related metadata your connected service returns (for example customer email, phone number, sender name)
  - category: financial
    text: Stripe customer ID Subscription status and plan details Payment history (processed and stored by Stripe)
  - category: device
    text: Browser version and type Operating system Device information
  - category: location
    text: IP address
  - category: communication
    text: Short text previews where needed for search (for example the first ~200 characters of a support message subject or body preview)
  deletion:
    route: Delete account or credentials in dashboard, or email privacy@mcpbundles.com for crash report deletion
    text: When you delete your account, we will delete or anonymize your personal information within 30 days, except where we are required to retain it for legal or security purposes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide and improve our Services
  - purpose: Process subscription and billing
    text: Process your subscription and billing
  - purpose: Security and abuse prevention
    text: Maintain and enhance security
  - purpose: Analytics
    text: Perform analytics to improve our platform
  - purpose: Customer support
    text: Provide customer support
  residency:
  - region: European Union (AWS London, eu-west-2)
    text: stored in our EU production database (AWS London, eu-west-2)
  - region: European Union (Frankfurt)
    text: Crash reports are processed in the European Union (Frankfurt).
  retention:
  - period: within 30 days
    scope: Account data after account deletion
    text: When you delete your account, we will delete or anonymize your personal information within 30 days, except where we are required to retain it for legal or security purposes.
  - period: about 30 days
    scope: Connection data cache summary metadata
    text: Cached rows roll off on a per-provider schedule (typically about 30 days for summary metadata; shorter when optional heavy payloads are stored).
  - period: 90 days
    scope: Crash reports
    text: Reports are retained for 90 days and then automatically deleted.
  rights:
  - right: Access
    text: 'Right to Access: Request copies of your personal data'
  - right: Erasure
    text: 'Right to Erasure: Request deletion of your personal data'
  - right: Rectification
    text: 'Right to Rectification: Request correction of inaccurate information'
  - right: Portability
    text: 'Right to Data Portability: Request transfer of your data to another organization or directly to you'
  - right: Object
    text: 'Right to Object: Object to our processing of your personal data'
  - right: Know (CCPA)
    text: 'Right to Know: Request disclosure of the categories and specific pieces of personal data we have collected about you'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MCPBundles
provenance_date: '2026-11-10'
provider_name: MCPBundles
provider_slug: mcpbundles
slug: mcpbundles-privacy-policy
source_date: '2026-11-10'
source_filename: mcpbundles-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mcpbundles.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MCPBundles\naid: mcpbundles\nurl: https://www.mcpbundles.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address Full name (optional) Password hash (never stored in plaintext)\n- category: contact\n  text: Contact-related metadata your connected service returns (for example customer email, phone number, sender\n    name)\n- category: financial\n  text: Stripe customer ID Subscription status and plan details Payment history (processed and stored by Stripe)\n- category: device\n  text: Browser version and type Operating\
  \ system Device information\n- category: location\n  text: IP address\n- category: communication\n  text: Short text previews where needed for search (for example the first ~200 characters of a support message\n    subject or body preview)\npurposes:\n- purpose: Provide and improve services\n  text: Provide and improve our Services\n- purpose: Process subscription and billing\n  text: Process your subscription and billing\n- purpose: Security and abuse prevention\n  text: Maintain and enhance security\n- purpose: Analytics\n  text: Perform analytics to improve our platform\n- purpose: Customer support\n  text: Provide customer support\nretention:\n- scope: Account data after account deletion\n  period: within 30 days\n  text: When you delete your account, we will delete or anonymize your personal information within 30 days, except\n    where we are required to retain it for legal or security purposes.\n- scope: Connection data cache summary metadata\n  period: about 30 days\n  text: Cached\
  \ rows roll off on a per-provider schedule (typically about 30 days for summary metadata; shorter when\n    optional heavy payloads are stored).\n- scope: Crash reports\n  period: 90 days\n  text: Reports are retained for 90 days and then automatically deleted.\nresidency:\n- region: European Union (AWS London, eu-west-2)\n  text: stored in our EU production database (AWS London, eu-west-2)\n- region: European Union (Frankfurt)\n  text: Crash reports are processed in the European Union (Frankfurt).\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account or credentials in dashboard, or email privacy@mcpbundles.com for crash report deletion\n  text: When you delete your account, we will delete or anonymize your personal information within 30 days, except\n    where we are required to retain it for legal or security\
  \ purposes.\nrights:\n- right: Access\n  text: 'Right to Access: Request copies of your personal data'\n- right: Erasure\n  text: 'Right to Erasure: Request deletion of your personal data'\n- right: Rectification\n  text: 'Right to Rectification: Request correction of inaccurate information'\n- right: Portability\n  text: 'Right to Data Portability: Request transfer of your data to another organization or directly to you'\n- right: Object\n  text: 'Right to Object: Object to our processing of your personal data'\n- right: Know (CCPA)\n  text: 'Right to Know: Request disclosure of the categories and specific pieces of personal data we have collected\n    about you'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/mcpbundles/privacy/mcpbundles-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from MCPBundles's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Directory
- ManagedCloudPlatforms
- Tools
- Integration
---
