---
api_specs:
- filename: codequiry-com-auth-api-openapi.yml
  format: yaml
  label: Codequiry Auth API
  slug: codequiry-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-auth-api-openapi.yml
- filename: codequiry-com-checks-api-openapi.yml
  format: yaml
  label: Codequiry Checks API
  slug: codequiry-com-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-checks-api-openapi.yml
- filename: codequiry-com-reference-api-openapi.yml
  format: yaml
  label: Codequiry Reference API
  slug: codequiry-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-reference-api-openapi.yml
- filename: codequiry-com-results-api-openapi.yml
  format: yaml
  label: Codequiry Results API
  slug: codequiry-com-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-results-api-openapi.yml
- filename: codequiry-com-run-api-openapi.yml
  format: yaml
  label: Codequiry Run API
  slug: codequiry-com-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-run-api-openapi.yml
- filename: codequiry-com-submissions-api-openapi.yml
  format: yaml
  label: Codequiry Submissions API
  slug: codequiry-com-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-submissions-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, password (stored only as a hash), institution or company, role
  - category: contact
    text: Contact form tickets, help desk conversations (including answers from its AI assistant), emails and post you send us
  - category: financial
    text: Billing name and address, plan, invoices and transaction history.
  - category: device
    text: IP address and approximate location, browser, operating system, and a device signature derived from browser characteristics
  - category: behavioral
    text: Pages and features used, checks started, API and MCP calls, errors
  - category: other
    text: Code, files and documents you submit, their names and metadata, courses, checks and results
  deletion:
    route: Privacy Settings, or written request to the address in Contact; uploaded code on non-Rapid plans cannot be deleted; Rapid add-on enables on-demand deletion
    text: While Rapid is active you can delete submissions, checks and courses on demand, including content uploaded before you activated Rapid, and we stop using deleted content for matching.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running the Service
    text: Creating and securing accounts Running checks and producing results Team access and integrations Answering support requests Billing
  - purpose: Protecting the Service
    text: Detecting fraud, abuse and account farming
  - purpose: Improving detection and models
    text: We also use it to build and improve our detection methods and models.
  - purpose: Marketing
    text: Product news and offers (you can opt out)
  residency:
  - region: India
    text: We are based in India, our payment agent and main hosting are in the United States, and our providers operate in other countries, including China for some AI model providers.
  retention:
  - period: While the account exists, plus 30 days
    scope: Account information
    text: Account information While the account exists, plus 30 days
  - period: Until you delete it, or the account is deleted
    scope: Uploaded code (Rapid add-on active)
    text: Uploaded code (Rapid add-on active) Until you delete it, or the account is deleted
  - period: Kept indefinitely
    scope: Uploaded code (all other plans)
    text: Kept indefinitely in the anonymised matching corpus, including after account deletion, and not deletable on request.
  - period: While the account exists, plus 90 days
    scope: Check results and reports
    text: Check results and reports While the account exists, plus 90 days
  - period: 7 years, or longer where the law requires
    scope: Transaction and tax records
    text: Transaction and tax records 7 years, or longer where the law requires
  - period: 3 years from the last message
    scope: Support conversations
    text: Support conversations 3 years from the last message
  rights:
  - right: Access
    text: 'Access: get a copy of your personal data'
  - right: Correction
    text: 'Correction: fix inaccurate or incomplete data'
  - right: Deletion
    text: 'Deletion: have your personal data erased, subject to the corpus exception below'
  - right: Portability
    text: 'Portability: receive your data in a machine-readable format'
  - right: Objection
    text: 'Objection: object to processing based on legitimate interests, and to marketing'
  - right: Restriction
    text: 'Restriction: limit how we use your data'
  - right: Withdraw consent
    text: 'Withdraw consent: where we rely on consent, at any time'
  - right: Complain
    text: 'Complain: to your data protection authority'
  role:
    text: We are the controller for account, billing, security and support data, and for the matching corpus and model improvement described in Submitted code .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where data protection law restricts transfers, we rely on appropriate safeguards or another lawful basis.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Codequiry
