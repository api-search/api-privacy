---
api_specs:
- filename: clearly-sh-openapi-generated.yml
  format: yaml
  label: Clearly API
  slug: clearly-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearly-sh/openapi/_ae-authored/clearly-sh-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email address, display name, and either a hashed password or your Google profile.'
  - category: financial
    text: 'Payments: plan, trial status and the customer ID from our payment processor.'
  - category: location
    text: 'Country: derived from your IP address on each request.'
  - category: behavioral
    text: 'Usage: product events and, only with your consent, Google Analytics page views.'
  - category: communication
    text: 'Support reports: what you tell us when you report a problem or ask a question, with any screenshot you add.'
  - category: other
    text: 'Your work: what you create and upload in your workspace, including chats with the agent, and transcripts of voice conversations.'
  deletion:
    route: Email request for server records
    text: To request deletion of server records, contact [email protected] with an App Store transaction reference; never send the installation key.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the product
    text: 'Run the product: your workspace, the agent, generation, sync, support'
  - purpose: Security and abuse prevention
    text: Security, abuse prevention and service reliability
  - purpose: Answering support reports
    text: Answering support reports, which a person on our team reads
  residency:
  - region: Global, primary US
    text: Cloud infrastructure Hosting, databases and storage Global, primary US
  - region: US, EU
    text: Authentication Sign-in US, EU
  retention:
  - period: While your account is open
    scope: Account and workspace content
    text: While your account is open. Deleting your account removes it at once; backups are erased within 30 days
  - period: Up to 2 days
    scope: Temporary tracing uploads
    text: Temporary tracing uploads Up to 2 days
  - period: 7 years
    scope: Billing records
    text: Billing records 7 years (tax law)
  - period: 7 days
    scope: Request logs
    text: operational logs that may contain fragments are deleted within 7 days
  rights:
  - right: Access, correction, deletion, portability and objection
    text: Depending on where you live (including under the GDPR, UK GDPR and California law), you can ask to access, correct, delete or port your data, object to or restrict processing, withdraw consent, and opt out of sale or sharing (we do neither).
  - right: Complaint to data-protection authority
    text: You can also complain to your data-protection authority (in the UK, the ICO; in California, the CPPA).
  role:
    text: Clearly is an independent software product operated from the Commonwealth of Virginia, USA by a sole proprietor, who is the controller of your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your personal information, share it for cross-context behavioural advertising, or train AI models on your content.
  subprocessors:
    text: The current list of named providers is available from [email protected] .
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers from the EU/UK to the US rely on the EU Standard Contractual Clauses (Decision 2021/914).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clearly
provenance_date: '2026-11-09'
provider_name: Clearly
provider_slug: clearly-sh
slug: clearly-sh-privacy-policy
source_date: '2026-11-09'
source_filename: clearly-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clearly.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clearly\naid: clearly-sh\nurl: https://www.clearly.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Clearly is an independent software product operated from the Commonwealth of Virginia, USA by a sole proprietor,\n    who is the controller of your personal data.\ndata_categories:\n- category: identifying\n  text: 'Account: email address, display name, and either a hashed password or your Google profile.'\n- category: financial\n  text: 'Payments: plan, trial status and the customer ID from our payment processor.'\n- category: location\n  text: 'Country: derived from your IP address\
  \ on each request.'\n- category: behavioral\n  text: 'Usage: product events and, only with your consent, Google Analytics page views.'\n- category: communication\n  text: 'Support reports: what you tell us when you report a problem or ask a question, with any screenshot you\n    add.'\n- category: other\n  text: 'Your work: what you create and upload in your workspace, including chats with the agent, and transcripts\n    of voice conversations.'\npurposes:\n- purpose: Run the product\n  text: 'Run the product: your workspace, the agent, generation, sync, support'\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention and service reliability\n- purpose: Answering support reports\n  text: Answering support reports, which a person on our team reads\nretention:\n- scope: Account and workspace content\n  period: While your account is open\n  text: While your account is open. Deleting your account removes it at once; backups are erased within 30 days\n- scope: Temporary\
  \ tracing uploads\n  period: Up to 2 days\n  text: Temporary tracing uploads Up to 2 days\n- scope: Billing records\n  period: 7 years\n  text: Billing records 7 years (tax law)\n- scope: Request logs\n  period: 7 days\n  text: operational logs that may contain fragments are deleted within 7 days\nresidency:\n- region: Global, primary US\n  text: Cloud infrastructure Hosting, databases and storage Global, primary US\n- region: US, EU\n  text: Authentication Sign-in US, EU\ntransfers:\n- mechanism: SCC\n  text: Transfers from the EU/UK to the US rely on the EU Standard Contractual Clauses (Decision 2021/914).\nsubprocessors:\n  url: null\n  text: The current list of named providers is available from [email protected] .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request for server records\n  text: To request deletion of server records, contact [email protected] with an App Store transaction reference;\n    never send the installation key.\nrights:\n- right:\
  \ Access, correction, deletion, portability and objection\n  text: Depending on where you live (including under the GDPR, UK GDPR and California law), you can ask to access,\n    correct, delete or port your data, object to or restrict processing, withdraw consent, and opt out of sale or\n    sharing (we do neither).\n- right: Complaint to data-protection authority\n  text: You can also complain to your data-protection authority (in the UK, the ICO; in California, the CPPA).\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your personal information, share it for cross-context behavioural advertising, or train AI\n    models on your content.\n"
source_yaml_url: https://artifacts.apis.io/clearly-sh/privacy/clearly-sh-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Clearly's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Workspace
- Design Tools
---
