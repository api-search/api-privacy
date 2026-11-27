---
api_specs:
- filename: asyntai-com-openapi-generated.yml
  format: yaml
  label: Asyntai API
  slug: asyntai-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asyntai-com/openapi/_ae-authored/asyntai-com-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Name: Used for identification and communication purposes'
  - category: contact
    text: 'Email Address: Essential for account creation, service notifications, billing communications, and customer support'
  - category: financial
    text: 'Billing Information: Including billing address, state, country, and payment method details necessary for processing subscription payments'
  - category: communication
    text: 'Chat Conversations: Messages between your website visitors and the AI agent, necessary for providing the chat service'
  - category: device
    text: 'IP Address: Used to diagnose server problems, administer our website, and provide localized content'
  - category: behavioral
    text: 'Website Activity: Pages visited and actions taken on our website to improve user experience'
  deletion:
    route: Account termination or chat data deletion through account settings
    text: Upon account termination, we will delete or anonymize your personal data within a reasonable timeframe, except where retention is required by law.
  dpa:
    available: true
    text: governed by our Data Processing Agreement
    url: null
  purposes:
  - purpose: Service delivery
    text: To provide and maintain our AI live chat agent service, including processing chat conversations, generating AI responses, and managing your account
  - purpose: Billing and account management
    text: To process subscription payments, manage your account, track usage limits, and provide billing support
  - purpose: Service improvement
    text: (we do not use your specific chat data for general AI model development)
  retention:
  - period: null
    scope: Account information
    text: Retained while your account is active and for a reasonable period after account closure to handle any remaining obligations
  - period: typically 7 years
    scope: Billing records
    text: Retained for the period required by tax and accounting regulations (typically 7 years)
  - period: indefinitely
    scope: Usage analytics
    text: Aggregated and anonymized usage data may be retained indefinitely for service improvement
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you
  - right: Rectification
    text: Request correction of inaccurate or incomplete personal data
  - right: Erasure
    text: Request deletion of your personal data under certain circumstances
  - right: Restrict processing
    text: Request limitation of processing in specific situations
  - right: Portability
    text: Request transfer of your data in a machine-readable format
  - right: Object
    text: Object to processing based on legitimate interests or for direct marketing
  - right: Withdraw consent
    text: Withdraw consent for processing based on consent at any time
  role:
    text: when Asyntai processes data on behalf of our business customers (such as when end-users interact with a chat widget on a customer's website), Asyntai acts as a Processor governed by our Data Processing Agreement
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: including Standard Contractual Clauses (SCCs) approved by the European Commission or transfers to countries covered by an adequacy decision
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Asyntai
provenance_date: '2026-11-09'
provider_name: Asyntai
provider_slug: asyntai-com
slug: asyntai-com-privacy-policy
source_date: '2026-11-09'
source_filename: asyntai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asyntai.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Asyntai\naid: asyntai-com\nurl: https://asyntai.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: when Asyntai processes data on behalf of our business customers (such as when end-users interact with a\n    chat widget on a customer's website), Asyntai acts as a Processor governed by our Data Processing Agreement\ndata_categories:\n- category: identifying\n  text: 'Name: Used for identification and communication purposes'\n- category: contact\n  text: 'Email Address: Essential for account creation, service notifications, billing communications, and customer\n    support'\n- category:\
  \ financial\n  text: 'Billing Information: Including billing address, state, country, and payment method details necessary for\n    processing subscription payments'\n- category: communication\n  text: 'Chat Conversations: Messages between your website visitors and the AI agent, necessary for providing the\n    chat service'\n- category: device\n  text: 'IP Address: Used to diagnose server problems, administer our website, and provide localized content'\n- category: behavioral\n  text: 'Website Activity: Pages visited and actions taken on our website to improve user experience'\npurposes:\n- purpose: Service delivery\n  text: To provide and maintain our AI live chat agent service, including processing chat conversations, generating\n    AI responses, and managing your account\n- purpose: Billing and account management\n  text: To process subscription payments, manage your account, track usage limits, and provide billing support\n- purpose: Service improvement\n  text: (we do not use your\
  \ specific chat data for general AI model development)\nretention:\n- scope: Account information\n  period: null\n  text: Retained while your account is active and for a reasonable period after account closure to handle any remaining\n    obligations\n- scope: Billing records\n  period: typically 7 years\n  text: Retained for the period required by tax and accounting regulations (typically 7 years)\n- scope: Usage analytics\n  period: indefinitely\n  text: Aggregated and anonymized usage data may be retained indefinitely for service improvement\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: including Standard Contractual Clauses (SCCs) approved by the European Commission or transfers to countries\n    covered by an adequacy decision\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: governed by our Data Processing Agreement\ndeletion:\n  route: Account termination or chat data deletion through account settings\n  text: Upon account termination,\
  \ we will delete or anonymize your personal data within a reasonable timeframe,\n    except where retention is required by law.\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you\n- right: Rectification\n  text: Request correction of inaccurate or incomplete personal data\n- right: Erasure\n  text: Request deletion of your personal data under certain circumstances\n- right: Restrict processing\n  text: Request limitation of processing in specific situations\n- right: Portability\n  text: Request transfer of your data in a machine-readable format\n- right: Object\n  text: Object to processing based on legitimate interests or for direct marketing\n- right: Withdraw consent\n  text: Withdraw consent for processing based on consent at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asyntai-com/privacy/asyntai-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 23 quoted statements, read from Asyntai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- Customer Service
- Software-as-a-Service
- Website Integration
- Multilingual
---