provenance_date: '2026-11-09'
provider_name: Codequiry
provider_slug: codequiry-com
slug: codequiry-com-privacy-policy
source_date: '2026-11-09'
source_filename: codequiry-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codequiry.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Codequiry\naid: codequiry-com\nurl: https://codequiry.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller for account, billing, security and support data, and for the matching corpus and model\n    improvement described in Submitted code .\ndata_categories:\n- category: identifying\n  text: Name, email, password (stored only as a hash), institution or company, role\n- category: contact\n  text: Contact form tickets, help desk conversations (including answers from its AI assistant), emails and post\n    you send us\n- category: financial\n  text: Billing\
  \ name and address, plan, invoices and transaction history.\n- category: device\n  text: IP address and approximate location, browser, operating system, and a device signature derived from browser\n    characteristics\n- category: behavioral\n  text: Pages and features used, checks started, API and MCP calls, errors\n- category: other\n  text: Code, files and documents you submit, their names and metadata, courses, checks and results\npurposes:\n- purpose: Running the Service\n  text: Creating and securing accounts Running checks and producing results Team access and integrations Answering\n    support requests Billing\n- purpose: Protecting the Service\n  text: Detecting fraud, abuse and account farming\n- purpose: Improving detection and models\n  text: We also use it to build and improve our detection methods and models.\n- purpose: Marketing\n  text: Product news and offers (you can opt out)\nretention:\n- scope: Account information\n  period: While the account exists, plus 30 days\n\
  \  text: Account information While the account exists, plus 30 days\n- scope: Uploaded code (Rapid add-on active)\n  period: Until you delete it, or the account is deleted\n  text: Uploaded code (Rapid add-on active) Until you delete it, or the account is deleted\n- scope: Uploaded code (all other plans)\n  period: Kept indefinitely\n  text: Kept indefinitely in the anonymised matching corpus, including after account deletion, and not deletable\n    on request.\n- scope: Check results and reports\n  period: While the account exists, plus 90 days\n  text: Check results and reports While the account exists, plus 90 days\n- scope: Transaction and tax records\n  period: 7 years, or longer where the law requires\n  text: Transaction and tax records 7 years, or longer where the law requires\n- scope: Support conversations\n  period: 3 years from the last message\n  text: Support conversations 3 years from the last message\nresidency:\n- region: India\n  text: We are based in India, our payment\
  \ agent and main hosting are in the United States, and our providers operate\n    in other countries, including China for some AI model providers.\ntransfers:\n- mechanism: other\n  text: Where data protection law restricts transfers, we rely on appropriate safeguards or another lawful basis.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy Settings, or written request to the address in Contact; uploaded code on non-Rapid plans cannot\n    be deleted; Rapid add-on enables on-demand deletion\n  text: While Rapid is active you can delete submissions, checks and courses on demand, including content uploaded\n    before you activated Rapid, and we stop using deleted content for matching.\nrights:\n- right: Access\n  text: 'Access: get a copy of your personal data'\n- right: Correction\n  text: 'Correction: fix inaccurate or incomplete data'\n- right: Deletion\n  text: 'Deletion: have your personal data erased, subject\
  \ to the corpus exception below'\n- right: Portability\n  text: 'Portability: receive your data in a machine-readable format'\n- right: Objection\n  text: 'Objection: object to processing based on legitimate interests, and to marketing'\n- right: Restriction\n  text: 'Restriction: limit how we use your data'\n- right: Withdraw consent\n  text: 'Withdraw consent: where we rely on consent, at any time'\n- right: Complain\n  text: 'Complain: to your data protection authority'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/codequiry-com/privacy/codequiry-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Codequiry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Plagiarism
- AI Code Detection
- Education
- Source Code Analysis
- Academic Integrity
- MCP
---
