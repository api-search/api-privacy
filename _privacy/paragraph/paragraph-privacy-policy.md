---
api_specs:
- filename: paragraph-analytics-api-openapi.yml
  format: yaml
  label: Paragraph Analytics API
  slug: paragraph-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-analytics-api-openapi.yml
- filename: paragraph-auth-api-openapi.yml
  format: yaml
  label: Paragraph Auth API
  slug: paragraph-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-auth-api-openapi.yml
- filename: paragraph-coins-api-openapi.yml
  format: yaml
  label: Paragraph Coins API
  slug: paragraph-coins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-coins-api-openapi.yml
- filename: paragraph-discover-api-openapi.yml
  format: yaml
  label: Paragraph Discover API
  slug: paragraph-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-discover-api-openapi.yml
- filename: paragraph-emails-api-openapi.yml
  format: yaml
  label: Paragraph Emails API
  slug: paragraph-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-emails-api-openapi.yml
- filename: paragraph-me-api-openapi.yml
  format: yaml
  label: Paragraph Me API
  slug: paragraph-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-me-api-openapi.yml
- filename: paragraph-posts-api-openapi.yml
  format: yaml
  label: Paragraph Posts API
  slug: paragraph-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-posts-api-openapi.yml
- filename: paragraph-publications-api-openapi.yml
  format: yaml
  label: Paragraph Publications API
  slug: paragraph-publications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-publications-api-openapi.yml
- filename: paragraph-subscribers-api-openapi.yml
  format: yaml
  label: Paragraph Subscribers API
  slug: paragraph-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-subscribers-api-openapi.yml
- filename: paragraph-users-api-openapi.yml
  format: yaml
  label: Paragraph Users API
  slug: paragraph-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paragraph/openapi/paragraph-users-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect identifiers and profile information such as your name, email address, account ID, login method, profile image, publication or company name, role, team membership, and settings.
  - category: financial
    text: We collect billing contact details, plan and subscription information, invoices, payment status, transaction identifiers, and limited payment method details, such as card brand and last four digits
  - category: location
    text: approximate location inferred from IP
  - category: device
    text: IP address, browser and device type, operating system, approximate location inferred from IP, language
  - category: communication
    text: Email interaction data may include delivery, bounce, complaint, open, and click events.
  - category: behavioral
    text: pages and features used, referring page, dates and times, session and account identifiers, clicks, resource performance, error and diagnostic data
  deletion:
    route: Delete a workspace or account through available settings; email support@paragraph.com for privacy requests
    text: You can export subscriber data and can delete a workspace or account through available settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and support the Services
    text: provide, personalize, maintain, and support the Services;
  - purpose: Develop or improve features
    text: understand how the Services are used, diagnose errors, evaluate system and model performance, and develop or improve features;
  - purpose: Marketing
    text: send product news or marketing where permitted by law.
  - purpose: AI processing
    text: Paragraph may send relevant prompts, conversations, files, publication context, connected-service data, and other instructions to AI model, search, image, code-execution, or agent infrastructure providers.
  residency:
  - region: United States
    text: Paragraph is based in the United States.
  retention:
  - period: null
    scope: General personal information
    text: We keep personal information only as long as reasonably necessary for the purposes described in this policy.
  - period: null
    scope: Backups
    text: Some information may remain for a limited time in backups or be retained where needed for legal compliance, security, fraud prevention, billing, disputes, or enforcement.
  rights:
  - right: access
    text: you may have the right to request access to, correction of, deletion of, or a portable copy of your personal information
  - right: object or restrict
    text: to object to or restrict certain processing
  - right: withdraw consent
    text: to withdraw consent
  - right: appeal
    text: and to appeal a denied request
  - right: complain
    text: You may also have the right to complain to your local data protection authority.
  role:
    text: Paragraph is the controller or business responsible for personal information used to operate our own accounts, websites, product, analytics, billing, security, and communications.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Paragraph does not sell personal information for money. We also do not share personal information for cross-context behavioral advertising as those terms are defined by California law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use lawful transfer mechanisms and safeguards for international transfers, such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Paragraph
provenance_date: '2026-11-10'
provider_name: Paragraph
provider_slug: paragraph
slug: paragraph-privacy-policy
source_date: '2026-11-10'
source_filename: paragraph-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://paragraph.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Paragraph\naid: paragraph\nurl: https://paragraph.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Paragraph is the controller or business responsible for personal information used to operate our own accounts,\n    websites, product, analytics, billing, security, and communications.\ndata_categories:\n- category: identifying\n  text: We collect identifiers and profile information such as your name, email address, account ID, login method,\n    profile image, publication or company name, role, team membership, and settings.\n- category: financial\n  text: We collect billing contact details,\
  \ plan and subscription information, invoices, payment status, transaction\n    identifiers, and limited payment method details, such as card brand and last four digits\n- category: location\n  text: approximate location inferred from IP\n- category: device\n  text: IP address, browser and device type, operating system, approximate location inferred from IP, language\n- category: communication\n  text: Email interaction data may include delivery, bounce, complaint, open, and click events.\n- category: behavioral\n  text: pages and features used, referring page, dates and times, session and account identifiers, clicks, resource\n    performance, error and diagnostic data\npurposes:\n- purpose: Provide and support the Services\n  text: provide, personalize, maintain, and support the Services;\n- purpose: Develop or improve features\n  text: understand how the Services are used, diagnose errors, evaluate system and model performance, and develop\n    or improve features;\n- purpose: Marketing\n\
  \  text: send product news or marketing where permitted by law.\n- purpose: AI processing\n  text: Paragraph may send relevant prompts, conversations, files, publication context, connected-service data,\n    and other instructions to AI model, search, image, code-execution, or agent infrastructure providers.\nretention:\n- scope: General personal information\n  period: null\n  text: We keep personal information only as long as reasonably necessary for the purposes described in this policy.\n- scope: Backups\n  period: null\n  text: Some information may remain for a limited time in backups or be retained where needed for legal compliance,\n    security, fraud prevention, billing, disputes, or enforcement.\nresidency:\n- region: United States\n  text: Paragraph is based in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we use lawful transfer mechanisms and safeguards for international transfers, such as standard\n    contractual clauses.\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a workspace or account through available settings; email support@paragraph.com for privacy requests\n  text: You can export subscriber data and can delete a workspace or account through available settings.\nrights:\n- right: access\n  text: you may have the right to request access to, correction of, deletion of, or a portable copy of your personal\n    information\n- right: object or restrict\n  text: to object to or restrict certain processing\n- right: withdraw consent\n  text: to withdraw consent\n- right: appeal\n  text: and to appeal a denied request\n- right: complain\n  text: You may also have the right to complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: Paragraph does not sell personal information for money. We also do not share personal information for cross-context\n    behavioral advertising as those terms are defined by California\
  \ law.\n"
source_yaml_url: https://artifacts.apis.io/paragraph/privacy/paragraph-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Paragraph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Publishing
- Newsletters
- Web3
- Content
- Blogging
- Creator Economy
---
