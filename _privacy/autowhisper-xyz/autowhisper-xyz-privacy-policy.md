---
api_specs:
- filename: autowhisper-xyz-openapi-generated.yml
  format: yaml
  label: AutoWhisper API
  slug: autowhisper-xyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autowhisper-xyz/openapi/_ae-authored/autowhisper-xyz-openapi-generated.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name Email address Account password (encrypted storage) Phone number (optional)
  - category: financial
    text: Depending on your subscription plan, we may collect payment information and transaction history.
  - category: biometric
    text: Certain Service features require us to process facial or body parts in videos or photos, which may include facial images and voice data.
  - category: location
    text: Approximate location based on IP address (country, city level)
  - category: device
    text: Unique device identifiers IP address Browser type and version
  - category: behavioral
    text: Clickstream data Websites you exit to
  - category: communication
    text: We collect the name, email address, and other information you provide when you communicate with us
  deletion:
    route: Email xnjiang@qumge.com with a privacy rights request
    text: If you submit a request to delete information, we will process it without undue delay and generally within 30 days
  dpa:
    available: true
    text: 'Data Processing Agreements (DPA): Where required by applicable law, we enter into data processing agreements or equivalent safeguards with relevant third parties who receive personal data.'
    url: null
  purposes:
  - purpose: Train and improve AI models
    text: Train and improve AI models that power our products and services
  - purpose: Provide and manage account and services
    text: Provide and manage your account and access to and use of the Services
  - purpose: Send marketing communications
    text: Send marketing communications, including news and offers for products or services
  - purpose: Targeted advertising
    text: we may "share" certain information with third parties for targeted advertising purposes
  residency:
  - region: China
    text: 'China: Primary servers and operations team'
  - region: United States
    text: 'United States: Google (AI video generation), OpenAI/Anthropic (large language models)'
  retention:
  - period: 30 days
    scope: Account information
    text: Duration of account activity + 30 days after account deletion
  - period: 12 months
    scope: Log and usage data
    text: Typically no more than 12 months
  - period: 3 years
    scope: Biometric data
    text: No more than 3 years maximum, unless you actively use related features or law requires a longer retention period
  - period: 3-7 years
    scope: Transaction and payment records
    text: As required by tax and accounting laws (typically 3-7 years)
  rights:
  - right: Access
    text: Request a copy of personal information we hold about you
  - right: Erasure
    text: Request deletion of your personal information (certain exceptions apply)
  - right: Portability
    text: Receive your personal information in a structured, commonly used, and machine-readable format
  - right: Object
    text: Object to our processing of your personal information based on legitimate interests
  - right: Withdraw consent
    text: Withdraw your consent at any time when we process based on your consent
  - right: Opt out of sale or sharing (California)
    text: 'Right to Opt-Out: Opt out of "sale" or "sharing" of your personal information'
  role:
    text: 'We act as a data processor: When we process personal data on behalf of our enterprise customers according to their instructions'
    value: both
  sale_or_sharing:
    stance: conditional
    text: Except as otherwise stated, we will never sell your personal information to anyone for monetary gain.
  subprocessors:
    text: A complete sub-processor list is available by contacting us.
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers of personal information to third countries, we use Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AutoWhisper
provenance_date: '2026-11-09'
provider_name: AutoWhisper
provider_slug: autowhisper-xyz
slug: autowhisper-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: autowhisper-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://autowhisper.xyz/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AutoWhisper\naid: autowhisper-xyz\nurl: https://autowhisper.xyz/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We act as a data processor: When we process personal data on behalf of our enterprise customers according\n    to their instructions'\ndata_categories:\n- category: identifying\n  text: Name Email address Account password (encrypted storage) Phone number (optional)\n- category: financial\n  text: Depending on your subscription plan, we may collect payment information and transaction history.\n- category: biometric\n  text: Certain Service features require us to process facial\
  \ or body parts in videos or photos, which may include\n    facial images and voice data.\n- category: location\n  text: Approximate location based on IP address (country, city level)\n- category: device\n  text: Unique device identifiers IP address Browser type and version\n- category: behavioral\n  text: Clickstream data Websites you exit to\n- category: communication\n  text: We collect the name, email address, and other information you provide when you communicate with us\npurposes:\n- purpose: Train and improve AI models\n  text: Train and improve AI models that power our products and services\n- purpose: Provide and manage account and services\n  text: Provide and manage your account and access to and use of the Services\n- purpose: Send marketing communications\n  text: Send marketing communications, including news and offers for products or services\n- purpose: Targeted advertising\n  text: we may \"share\" certain information with third parties for targeted advertising purposes\n\
  retention:\n- scope: Account information\n  period: 30 days\n  text: Duration of account activity + 30 days after account deletion\n- scope: Log and usage data\n  period: 12 months\n  text: Typically no more than 12 months\n- scope: Biometric data\n  period: 3 years\n  text: No more than 3 years maximum, unless you actively use related features or law requires a longer retention\n    period\n- scope: Transaction and payment records\n  period: 3-7 years\n  text: As required by tax and accounting laws (typically 3-7 years)\nresidency:\n- region: China\n  text: 'China: Primary servers and operations team'\n- region: United States\n  text: 'United States: Google (AI video generation), OpenAI/Anthropic (large language models)'\ntransfers:\n- mechanism: SCC\n  text: For transfers of personal information to third countries, we use Standard Contractual Clauses approved by\n    the European Commission\nsubprocessors:\n  url: null\n  text: A complete sub-processor list is available by contacting\
  \ us.\ndpa:\n  available: true\n  url: null\n  text: 'Data Processing Agreements (DPA): Where required by applicable law, we enter into data processing agreements\n    or equivalent safeguards with relevant third parties who receive personal data.'\ndeletion:\n  route: Email xnjiang@qumge.com with a privacy rights request\n  text: If you submit a request to delete information, we will process it without undue delay and generally within\n    30 days\nrights:\n- right: Access\n  text: Request a copy of personal information we hold about you\n- right: Erasure\n  text: Request deletion of your personal information (certain exceptions apply)\n- right: Portability\n  text: Receive your personal information in a structured, commonly used, and machine-readable format\n- right: Object\n  text: Object to our processing of your personal information based on legitimate interests\n- right: Withdraw consent\n  text: Withdraw your consent at any time when we process based on your consent\n- right: Opt\
  \ out of sale or sharing (California)\n  text: 'Right to Opt-Out: Opt out of \"sale\" or \"sharing\" of your personal information'\nsale_or_sharing:\n  stance: conditional\n  text: Except as otherwise stated, we will never sell your personal information to anyone for monetary gain.\n"
source_yaml_url: https://artifacts.apis.io/autowhisper-xyz/privacy/autowhisper-xyz-privacy-policy.yml
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
summary_line: 29 quoted statements, read from AutoWhisper's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- E-Commerce
- Content Generation
- Automation
---
