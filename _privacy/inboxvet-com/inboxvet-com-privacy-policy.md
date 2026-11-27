---
api_specs:
- filename: inboxvet-com-openapi-generated.yml
  format: yaml
  label: inboxvet-com API
  slug: inboxvet-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inboxvet-com/openapi/_ae-authored/inboxvet-com-openapi-generated.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up we collect your name, email address and password
  - category: contact
    text: If you contact us through the website we receive your name, email address, company (optional) and message.
  - category: financial
    text: We store your Stripe customer ID and a record of each purchase (amount and credits).
  - category: device
    text: the browser, operating system and device type we derive from it
  - category: location
    text: the country when our hosting provider supplies it
  - category: behavioral
    text: understand how the website is used so we can improve it
  - category: other
    text: we process the email addresses you submit, the results we return
  deletion:
    route: Email support@inboxvet.com with the subject Privacy request
    text: To make a request, email support@inboxvet.com with the subject “Privacy request”.
  dpa:
    available: true
    text: Roles, lawful bases, rights and our DPA.
    url: null
  purposes:
  - purpose: Provide the service
    text: 'provide the service: run verifications, show results and keep your account working'
  - purpose: Security and fraud prevention
    text: protect accounts, detect fraud and abuse, and enforce rate limits
  - purpose: Legal and accounting compliance
    text: comply with legal, tax and accounting obligations
  - purpose: Support
    text: answer support and contact requests
  - purpose: Website analytics
    text: understand how the website is used so we can improve it
  residency:
  - region: us-east-2 (Ohio)
    text: Uploaded CSV files are stored in Amazon Web Services S3 in the us-east-2 (Ohio) region.
  - region: United States
    text: InboxVet is based in, and processes data in, the United States.
  retention:
  - period: 12 months
    scope: Sign-in and sign-up security logs
    text: 12 months, then deleted automatically
  - period: While your account is active
    scope: Verification data and CSV files
    text: While your account is active, unless you ask us to delete it sooner
  - period: 12 months
    scope: Homepage verifier logs
    text: Homepage verifier logs 12 months
  - period: As long as tax and accounting law requires
    scope: Billing records
    text: Billing records As long as tax and accounting law requires
  rights:
  - right: Access
    text: access the personal data we hold about you and get a copy
  - right: Correction
    text: correct inaccurate data
  - right: Deletion
    text: have your data deleted
  - right: Restrict or object
    text: restrict or object to certain processing
  - right: Portability
    text: receive your data in a portable format
  - right: Withdraw consent
    text: withdraw consent at any time
  - right: Complain to authority
    text: complain to your local data protection authority
  role:
    text: For account, billing, website and security data we act as the controller .
    value: both
  sale_or_sharing:
    stance: conditional
    text: If you opt in to marketing cookies, the Meta Pixel may count as “sharing” for cross-context behavioural advertising under the CPRA.
  subprocessors:
    text: We share personal data only with service providers that help us run InboxVet, under contracts that limit how they may use it
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as the European Commission’s Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: inboxvet-com
provenance_date: '2026-11-09'
provider_name: inboxvet-com
provider_slug: inboxvet-com
slug: inboxvet-com-privacy-policy
source_date: '2026-11-09'
source_filename: inboxvet-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://inboxvet.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: inboxvet-com\naid: inboxvet-com\nurl: https://inboxvet.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account, billing, website and security data we act as the controller .\ndata_categories:\n- category: identifying\n  text: When you sign up we collect your name, email address and password\n- category: contact\n  text: If you contact us through the website we receive your name, email address, company (optional) and message.\n- category: financial\n  text: We store your Stripe customer ID and a record of each purchase (amount and credits).\n- category: device\n  text: the browser,\
  \ operating system and device type we derive from it\n- category: location\n  text: the country when our hosting provider supplies it\n- category: behavioral\n  text: understand how the website is used so we can improve it\n- category: other\n  text: we process the email addresses you submit, the results we return\npurposes:\n- purpose: Provide the service\n  text: 'provide the service: run verifications, show results and keep your account working'\n- purpose: Security and fraud prevention\n  text: protect accounts, detect fraud and abuse, and enforce rate limits\n- purpose: Legal and accounting compliance\n  text: comply with legal, tax and accounting obligations\n- purpose: Support\n  text: answer support and contact requests\n- purpose: Website analytics\n  text: understand how the website is used so we can improve it\nretention:\n- scope: Sign-in and sign-up security logs\n  period: 12 months\n  text: 12 months, then deleted automatically\n- scope: Verification data and CSV files\n\
  \  period: While your account is active\n  text: While your account is active, unless you ask us to delete it sooner\n- scope: Homepage verifier logs\n  period: 12 months\n  text: Homepage verifier logs 12 months\n- scope: Billing records\n  period: As long as tax and accounting law requires\n  text: Billing records As long as tax and accounting law requires\nresidency:\n- region: us-east-2 (Ohio)\n  text: Uploaded CSV files are stored in Amazon Web Services S3 in the us-east-2 (Ohio) region.\n- region: United States\n  text: InboxVet is based in, and processes data in, the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as the European Commission’s Standard Contractual\n    Clauses.\nsubprocessors:\n  url: null\n  text: We share personal data only with service providers that help us run InboxVet, under contracts that limit\n    how they may use it\ndpa:\n  available: true\n  url: null\n  text: Roles, lawful bases, rights and\
  \ our DPA.\ndeletion:\n  route: Email support@inboxvet.com with the subject Privacy request\n  text: To make a request, email support@inboxvet.com with the subject “Privacy request”.\nrights:\n- right: Access\n  text: access the personal data we hold about you and get a copy\n- right: Correction\n  text: correct inaccurate data\n- right: Deletion\n  text: have your data deleted\n- right: Restrict or object\n  text: restrict or object to certain processing\n- right: Portability\n  text: receive your data in a portable format\n- right: Withdraw consent\n  text: withdraw consent at any time\n- right: Complain to authority\n  text: complain to your local data protection authority\nsale_or_sharing:\n  stance: conditional\n  text: If you opt in to marketing cookies, the Meta Pixel may count as “sharing” for cross-context behavioural\n    advertising under the CPRA.\n"
source_yaml_url: https://artifacts.apis.io/inboxvet-com/privacy/inboxvet-com-privacy-policy.yml
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
summary_line: 31 quoted statements, read from inboxvet-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- Software-as-a-Service
- Marketing
---
