---
api_specs:
- filename: latchkey-jobs-api-openapi.yml
  format: yaml
  label: Latchkey Jobs API Jobs API
  slug: latchkey-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latchkey/openapi/latchkey-jobs-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: We keep your name, your email address, and a link to your profile picture with your account
  - category: behavioral
    text: which pages are visited, which links and buttons are used
  - category: other
    text: Build logs and error messages required to identify bottlenecks and failures.
  - category: other
    text: We read your .github/workflows YAML files to analyze job structure, caching, and dependencies.
  deletion:
    route: Request full data deletion after plan cancellation
    text: You may request full data deletion at any time following the cancellation of your plan.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To generate analytics dashboards, cost reports, and optimization insights.
  - purpose: Runner operation
    text: To provision, operate, and tear down the ephemeral Latchkey Runner instances that execute your workflow jobs, and to meter their usage for billing.
  - purpose: Self-healing
    text: To detect, diagnose, and apply bounded fixes to failing build steps on Latchkey Runners
  - purpose: Security and reliability
    text: To detect technical issues, security risks, or abuse of the Service.
  residency:
  - region: United States
    text: Google processes this data in the United States on our behalf.
  retention:
  - period: up to one year
    scope: Active account data
    text: We retain data in an active status for up to one year after which it is transferred to cold storage.
  - period: 90 days
    scope: Heal record
    text: It also stays in a heal record, which keeps what self-healing read of your files for 90 days
  - period: 365 days
    scope: Proposed fix file contents
    text: whose file contents are kept for 365 days
  - period: 14 days
    scope: Runner NAT flow records
    text: It is kept for 14 days and deleted within three days after that
  - period: 90 days
    scope: Pull request changed files
    text: keep their paths, with the pull request's number and commit, for 90 days
  - period: five years
    scope: Archived data
    text: Archived data is typically purged after five years unless otherwise required by law.
  rights:
  - right: access, correction, or deletion
    text: Depending on your location (e.g., GDPR, CCPA), you may have rights regarding access, correction, or deletion of your personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal data to third parties.
  subprocessors:
    text: AWS hosts our application and the compute that backs Latchkey Runners, and a managed database provider hosts our database.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Latchkey Jobs API
provenance_date: '2026-11-09'
provider_name: Latchkey Jobs API
provider_slug: latchkey
slug: latchkey-privacy-policy
source_date: '2026-11-09'
source_filename: latchkey-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://latchkey.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Latchkey Jobs API\naid: latchkey\nurl: https://latchkey.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We keep your name, your email address, and a link to your profile picture with your account\n- category: behavioral\n  text: which pages are visited, which links and buttons are used\n- category: other\n  text: Build logs and error messages required to identify bottlenecks and failures.\n- category: other\n  text: We read your .github/workflows YAML files to analyze job structure, caching, and dependencies.\npurposes:\n- purpose:\
  \ Service delivery\n  text: To generate analytics dashboards, cost reports, and optimization insights.\n- purpose: Runner operation\n  text: To provision, operate, and tear down the ephemeral Latchkey Runner instances that execute your workflow\n    jobs, and to meter their usage for billing.\n- purpose: Self-healing\n  text: To detect, diagnose, and apply bounded fixes to failing build steps on Latchkey Runners\n- purpose: Security and reliability\n  text: To detect technical issues, security risks, or abuse of the Service.\nretention:\n- scope: Active account data\n  period: up to one year\n  text: We retain data in an active status for up to one year after which it is transferred to cold storage.\n- scope: Heal record\n  period: 90 days\n  text: It also stays in a heal record, which keeps what self-healing read of your files for 90 days\n- scope: Proposed fix file contents\n  period: 365 days\n  text: whose file contents are kept for 365 days\n- scope: Runner NAT flow records\n  period:\
  \ 14 days\n  text: It is kept for 14 days and deleted within three days after that\n- scope: Pull request changed files\n  period: 90 days\n  text: keep their paths, with the pull request's number and commit, for 90 days\n- scope: Archived data\n  period: five years\n  text: Archived data is typically purged after five years unless otherwise required by law.\nresidency:\n- region: United States\n  text: Google processes this data in the United States on our behalf.\ntransfers: []\nsubprocessors:\n  url: null\n  text: AWS hosts our application and the compute that backs Latchkey Runners, and a managed database provider hosts\n    our database.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request full data deletion after plan cancellation\n  text: You may request full data deletion at any time following the cancellation of your plan.\nrights:\n- right: access, correction, or deletion\n  text: Depending on your location (e.g., GDPR, CCPA), you may have rights regarding\
  \ access, correction, or deletion\n    of your personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/latchkey/privacy/latchkey-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Latchkey Jobs API's own page on 2026-11-09.
synthetic: false
tags:
- CI/CD
- DevOps
- GitHub Actions
- Ephemeral Compute
- Build & Test Infrastructure
- Agent-Native
- AI Coding Agents
- Developer Tools
---
