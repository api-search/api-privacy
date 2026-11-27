---
api_specs:
- filename: briq-cloud-v1-openapi.json
  format: json
  label: briq API V1 API
  slug: briq-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/briq-cloud/openapi/_original/briq-cloud-v1-openapi.json
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address
  - category: contact
    text: Name and email are required to create an account; the rest follows from using the service.
  - category: device
    text: Session token, IP address, user agent
  - category: financial
    text: 'Billing details: billing address, company name and VAT number if you give them, the card''s brand and last four digits (the card itself stays with our payment provider)'
  - category: behavioral
    text: Page visits and product events ( audience measurement )
  - category: location
    text: your approximate location (country, region, city) derived from your IP address
  - category: communication
    text: 'Messages you send with the help button: the text, the email address you give or your account''s'
  deletion:
    route: Email privacy@briq.cloud to delete your account
    text: To delete your account or unlink Google, write to privacy@briq.cloud .
  dpa:
    available: true
    text: Each is our processor, bound by a data processing agreement
    url: null
  purposes:
  - purpose: Create account and send service email
    text: Create your account; send service email (security notices, invitations)
  - purpose: Run and meter briqs
    text: Run and meter your briqs
  - purpose: Billing and invoices
    text: Take payments, apply VAT, issue invoices
  - purpose: Audience measurement
    text: Understand what works in briq
  residency:
  - region: Netherlands
    text: Hosting provider Runs the website, dashboard, API and account database Amsterdam, Netherlands
  - region: France
    text: 'Infrastructure provider Runs your briqs: compute, volumes, logs Roubaix, France (Paris region)'
  retention:
  - period: Life of the account, then deleted within 30 days
    scope: Account, team and membership records
    text: Account, team and membership records, and how you found briq Life of the account, then deleted within 30 days
  - period: Until they expire or you sign out
    scope: Sessions
    text: Sessions Until they expire or you sign out
  - period: 12 months
    scope: Briq metadata and audit rows
    text: Briq metadata and audit rows 12 months
  - period: 12 months
    scope: Audience measurement and product events
    text: Audience measurement and product events 12 months
  - period: 12 months after our last reply
    scope: Messages sent with the help button
    text: Messages sent with the help button 12 months after our last reply
  - period: 10 years
    scope: Invoices
    text: Invoices 10 years (French commercial code, Art. L123-22)
  rights:
  - right: access
    text: You may ask for access to your data, correction, deletion, restriction, portability, or object to processing based on legitimate interests (Arts. 15–22), and withdraw consent at any time.
  - right: complaint to supervisory authority
    text: You can complain to the CNIL , the French supervisory authority.
  role:
    text: For personal data inside your briqs, you are the controller and we are the processor, under the data processing agreement .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, use it for advertising, share it for others' marketing, or use it to train AI or machine learning models.
  subprocessors:
    text: We name each provider on request. More in data protection .
    url: null
  transfers:
  - mechanism: DPF
    text: Where data leaves the EU (service email, requests the traffic provider carries), the transfer relies on the EU–US Data Privacy Framework or the European Commission's Standard Contractual Clauses.
  - mechanism: SCC
    text: Where data leaves the EU (service email, requests the traffic provider carries), the transfer relies on the EU–US Data Privacy Framework or the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: briq
provenance_date: '2026-11-09'
provider_name: briq
provider_slug: briq-cloud
slug: briq-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: briq-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://briq.cloud/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: briq\naid: briq-cloud\nurl: https://briq.cloud/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For personal data inside your briqs, you are the controller and we are the processor, under the data processing\n    agreement .\ndata_categories:\n- category: identifying\n  text: Name, email address\n- category: contact\n  text: Name and email are required to create an account; the rest follows from using the service.\n- category: device\n  text: Session token, IP address, user agent\n- category: financial\n  text: 'Billing details: billing address, company name and VAT number if you give\
  \ them, the card''s brand and last\n    four digits (the card itself stays with our payment provider)'\n- category: behavioral\n  text: Page visits and product events ( audience measurement )\n- category: location\n  text: your approximate location (country, region, city) derived from your IP address\n- category: communication\n  text: 'Messages you send with the help button: the text, the email address you give or your account''s'\npurposes:\n- purpose: Create account and send service email\n  text: Create your account; send service email (security notices, invitations)\n- purpose: Run and meter briqs\n  text: Run and meter your briqs\n- purpose: Billing and invoices\n  text: Take payments, apply VAT, issue invoices\n- purpose: Audience measurement\n  text: Understand what works in briq\nretention:\n- scope: Account, team and membership records\n  period: Life of the account, then deleted within 30 days\n  text: Account, team and membership records, and how you found briq Life of the\
  \ account, then deleted within 30\n    days\n- scope: Sessions\n  period: Until they expire or you sign out\n  text: Sessions Until they expire or you sign out\n- scope: Briq metadata and audit rows\n  period: 12 months\n  text: Briq metadata and audit rows 12 months\n- scope: Audience measurement and product events\n  period: 12 months\n  text: Audience measurement and product events 12 months\n- scope: Messages sent with the help button\n  period: 12 months after our last reply\n  text: Messages sent with the help button 12 months after our last reply\n- scope: Invoices\n  period: 10 years\n  text: Invoices 10 years (French commercial code, Art. L123-22)\nresidency:\n- region: Netherlands\n  text: Hosting provider Runs the website, dashboard, API and account database Amsterdam, Netherlands\n- region: France\n  text: 'Infrastructure provider Runs your briqs: compute, volumes, logs Roubaix, France (Paris region)'\ntransfers:\n- mechanism: DPF\n  text: Where data leaves the EU (service\
  \ email, requests the traffic provider carries), the transfer relies on\n    the EU–US Data Privacy Framework or the European Commission's Standard Contractual Clauses.\n- mechanism: SCC\n  text: Where data leaves the EU (service email, requests the traffic provider carries), the transfer relies on\n    the EU–US Data Privacy Framework or the European Commission's Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: We name each provider on request. More in data protection .\ndpa:\n  available: true\n  url: null\n  text: Each is our processor, bound by a data processing agreement\ndeletion:\n  route: Email privacy@briq.cloud to delete your account\n  text: To delete your account or unlink Google, write to privacy@briq.cloud .\nrights:\n- right: access\n  text: You may ask for access to your data, correction, deletion, restriction, portability, or object to processing\n    based on legitimate interests (Arts. 15–22), and withdraw consent at any time.\n- right: complaint to\
  \ supervisory authority\n  text: You can complain to the CNIL , the French supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, use it for advertising, share it for others' marketing, or use it to train\n    AI or machine learning models.\n"
source_yaml_url: https://artifacts.apis.io/briq-cloud/privacy/briq-cloud-privacy-policy.yml
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
summary_line: 28 quoted statements, read from briq's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Sandbox
- Database
- Platform
- Company
---
