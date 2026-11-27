---
api_specs:
- filename: pipeboard-co-openapi-generated.yml
  format: yaml
  label: pipeboard-co API
  slug: pipeboard-co-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipeboard-co/openapi/_ae-authored/pipeboard-co-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Pipeboard account: your name and email address, and (where you sign in with email and password) a securely hashed password.'
  - category: identifying
    text: 'Connection identity: when you connect a platform, we store the identifiers that platform returns so we can label the connection and route requests'
  - category: communication
    text: 'Comments on your posts and ads: where you ask us to, we read the comments left on your Facebook Page posts, Instagram posts, and the posts underlying your ads'
  - category: other
    text: 'Lead form data: LinkedIn Ads — if you grant the LinkedIn lead-generation permission and ask us to, we retrieve the responses submitted through your lead gen forms.'
  - category: other
    text: 'Usage Metadata: We collect data such as timestamps, API calls made, account identifiers, or error logs for operational and debugging purposes.'
  deletion:
    route: Deleting your account through our dashboard
    text: For comprehensive information on how to delete your account and data, please visit our User Data Protection page.
  dpa:
    available: true
    text: Data Processing Agreement (DPA), available at pipeboard.co/dpa
    url: pipeboard.co/dpa
  purposes:
  - purpose: Authenticate users
    text: To authenticate you via Facebook Login, Google OAuth, Pinterest OAuth, TikTok OAuth, Snap OAuth, or Shopify OAuth.
  - purpose: Connect AI assistant to ad platforms
    text: To connect your chosen AI assistant to your ad platforms so it can analyze, suggest, or — where you instruct — carry out ad operations on your data
  - purpose: Improve system performance
    text: To improve our system performance and reliability.
  residency:
  - region: United States
    text: transferred to and processed in the United States and other countries where our sub-processors operate
  - region: European Union (France)
    text: Crisp IM SAS Customer support messaging European Union (France)
  retention:
  - period: 30 days
    scope: Account data
    text: deleted within 30 days after account closure or a verified deletion request
  - period: minutes to a few hours
    scope: Connected-platform data
    text: cached briefly (minutes to a few hours) for performance
  - period: 90 days
    scope: Application and request logs
    text: Retained for up to 90 days, then deleted automatically.
  - period: null
    scope: Billing records
    text: Retained as long as required by applicable tax and accounting law
  rights:
  - right: Access
    text: Access to your data — in a simplified format immediately, or a complete report within 15 days.
  - right: Correction
    text: Correction of incomplete, inaccurate, or outdated data.
  - right: Deletion
    text: Deletion of data we process on the basis of your consent.
  - right: Portability
    text: Portability of your data to another provider, subject to our trade secrets.
  - right: Revoke consent
    text: Revocation of your consent at any time (see below).
  - right: Review automated decisions
    text: Review of automated decisions that affect your interests, including the criteria and procedures used (see below) — art. 20.
  role:
    text: We act as operator ( operadora ) on your instruction; the legal basis is yours to determine as controller of that data
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Your data is never sold, shared with third parties for marketing purposes, or used beyond the described scope.
  subprocessors:
    text: Vercel Inc. Application hosting and global CDN United States (global edge)
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses approved by the ANPD (Resolução CD/ANPD nº 19/2024)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pipeboard-co
provenance_date: '2026-11-10'
provider_name: pipeboard-co
provider_slug: pipeboard-co
slug: pipeboard-co-privacy-policy
source_date: '2026-11-10'
source_filename: pipeboard-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pipeboard.co/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pipeboard-co\naid: pipeboard-co\nurl: https://pipeboard.co/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as operator ( operadora ) on your instruction; the legal basis is yours to determine as controller\n    of that data\ndata_categories:\n- category: contact\n  text: 'Pipeboard account: your name and email address, and (where you sign in with email and password) a securely\n    hashed password.'\n- category: identifying\n  text: 'Connection identity: when you connect a platform, we store the identifiers that platform returns so we\n    can label the connection and route\
  \ requests'\n- category: communication\n  text: 'Comments on your posts and ads: where you ask us to, we read the comments left on your Facebook Page posts,\n    Instagram posts, and the posts underlying your ads'\n- category: other\n  text: 'Lead form data: LinkedIn Ads — if you grant the LinkedIn lead-generation permission and ask us to, we retrieve\n    the responses submitted through your lead gen forms.'\n- category: other\n  text: 'Usage Metadata: We collect data such as timestamps, API calls made, account identifiers, or error logs\n    for operational and debugging purposes.'\npurposes:\n- purpose: Authenticate users\n  text: To authenticate you via Facebook Login, Google OAuth, Pinterest OAuth, TikTok OAuth, Snap OAuth, or Shopify\n    OAuth.\n- purpose: Connect AI assistant to ad platforms\n  text: To connect your chosen AI assistant to your ad platforms so it can analyze, suggest, or — where you instruct\n    — carry out ad operations on your data\n- purpose: Improve system\
  \ performance\n  text: To improve our system performance and reliability.\nretention:\n- scope: Account data\n  period: 30 days\n  text: deleted within 30 days after account closure or a verified deletion request\n- scope: Connected-platform data\n  period: minutes to a few hours\n  text: cached briefly (minutes to a few hours) for performance\n- scope: Application and request logs\n  period: 90 days\n  text: Retained for up to 90 days, then deleted automatically.\n- scope: Billing records\n  period: null\n  text: Retained as long as required by applicable tax and accounting law\nresidency:\n- region: United States\n  text: transferred to and processed in the United States and other countries where our sub-processors operate\n- region: European Union (France)\n  text: Crisp IM SAS Customer support messaging European Union (France)\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses approved by the ANPD (Resolução CD/ANPD nº 19/2024)\nsubprocessors:\n  url: null\n  text:\
  \ Vercel Inc. Application hosting and global CDN United States (global edge)\ndpa:\n  available: true\n  url: pipeboard.co/dpa\n  text: Data Processing Agreement (DPA), available at pipeboard.co/dpa\ndeletion:\n  route: Deleting your account through our dashboard\n  text: For comprehensive information on how to delete your account and data, please visit our User Data Protection\n    page.\nrights:\n- right: Access\n  text: Access to your data — in a simplified format immediately, or a complete report within 15 days.\n- right: Correction\n  text: Correction of incomplete, inaccurate, or outdated data.\n- right: Deletion\n  text: Deletion of data we process on the basis of your consent.\n- right: Portability\n  text: Portability of your data to another provider, subject to our trade secrets.\n- right: Revoke consent\n  text: Revocation of your consent at any time (see below).\n- right: Review automated decisions\n  text: Review of automated decisions that affect your interests, including\
  \ the criteria and procedures used (see\n    below) — art. 20.\nsale_or_sharing:\n  stance: prohibited\n  text: Your data is never sold, shared with third parties for marketing purposes, or used beyond the described\n    scope.\n"
source_yaml_url: https://artifacts.apis.io/pipeboard-co/privacy/pipeboard-co-privacy-policy.yml
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
summary_line: 26 quoted statements, read from pipeboard-co's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- Marketing
- Artificial Intelligence
- Automation
- MCP
---
